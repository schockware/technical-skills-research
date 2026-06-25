# CTO Mode Mismatch Diagnostic — Quiz Specification

> **⚠️ SUPERSEDED (June 25, 2026): this diagnostic was NOT built.** Following the research to its conclusion, the decision was made not to release a CTO self-diagnostic — it would be administered to an epistemologically isolated individual, with input signals corrupted by the HiPPO effect, and a label that crystallizes rather than loosens identity investment; it is also weaponizable across a power gradient. See **[`16_RESEARCH_why_we_didnt_build_it.md`](16_RESEARCH_why_we_didnt_build_it.md)** for the full rationale. This spec is retained as the artifact-of-record — the careful work that the research then argued against shipping. The build status below is historical.

**Built from:** `14_PROMPT_quiz_build_for_opus.md`
**Grounded in:** `00_RESEARCH_CONTEXT.md`, `../13_RESEARCH_domain_centric_CTO.md`, `../05_FULLTEXT_working_document.md`, `../../Software Developer/01_RESEARCH_software_developer_career.md`
**Author:** Opus 4.8, June 24, 2026
**Reviewed and patched by:** Sonnet 4.6, June 24, 2026
**Status:** ~~Spec for build — patches applied, React build approved~~ → **Superseded; not built** (see banner above).

---

## How to read this spec

This is the complete blueprint: every question, every answer option, the points each option contributes, the scoring math, and the result templates. The React app will be a faithful render of this — nothing in the app's logic that isn't decided here.

Three things are deliberately invisible to the quiz taker and live only in this document:
- **Mode labels** (Builder / Multiplier / Strategist) — never shown until results.
- **Point weights** — each option's contribution to a mode score.
- **The give-up-the-hats vs. wear-all-the-hats axis** — Section 3 is engineered around it; the taker never sees the term.

Scoring uses three running tallies — **B** (Builder), **M** (Multiplier), **S** (Strategist) — kept *separately* for company-required mode (Section 1) and CTO operating mode (Sections 2–3). Section 4 produces an independent domain flag.

---

## Scoring model overview

| Tally | Fed by | Produces |
|---|---|---|
| `companyB / companyM / companyS` | Section 1 only | **Company-required mode** + transition-zone flag |
| `ctoB / ctoM / ctoS` | Sections 2 + 3 | **CTO operating mode** |
| `domainSelf` (0–100) | Section 4 Q1–Q3 | Domain-centric ↔ generalist |
| `domainMarket` (0–100) | Section 4 Q4–Q6 | Market domain dependency |

**Mode resolution (company and CTO both):** the mode with the highest tally wins.
**Transition-zone rule (company only):** if the top two company tallies are within **20%** of each other, the company is flagged *in transition* — the highest-risk reading — and both adjacent modes are named.

**Gap resolution:**
- Company mode == CTO mode → **Match**
- CTO mode is *earlier* than company mode (CTO=B, company=M; CTO=M, company=S; CTO=B, company=S) → **Lagging gap** (highest risk)
- CTO mode is *later* than company mode → **Leading gap**

Mode ordering for "earlier/later": Builder(1) < Multiplier(2) < Strategist(3).

**Tie-breaking:** on equal top tallies, default to the *earlier* mode (conservative — surfaces lagging gaps rather than hiding them). A Builder CTO who ties with Multiplier gets the lagging-gap flag, not a pass. The cost of a false negative is higher than a false positive.

---

## Section 1 — Company Stage (8 questions)

**Frame shown to taker:** *"First, some facts about your company right now. Answer based on what's true today, not where you're headed."*

Objective signals only. The taker reports facts, not self-diagnosis. Scores feed `companyB/M/S`.

---

**Q1. How many engineers report up through you (including indirectly)?**
- 1–3 (or just me) → B+2
- 4–10 → B+1, M+1
- 11–30 → M+2
- 31–80 → M+1, S+1
- 80+ → S+2

**Q2. Of the people who report directly to you, how many are themselves managers?**
- None — they're all individual contributors → B+2
- One, and it's recent / informal → B+1, M+1
- Some, but I still have ICs reporting to me directly → M+2
- All of my directs are managers or leads → M+1, S+1
- I have managers-of-managers reporting to me → S+2

*(Q2 is the load-bearing org-shape signal — manager-of-managers is the single cleanest objective marker that the company has left Builder territory.)*

