# Audience Derivation Prompts — 5 Chats, One Per Actor

**Purpose:** Five separate chats, each producing an audience-specific version of the public draft from the *same* rigorous spine. Hand one prompt per chat. Each derived draft is a **projection** of `DRAFT_SYNTHESIS.md` (softening downward, losslessly) — **not a new argument.**

**Hard rule for all five (state it in every chat):** the rigorous spine `DRAFT_SYNTHESIS.md` is the **single source of truth**. A derived draft may *re-weight, re-voice, and drop* — it may **never add a claim not in the spine, nor restore a claim the spine's §5 concessions or `R3`'s must-not-claim table retired.** If a derived draft needs a claim the spine doesn't license, that's a finding to bring *back* to the spine, not to assert in the derivation.

**Shared inputs (every chat reads these first):**
- `CTO/DRAFT_SYNTHESIS.md` — the spine (§0–§5) + the **Audience Map** (each actor's column is that draft's brief)
- `CTO/R3_STEELMAN_strongest_form.md` — the must-not-claim table + the one-paragraph version
- `CTO/17_PREMISES_load_bearing_assumptions.md` — P1 (borrowed-evidence boundary), P2 (etymology contingent)
- `CTO/CONVENTIONS.md` — anchor scheme (keep `AX-`/`RISK-` discipline)

**Shared output spec:** `CTO/derived/DRAFT_SYNTHESIS_<actor>.md`. Commit when done. Keep the audience-map row for that actor at the top as the brief. Carry a one-line "derived from `DRAFT_SYNTHESIS` @ <commit>" provenance stamp.

---

## CHAT 1 — CTOs / Engineering Leaders

