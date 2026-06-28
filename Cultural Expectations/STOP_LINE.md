# Cultural Expectations — Research Stop-Line Assessment

**Date:** 2026-06-27
**Purpose:** Identify where the Cultural Expectations research cycle can be ended **safely** — i.e. stopped without undermining the track's core deliverables or argument — to halt the token bleed.
**Method:** Read against the track's own priority list (`00_RESEARCH_PRIORITY.md`), research plan (`00_RESEARCH_PLAN.md`), and the actual state of every research file on disk (`02_`–`10_RESEARCH_*.md`).

---

## 1. Current state

This is the **only** track in the repository still **pre-synthesis**. There is no `DRAFT_SYNTHESIS.md`, no `R1`–`R4` adversarial pass — just research files being generated against the priority list. (For contrast, CTO, Software Developer, and Software Industry all have a synthesis plus an R1–R4 track.)

The track exists to answer two questions inherited from `CTO/TODO.md`:

- **T2** — Does the "irrationality" live in the *cultural expectation* of the CTO (the standard the judges apply), rather than in the role design? `R3_STEELMAN` already retired "the role is irrational"; T2 relocates the irrationality to the *expectation/attribution* locus.
- **T4** — Why does the culture grant "smart → learn anything" to technical roles but withhold it from doctors, lawyers, and accountants?

**The hardest discipline rule in the plan** (`00_RESEARCH_PLAN.md` lines 24, 519): the clean separation must hold. Nothing may smuggle role-design back in after R3 retired it. Every finding must attach to the *expectation/attribution* locus. This rule is the key test for what is safe to cut (see §2).

The priority list itself is sound: a weighted ranking of 36 sections across five tracks, scored `weighted = depth + 2×value + 1.5×axis_count`, with explicit dependency notes and redundancy flags. The recommendations below honor that ranking rather than overriding it.

---

## 2. Completion map

### Done (first pass complete)
- **`04_RESEARCH_pre_software_history.md` 4.2 — Taylor.** Claim split; only half survives (functional foremanship *decomposed* the supervisor — the "manager as amplified composite" claim is disconfirmed at role level). Resolved.
- **`04_RESEARCH_pre_software_history.md` 4.4 — Drucker.** Diagnosis confirmed; the strong-form akrasia framing softened. Resolved.
- **`04_RESEARCH_pre_software_history.md` 4.7 — Occupational transitions (Tay Bridge pattern).** The comparison baseline for the whole thesis and the core of T4. "Named catastrophic failure as universal trigger" revised (medicine/actuarial show non-failure pathways), but the section survives and is more precise for it.
- **`04_RESEARCH_pre_software_history.md` 4.8 — Price's Law.** √N form disconfirmed in its home domain; the loading claim re-founded on citizenship-pressure / CCB literature. Resolved (mechanism swapped).
- **`03_RESEARCH_axes_in_the_wild.md` 3.9 — Axis 9 (liability) in the wild.** Strong "liability is the master variable" claim **decisively disconfirmed**; liability demoted to one of several co-equal brakes. Resolved.
- **`03_RESEARCH_axes_in_the_wild.md` 4.9 — Gendered reclassification.** The keystone of Track 4 (dates the installation of the fungibility assumption). First pass complete; one Misa counter-argument to integrate. Confidence capped pending primary sources (see §5).

### Partial / blocked
- **`03_RESEARCH_axes_in_the_wild.md` 3.2 — Axis 2 (institutional memory).** CHAOS Report case well-evidenced; the 2008-structured-finance and NASA Challenger/Columbia second passes are outstanding (rate-limited).
- **`02_RESEARCH_expectation_audit.md` 2.1 — JD archaeology.** Only a "template pass" (2 of 4 URLs usable; one 403, one was a Chief *Talent* Officer, not Technology). Real JD pass pending. 2.2 (post-mortems), 2.3 (diligence), 2.4 (reflection-gap test) not started.