**Q3. What's your current funding stage?**
- Bootstrapped / pre-seed → B+2
- Seed → B+1, M+1
- Series A → M+2
- Series B → M+1, S+1
- Series C+ / late stage → S+2

**Q4. How long since your last raise (or last major capital event)?**
- We haven't raised / very early → B+1
- Under 12 months → (no mode points; modifier — see note)
- 12–24 months → (no mode points)
- Over 24 months → S+1

*Note: Q4 doesn't pick a mode directly. "Over 24 months since last raise" nudges toward a later operating reality (the company has been compounding); "haven't raised" reinforces Builder. Kept light so it can't dominate.*

**Q5. Where is the company on revenue?**
- Pre-product — still building the first sellable thing → B+2
- Have a product, pre-meaningful-revenue → B+1, M+1
- Revenue exists, not yet scaling predictably → M+2
- Revenue is scaling on a repeatable motion → S+2

**Q6. What is the company's single biggest technical risk right now?**
- "Will the thing even work / can we build it?" → B+2
- "Can we ship fast enough to find product-market fit?" → B+1, M+1
- "Can we build a team and systems that scale with demand?" → M+2
- "Can this architecture scale 10–100× without falling over?" → S+1, M+1
- "Can we make the right long-horizon platform/ecosystem bets?" → S+2

