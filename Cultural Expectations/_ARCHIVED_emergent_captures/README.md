# Archived — Emergent Captures (off-plan)

**Archived:** 2026-06-27
**Status:** Preserved, not deleted. Out of the active research cycle.

## Why these were archived

These six files were generated during the Cultural Expectations research cycle but sit **outside the five-track research plan** in `../00_RESEARCH_PLAN.md`. Specifically:

- **Off-plan.** None of them maps to Tracks 1–5 or to any section in `../00_RESEARCH_PRIORITY.md`. They are emergent "candidate structural condition" notes, not planned research. (The filename `05_` also collided with the slot the plan reserved for Track 5, `05_RESEARCH_cognitive_biases_and_fallacies.md` — see `../00_RESEARCH_PLAN.md` line 712.)
- **Self-flagged as ungrounded.** Each is marked "New finding — candidate structural condition," "needs grounding," or "open track — needs grounding" in its own status line. None is evidence-backed to the standard the planned tracks require.
- **Clean-separation violation.** The plan's hardest discipline rule (`../00_RESEARCH_PLAN.md` lines 24 and 519) is that every finding must attach to the *expectation/attribution* locus, and nothing may smuggle CTO **role design** back in after `R3_STEELMAN` retired it. Several of these files drift squarely back into role design — the CTO's individual cognitive load, fatigue, and IC identity — which is exactly what the rule forbids.
- **Primary token bleed.** Continuing to expand these was the largest source of wasted research effort in the track.

They are **preserved rather than deleted** in case any individual finding turns out to be worth grounding and reintroducing later (properly scoped to the expectation/attribution locus, with real evidence). If reintroduced, a finding should re-enter through the planned track structure, not as a standalone capture.

For the full rationale and the recommended research stop line, see **`../STOP_LINE.md`**.

## Files

| File | One-line contents |
|---|---|
| `05_RESEARCH_feedback_loop_paradox.md` | Argues software has the shortest unit-level feedback loop yet decisions resist correction for years — a "selectively blocked" loop at the organizational decision layer (Axis 6 / Axis 5). |
| `06_RESEARCH_rational_degradation_pattern.md` | Claims cognitive load doesn't cause bad decisions directly but defers good ones until the decision context degrades; load is the output of the blocked loop, not the input. **Drifts into role design.** |
| `07_RESEARCH_values_practice_gap.md` | An IC-first CTO can hold genuine values yet be structurally unable to practice them at scale; "identity load" leads to avoidance. **Drifts into role design.** |
| `08_RESEARCH_knowledge_legibility_pipeline.md` | Frames the software specification failure as a knowledge-legibility problem — knowledge exists but in a form non-context-holders can't act on; proposes a conversion pipeline (Axis 1 / Axis 6). |
| `09_RESEARCH_bullet_problem.md` | Open question on why leaders compress complex problems into bullet points and what that compression costs (Axis 1 / Axis 6). Flagged "open — needs grounding." |
| `10_RESEARCH_lossy_information_hierarchy.md` | Argues systems route decision authority upward while routing information upward in progressively lossier form; proposes inverting it (decision travels to the expertise, summary to the leader). Flagged "open track — needs grounding." |

## Note on git state

At archival time the repository's git index was corrupt (`bad signature`, a stuck `.git/index.lock` that could not be removed). The moves were therefore completed as plain filesystem moves rather than `git mv`. The files are physically relocated and intact; git will need its index repaired (e.g. `git status` / re-add) before these moves are reflected in version control. See the chat summary for details.