### Done since this stop-line was written (2026-06-28 update)
- **3.10 — Axis 10 (citation trail). ✅ RESOLVED — was the single pending load-bearing item.** The trail is **broken at every node** (NATO 1968 / Brooks 1975 / CHAOS 1994 do not form a citation chain — independent rediscovery, not knowing-and-ignoring). Verdict: the cross-generational software pattern is **Axis 2 (civilizational amnesia), not Axis 10 (akrasia)**. Synthesis instruction filed: use "amnesia" for the cross-generational case, reserve "akrasia" for the intra-generational case (Brooks cited in MBA curricula, practice unchanged). **The §3.1 capstone hinge is now settled — the one pending load-bearing item is done.**
- **3.9 — Axis 9 (liability). ✅** Already listed done above; demotion to "one of several" resolved.
- **4.2 / 4.4 — Taylor / Drucker. ✅** Already listed done above.
- **4.8 — Price's Law. ✅** Already listed done above.
- **4.1b — Fayol (NEW, off the original plan; enrichment per §4).** Core CONFIRMED (composite generalist manager descends from Fayol, not Taylor; admin ability general/teachable/dominates technical at top; Weber+Fayol = two channels of one prior). ⚑ Downstream HBS/Chandler lineage + the "invented tradition" disconfirmation UNVERIFIED — the run hit the monthly spend limit mid-verification (those votes are abstain/0-0 = untested, NOT refuted). Second pass queued for limit reset. **This is enrichment, not load-bearing** (4.1 Weber is a §4 cut) — do not let synthesis over-weight it.

### Not started
- **Track 1 (psychological mechanisms)** — no `01_RESEARCH` file exists.
- **Track 5 (cognitive biases/fallacies)** — no literature-pass file exists.
- **Track 4** — 4.1 (Weber), 4.3 (Hawthorne), 4.5 (computer-arrives), 4.6 (Lean Six Sigma).
- **Track 3** — 3.0, 3.1, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8.

### Off-plan emergent captures (not part of the five-track plan)
- `05_RESEARCH_feedback_loop_paradox.md`
- `06_RESEARCH_rational_degradation_pattern.md`
- `07_RESEARCH_values_practice_gap.md`
- `08_RESEARCH_knowledge_legibility_pipeline.md`
- `09_RESEARCH_bullet_problem.md`
- `10_RESEARCH_lossy_information_hierarchy.md`

All six are flagged "New finding — candidate structural condition," "needs grounding," or "open track." They are not in the plan, and `05_` collides with the filename the plan reserved for Track 5 (`05_RESEARCH_cognitive_biases_and_fallacies.md`, per `00_RESEARCH_PLAN.md` line 712).

---

## 3. What is load-bearing — must NOT be cut

Four things hold up the T2/T4 argument. Cutting any one collapses a deliverable.

1. **3.10 — the citation trail** (`03_RESEARCH_axes_in_the_wild.md`). The plan calls this "the highest-stakes single finding in the plan" (lines 183, 198). The entire **Axis 2 vs. Axis 10 distinction** — memory *doesn't exist yet* vs. memory *exists, is cited, and is ignored* — and therefore the whole capstone hold or collapse here. ✅ **RESOLVED (2026-06-28): the trail is broken → Axis 2 (amnesia), not Axis 10 (akrasia).** No synthesis may use "akrasia" language for the cross-generational case; use "amnesia." Intra-generational akrasia (Brooks cited, practice unchanged) is the one reserved use. **This load-bearing item is now DONE — it is no longer pending.**
2. **2.1 — JD archaeology, real pass** (`02_RESEARCH_expectation_audit.md`). The priority doc calls the JD "the single most direct behavioral artifact of the expectation," and the plan's discipline is "behavioral evidence over sentiment" (line 517). The current template pass has two dead URLs and no real sample. Without a genuine CTO-JD sample plus the CFO/CMO/CRO comparison, T2 has no empirical spine.
3. **The mechanism core for T2 — 5.6 (IOED/Fernbach), 5.1 and 5.2 (Milgram/Asch dissenter).** Dependency Note #2 states 5.6 *is* the engine that makes the 2.4 reflection-gap test work at all ("determines whether 2.4's test can work"); 5.1/5.2's single-dissenter finding is "the most actionable lever in the framework." These three are load-bearing; the rest of Track 5 is enrichment.
4. **4.9 and 4.7 — already done.** 4.9 is "the keystone dependency of Track 4" (line 160); 4.7 is "the comparison baseline for the entire thesis" and the core of T4. Do not reopen — but note 4.9's confidence cap (§5).

