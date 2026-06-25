# 06: Falsification & Bias Audit
## A Hostile-but-Fair Review of the Software Industry Thread

**Research date:** June 25, 2026
**Series:** Software Industry — Human Capacity Research Thread
**File:** 06 of series
**Companion:** `R1_ADVERSARY_strongest_counterevidence.md` (the opposing evidence, claim by claim)
**Reviews:** files `01`–`04`, `13`, `00_AXES_SUMMARY.md`

**What this is.** A structured bias audit of the thread, organized by *failure mode* rather than by file — so it doubles as a reusable checklist for the rest of the corpus. Plus a falsification protocol the thread currently lacks. The adversary file (`R1`) handles "what's the counterevidence." This file handles "what cognitive traps is the thread falling into, and how would we know if we were wrong."

**Stance.** The thread's core is strong. This audit is written *because* it is strong — a weak argument doesn't deserve this scrutiny. The findings below are the distance between "persuasive to people who already agree" and "persuasive to a skeptic who knows the field."

---

## The bottom line up front

The thread is **one keystone overstatement and one missing null hypothesis away from being hard to dismiss.** It currently reads as built backward from a conclusion (the personal performance-review grievance) toward supporting evidence — which is fine as a *process* but leaves *tells* in the text that a skeptic will read as motivated reasoning. None of the tells are fatal. All are fixable without surrendering the thesis. Ranked by damage potential:

1. **Confirmation bias in source selection** (biggest exposure) — every citation points one way; disconfirmation is outsourced to a stub.
2. **One keystone overstatement** — file 04's "no stable craft."
3. **One triple-leaned brittle citation** — CHAOS.
4. **Unfalsifiability creep** — every outcome routed to confirmation.
5. **The asymmetry trick** — comparators shown at their best, software at its worst.
6. **Correlation→causation** on imposter syndrome.
7. **Rhetorical tells** — heat that lowers credibility.

---

## Bias 1 — Confirmation bias in source selection