> You are writing an audience-specific version of a completed research paper, **for the people the paper is about: current and aspiring CTOs and engineering leaders.** It is a *projection* of an existing rigorous spine — you re-voice and re-weight it, you never add claims.
>
> **Read first:** `CTO/DRAFT_SYNTHESIS.md` (the spine — §0–§5 and the Audience Map; your column is "CTOs / eng leaders"), `CTO/R3_STEELMAN_strongest_form.md` (the must-not-claim table), `CTO/17_PREMISES_load_bearing_assumptions.md`.
>
> **The payload (what this audience needs):** the **non-pejorative reframe.** The single thing a CTO should walk away with: *"the ~50% isn't you — it's an identity switch the structure gave you no cushion for; 'he couldn't scale' is the structure talking, not a verdict on you."* Lead with §3 (misattribution) and §2's reversion reframe; §1 supplies the "you were told to pick a track, the founding seat made you skip the choice" framing.
>
> **Register:** plain, direct, low-jargon, second-person where it helps. Vivid but not motivational-poster. This is the version that gets *shared* among engineering leaders — it has to feel true to someone living it.
>
> **Drop / soften:** the four falsifiers (§5b) — drop them; keep only the honest *tone* ("we're describing a pattern, not predicting your future"). The borrowed-evidence boundaries (Premise 1) stay *true* but can be stated once, lightly, rather than at every claim.
>
> **Never:** tell them how to "win" the transition (no recipe — that's the survivor trap, `RISK-SURVIVORSHIP`). The deliverable is *legibility and relief from misattribution*, not a playbook. Don't promise the structure is fixable by the individual; §3c's "naming is necessary-but-not-sufficient" holds.
>
> **Length:** tight — 800–1500 words. A CTO reads this on a Sunday and feels *seen and re-oriented*, not lectured.
>
> Output to `CTO/derived/DRAFT_SYNTHESIS_cto_eng_leaders.md`.

---

## CHAT 2 — Founders / CEOs

> You are writing an audience-specific version of a completed research paper, **for founders and CEOs who hire, manage, and sometimes displace CTOs.** It is a *projection* of an existing rigorous spine — re-voice and re-weight, never add claims.
>
> **Read first:** `CTO/DRAFT_SYNTHESIS.md` (spine + Audience Map; your column is "Founders / CEOs"), `CTO/R3_STEELMAN_strongest_form.md`, `CTO/17_PREMISES_load_bearing_assumptions.md`.
>
> **The payload:** *name the mode, don't blame the person — and resource the transition before the boundary, because serial replacement never converges.* The CEO is the actor who can actually break the misattribution loop (§3b): instead of "replace the CTO," the move is "provide the cushions (honest label, fallback, a capable receiving team / VP-Eng hire, a real timeline) ahead of the boundary." §4's accidental-concession lands hard here: *"we couldn't afford to split it" already concedes it should be split — so plan for the split instead of being surprised by it.*
>
> **Register:** operator-to-operator, decision-oriented. A CEO wants "what do I *do* with this." Give them the diagnostic sentence ("we're at a Multiplier stage and resourced no transition") and the concrete moves it unlocks.
>
> **Drop / soften:** falsifiers → a light "here's where this could be wrong" footnote, not a section. Academic boundaries stay true, stated lightly.
>
> **Never:** imply the CEO should pre-emptively fire/replace (that *is* the broken loop). And do not claim the role is "irrational" (§5 concession 3) — to a CEO that reads as "your company is badly run"; the honest claim is "this is under-resourced and you can resource it."
>
> **Length:** 1000–1800 words. Practical, slightly more structured than the CTO version.
>
> Output to `CTO/derived/DRAFT_SYNTHESIS_founders_ceos.md`.

---

## CHAT 3 — Investors / Board

> You are writing an audience-specific version of a completed research paper, **for venture investors and board members** — the actors who, historically, *installed* the demand signal (the "do you have a CTO?" diligence reflex). It is a *projection* of an existing rigorous spine — re-voice and re-weight, never add claims.
>
> **Read first:** `CTO/DRAFT_SYNTHESIS.md` (spine + Audience Map; your column is "Investors / board"), `CTO/R3_STEELMAN_strongest_form.md`, `CTO/17_PREMISES`. Also skim `CTO/09_RESEARCH_cross_role_pattern.md` §3.3 (investor-signaling) — **but carry its `RISK-INVESTOR-CAUSAL` guard: "consistent with the title functioning as an investor signal," NOT "investors caused the failure."**
>
> **The payload:** *the diligence question isn't "do they have a CTO" but "what mode does the company need, and is the CTO in it" — and the VP-Eng split you defer is the cushion you removed.* This audience uniquely gets §4 from the inside (they price the composite) and §5's F2 falsifier as *their own portfolio experiment to run* (do early-split startups survive technical leadership better?). The honest sharp edge (§3, handled carefully): the replacement loop is a **cost the investor is already paying** — 12–24mo strategic gaps per cycle (practitioner-sourced) — for a failure the signal helped select for.
>
> **Register:** analytical, risk-and-returns framed, peer-level. No moralizing. The move is "here is a mispriced risk and a cheap diligence change," not "you broke this."
>
> **Drop / soften:** keep one or two falsifiers (this audience respects stated disconfirmers); state F2 as actionable.
>
> **Never:** assert the causal "investors caused it" claim (`RISK-INVESTOR-CAUSAL`). Frame as signaling/incentive, "consistent with," co-authorship-not-blame. Don't lean on the $1.1M as a hard number (§5 concession 4) — investors will recompute it; use the qualitative "split-when-affordable" revealed-preference argument, which is number-independent.
>
> **Length:** 1000–1800 words.
>
> Output to `CTO/derived/DRAFT_SYNTHESIS_investors_board.md`.

---

## CHAT 4 — Academic / Researcher

> You are writing an audience-specific version of a completed research paper, **for an academic / researcher audience** — the people who could actually run the studies that would confirm or break the thesis. It is a *projection* of an existing rigorous spine. For this audience, the projection is *closest to the spine* — you may keep nearly all of it; your job is emphasis and research-agenda framing, not simplification.
>
> **Read first:** `CTO/DRAFT_SYNTHESIS.md` (spine + Audience Map; your column is "Academic / researcher"), `CTO/R3_STEELMAN_strongest_form.md`, `CTO/R4_OPEN_RESEARCH_agenda.md` (the open studies), `CTO/17_PREMISES`, `CTO/R2_FALSIFICATION_and_bias_audit.md` (the falsification protocol).
>
> **The payload:** *the falsifiers are the deliverable.* §5b's F1–F4 are study designs; `GAP-CTO-TRANSITION` is the central unrun cohort study. Lead with what is *established* (the IC/management institutional fact §1 — needs no framework; the n≈30,000 behavioral anchor §2) vs. what is *framework* (the three-mode lens, the CTO-specific severity = the corpus's extension per Premise 1). The honest framing the corpus insists on: **this is a framework with strong component grounding and an unrun central experiment** — present it as that, with the experiment specified.
>
> **Register:** rigorous, citation-precise, concedes openly. This audience *rewards* the concessions and falsifiers — foreground them. State the bias disclosure (`R2` Bias 8: the n≈4 firsthand origin, mitigated by evidence-independence) up front; it's a credibility asset here.
>
> **Drop:** almost nothing. This is the version that keeps §5 in full and *expands* the research agenda. Drop only the practitioner-vivid framings that don't carry evidential weight.
>
> **Never:** overclaim the framework as a finding (the cardinal sin for this audience). Every "framework vs. finding" line in the spine stays. Flag T2/T4 (the cultural-expectation studies, see `CTO/TODO.md`) as open adjacent research.
>
> **Length:** can run longer — 1800–3000 words. This is the citable version.
>
> Output to `CTO/derived/DRAFT_SYNTHESIS_academic.md`.

