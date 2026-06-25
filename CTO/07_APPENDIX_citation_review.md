# Appendix: Citation Review & Verification Log

**Purpose:** Rate every citation in the CTO Operating Modes corpus for verifiability and load-bearing weight before publication.
**Status:** In progress — ratings to be filled in by researcher.
**Created:** 2026-06-24

---

## How to use this appendix

For each citation, fill in the three rating columns:

- **Verified?** — `✅ Yes` (found the primary source, claim matches) · `⚠️ Partial` (source exists, claim is paraphrased/stretched) · `❌ No` (could not locate) · `⬜ Not yet checked`
- **Load-bearing?** — `High` (an argument collapses if this is wrong) · `Medium` (supports but not sole support) · `Low` (illustrative/color)
- **Confidence** — your subjective 1–5 on how solid the citation is after checking.

Priority = high load-bearing × unverified. Those are the publication risks.

---

## Draft-anchored callouts (08_DRAFT new sections — bidirectional)

These three callouts are linked from `08_DRAFT_skills_divergence_thesis.md` by matching `<!-- APPENDIX-REF: <ID> -->` comments. Each anchor ID below points back to the draft location it serves. When verifying, update status here; when editing the draft claim, check the anchor still matches. *(These came in after the cross-role research — `09_RESEARCH_cross_role_pattern.md` holds the full analysis behind each.)*

### `AX-MW2018` — Mathias & Williams (2018), transformation model + identity mechanism ✅ VERIFIED (full text)
- **Draft location:** `08_DRAFT` §1, after the "How the transformation fails" table.
- **Claim it supports:** the offload-and-acquire (transformation) model is peer-reviewed-grounded, and the *slippage* failure mode has a named cause (role-identity attachment).
- **Source:** Mathias, B.D. & Williams, D.W. (2018). "Giving up the hats? Entrepreneurs' role transitions and venture growth." *Journal of Business Venturing*, 33(3), 261–277. DOI 10.1016/j.jbusvent.2017.12.007.
- **Verified?** ✅ **Full text read** (purchased PDF, 2026-06-24). **Load-bearing?** High (only peer-reviewed anchor for the core model). **Confidence** — **5**.
- **What the full text confirms (beyond the abstract):**
  - **Method:** inductive field study, **45 entrepreneurs**, varied growth trajectories. (N was not in the abstract.)
  - **Transformation model verbatim:** entrepreneurs decide "which roles to **give up**, which roles to **retain**, and which new roles to **adopt**" = offload-and-acquire. ✅
  - **Identity as the blocker, verbatim:** roles "become deeply meaningful and self-defining... difficult to relinquish." Grounds the *slippage* failure mode. ✅
  - **NEW — physical vs. psychological disengagement:** growth depends on founders *physically* giving up enacting a role identity, but **not** necessarily *psychologically* withdrawing from it. They keep the meaning, drop the activity. (Answers the identity-threat objection — upgrade for `08_DRAFT`.)
  - **NEW — named success mechanism ("role identity imprinting"):** founders offload by *imprinting* the role onto an employee (training/molding them to value the work); seeing their "stamp" on that person is what lets them move on. Fig. 1 failure paths — "Belief that no one can 'be me'," "Failure to see employees as an extension of one's self" — are the won't-delegate slippage mode, peer-reviewed. (This is the *predictor of success* the abstract withheld.)
- **Caveat to preserve:** sample is entrepreneurs/founders broadly, not CTOs; the CTO-specific application remains our extension (consistent with `09_RESEARCH` "does not solve it for the CTO").

### `AX-VL2023` — Van Lancker et al. (2023), the offload SUCCESS CONDITIONS ✅ VERIFIED (full text)
- **Source location:** `09_RESEARCH` (the "success-predictor" companion to `AX-MW2018`). Candidate for `08_DRAFT` §1 / new solutions section.
- **Claim it supports:** the offload half of the transformation has *named, peer-reviewed success conditions* — the gap the MW2018 abstract left open.
- **Source:** Van Lancker, E., Knockaert, M., Collewaert, V., & Breugst, N. (2023). "Preparing for scaling: A study on founder role evolution." *Journal of Business Venturing*, 38(?), article 106315. DOI 10.1016/j.jbusvent.2023.106315. **⚠️ Year is 2023, not 2024** — corpus had mislabeled it "2024 companion." In-depth case study + multi-method.
- **Verified?** ✅ **Full text read** (purchased PDF, 2026-06-24). **Load-bearing?** Medium-High (supplies the solution mechanism). **Confidence** — **5**.
- **What it establishes:**
  - **Founders offload via "joiners" taking over roles** ("role set decrease") — directly the offload mechanism, and explicitly builds on Mathias & Williams (2018).
  - **Two success conditions for the offload to stick:** (1) **psychological safety** experienced by the joiner — and it cites **Edmondson (1999)**, the *same* construct already in our corpus via Project Aristotle (independent convergence); (2) **value fit** perceived by the founder. Low value fit → founder pulls the role back (the won't-delegate slippage, from the founder's side).
  - **Dovetails with MW2018 "role identity imprinting":** both papers converge — the offload succeeds when the founder trusts the receiver shares their values. Two independent JBV studies, same conclusion.
- **Why it matters:** this is the *constructive* half — the framework can now say what a successful transformation **requires** (psych safety + value fit in the receiving team), not just how it fails. Strengthens `08_DRAFT` §1 and the solutions story (`12_RESEARCH` Solution 3/5).
- **Caveat:** single-company in-depth case study (deep but narrow N); founders generally, not CTOs.