---

## 4. What to cut or defer — with reasons

### Cut immediately
**The six emergent captures `05_`–`10_`.** These are the clearest token bleed. They are ungrounded ("needs grounding," "open track"), off-plan, and — critically — several drift back into *role design*: `06_RESEARCH_rational_degradation_pattern.md` and `07_RESEARCH_values_practice_gap.md` are about the CTO's individual cognitive load and IC identity, not the expectation/attribution locus the track must isolate. They violate the plan's clean-separation rule (lines 24, 519) and are the least defensible work in the folder.

**The "Known Literature Gaps — Do Not Re-Search" set** (`00_RESEARCH_PLAN.md` lines 486–510). The plan already ran three passes and found nothing for: Axis 3 in software, Axis 7's internal trap, a licensed-profession positive control, real-world "one dissenter" cases, Axis 6 measured directly, and CTO survivorship data. The plan explicitly says do not re-run these. Any further effort here is pure waste.

### Defer (low value or redundant by the plan's own scoring)
- **Track 1 as a separate literature pass (1.1–1.5).** Redundancy Flag #3: research 5.1/5.2/5.5 *once*, then write Track 1 as synthesis. Never run Track 1 as its own research.
- **1.3 (authoritarian personality, weighted 8.5)** — the plan itself calls it "less directly applicable."
- **4.6 (Lean Six Sigma)** — its own ranking says "illustrative more than load-bearing."
- **3.0 / 3.7 and 3.1** — near-duplicates of 5.4 / 5.3 / 5.6 (Redundancy Flags #4). One pass, not two.
- **3.3, 3.5, 3.8** — single-axis, narrow, or subsumed by 2.1 (3.8 title inflation overlaps JD archaeology).
- **3.2 second passes (2008 structured finance, NASA)** — Case A (CHAOS) already carries the Axis 2 claim; the rest is deepening, not load-bearing.
- **3.9 second pass** — the strong claim is already decisively disconfirmed and resolved; just carry the demotion forward.
- **4.1 (Weber), 4.3 (Hawthorne), 4.5 (computer-arrives)** — 4.5 pairs with 4.9, which is done; 4.2 already carries the lineage (with the Fayol correction noted at line 55); Hawthorne's value is "mostly as a negative."
- **Track 5 sections 5.3, 5.4, 5.5, 5.7** — enrichment, not load-bearing for the minimal T2/T4 argument.

---

## 5. Recommended stop line

### Finish only this — the minimal defensible set
1. ~~**3.10 citation trail**~~ ✅ **DONE (2026-06-28)** — the capstone hinge is resolved (trail broken → Axis 2/amnesia). Was non-negotiable; now complete.
2. **2.1 real JD pass** — replace the 403 URL and the wrong-role (Chief *Talent* Officer) URL; pull a genuine CTO-JD sample across stages plus the CFO/CMO/CRO comparison. **← NEXT (the irreplaceable remaining pull; T2's empirical spine).**
3. **One consolidated Track 5 pass covering only 5.1, 5.2, 5.6** — then write Track 1 as a synthesis from it (no separate Track 1 research).
4. **2.4 reflection-gap section** — written as analysis on top of 5.6 plus the founder-separation accounts already captured in 4.7 (the plan concedes direct evidence is rare, line 140 — construct it, don't hunt for it).

**Remaining after the 2026-06-28 update: items 2, 3, 4 — i.e. ~2 real research pulls (2.1, then 5.1/5.2/5.6) plus 2.4 as near-free analysis. Item 1 is done.**

**>>> 2026-06-28 END-OF-MORNING UPDATE: THE MINIMAL DEFENSIBLE SET IS COMPLETE. <<<**
- Item 1 (3.10) ✅ — done (prior session).
- Item 2 (2.1 real JD pass) ✅ — done (run wf_565535ba-e35). Composite confirmed + stage-modulated; CTO-specificity under-powered (open follow-up: verbatim CFO/CMO audit).
- Item 3 (5.1/5.2/5.6 consolidated pass) ✅ — done (run wf_5e3e5209-abc); Track 1 written as synthesis (`01_RESEARCH_psychological_mechanisms.md`), no separate run.
- Item 4 (2.4 reflection-gap) ✅ — written as analysis on 5.6 + 4.7 + 2.1, no run.

**Key reframe to carry into synthesis:** the reflection-gap test is a robust DIAGNOSTIC but a fragile LEVER (the Fernbach moderation effect failed 3 preregistered replications, is value-bounded, and is untested on role beliefs). The actual intervention lever is the **dissenter** (Asch/Milgram convergence), whose exact figures are unverified-in-corpus and need a cheap check.

**Next per §7: run the adversarial pass R1→R2→R3, then DRAFT_SYNTHESIS (writing, not research runs).** Afternoon research runs (≤2) are now OPTIONAL enrichment — best candidates: CFO/CMO specificity comparison (closes the 2.1 gap), Milgram/Asch figure verification, or the 4.1b Fayol second pass. Spend them on whatever R1 proves is genuinely missing rather than pre-committing.

### Optional, cheap
5. **4.9 confidence top-up** — retrieve the NATO 1968 proceedings and the Light (1999) DOI to lift 4.9 above its current confidence cap (`03_RESEARCH_axes_in_the_wild.md` lines 403, 463). Not required for a defensible track; just inexpensive insurance on the keystone.

### Drop below the line — now
- All six emergent captures `05_`–`10_RESEARCH_*.md` (off-plan, ungrounded, role-design drift).
- The entire "Do Not Re-Search" gap list (`00_RESEARCH_PLAN.md` lines 486–510).
- Track 3: 3.0, 3.1, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, and the 3.2 / 3.9 second passes.
- Track 4: 4.1, 4.3, 4.5, 4.6.
- Track 1 as separate research; Track 5 sections 5.3, 5.4, 5.5, 5.7; section 1.3.

### The bet behind this stop line
T2 needs a documented expectation (2.1), a mechanism for the reflection gap (5.6 + 5.1/5.2 → 2.4), and the akrasia boundary resolved (3.10). T4 needs the comparison baseline and the installation event — both already done (4.7, 4.9). Everything else on the priority list is corroboration, depth, or redundancy a steelman can survive without. The bleed stops at roughly **four remaining research actions** instead of the ~25 sections still nominally open.

---

## 6. Stale-status reconciliation note (do this first — it's free)

The status lines disagree on whether **4.9** is done:

- `03_RESEARCH_axes_in_the_wild.md` header lists 4.9 under "Complete first pass," and the file contains the completed 4.9 section.
- `04_RESEARCH_pre_software_history.md` header (line 5) lists 4.9 as **pending**.

This is a stale status line, not real missing work — 4.9 was researched in `03_`. Reconcile the `04_` header so the keystone isn't accidentally re-run. Cost: one edit.

---

## 7. Recommended sequence to wrap by tomorrow

1. **Reconcile the 4.9 status line** (§6) — one edit, prevents a wasted re-run.
2. **Finish the four must-do items** (§5): 3.10 → 2.1 real pass → consolidated 5.1/5.2/5.6 pass (write Track 1 as synthesis) → 2.4 written on top of 5.6 + 4.7. Optionally fold in the 4.9 top-up while pulling primary sources.
3. **Run the adversarial track in order:** `R1_ADVERSARY` → `R2_FALSIFICATION` → `R3_STEELMAN` (per `00_RESEARCH_PLAN.md` lines 713–719: do not write the synthesis until the adversarial pass is complete).
4. **Write `DRAFT_SYNTHESIS.md`** built on `R3_STEELMAN`, not on the raw research files — and keep the clean separation: every claim attached to the expectation/attribution locus, nothing smuggling role-design back in.

---

*Sources: `Cultural Expectations/00_RESEARCH_PRIORITY.md`, `00_RESEARCH_PLAN.md`, `02_RESEARCH_expectation_audit.md`, `03_RESEARCH_axes_in_the_wild.md`, `04_RESEARCH_pre_software_history.md`, and `05_`–`10_RESEARCH_*.md`.*
