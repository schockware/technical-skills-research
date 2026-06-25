# Software Industry — Industry-Structural Scope

**Scope tier:** widest. The broadest framing of the study, above the [career-ladder view](../Software%20Developer/) and the [CTO case study](../CTO/).

**Core claim:** Every mature profession that hit the limits of human cognitive capacity responded the same way — **specialization** (medicine's 40+ specialties, law's practice areas, engineering's disciplines). Software didn't. It instead built a career ladder demanding distinct skill sets on compressed timelines with no on-the-job runway between them, and a culture that attributes the resulting failures to individuals rather than to the structure.

> *"What we have here is a human capacity issue, disguised as a 'smart people should be able to learn everything' problem."*

---

## Contents

| File | Contents |
|---|---|
| [`13_RESEARCH_software_industry_structural.md`](13_RESEARCH_software_industry_structural.md) | Five exhibits: the specialization comparison; imposter syndrome as industry diagnostic; the knowledge-obsolescence treadmill; the Peter Principle at maximum intensity; the dual career track as partial acknowledgment. |
| [`00_AXES_SUMMARY.md`](00_AXES_SUMMARY.md) | The five axes, compound matrix, Red Baron / fungibility, CTO connections. Start here. |
| [`01`–`04` (MMM series)](01_MMM_brooks_original_argument.md) | The Brooks-rooted argument: non-fungibility (`01`), the operationalized fungibility assumption (`02`), the 10x/Aristotle evidence (`02b`), the transformation-expectation axis (`03`), the unstable-craft compounder (`04`, **over-stated — see `R1`**). |
| [`05_MMM_ray_of_hope.md`](05_MMM_ray_of_hope.md) | Where the industry corrects itself (dual-track IC, rubrics, Principal PM, DevRel) and the startup gap the corrections don't reach. |
| [`06_MMM_synthesis.md`](06_MMM_synthesis.md) | The CTO composite as terminal expression of the pattern; axes→CTO mapping; what a structurally honest industry requires. |
| [`08_CITATIONS_gap_closure.md`](08_CITATIONS_gap_closure.md) | **Verification pass** closing the `⬜` flags the review track raised — DORA, SPACE, the CHAOS critique, ISBSG team-size, physician-burnout & imposter base rates, all verified to primary. Two findings came back *strengthening the narrowing* the review track called for. |

**Review track (`R`) — the adversarial / steelman meta-pass (added 2026-06-25)**

| File | Contents |
|---|---|
| [`R1_ADVERSARY_strongest_counterevidence.md`](R1_ADVERSARY_strongest_counterevidence.md) | **Red-team.** The strongest case *against* the series, claim by claim, with HOLDS / NARROW / OPEN verdicts. Engages the omitted opposing literature (DORA, SPACE) and the CHAOS-dataset critique. |
| [`R2_FALSIFICATION_and_bias_audit.md`](R2_FALSIFICATION_and_bias_audit.md) | **Bias audit + falsification protocol.** Seven failure modes (confirmation bias, keystone overstatement, brittle citation, unfalsifiability, asymmetry trick, correlation→causation, rhetorical tells), the measurement-artifact null hypothesis, and a stated disconfirmer for every core claim. |
| [`R3_STEELMAN_strongest_form.md`](R3_STEELMAN_strongest_form.md) | **The defensible distillation.** The thesis in the form that survives `R1`/`R2` — three load-bearing pillars, five pre-made concessions, the do-not-build-on table, the accidental-concession argument, and a drop-in one-paragraph conclusion. **Build externally-facing conclusions on this file, not on the rhetorical phrasing of `01`–`04`.** |
| [`R4_OPEN_RESEARCH_agenda.md`](R4_OPEN_RESEARCH_agenda.md) | **What's still genuinely unknown.** The *hard* research — falsification natural-experiments, the consulting puzzle, the artifact-null behavioral data — that `08`'s citation pass could **not** close. Separates closed-citation gaps from open-research gaps; priority-ordered for the next pass. |

*(Lightweight area — will gain its own appendix/conventions if developed into a standalone piece.)*

> **Stabilization note (2026-06-25):** the `R1`–`R3` review track is the adversarial pass. Net finding — the thesis survives its strongest adversary, but **must narrow in three places** (file 04's "no stable craft," the CHAOS lean, the asymmetry trick) and **name three open flanks** (imposter causation, reversion-as-refusal, the documentation-artifact null). Highest-leverage single edit: restate file 04 from *"no stable craft"* → *"the credited skill layer is unstable; the durable layer is uncredited."* See `R2` triage list. For any conclusion-grade statement, prefer the steelman in `R3`.
>
> **Verification follow-through (`08`):** the counter-citations the review track raised are now verified to primary in `08_CITATIONS_gap_closure.md`. Two of the three OPEN flanks came back *confirming the thread must narrow, not the adversary*: imposter syndrome at 52.7% is **not** a software outlier (healthcare 62%, law 50–83%), and physician burnout shows the same craft→admin rotation dynamic — so the cross-industry comparison must concede the comparators' pathologies (`R2` Bias 5) and retire the "imposter = structural diagnostic" causal claim (`R1`/`R3`). What remains genuinely open is only the falsification tests (natural experiments not yet run). **Still to do:** apply the narrowings to the substantive `MMM` files — `08` verified the sources but deliberately did **not** rewrite `01`–`06`.
>
> **✅ "Incompatible" reconciliation complete (2026-06-25):** the CTO flagship retired the word **"incompatible"** corpus-wide — disconfirming research ([`../CTO/18_RESEARCH_modes_not_incompatible.md`](../CTO/18_RESEARCH_modes_not_incompatible.md)) shows the skill sets are **distinct but demonstrably can coexist** (the engineer/manager pendulum shows *positive* transfer between them). The defensible claim is **"distinct skill sets with no on-the-job runway to learn the next,"** not "incompatible." **This narrowing has now been propagated into this thread's substantive files** — `01` (13/135/158/170), `03` (181), `04` (185), `06` (23/155), `13` (21/114/166), and `HANDOFF`. Two senses were distinguished in the rewrite: the *career-rotation* sense ("incompatible across a career" → "distinct, no runway"; the skills coexist over time) and the *composite* sense ("three incompatible skill sets at once" → "three distinct skill sets demanded simultaneously, no runway between them"). The `DRAFT_SYNTHESIS.md` spine was authored in the corrected form from the start (`§1` + must-not-claim table). Anchor for the open-question framing: `08_RESEARCH_axes_integration` line 217.

---

## Relationship to the rest of the study

- **Contains ↓** [`../Software Developer/`](../Software%20Developer/) (the same pattern at the individual-career level) and [`../CTO/`](../CTO/) (its most acute, flagship instance).
- **The steelman that proves the point:** "you can't compare a CTO to a medical specialist — startups can't afford specialists." That argument *accidentally concedes the thesis* — the human-capacity constraint that forced medicine to specialize didn't disappear for software; the industry just stopped acknowledging it.

## Status & verification

Active research, **published while under verification.** Introduces citations not yet in the CTO citation log — the specialization counts, **Darshan et al. (2013)** IT-stress study, software-engineer tenure figures, and the **Peter Principle agent-based model** (2025, shared with the Developer note). **Unverified pending a dedicated pass**; treat as illustrative until logged. Anything that feeds the flagship CTO paper gets verified and recorded in [`../CTO/07_APPENDIX_citation_review.md`](../CTO/07_APPENDIX_citation_review.md).

---

*Part of the [Technical Skills Analysis](../README.md) study. Research conducted June 2026.*