### `AX-SCOPEKIND` — C-suite origin comparison; scope-vs-kind
- **Draft location:** `08_DRAFT` §3.2 (the keystone blockquote).
- **Claim it supports:** every C-suite title imported a *scope* mismatch at startup scale; only the CTO imported a *kind* mismatch (focus rotates, due to the IC/management bifurcation).
- **Sources (all first-pass content sites — VERIFY each):** CEO ~1917 origin (unsourced); CFO 1970s–80s / 1979 accounting trigger (LinkedIn, Sage); CMO 1993 Coca-Cola (AMA, Wikipedia); CMO tenure ~40mo 2020 (content site — Spencer Stuart is the usual primary).
- **Partial verification (2026-06-24):**
  - **Adler & Ferdows (1990)** ✅ confirmed — *California Management Review* **32(3)**, 55–62 (the CTO origin anchor). ⚠️ but the "25 CTOs in 100 companies" specific figures were NOT confirmed in search, and the corpus's "25" may be a garble of *volume 32* — confirm the 25/100 from the PDF if available (`AX-SCOPEKIND` shares this with master-table #1).
  - **CMO tenure ❌ CORRECTED:** corpus said "~40 months (2020), lowest in a decade." Spencer Stuart's actual figure: **4.2 years (2023), unchanged YoY, NOT a decade low.** The "40mo/decade-low" stat is wrong. The CMO-as-emerging-second-instance point survives *directionally* (CMO tenure is among the shortest C-suite tenures) but the specific number must be cut or replaced with 4.2yr.
  - CEO 1917, CFO 1979 trigger, CMO 1993/Coca-Cola — ⬜ still unverified (next batch).