**Q7. Who are your most important *external* relationships, in practice, this quarter?**
- We don't really have external technical relationships yet → B+2
- Early customers / design partners → B+1, M+1
- Investors (we're raising or reporting closely) → M+1, S+1
- Strategic partners, ecosystem, or industry bodies → S+2

**Q8. Which statement best describes how technical decisions get made today?**
- Almost everything routes through me → B+2
- I make the big calls; the team handles the rest → B+1, M+1
- My leads make most calls; I set direction and unblock → M+2
- My org makes calls within a strategy I own; I'm rarely in the room → S+2

*(Note for results engine: centralized decision-making at seed was appropriate — it was the correct mode. The lagging-gap narrative should acknowledge this explicitly: the problem is not that the CTO was central then, it is that the pattern persists now.)*

**Section 1 scoring:** sum into `companyB/M/S`. Resolve top mode. Apply the 20%-proximity transition-zone rule.

---

## Section 2 — How You Actually Spend Time (10 questions)

**Frame shown to taker:**

> *"Now, your actual last few weeks. Not a typical week, not your best week — the real recent one. Resist the urge to answer how you wish it looked."*
>
> *"A note on how these questions are written: we don't ask you to rate your skills. Self-ratings of technical and leadership ability are unreliable predictors — what matters is what you actually did with your time and what you found meaningful. Answer for your real recent week, not your best week or your intended week."*

Behavioral. Anchored to *last week / last month*. Scores feed `ctoB/M/S`.

---

**Q1. In the last 7 days, roughly what share of your working hours went to writing or reviewing code?**
- More than half → B+2
- A quarter to half → B+1, M+1
- Under a quarter, but some most days → M+1
- Almost none, and that was deliberate → M+1, S+1
- None, and I barely noticed → S+2

**Q2. In the last 7 days, roughly what share of your hours went to 1:1s, coaching, or unblocking people?**
- Almost none → B+2
- A little, when something broke → B+1
- A regular, planned chunk of my week → M+2
- Most of my internal time → M+1, S+1
- I've largely handed this to my managers → S+2

**Q3. In the last 30 days, what share of your hours went to *external* rooms — board, investors, customers, partners?**
- None → B+1
- A meeting or two → M+1
- A standing, significant part of my month → S+2
- It's the center of gravity of my job now → S+2

**Q4. Think of the most important technical decision in the last week. Who actually made the call?**
- I did, directly → B+2
- I did, after the team brought me the options → B+1, M+1
- A lead or engineer made it; I was a sounding board → M+2
- Someone on the team made it and I heard about it after → M+1, S+1
- It was made inside a framework I'd set; I wasn't involved → S+2

**Q5. The last time an engineer was clearly struggling (last month-ish), what did you do?**
- I stepped in and did / fixed the hard part myself → B+2
- I paired with them until it was unblocked → B+1, M+1
- I coached them through it and let them finish → M+2
- I made sure their manager was handling it → M+1, S+1
- I honestly didn't hear about it directly → S+1

*(Calibrated per Constraint 7: "I stepped in and fixed it" reads as decisive help but scores Builder. The Multiplier answer requires letting someone less capable finish — the harder thing to admit.)*

**Q6. When was your last board or serious investor meeting, and what was your role?**
- Haven't had one / wasn't in it → B+1
- I attended and answered technical questions → B+1, M+1
- I presented the technical/org story → M+1, S+1
- I co-own the narrative and shape what we raise toward → S+2

**Q7. Right now, without checking a tool, can you name the top 3 things blocking your team?**
- Yes — and I'm personally working on at least one → B+2
- Yes — my leads own them, I track them → M+2
- Roughly — I'd check with my managers to be sure → M+1, S+1
- No — that's deliberately not my altitude anymore → S+2

*(Note the inversion: deep blocker-knowledge is a Builder signal here, not a virtue. A Strategist who can rattle off three team blockers may be operating too low.)*

**Q8. How much of your week is recurring 1:1s and team rituals you personally run?**
- Very little — my calendar is reactive/build-focused → B+2
- A few key ones → B+1, M+1
- A structured cadence I maintain → M+2
- My managers run the cadence; I run the leadership layer → S+2

**Q9. In the last month, did you ship something with your own hands that was on the critical path?**
- Yes, more than once → B+2
- Once → B+1, M+1
- No, but I reviewed critical-path work closely → M+1
- No — critical-path delivery doesn't route through me → M+1, S+1

**Q10. Does your actual last week resemble your idea of an optimal week?**

*(The Mathias & Williams calendar assessment, applied directly.)*

- Yes — I spent my time on what I think matters most → +1 to current top CTO tally
- Mostly, but too much firefighting → +1 to current top CTO tally
- No — I was pulled into work I think is below where I should be → S+1 (signals upward pull)
- No — I was pulled *up* into work I'd rather not do, away from building → **SOFT FLAG: wear-all-the-hats** (B+1, but also triggers flag — see note)

*⚑ PATCH — Q10 soft flag:* The last option ("pulled up, away from building") is not just B+1. It is a **wear-all-the-hats soft flag** that must surface explicitly in the lagging-gap narrative regardless of overall mode score. A CTO whose optimal week pulls them back toward building, while the company needs Multiplier, is the textbook lagging-gap profile. The results engine should treat this answer the same as S3-Q6 "all three" — a named flag, not just a point. Add to lagging-gap copy: *"You told us your optimal week would pull you back toward building. That pull isn't a discipline problem — it's the identity signal the research says most reliably predicts a stalled transition."*

---

## Section 3 — Identity & Energy Signals (8 questions)

**Frame shown to taker:** *"These last questions are about what the work feels like from the inside. There are no right answers — answer for who you are right now, not who you're trying to become."*

This section is the Mathias & Williams mechanism. It surfaces *give up the hats* vs. *wear all the hats* without ever naming it. Per Constraint 7, the Multiplier-coded options are written to be the *less* flattering / less instinctive choice, so Builder CTOs don't reflexively select them.

---

**Q1. An unexpected free day, nothing on the calendar. What actually energizes you to do?**
- Sit down and build something I've been itching to → B+2
- Go deep on a gnarly technical problem the team's stuck on → B+1, M+1
- Spend it developing someone — a long coaching session, org design → M+2
- Think about where the company should be in two years → S+2

**Q2. Of the last six months, which accomplishment are you proudest of?**
- A thing I personally built or fixed that mattered → B+2
- A hard technical bet that paid off → B+1, S+1
- An engineer who leveled up because of how I invested in them → M+2
- A strategic or external win that moved the company → S+2

*(Q1 and Q2 are the core identity pair. The Multiplier answer in Q2 — pride in someone else's growth rather than your own output — is exactly the orientation that does not come naturally to a Builder, which is the point.)*

**Q3. What is hardest for you to let go of in your role right now?**
- Being in the code / the architecture decisions → B+2
- Being the person who can solve anything technical → B+1, M+1
- Being close enough to the team to feel their day-to-day → M+1
- Being the one who sets technical direction → S+1
- Honestly, I've let go of most of it and that's fine → M+1, S+1

**Q4. A new engineer joins who is clearly better than you at something core to the product. Your gut reaction?**
- A little threatened, even if I know I shouldn't be → B+2
- Excited to learn from them → B+1, M+1
- Great — that's exactly who I'm trying to hire → M+2
- I assume my best hires are better than me; that's the job → S+1, M+1

*(Constraint 7 calibration: "excited to learn from them" is the easy, flattering answer and is deliberately *not* the strongest Multiplier signal. The strongest Multiplier signal is treating "better than me" as the goal — an orientation, not a feeling.)*

**Q5. "The company needs a different kind of CTO than it did a year ago." How does that land?**
- Stings — I am the CTO this company needs → B+2
- I get it intellectually but it's uncomfortable → B+1, M+1
- That's just true at every stage; my job is to change with it → M+1, S+1
- I've been actively reshaping my own role toward that → S+2

**Q6. Right now, which feels most like you?**
- A craftsperson → B+2
- A coach → M+2
- A navigator → S+2
- A bit of all three, honestly → B+1, M+1 + **SOFT FLAG: wear-all-the-hats**

*Note on the "all three" option: it scores nothing toward Strategist deliberately. The "wear all the hats" instinct — refusing to give up any identity — is itself the Builder/anti-transition signal. The results engine treats a top-tally tie that includes this answer as a soft wear-all-the-hats flag.*

**Q7. When you delegate something important, what's the honest reason you sometimes pull it back?**
- It's faster / better if I just do it → B+2
- I worry it won't meet the bar → B+1, M+1
- I rarely pull things back — I'd rather it be done their way → M+2
- I delegate the what and the how; pulling back isn't really a thing for me → S+1, M+1

**Q8. Imagine the company 18 months out, thriving, and your day-to-day no longer involves technical work at all. How does that future feel?**
- Like a loss — that's the part I love → B+2
- Mixed — proud of the company, but I'd miss it → B+1, M+1
- Right — that's the trajectory I want → M+1, S+1
- Like the goal — building the *company* is the work now → S+2

*(Q8 is the cleanest single give-up-the-hats item. "Like a loss" is the wear-all-the-hats identity; "like the goal" is give-up-the-hats. Per the research, this orientation is the strongest single predictor of transition success.)*

**Sections 2+3 scoring:** sum all into `ctoB/M/S`. Resolve top CTO mode. Note any wear-all-the-hats soft flags (S2-Q10 last option, S3-Q6 "all three") for the narrative.

---

## Section 4 — Domain Profile (6 questions)

**Frame shown to taker:** *"Last short section. This is about your relationship to your field — separate from everything above."*

Produces two independent 0–100 scores. **This is a parallel risk dimension, not a tiebreaker for mode** — do not collapse into mode resolution.

`domainSelf` (CTO's own domain-centricity), `domainMarket` (market's domain dependency).

---

**Q1. How would you describe your technical identity? → `domainSelf`**
- "I'm a [specific domain] person" — it's a decade-plus of depth → +35
- Deep in my domain, but I've worked across a few → +20
- I go deep where needed but think of myself as a generalist → +5
- "I figure things out and build teams" — domain is secondary → 0

**Q2. In the last 12 months, did you successfully lead a technical initiative *outside* your primary domain? → `domainSelf` (inverse)**
- No — I've stayed in my lane → +25
- One, and it was a stretch → +12
- Yes, more than one, comfortably → 0

**Q3. If your company pivoted to a technically adjacent-but-different area tomorrow, how do you feel? → `domainSelf`**
- I'd be out of my depth and I know it → +20
- I'd lean hard on hires; my instincts might mislead me → +12
- Fine — I'd learn it like I've learned everything else → 0

**Q4. Do your buyers, partners, or regulators require domain credibility to even engage? → `domainMarket`**
- Yes — without domain fluency, doors don't open (e.g. clinicians, regulators) → +40
- Somewhat — it helps a lot in key conversations → +20
- Not really — they care about the product, not my credentials → 0

**Q5. Is your domain itself the hard part of the business — regulation, science, compliance, safety? → `domainMarket`**
- Yes — the domain *is* the product (HealthTech, regulated FinTech, DeepTech, defense, biotech) → +35
- Partly — there's a real domain layer over a general product → +18
- No — it's general tech / SaaS / consumer / marketplace → 0

**Q6. Is the company's scope expanding into adjacent markets, or staying domain-focused? → `domainMarket` (inverse modifier)**
- Expanding into new domains/markets → −15 (lowers market dependency for current fit; raises expansion risk — see flag logic)
- Some adjacent exploration → −5
- Staying focused on our core domain → +10

*Note: Q6 is a modifier with a special role — "expanding" simultaneously lowers `domainMarket` and raises the **market-expansion risk flag**, because expansion is precisely what pushes a domain-expert CTO from the safe bottom-right cell into the high-risk bottom-left cell.*

**Section 4 scoring & flag logic** (from the 2×2 in `10_RESEARCH_domain_centric_CTO.md`):

```
domainSelf   = clamp(sum Q1–Q3, 0, 100)   →  HIGH if ≥ 45 (domain-centric)
domainMarket = clamp(sum Q4–Q6, 0, 100)   →  HIGH if ≥ 45 (domain-dependent)
expanding    = (Q6 == "Expanding")

if  domainSelf HIGH and domainMarket LOW:
        → DOMAIN-CENTRIC RISK   (bottom-left: curse-of-expertise / alignment-trap cell)
elif domainSelf HIGH and domainMarket HIGH and expanding:
        → MARKET-EXPANSION RISK (was safe bottom-right, scope is pushing toward bottom-left)
elif domainSelf HIGH and domainMarket HIGH:
        → TIME-LIMITED FIT NOTE (safe today, watch scope)
elif domainSelf LOW and domainMarket HIGH:
        → CREDIBILITY-GAP NOTE  (generalist in a domain market — needs domain VP/architect)
else:
        → NO FLAG               (generalist / general market — identity amplified by transitions)
```

---

## Output Format

Four outputs, rendered in order. Every output **must** quote back specific answers the taker gave — no generic language. Below, `{…}` are fill-ins the engine pulls from the highest-contributing answers.

### Output 1 — Company Mode

> **Your company is in the {CompanyMode} stage.**
> The clearest signals: {top 2–3 Section-1 facts, e.g. "Series A funding, 11–30 engineers, and revenue that exists but isn't yet scaling predictably."}

If transition-zone flag fired:

> ⚠️ **Your company is straddling the {ModeA}→{ModeB} boundary.** Your signals split between two stages — and the boundary is exactly where the most CTO transitions fail. Treat everything below as higher-stakes than a clean single-stage reading.

### Output 2 — CTO Operating Mode

> **You are currently operating as a {CTOMode}.**
> What says so: {top 2–3 Section-2/3 behaviors & identity signals, e.g. "you shipped critical-path code twice last week, you'd step in and fix a struggling engineer's hard part yourself, and a tech-free future 18 months out would feel like a loss."}

### Output 3 — Gap Assessment

**Match:**
> **Your operating mode matches what your company needs right now.** That's the goal — and it's worth protecting. Watch item: {the single nearest-boundary signal, e.g. "your company's manager-of-managers structure is one hire away from needing you to operate a level up. The behavior to watch: how often you still personally make the top technical call."}

**Lagging gap (highest risk):**
> **Your company has moved into {ModeB} territory, but you're still operating as a {ModeA}.** This is the highest-risk configuration in the framework. ~~it's where the average 2.5-year CTO tenure tends to end.~~ *(⚠️ the 2.5yr tenure figure is retracted — unsupported; see `07_APPENDIX` `AX-CTO-TENURE`. Whole quiz superseded by `16_`.)* This is not a verdict on your ability. The same mismatch breaks roughly half of engineers at the IC→manager step, under easier conditions than yours.
>
> The specific signals: {2–3 named behaviors, e.g. "you can name your team's top 3 blockers because you're personally working one; you'd fix a struggling engineer's problem yourself; and a tech-free future would feel like a loss."}
>
> *If wear-all-the-hats flag (S2-Q10 or S3-Q6):* "You told us {specific answer}. That pull isn't a discipline problem — it's the identity signal the research says most reliably predicts a stalled transition. The research on founder role transitions is unambiguous: the barrier isn't skill, it's whether you can find meaning in someone else's growth rather than your own output."
>
> *For lagging Builder→Multiplier specifically:* "Being central to every decision was exactly right at seed. The problem isn't that you were central then — it's that the pattern persists now, when your company needs something different from you."

**Leading gap:**

> **You're operating ahead of your company's current stage** — running a {CTOMode} playbook at a {CompanyMode} company.
>
> *⚑ PATCH — leading gap copy:* The risk here is concrete: at {CompanyMode} stage, the primary job is still {specific stage job}. A Strategist-mode CTO at a seed company isn't building the thing, isn't close enough to the team to unblock fast, and may be thinking about where the company should be in two years while nobody is shipping. The advantage — if it is one — is building the org and systems the next stage will need before it arrives. That's only an advantage if someone else has the current stage covered.
>
> "This can work if you have a strong technical co-founder or VP Engineering handling {CompanyMode}-stage execution. If you don't, the gap between your altitude and the day-to-day isn't strategic — it's a vacuum."

### Output 4 — Domain Risk Flag (only if triggered)

**Domain-centric risk:**
> **Domain risk: your expertise may be working against you here.** You read as deeply identified with your domain, but your market doesn't strictly require that depth — {if expanding: "and your scope is widening."}. This is the configuration where deep expertise quietly misfires across domain boundaries: confident, fast, and structurally wrong outside your lane. Teams built around one domain worldview also tend to validate each other's assumptions rather than challenge them. The defense is structural, not willpower: a credible dissenter outside your domain, and a pre-mortem before any cross-domain bet.

**Market-expansion risk:**
> **Domain risk: your fit is real today but scope-dependent.** Your deep domain expertise is a genuine asset in a domain-dependent market — it becomes a Strategist-stage superpower (regulatory credibility, the relationships generalists can't replicate). The flag: you're expanding beyond the core domain. The moment scope leaves your domain, that same expertise stops being calibrated. Pair yourself with breadth before the expansion, not after.

**Time-limited fit note:**
> **Domain note: strong fit, with a horizon.** Your domain depth matches a domain-dependent market — the best-case cell. It holds as long as the company stays in-domain. Keep one eye on scope.

**Credibility-gap note:**
> **Domain note: watch the credibility layer.** You're a generalist in a market where domain credibility opens doors. That's workable — generalist adaptability is the right primary trait — but make sure a domain-deep VP of Engineering or chief architect is carrying the credibility your buyers and partners expect.

**No flag:** *(Output 4 omitted entirely.)*

---

## Cross-check against Sonnet's caution list

| Caution | How this spec answers it |
|---|---|
| Multiplier questions too easy | S2-Q5, S3-Q2, S3-Q4, S3-Q7 deliberately make the Multiplier option the *less* flattering / less instinctive choice; "excited to learn" / "fix it myself" are decoys that score Builder. |
| Domain axis removed or collapsed | Section 4 is fully independent; produces its own 0–100 scores and its own Output 4, never feeds mode resolution. |
| Gap language softened to platitudes | Lagging-gap copy keeps weight ("highest-risk configuration," "where the average tenure ends") while de-personalizing blame. |
| Modes named in questions | No question text uses Builder/Multiplier/Strategist. Labels appear only in Outputs 1–3. |
| Asks skills not behavior/identity | S1 = objective facts, S2 = last-week behavior, S3 = identity/energy. No "how good are you at X" anywhere. |
| Produces a grade | Output is company-mode + cto-mode + gap, never good/bad. |
| Loses M&W identity orientation | Section 3 is built entirely on give-up-vs-wear-the-hats; Q8 is the explicit anchor; soft flags surface "all the hats." |
| CTO self-assesses company stage | Section 1 is observable facts only (team size, org shape, funding, revenue, risk, external relationships). |
| Sections 1 & 2 merged | Kept structurally separate with separate tallies (`company*` vs `cto*`) — the gap depends on it. |
| Transition zone lost | Explicit 20%-proximity rule on company tallies → dedicated ⚠️ block in Output 1. |
| Generic result language | Every output template quotes the taker's highest-contributing answers verbatim. |
| Domain framed as secondary | Output 4 is a peer output, labeled "Domain risk," with its own four-way flag logic. |
| Self-assessment reliability not addressed | Section 2 framing paragraph explains *why* the quiz asks about behavior rather than skill ratings. |
| Q10 soft flag missing | Patched: last option now triggers explicit wear-all-the-hats flag, surfaces in lagging-gap narrative. |
| Leading-gap copy too generic | Patched: concrete failure mode named (Strategist at seed = vacuum, not strategy); condition for it being an advantage made explicit. |
| Lagging-gap doesn't acknowledge seed-stage centralization was correct | Patched: S1-Q8 note and lagging-gap copy both acknowledge it. |

---

## Open decisions for the build

1. **Question count:** 8 + 10 + 8 + 6 = **32** total.
2. **Tie-breaking:** default to earlier mode (conservative — surfaces lagging gaps). Confirmed in scoring model.
3. **Persistence/sharing:** on-screen + print-friendly for v1. Export/sharing in v2 if needed.
4. **The 20% transition threshold** is tunable after we see real answer distributions.
5. **Wear-all-the-hats flag accumulation:** if both S2-Q10 and S3-Q6 fire, the flag should appear once in results with stronger language, not twice.