---

## CHAT 5 — Job Boards / Recruiters

> You are writing an audience-specific version of a completed research paper, **for the people who write and place the job descriptions: recruiters, talent teams, job-board taxonomy owners.** They are the actors who *operationalize* the composite into the JD ("CTO/VP-Eng, hands-on AND strategic"). It is a *projection* of an existing rigorous spine — re-voice and re-weight, never add claims.
>
> **Read first:** `CTO/DRAFT_SYNTHESIS.md` (spine + Audience Map; your column is "Job boards / recruiters"), `CTO/R3_STEELMAN_strongest_form.md`, `CTO/17_PREMISES`. Also `CTO/12_RESEARCH_rational_solutions.md` for the "combined CTO/VP-Eng JD attracts mediocre-at-both" point.
>
> **The payload:** *the JD that demands the composite is the first link in the misattribution loop — and the CRO/VP-Sales split is the template you already apply in sales but not in engineering.* The practical move: "hands-on AND strategic" demands both sides of a boundary half the field can't cross once (§2's reversion); writing the composite JD selects for people who will then be blamed for not being superhuman (§3). The §4 line for this audience: the "full-stack CTO forever" JD is **a budget compromise dressed as a requirement.** §5 concession 2 reassures them: you're not being told to stop writing CTO roles — to stop writing the *composite* one.
>
> **Register:** practical, taxonomy-aware, concrete. This audience thinks in titles, levels, and search filters. Give them the *distinction* (Builder-mode vs Multiplier-mode vs Strategist-mode hiring criteria) as something operational — what to actually put in the req at each stage.
>
> **Drop:** the falsifiers, most of the academic boundaries. Keep it short and usable.
>
> **Never:** turn it into a "how to hire a unicorn CTO" guide (the opposite of the message). The message is *stop specifying the unicorn.* No recipe for finding someone who *can* do all three (`RISK-SURVIVORSHIP`).
>
> **Length:** short — 600–1200 words. Closer to a practitioner brief than an essay.
>
> Output to `CTO/derived/DRAFT_SYNTHESIS_recruiters.md`.

---

## After all five

Each derived draft should be auditable against the spine the same way the increments were: a derived claim that isn't traceable to a spine section (or that restores a retired claim) is a defect. A quick post-pass: grep each derived draft for the must-not-claim left-column phrases ("mismatch of kind", "irrational", "survivor-proof", "investors caused") — any hit that isn't a *denial* is a regression to fix.

*Derived from `DRAFT_SYNTHESIS.md` (spine §0–§5 complete). One actor per chat; consistency enforced by the shared spine + must-not-claim discipline.*