- **Verified?** ⚠️ Partial — Adler & Ferdows core confirmed; CMO tenure corrected; other dates pending. **Load-bearing?** High (keystone argument). **Confidence** — 3 and rising. **Note:** the *logic* (Mill's method of difference) holds independent of exact dates, but each origin date must be defensible since the argument parades them. Full analysis: `09_RESEARCH` keystone section.

### `AX-INVESTOR` — investor-signaling causal chain
- **Draft location:** `08_DRAFT` §3.3 (the "investors helped create the problem" blockquote).
- **Claim it supports:** the misnomer was *installed/maintained* by investor signaling, not merely inherited.
- **Sources (all first-pass content/industry sites — VERIFY):** Cobloom, WTT-solutions (~90% prefer technical cofounder), Deckary/Seedscope (team-slide weighting), CFA Institute ("management by press release," >80% late-90s IPOs loss-making — most credible, cite directly).
- **Verified?** ⬜ Not yet. **Load-bearing?** Medium-High (powerful but not load-bearing for the core skills argument — it's the *cause* story, not the *structure*). **Confidence** — to set. **⚠️ FRAMING CAUTION:** this is a causal *narrative* assembled from signaling evidence, not a measured causal study. Published form must claim "evidence is **consistent with** the title functioning as an investor signal," NOT "investors caused the failure." The strong version is argument; the defensible version publishes. Full analysis: `09_RESEARCH` causal-mechanism section.

### `AX-COMPRESSION` — the $1.1M distributed cost / ~4–6:1 compression ratio
- **Source location:** `10_RESEARCH_who_does_cto_work.md` Part 2 + headline + methodology note. (Not yet in `08_DRAFT` — economic argument is a candidate new draft section.)
- **Claim it supports:** seed-stage CTO compresses ~$1.1M of distributed-role work into ~$177K cash; the compression is the equilibrium that keeps the composite stable.
- **Sources (mostly content sites — VERIFY against comp-survey primaries):** ctaio.dev salary medians (EM ~$220K, VP Eng ~$300K, Staff/Principal ~$275K); christianandtimbers.com; kompella.io. **Primaries to substitute:** Levels.fyi, Pave, Radford, or Kruze's own dataset.
- **Status update (2026-06-24):** headline softened from a flat `6:1` to a **`~4–6:1` cash-basis band** across all five mention sites in `10_RESEARCH`; methodology note added explaining the band. The `RISK-COMPRESSION-RATIO` distortion is now disclosed in-text rather than latent. ✅ framing fixed; ⬜ source numbers still unverified.
- **Verified?** ⬜ Not yet (numbers). **Load-bearing?** **High** — headline number of the economic finding. **Confidence** — to set. **Paired RISK:** `RISK-COMPRESSION-RATIO` (below).

> **⬜ OPEN DATA NEED — full founding-CTO equity package.** To convert the `~4–6:1` band into a single defensible figure (and to compute the break-even multiple in `10_RESEARCH` Open Question #1), we need: (1) typical founding-CTO **equity grant size** at seed and Series A (%), (2) the **dilution schedule** across subsequent rounds, (3) a **liquidity-probability discount** (P(reaching a liquidity event) for the relevant cohort). Candidate sources: Carta, Index Ventures *Rewarding Talent* (corpus #12), AngelList/Kruze equity data. Until obtained, the cash-basis band is the honest published claim. *This is the single most valuable piece of missing data for the economic argument.*

### `AX-EQUITY-PREMIUM` — 20–50% co-founder equity as revealed price of Builder-mode work
- **Source location:** `10_RESEARCH` Part 1.
- **Claim it supports:** the market's revealed price for irreplaceable Builder-mode work is 20–50% equity (vs $133K cash when it doesn't acknowledge the cost).
- **Source:** icanpitch.com (content site). **Verify** against a co-founder-equity dataset (Carta, Index Ventures Rewarding Talent — already in corpus as #12).
- **Verified?** ⬜ Not yet. **Load-bearing?** Medium (supports the Part 1 "no market substitute" point; the equity range is wide). **Confidence** — to set.

### `AX-REVERSION` — the ~50% IC→EM reversion rate ✅ VERIFIED (source) + UPGRADED (corroboration)
- **Source location:** `11_RESEARCH` Stage 1.
- **Claim it supports:** the IC→EM transition (the proxy for Builder→Multiplier) reverts ~50% *even with* org support — so training the founding CTO through it, alone and faster, is asking them to beat a transition that breaks supported engineers. **The single most load-bearing empirical number in the corpus.**
- **Source:** Marcel Weekes (Figma, ex-Slack), [First Round Review](https://review.firstround.com/new-engineering-manager-advice/) — confirmed real; the "at least half the time" is a **named-practitioner estimate, not a measured study.**
- **Verified? ✅ (2026-06-24)** — quote and attribution confirmed, AND **corroborated by large-sample management research** that the original didn't cite:
  - **CEB / Gartner: 50% of executives fail within 18 months** of promotion (2013 study, n ≈ 30,000 leaders).
  - **CEB / Gartner: 60% of new managers fail within 24 months** (industry-baseline figure).
  - **McKinsey: ~40% failure rate for newly promoted/hired executives** (stable over 15 years).
- **Load-bearing?** **High.** **Confidence — 4.** **How to present:** keep Weekes as the vivid framing, but anchor the *number* to CEB/Gartner ("management research finds roughly half of new managers/executives fail within 18–24 months"). This moves it from one VP's estimate to estimate-plus-large-sample-corroboration — a real strengthening.
- Sources: [First Round Review](https://review.firstround.com/new-engineering-manager-advice/); CEB/Gartner new-manager failure data (2013, n≈30,000); McKinsey leadership transitions (2014).

### `AX-CURSE` — the curse of expertise (cross-domain failure mechanism) ✅ VERIFIED
- **Source location:** `13_RESEARCH` §Failure Cascade #2; `14_RESEARCH` Findings 1 & 4. **This is the human-domain replacement for TEE** (`#10`) as the load-bearing cross-domain failure mechanism.
- **Claim it supports:** deep expertise in one domain *actively interferes* with competence in an adjacent one — confident, miscalibrated pattern-matching that awareness can't fix.
- **Sources (all ✅ verified 2026-06-24, peer-reviewed):**
  - **Camerer, Loewenstein & Weber (1989)** — "The Curse of Knowledge in Economic Settings," *J. Political Economy* 97(5):1232–54. The foundational curse-of-knowledge paper.
  - **Hinds (1999)** — "The Curse of Expertise," *J. Experimental Psychology: Applied* 5:205–221. Experts worse than intermediates at predicting novice difficulty AND **resistant to debiasing** — the keystone for "awareness doesn't fix it."
  - **Gupta, Boland & Aron (2017)** — "The physician's experience of changing clinical practice: a struggle to unlearn," *Implementation Science* (15 physician interviews, Cleveland VA). Deep unlearning > learning.
- **Load-bearing? High.** **Confidence — 5.** **This is strictly better than the TEE citation it replaces** — three peer-reviewed human-cognition sources vs. one AI-systems paper. Pairs with Dunning-Kruger cross-domain (#21, ✅) and competence trap / March 1991 (#20, ✅).
- **⚠️ Sub-caveats in `14_RESEARCH` to fix:** (a) the **"17-year evidence-to-practice gap"** (Balas & Boren 2000) is real but NOT a universal figure — it's "17yr for 14% of findings," an average across few specialties; soften the phrasing. (b) Ericsson "10,000 hours" and the Feldon bootcamp study still ⬜ unverified (next pass). (c) `14` cites "Mars (2026)/TEE" twice — now reframed as analogy.

### `AX-VPENG-TIMELINE` — 8–15 year IC→VP Eng path
- **Source location:** `11_RESEARCH` timeline + summary table.
- **Claim it supports:** the full Builder→Multiplier→(VP) path takes 8–15 years; the founding CTO is asked to do it in 18–24 months. The compression that makes training implausible.
- **Source:** em-tools.io (content site). Corroborate with USD "10-year minimum" claim (University of San Diego) already in `11`.
- **Verified?** ⬜ Not yet. **Load-bearing?** High (the 8–15 vs 18–24 contrast is a headline visual). **Confidence** — to set.

### `AX-CTO-TENURE` — 2.5-year average CTO tenure ❌ NOT SUPPORTED — claim must change
- **Source location:** `12_RESEARCH` Solution 2.
- **Claim it supports:** avg CTO tenure ≈ the Builder→Multiplier window — the industry cycles CTOs at exactly the transition boundary without naming it.
- **Original source as cited:** "Spencer Stuart, 2023, 2.5 years."
- **Verified? ❌ FAILED (2026-06-24).** No source supports a 2.5-year CTO tenure; the Spencer Stuart attribution could not be confirmed. **Contradicting evidence:** Korn Ferry puts CIO/CTO tenure at **~4.3 years** (2016); overall C-suite avg **4.9 years** (2019, Korn Ferry); Spencer Stuart's *CTO* page shows no tenure figure. The figure appears **fabricated or badly garbled.**
- **What IS defensible (use instead):** tech executives turn over *faster than other C-suite roles* — **56% of tech execs changed employers in 2021** (Russell Reynolds, via Fortune 2023); ~half say they'd switch for the right opportunity. That supports "high CTO churn" but **NOT** "tenure ≈ the 2.5yr transition window."
- **Action:** ✅ **DONE (2026-06-24)** — `12_RESEARCH` Solution 2 rewritten: 2.5yr claim removed, replaced with churn framing (Russell Reynolds 56%/2021; Korn Ferry ~4.3yr), boundary-timing re-pointed to Greiner/Carta. **Confidence — 1** in original; ~4 in churn replacement.
- Sources: [Fortune 2023 (CTO job-hopping)](https://fortune.com/2023/02/21/chief-technology-officer-in-demand-retention-job-hop-cto/); Korn Ferry C-suite tenure analysis.

### `AX-COMPETENCE` — competence trap + cross-domain overconfidence (the HUMAN boundary-failure mechanism)
- **Draft location:** `08_DRAFT` §1 (replaced the TEE citation as the load-bearing mechanism).
- **Claim it supports:** skill in one mode actively resists the next — via the competence trap (over-exploit existing competence) and Dunning-Kruger-style cross-domain overconfidence. These are *human-domain* mechanisms, unlike TEE (#10, an AI-systems paper).
- **Sources:** competence trap → **March (1991), *Organization Science* 2:71–87** ✅ (master table #20); cross-domain overconfidence → Dunning-Kruger cross-domain extension ✅ (#21).
- **Verified? ✅ (2026-06-24)** — both underpinnings confirmed. March (1991) is the canonical competence-trap source; the cross-domain D-K application is documented and defensible. **Load-bearing?** **High** (carries what TEE used to). **Confidence — 5.** This is now a *better-grounded* mechanism than the TEE citation it replaced — both are peer-reviewed and in the correct (human) domain.

### `AX-INDEX78` — Index Ventures 78% (corrected)
- **Location:** `10_RESEARCH` Open Q4; also `00_CONTEXT`. Mirrors master table #12.
- **Corrected claim:** "78% of successful companies had a founding CTO **or technical CEO**" (210-company dataset) — NOT "founding CTO at seed." ✅ Fixed in source 2026-06-24.

### `AX-ATROPHY` — IC/management track divergence + skill atrophy (corrected)
- **Draft location:** `08_DRAFT` §2a; also `11`, `12`.
- **Corrected claim:** technical skills atrophy after the move into management — kept as a **qualitative, well-corroborated** claim; the "2–3 year" precision and "HR Oasis" attribution were dropped. Mirrors master table #13 (Ewing) / #14 (HR Oasis). ✅ Fixed in source 2026-06-24.

### `AX-BIFURCATION-COST` — CTO + VP Eng combined cost $350–600K
- **Source location:** `12_RESEARCH` Solution 3.
- **Claim it supports:** the cleanest structural fix (early role split) costs +$173–423K over a solo CTO — unaffordable pre-Series A. Why the correct solution has wrong timing.
- **Source:** derived from the **same content-site comp medians as `AX-COMPRESSION`** — verify the two together against one primary (Levels.fyi / Pave / Radford).
- **Verified?** ⬜ Not yet. **Load-bearing?** Medium. **Confidence** — to set. Shares fate with `AX-COMPRESSION`.

---

## Research gaps (GAP- anchors)

### `GAP-CTO-TRANSITION` — founding-CTO Builder→Multiplier success rate is unstudied
- **Anchor site:** `11_RESEARCH` "What No One Has Studied."
- **The gap:** no study measures what proportion of founding CTOs successfully make the Builder→Multiplier transition, or what predicts success. This is **the framework's central falsifiable test** — the one study that would validate or break it.
- **Not a citation to verify — a gap to state honestly.** In the draft, present as the headline item of the research agenda. Consistent with (and distinct from) `RISK-ASYMMETRY`: the Builder mode is under-researched, which the framework predicts.

---

## Framing-risk register (RISK- anchors)

### `RISK-COMPRESSION-RATIO` — the 6:1 number is cash-vs-total-comp ✅ RESOLVED (framing)
- **Claim site:** `10_RESEARCH` headline + Part 2 + Part 4 + reference table (paired with `AX-COMPRESSION`).
- **The risk:** the ratio divides the CTO's **cash-only** comp (~$177K) into the distributed roles' **total-cash** comp (~$1.1M), implicitly valuing the CTO's equity at zero. A reviewer who adds the CTO's equity back recomputes a lower ratio (~4:1). The number is also built on content-site medians (see `AX-COMPRESSION`).
- **Resolution (done 2026-06-24):** restated as a **range "~4–6:1 on cash"** at all five sites; added a Part 2 methodology note showing the band (6:1 = CTO equity at zero; 4:1 = equity risk-discounted and added back) and framing the gap as itself the argument. **Framing risk closed.** Remaining work is *data*, not framing — see the OPEN DATA NEED under `AX-COMPRESSION` (full equity package). The numbers behind $1.1M still need primary-source verification (separate from this risk).
- **Status:** ⬜ Open. Registered in `CONVENTIONS.md`.

---

## Pre-flagged for review

These are the citations I flagged on first read as needing verification before publication. They are pre-marked `⬜ Not yet checked` and called out here so they don't get lost in the table below.

1. **Mars, F. (2026) — Transitive Expert Error (TEE)** — Load-bearing **High**. This is the *primary named mechanism* for Builder→Multiplier failure (Cluster 3, footnote 9). A 2026 theoretical paper attributed to a single author. If thin, recently coined, or AI-surfaced, the failure mechanism needs a second anchor (the Competence Trap and Dunning-Kruger findings can partially carry it).
2. **HR Oasis (2026) — technical skill atrophy within 2-3 years of management** — Load-bearing **High**. Footnote 13. This number directly supports the IC/management bifurcation argument in Section 10 (the irrational composite). "HR Oasis" reads like a content site, not peer-reviewed — verify the underlying study it's citing.
3. **The classification asymmetry itself (0 Strategist / ~2 Builder / 22 Multiplier)** — Not a citation but a *structural claim* presented as evidence. See the dedicated review note below — this one has multiple appearances across the corpus and needs to be re-graded everywhere it's framed as confirmation rather than gap.

---

## Review note: the "asymmetry as evidence" claim (PRE-FLAGGED #3)
<!-- RISK: RISK-ASYMMETRY — "0 Strategist findings" used as confirmation = arguing-from-silence. Claim sites: 00_RESEARCH_CONTEXT, 04_RESEARCH_classification_table (locs A–G below), 05_FULLTEXT §10.4. -->
<!-- XREF: XR-ASYMMETRY-DRAFT — guarded in 08_DRAFT §4 (do-not-reuse note). -->


**The problem (researcher's own finding):** The asymmetry was a second-hand remark that got baked in and hardened into a load-bearing argument. Technically it is **just a research gap**. It is currently framed in several places as *confirming evidence* — "this is not a flaw, it's a research population limitation that the taxonomy explains." That framing converts an absence of data into positive support, which is a textbook **selection-bias / arguing-from-silence** move. The bias is especially severe here because the ~35 threads were gathered in a single session oriented around the taxonomy itself — the sample was not assembled to test the taxonomy, so it cannot validate it.

**What to decide on review:** For each location below, choose one of:
- **(a) Downgrade to gap** — state plainly "no research found," drop the "this confirms the taxonomy" inference.
- **(b) Keep but caveat** — retain the observation, explicitly name the selection bias and arguing-from-silence risk in-line.
- **(c) Cut** — remove the claim where it adds rhetorical weight without earning it.

Recommended default: **(a)** for the headline/summary instances, **(b)** for the Project Oxygen note (where the population-limitation point is genuinely informative *about Oxygen*, not about the taxonomy).

**Every location the claim appears:**

| Loc | File / line | How it's currently framed | Suggested action |
|---|---|---|---|
| A | `00_RESEARCH_CONTEXT.md:88` | Table row: "Strategist — 0 peer-reviewed findings" | (b) Keep as gap; ensure not cited elsewhere as support. |
| B | `00_RESEARCH_CONTEXT.md:91` | "This is not a flaw in the taxonomy; it's a research population limitation that the taxonomy now explains." | (b) Caveat — this is the canonical "absence → confirmation" sentence. |
| C | `00_RESEARCH_CONTEXT.md:103` | "The research gap as evidence (management literature's blind spot ... confirms Builder mode's structural invisibility)" | **(a/c) Strongest offender** — literally titled "research gap as evidence." Downgrade or cut. |
| D | `04_RESEARCH_classification_table.md:6` | Key finding: "This is not a taxonomy failure — it's a research population limitation that the taxonomy explains." | (b) Caveat — mirrors B. |
| E | `04_RESEARCH_classification_table.md:27` | Oxygen row: "Zero Builder behaviors ... no Builders in scope." | (b) Keep — informative about Oxygen's population specifically. |
| F | `04_RESEARCH_classification_table.md:139` | Summary stat: "Strategist (pure) — 0 — 0%" | (a) Fine as a stat; problem is only the inference drawn from it. |
| G | `04_RESEARCH_classification_table.md:142` | Closing "The finding": "Builder mode is structurally invisible to the field..." | (b) Caveat — generalizes from one study (Oxygen) to "the entire management research literature." |

**Verified?** ⬜ Not yet reviewed · **Load-bearing?** High (it's used as a pillar of the "irrationality is real, not anecdotal" case) · **Confidence** — to be set after the in-line edits are made.

**Note for when Sonnet rebuilds the `.docx`:** this claim almost certainly also appears in Section 4 (failure clustering) and Section 9 (limitations) of the working document. Re-scan the reconstructed `.docx` for the same phrasings and apply the same decision.

---

## Sources from the 10/11/12 research wave (economic / solutions / training)

Citations introduced by the later research files, separate from the original document's footnotes. **Almost all are content/marketing sites or named-practitioner quotes — none are peer-reviewed.** This whole block needs primary-source substitution or explicit "practitioner estimate" framing before publication. Anchored ones link to the callouts above.

| Source | File(s) | Supports | Anchor | Authority | Verify action |
|---|---|---|---|---|---|
| Kruze Consulting (2024) | 10, 11, 12 | Founding-CTO cash comp ($133K/$177K) | (corpus #9) | **Named firm — strongest** | Confirm figures; already partly in master table. |
| Spencer Stuart (2023) | 12 | 2.5yr avg CTO tenure | `AX-CTO-TENURE` | **Named firm — strong** | Confirm figure + year. |
| Weekes / First Round Review | 11 | ~50% IC→EM reversion | `AX-REVERSION` | Named practitioner | Trace to dataset or reframe as estimate. **High priority.** |
| Charity Majors (Honeycomb) | 11 | 5–7yr senior-IC prerequisite; pendulum | — | Named practitioner | Quote accurate; fine as practitioner view. |
| Pat Kua | 11 | "EM is a role change, not promotion" | — | Named practitioner | Quote check. |
| Intuit Engineering | 11 | 82% balancing team vs mgmt | — | Company blog | Verify the 82%. |
| em-tools.io | 11 | 8–15yr IC→VP path | `AX-VPENG-TIMELINE` | Content site | Substitute primary. |
| University of San Diego | 11 | VP Eng "10yr minimum" | — | .edu content | Corroborates timeline; OK. |
| ctaio.dev | 10 | EM/VP/Staff salary medians | `AX-COMPRESSION`, `AX-BIFURCATION-COST` | Content site | **Substitute Levels.fyi/Pave/Radford.** |
| christianandtimbers.com | 10, 12 | CTO vs VP Eng comp + split timing | `AX-COMPRESSION` | Recruiter site | Substitute / corroborate. |
| kompella.io | 10, 12 | Fractional CTO trends; split-at-15–20-eng | (Sol 3/4) | Content site | Substitute / corroborate. |
| wtt-solutions.com | 10, 12 | 85% investor pref; 90% technical-cofounder pref | `AX-INVESTOR`, `AX-EQUITY-PREMIUM` | Content site | Substitute; load-bearing for investor signal. |
| cobloom.com | 10 | "Who is your technical leader?" | `AX-INVESTOR` | Content site | Substitute / corroborate. |
| deckary.com | 10 | Team-slide standard-titles advice | `AX-INVESTOR` | Content site | Substitute. |
| icanpitch.com | 10 | 20–50% co-founder equity | `AX-EQUITY-PREMIUM` | Content site | Substitute Carta / Index Ventures. |
| thelaunch.space | 10 | 160% more likely to reach Series A | — | Content site | **Verify — strong claim, weak source.** |
| profoundiq.com | 12 | Fractional CTO definition | — | Content site | Color quote; low stakes. |
| Mark Suster / Both Sides | 12 | "get your chief architect" → VP Eng | — | Named practitioner (VC) | Quote check; good source. |
| Jellyfish Engineering | 12 | Roles split at 15–20 engineers | — | Company blog | Corroborates bifurcation timing. |
| Airbnb/HashiCorp/Dropbox examples | 12 | Founding-CTO role-transition cases | — | Public record | Verify each transition's accuracy. |

---

## Master citation table

*(Original document footnotes / classification-table sources — files `00`–`06`.)*

| # | Citation | Used for / where | Verified? | Load-bearing? | Confidence | Notes |
|---|---|---|---|---|---|---|
| 1 | Adler & Ferdows (1990) | First academic CTO documentation; 25 CTOs in 100 firms (Etymology, fn1) | ⚠️ | High | 4 | ✅ Paper real — *Calif. Mgmt Review* **32**(3):55–62, 1990. ⚠️ "25 CTOs/100 firms" unconfirmed; the "25" may be a garble of *vol 32*. Confirm from PDF. |
| 2 | Smith (2002) via Jasinski (2018) | GE/Allied-Signal/ALCOA origin (Etymology, fn2) | ⚠️ | High | 4 | ✅ **Substance confirmed**: Allied-Signal & ALCOA elevated R&D heads to CTO in late 1980s; GE (Walter Robb, GE Medical) had a CTO in the 1980s. ⚠️ but the **specific "Smith 2002 via Jasinski 2018" chain could not be located** — find/replace the citation or cite the general CTO-history sources. The historical claim is safe; the source-chain attribution is not. |
| 3 | Greiner (1972, 1998) | Organizational growth model; phase-crisis mapping (Sections 4-5, fn3) | ✅ | High | 5 | ✅ Confirmed: HBR 1972, repub. as Classic 1998. 5 phases / 5 crises (leadership, autonomy, control, red-tape, saturation) as used. Phase→mode mapping is the corpus's own interpretation — already framed honestly in draft. |
| 4 | Wiseman & McKeown (2010) — Multipliers | 150 execs, 35 companies, 2x output gap (fn4) | ✅ | High | 5 | ✅ Confirmed: "more than 150 leaders across 35 companies," 2yr study, 2x gap. Bonus precision: multipliers tap 70–100% of capability vs diminishers 20–50%. |
| 5 | Google Project Oxygen (2008, upd. 2018) | 10 behaviors, technical skill ranked last (fn5) | ✅ | High | 5 | ✅ Confirmed: technical skill ranked **last**, relational first; 8 behaviors→10. (Studied ~10,000 managers' data — the "no Builders in scope" point holds.) |
| 6 | Google Project Aristotle (2012-2014) | 180 teams, psych safety #1 predictor | ✅ | Medium | 5 | ✅ Confirmed: 180 teams, 2yr, psychological safety = #1 predictor. |
| 7 | Carta / Crunchbase (2024-2025) | Two high-attrition transition points / survival data (fn6) | ⬜ | High | — | Verify these are real published datasets and that "two distinct transition points" is in the source, not inferred. |
| 8 | First Round CTO Summit | Strategist-mode failure modes (fn7) | ⬜ | Medium | — | Practitioner-only by your own admission. Fine as practitioner evidence; ensure it's framed as such, not empirical. |
| 9 | Kruze Consulting (2024) | Founding vs hired CTO comp gap, $57K-$116K, 250+ startups (fn8) | ✅ | Medium | 5 | ✅ Confirmed exactly: founding $133K seed/$177K Series A; hired $190K/$293K (gaps $57K/$116K); 250+ VC-backed startups. Strongest single comp source — prefer it over content-site medians where possible. |
| 10 | Mars, F. (2026) — TEE | Builder→Multiplier failure mechanism (fn9) | ⚠️ | **High** | 2 | ⚠️ **DOMAIN-MISMATCH — see verdict.** Paper is real (arXiv 2601.04416) but about **AI systems / model routing**, NOT human org psychology. Corpus applies it to *human CTOs* — an analogical transfer the paper doesn't make. Cannot remain the load-bearing *human* mechanism. **Action:** demote TEE to a borrowed metaphor; carry the actual load on competence-trap (#20) + Dunning-Kruger (#21), which ARE human-domain. Ironically, misapplying an AI-systems paper to humans is itself a transitive-expert error. |
| 11 | Myhrvold, N. | "many great CTOs didn't have the title" (fn10) | ✅ | Low | 5 | ✅ Confirmed: Gates/Myhrvold convo (~1996, Microsoft's first CTO). Real quote, context checks out. Good as-is. |
| 12 | Index Ventures — Rewarding Talent | 78% of successful companies had founding CTOs at seed (fn11) | ⚠️ | Medium | 4 | ⚠️ **CORRECTION:** the 78% is "founding CTO **OR technical CEO**," from a dataset of 210 top companies / 200K+ career profiles — NOT "founding CTO at seed." Corpus over-narrows it. Fix the claim to "founding CTO or technical CEO" wherever it appears (`00`, `05_FULLTEXT` §9.1, `08_DRAFT`). |
| 13 | Ewing, R. | IC vs management track divergence (fn12) | ⬜ | Medium | — | Who is Ewing, what's the source type? Supports the bifurcation argument. |
| 14 | HR Oasis (2026) | Tech skill atrophy within 2-3 years of mgmt (fn13) | ⚠️ | **High** | 3 | ⚠️ Phenomenon **well-corroborated** (atrophy after the IC→mgmt move is widely reported across multiple sources) — directional claim is safe. BUT "HR Oasis (2026)" is not a primary, the **"2–3 year" precision is unsourced**, and one source reports a *counter*-case (skills improve on return to IC). **Action:** keep the qualitative claim, drop the false precision + the weak attribution; cite the general IC/management-track literature instead. Load-bearing for §10 bifurcation, so don't lean on the exact number. |
| 15 | Larson, W. (2021) — Staff Engineer | Four archetypes, emergence timing (fn14, Section 10) | ✅ | High | 5 | ✅ Confirmed: Tech Lead / Architect / Solver / Right Hand; Architect emerges ~100 eng, Right Hand ~1,000 eng — exactly as cited. Source: staffeng.com / lethain.com. |
| 16 | Goleman EQ research (1998 HBR) | EQ differentiates, IQ/tech are thresholds | ✅ | Medium | 5 | ✅ Confirmed: "What Makes a Leader?" HBR 1998, ~200 companies. "Technical skill/IQ = threshold, EQ = differentiator" is verbatim Goleman. |
| 17 | Folkman / Zenger — TQ vs EQ | High-EQ/low-TQ outperforms high-TQ/low-EQ | ✅ | Medium | 4 | ✅ Confirmed + stronger: Zenger Folkman finds **STEMM/technical leaders rated *less* effective** — they direct rather than develop, which teams call micromanagement. Direct hit for Builder-in-Multiplier failure. (130K+ leaders studied.) |
| 18 | Goleman / "EQ = 70% of engagement variation" | 155,000 leaders, 22% strong EQ | ❌ | Low | 1 | ❌ Specific figures (70%/155K/22%) **not found**. Adjacent verified stats exist instead: TalentSmart — EQ = **58% of leadership-effectiveness variance**, "90% of what separates top performers." **Action:** replace the unverifiable 70%/155K numbers with the TalentSmart 58% figure, or cut. Low-stakes (it's "moderate" evidence already). |
| 19 | Learning agility → advancement | Adaptability predicts advancement > domain expertise | ✅ | Medium | 5 | ✅ Confirmed + attributable: **Korn Ferry / Lombardo & Eichinger (2000)** — learning agility "single best predictor of executive success, above IQ and education"; meta-analysis of 20 studies > IQ/EQ/experience. Add the citation (was unnamed). |
| 20 | Competence trap (org learning) | Over-exploitation of existing competencies | ✅ | Medium | 5 | ✅ Confirmed: **March (1991), *Organization Science* 2:71–87** — exploration/exploitation; exploitation crowds out exploration → self-reinforcing trap. Canonical source. Now load-bearing via `AX-COMPETENCE`. |
| 21 | Dunning-Kruger (cross-domain) | Expert overestimates adjacent-domain competence | ✅ | Medium | 4 | ✅ Cross-domain extension is **defensible**: "expertise in one area does not transfer to metacognitive accuracy in another"; accurate self-eval requires domain knowledge. Original D-K is within-domain but the cross-domain application is documented. Load-bearing via `AX-COMPETENCE`. |
| 22 | Startup Genome — premature scaling | 74% of startups fail from premature scaling | ✅ | High | 4 | ✅ Confirmed: 74%, n=3,200 high-growth tech startups, Startup Genome "Why Startups Fail / Premature Scaling." ⚠️ Note it's a **2011** report — flag the age; fine as a foundational figure but not "current." |
| 23 | Technical debt — Deloitte | Consumes 20-40% of eng capacity | ✅ | Medium | 5 | ✅ Confirmed: Deloitte Global Tech Leadership Study — tech debt = **21–40% of IT spending**. (Note: "IT spending," not literally "eng capacity" — phrase as spending.) |
| 24 | Micromanagement cost stats | 74% more stress, 50% less output, 2.6x job-hunt | ⚠️ | Medium | 2 | ⚠️ **MISATTRIBUTED + INVERTED.** "74% stress / 50% productivity" are **Paul Zak's HBR trust research** — and they describe high-**trust** vs low-trust (74% *less* stress, 50% *higher* productivity at high-trust firms), not "micromanagement causes." "2.6x job-hunt" unconfirmed. **Action:** reframe as Zak trust data (low trust ≈ micromanagement proxy), or use the verified micromanagement figures: 71% say it interfered with performance, 85% say it hurt morale. |
| 25 | Founder burnout (>50%) | Burnout peaks at transition points | ✅ | Low | 4 | ✅ >50% confirmed (WithDouble 2024: 53%; UCSF: founders 50% more likely to report mental-health conditions). ⚠️ but "peaks at transition points" is still the corpus's *interpretation* — not in the source. Keep the >50%, flag the peak-timing as inference. |
| 26 | McKinsey founder-CEO scaling | Founder-led outperform 3.1x over 15 years | ⚠️ | Medium | 4 | ⚠️ **MISATTRIBUTED:** the 3.1x-over-15-years figure is **Bain & Company** ("Founder's Mentality," HBR 2016), not McKinsey. Re-attribute. (McKinsey *does* have founder-scaling work, but the 3.1x number is Bain.) |
| 27 | Bessemer engineering scaling (1→50+) | Org design by headcount stage | ⬜ | Low | — | Practitioner content — confirm it exists and is attributed correctly. |

---

## ☑ Verification sweep results (2026-06-24) — whole-corpus pass

First full verification pass complete. Outcome: **the foundational academic spine is solid; the corrections cluster in the later-research stats and the 2026 sources.**

### ✅ Verified clean (high confidence — use freely)
- **Greiner (1972/1998)** — 5 phases/crises exactly as used.
- **Wiseman & McKeown (2010)** — 150 leaders/35 cos/2x gap; +precision (70–100% vs 20–50% capability).
- **Project Oxygen** — technical skill ranked last; 8→10 behaviors.
- **Project Aristotle** — 180 teams, psych safety #1.
- **Larson (2021)** — 4 archetypes; Architect ~100 eng, Right Hand ~1,000 eng.
- **Kruze (2024)** — full comp table exact ($133/$177/$190/$293K). Strongest comp source.
- **Mathias & Williams (2018)** + **Van Lancker et al. (2023)** — peer-reviewed, full-text verified (`AX-MW2018`, `AX-VL2023`).
- **Myhrvold quote** — confirmed (~1996).
- **Startup Genome 74%** — confirmed (n=3,200; ⚠️ it's a 2011 report).
- **Adler & Ferdows (1990)** — paper confirmed (CMR 32(3):55–62); ⚠️ "25/100" figures unconfirmed.

### ❌ / ⚠️ Corrections required before publishing (the important list)
1. **`AX-CTO-TENURE` (2.5yr) — ❌ NOT SUPPORTED.** No source. Real: CTO/CIO ~4.3yr (Korn Ferry), C-suite 4.9yr. **Rewrite `12` Solution 2** → use churn (56% changed employers 2021, Russell Reynolds), not tenure-as-window.
2. **Mars/TEE (fn9) — ⚠️ DOMAIN MISMATCH.** Paper is about **AI systems**, not human psychology. **Demote to metaphor**; load-bear on competence-trap + Dunning-Kruger instead.
3. **Index Ventures 78% — ⚠️ MIS-STATED.** It's "founding CTO **or technical CEO**," not "founding CTO at seed." Fix in `00`, `05_FULLTEXT` §9.1, `08_DRAFT`.
4. **McKinsey 3.1x — ⚠️ MISATTRIBUTED to McKinsey; it's Bain** ("Founder's Mentality," HBR 2016). Re-attribute.
5. **CMO tenure "40mo/decade-low" — ⚠️ WRONG.** Spencer Stuart actual: 4.2yr (2023), not a decade low. Fix in `AX-SCOPEKIND`/`09`.
6. **CFO "1979 trigger" — ⚠️ soften** to "1970s SEC/FASB changes (FASB est. 1973)."
7. **HR Oasis "2–3yr atrophy" — ⚠️ drop false precision**; phenomenon is corroborated, the number and source are not.
8. **`AX-REVERSION` ~50% — ✅ UPGRADE (not a correction):** now backed by CEB/Gartner (50%/18mo, n≈30,000) + McKinsey 40%. Re-cite to strengthen.

### Second pass complete (2026-06-24) — lower-stakes batch
**Newly ✅ verified:** Goleman 1998 (16), Zenger Folkman (17 — STEMM leaders rated *less* effective, direct hit), March 1991 competence trap (20), Dunning-Kruger cross-domain (21), Deloitte tech-debt 21–40% (23), founder burnout >50% (25), learning agility = Korn Ferry/Lombardo & Eichinger 2000 (19). `AX-COMPETENCE` now fully grounded (better than the TEE it replaced).

**Newly ⚠️/❌ — more corrections found:**
- **Micromanagement stats (24) ⚠️ MISATTRIBUTED + INVERTED:** "74% stress/50% productivity" are Paul Zak's HBR *trust* data (high-trust = 74% *less* stress), not micromanagement. "2.6x job-hunt" unconfirmed. Reframe or use verified micromanagement figures (71% interfered w/ performance, 85% hurt morale).
- **EQ "70%/155K/22%" (18) ❌ NOT FOUND:** replace with TalentSmart's 58%-of-variance figure or cut.
- **Smith/Jasinski chain (2) ⚠️:** GE/Allied-Signal/ALCOA *substance* confirmed, but the specific Smith-2002-via-Jasinski-2018 citation couldn't be located — re-source.
- **Founder burnout "peaks at transitions" (25):** >50% verified; the peak-timing is the corpus's inference, not in source — flag.

### ⬜ Still unverified (lowest-stakes / next pass)
Bessemer engineering scaling (27); content-site comp medians (`ctaio.dev` etc.) behind `AX-COMPRESSION`/`AX-BIFURCATION-COST` — substitute Kruze (verified) or a primary. `AX-VPENG-TIMELINE` (8–15yr, em-tools.io) and the `AX-INVESTOR` content-site cluster still want primaries.

### Walls hit (logged, per your instruction)
- Proprietary comp primaries (Levels.fyi/Pave/Radford) for `AX-COMPRESSION` — not freely queried this pass; **Kruze (verified) covers most of the CTO/VP figures and can replace the content sites.**
- Equity-package data (grant/dilution/liquidity) — still the open data need for the 4–6:1 band.

---

## Verification workflow notes

- Citations 1–15 are the footnoted, document-level claims — verify these first; they're what a reviewer or fact-checker hits.
- Citations 16–27 come from the classification table (file 04) and support individual thread mappings — lower stakes individually, but several feed the headline statistics.
- After rating, compute a **publication-risk shortlist**: every row that is (Load-bearing High) AND (Verified ❌/⚠️/⬜). Those block publication.
- When the real `.docx` is reconstructed, cross-check that the footnote numbers here still match the document.

---

*Companion to `00_RESEARCH_CONTEXT.md` and `04_RESEARCH_classification_table.md`. Update ratings inline.*