**The pattern.** Brooks, Sackman/Nichols, Aristotle, CHAOS, the Agile-empiricism critique, SEMAT, Larson — every load-bearing source was selected because it refutes fungibility or supports rotation-harm. There is a live opposing literature the thread never engages: **DORA/*Accelerate*** (practices transfer across orgs), **SPACE** (the field's own productivity-measurement answer), modern 10x reassessments that contextualize rather than collapse the effect.

**Why it's the biggest exposure.** A reviewer who knows this literature concludes the thread surveyed only its own side — and then discounts *everything*, including the parts that are correct. The cost of one-sided sourcing is not the one argument it weakens; it's the credibility tax on the whole corpus.

**The tell.** Disconfirmation lives in `14_RESEARCH_success_exceptions.md`, which is a **stub** that *pre-classifies* its future findings as `[CONTEXT/LUCK]` ("they didn't beat the structure, they operated where it didn't bite"). Deciding what the counterexamples mean *before collecting them* is the structure of confirmation bias, not the cure for it.

**Fix.** File `R1` is the start. The thread needs at least one source engaged *because it threatens the thesis*, with the threat taken seriously rather than pre-neutralized.

---

## Bias 2 — The keystone overstatement (file 04)

**The pattern.** File 04 is rhetorically the strongest file and evidentially the weakest. "There is no stable craft in software" is positioned as the keystone ("every other problem compounds from this") — and it overshoots. It conflates the **framework/methodology fashion layer** (genuinely volatile) with the **knowledge foundation** (data structures, algorithms, complexity theory, type systems, networking, concurrency, relational theory — decades-stable). The 2.5–5 year "half-life" measures the surface and is reported as the depth.

**Why it matters most after Bias 1.** It's the *keystone*. If the skeleton's strongest-stated claim is its most overstated, every compounding argument inherits the weakness, and a skeptic breaks the chain at exactly the point the thread leans hardest.

**The compounding error.** The "2.5–5 year half-life" number appears **four times across the thread** (00, 03, 04, 13). Repetition makes one unverified figure read as four pieces of evidence. The README already flags it as unverified.

**Fix (highest-leverage single edit in the whole corpus).** Restate from "no stable craft" to:
> *The legible, credited, fashionable layer of skill is unstable — and that is exactly the layer hiring/promotion/review systems measure. The durable foundation exists; the evaluation machinery doesn't credit it.*
Truer, sharper, sharpens the performance-review argument, and survives the DORA objection. See `R1` Claim 1.

---

## Bias 3 — The brittle citation leaned on three times (CHAOS)

**The pattern.** Standish CHAOS figures (61%/11%/6%) appear as decisive proof in files 01, 02, and 13. CHAOS is the **most methodologically criticized dataset in software engineering** (Jørgensen & Moløkken-Østvold, 2006: opaque proprietary method, self-selected sample, idiosyncratic "success" definition, non-reproducing figures).

**The irony that makes it worse.** File 04 dings Agile for resting on appealing stories rather than evidence — while three files rest a load-bearing claim on the field's most-contested dataset. A skeptic uses this to impeach the thread's *entire* evidentiary standard.

**Fix.** Mechanical and free: swap the load-bearing role to **ISBSG** (1,000+ projects, cleaner, larger), demote CHAOS to illustrative, footnote the critique at each use. Costs nothing, removes a real liability. See `R1` Claim 4.

---

## Bias 4 — Unfalsifiability creep

**The pattern.** The thread has built an interpretation machine where every outcome confirms it:

| Observation | Thread's reading |
|---|---|
| Engineer reverts to IC | Rational refusal of an unanchored identity ✓ |
| Engineer succeeds in management | Luck / context where structure "didn't bite" ✓ |
| Engineer plateaus | The "quiet fracture," invisible failure ✓ |
| Org splits the role and thrives | The funding allowed it, not the split ✓ |
| Practitioner feels like a fraud | Accurately perceiving real mismatch ✓ |

When no observation can count against the thesis, it has stopped being empirical and become a worldview. The `14_` stub's pre-classification of successes as `[CONTEXT/LUCK]` is the same move at the case-study level.

**Fix — the falsification protocol (below).** State, explicitly, what would disconfirm the thesis. This is the single change that most distinguishes "research finding" from "advocacy."

---

## Bias 5 — The asymmetry trick (file 13, and the cross-industry tables)

**The pattern.** Comparators are shown at their best; software at its worst.
- Medicine: shown as licensed, specialized, craft-deepening. **Not shown:** residency's compressed deceptive rotation, the clinician→administrator Red Baron drift, ~45–55% physician burnout.
- Law: filed under "craft-deepening, honest" (Category A). **Reality:** up-or-out partnership is a rotation (lawyering→rainmaking) disguised as advancement — arguably *more* deceptive than software's.
- The headline contrast pits the *seed-stage startup CTO* (worst case) against *established medicine* (best case), while the thread elsewhere concedes large-company software partially corrected.

**Fix.** Compare like-for-like (early-stage to early-stage), and concede the comparators' own rotation pathologies. The argument *survives and looks fairer*: the real, defensible contribution is "software has rotation **without the fallbacks, honest labels, and timeline** that make rotation survivable elsewhere" — not "software has rotation and others don't." See `R1` Claim 3.

---

## Bias 6 — Correlation read as causation

**The pattern.** Two causal claims asserted from correlational data with no mediating evidence:
1. **Imposter syndrome 52.7% → "accurately perceiving structural mismatch."** Imposter phenomenon is elevated across *all* high-achievement/high-evaluation populations regardless of rotation structure. The base-rate alternative is never ruled out.
2. **The reversion/imposter/burnout cluster → caused by software's specific structure.** Could equally be caused by achievement-pressure generally, which software shares with medicine, academia, and elite finance.

**Fix.** Restate as *candidate explanation the individual-pathology framing never tests*, and shift the burden ("given majority prevalence, the structural hypothesis deserves testing") rather than asserting the conclusion. Honest and still strong. See `R1` Claim 5.

---

## Bias 7 — Rhetorical tells (motivated-reasoning signals)

Independent of substance, these make a skeptic discount the work — and they cluster around the thread's emotional origin (the performance-review grievance):

- **Totalizing language:** "every word is wrong," "the myth collapses," "the framework cannot accommodate what you've built."
- **Second-person grievance voice:** the performance-review passages ("*you* want me to compress it into bullet points") import the researcher's personal stake into the analysis. This is the clearest "conclusion preceded the research" tell in the corpus.
- **Intent-attribution slippage:** the thread correctly says "the deception is structural, not intentional" — then repeatedly slides back to intent ("the industry's way of not having to fix it," "a mechanism for avoiding accountability"). Function-and-intent language applied to a diffuse system is rhetoric, not analysis.

**Fix.** The findings are strong enough to survive in neutral voice; the heat *lowers* their credibility. Convert the performance-review passages to third person, replace totalizing verbs with calibrated ones ("substantially overstated" not "every word is wrong"), and hold the "structural, not intentional" line consistently.

---

## The deepest blind spot — the measurement-artifact null hypothesis

The thread never confronts the most economical competing explanation for its *entire* evidence base:

> Software's dysfunction may not be categorically worse than other professions' — only better **documented.** Software is younger, more introspective, more online, and more surveyed. It is the profession that blogs about its feelings and publishes its imposter rates. The thread reads *visible pain* as *unique brokenness*; a skeptic reads the same fact as *unique vocalness.*

One assumption (differential documentation) explains the imposter stats, burnout surveys, career-abandonment essays, and the whole reflective literature — versus the thread's stack of structural claims. **The thread must address this directly.** The rebuttal exists and is strong: the *behavioral/organizational* data (reversion n≈30,000, ISBSG outcomes, tenure) is not self-report and not bloggable sentiment. But the thread currently mixes sentiment and behavior as if equally probative. To beat the artifact hypothesis it must **foreground the behavioral data and explicitly downgrade the sentiment data to corroborating-not-load-bearing.** See `R1`, final section.

---

## The Falsification Protocol

The thread's most important missing artifact. Every core claim gets a stated disconfirmer. If these conditions were met and the thread still held, *that* would be the bias.

| Claim | Would be **disconfirmed** if… |
|---|---|
| Rotation-without-fallback is the harm | Orgs that split CTO/VP-Eng **from seed**, funding held constant, showed *no better* technical-leadership survival than composite-CTO orgs. |
| Identity-anchoring drives the ~50% reversion | A respected, well-supported **IC track at startup scale** still produced ~50% reversion (→ anchoring isn't the mechanism). |
| Software's structure causes the imposter/burnout load | **Matched high-achievement non-rotation professions** showed the same imposter/burnout rates (→ it's achievement-pressure, not structure). |
| "No (credited) stable craft" | A durable, **credited-in-promotion** skill foundation were shown to exist and be rewarded by current review systems (→ the evaluation-mismatch claim fails). |
| Software is uniquely broken (not just documented) | Comparator professions, measured on **behavioral outcomes** (not surveys), showed equal rotation-failure/reversion/tenure pathology (→ artifact hypothesis wins). |
| Fungibility is refuted | Headcount-linear output and free unit-swap (post-ramp) were demonstrated at scale (→ but ramp-cost + n(n-1)/2 + ISBSG already foreclose this; this one looks safe). |

**Standing instruction for the success-case thread (`14_`):** a success case may **only** be classified `[CONTEXT/LUCK]` *after* it fails a pre-registered test for genuine structural success — not by default. Define, in advance, what a real structural win looks like (e.g., *a non-domain-locked org that split roles early, held funding constant, and beat the composite baseline on technical-leadership tenure*). If such a case appears and is waved away as luck, the thread has become unfalsifiable in practice.

---

## Triage — what to fix, in order

1. **Narrow file 04** ("no stable craft" → "the credited layer is unstable; the durable layer is uncredited"). Repairs the keystone; neutralizes DORA; sharpens the review argument. *Highest leverage, lowest cost.*
2. **De-risk CHAOS** (swap to ISBSG as load-bearing, demote CHAOS, footnote the critique). *Free; removes a clean line of attack.*
3. **Write the artifact-null rebuttal** (foreground behavioral data; downgrade sentiment to corroborating). *Closes the deepest flank.*
4. **Adopt the falsification protocol** (above). *Converts worldview back into thesis.*
5. **Concede the comparators' pathologies** in file 13 (kill the asymmetry trick). *Looks fairer, argues stronger.*
6. **Cool the rhetoric** (neutral voice, calibrated verbs, hold "structural-not-intentional"). *Removes the motivated-reasoning tells.*
7. **Restate the imposter claim** as untested candidate + burden-shift, not causation. *Honest; still strong.*

None of these surrender the thesis. Each one makes it harder to dismiss. The thread is good enough that the only thing left to do is stop giving a skeptic easy reasons to stop reading.

---

*Companion: `R1_ADVERSARY_strongest_counterevidence.md`. Counter-citations referenced here have been verified to primary in [`08_CITATIONS_gap_closure.md`](08_CITATIONS_gap_closure.md), logged to the `../CTO/07_APPENDIX_citation_review.md` standard.*
*Framework developed in collaboration with Claude Opus 4.8 (Anthropic). Research conducted June 2026.*
