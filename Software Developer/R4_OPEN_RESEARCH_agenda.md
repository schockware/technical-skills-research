# R4: The Open Research Agenda

## What Is Genuinely Unknown at the Career-Ladder Tier — The Questions No Citation Can Close

**Review date:** 2026-06-25
**Series:** Software Developer career-ladder — independent adversarial review track (`R1`–`R4`)
**Predecessors:** `R1_ADVERSARY` (external attack), `R2_FALSIFICATION_and_bias_audit` (bias audit + falsifiers F1–F8), `R3_STEELMAN` (the defensible form).
**Reviewer stance:** Independent, no stake.
**Predecessors read in full:** the dev-ladder corpus; the parent **Software Industry** `R1`–`R4` (esp. its `R4` open agenda, which this extends to career-ladder scope); the **CTO** `R1`–`R4` (form template); `CTO/07_APPENDIX_citation_review.md`.

> **Purpose.** `R1`–`R3` repeatedly hit the same wall: the dev-ladder corpus's strongest distinctiveness claims rest on studies that *do not exist yet* — and, because the area borrowed its R-track, several of its native gaps were never even *named* by the inherited agenda. This file names them precisely enough to commission, and separates them from the questions that are not "unstudied" but **unstudiable**.

> **The organizing distinction (inherited from both siblings' `R4`, and the right one).**
> - **Open-but-answerable** — a study could be run; the gap is effort and access, not epistemics. Named precisely enough to commission: cohort design, denominator, confounds, what each result would mean. (Part I.)
> - **Open-and-unstudiable** — the question resists measurement by its nature (survivorship, base-rate invisibility, identity self-report, counterfactuals). No future citation closes these; the honest move is to hold them as permanent caveats, not promissory notes. (Part III.)
>
> A corpus that lists only the first kind implies the thesis is one grant from proven. A corpus honest about the second admits some claims will *never* be more than "consistent with." This file insists on the difference.

> **Promotion note.** Each item is tagged **[inherited]** (the Industry `R4` already named it; it transfers to this tier unchanged), **[re-derived at this tier]** (the Industry named a wider-altitude version; the dev-ladder form is sharper), or **[native — never previously on any agenda]** (the borrowed track had no reason to name it). The native items are the highest-value, because they are the gaps the borrowing hid.

---

## Part I — The answerable studies (commission these; they would settle the thesis)

These are the falsifiers from `R2` Part III, restated as a forward program, ordered by **leverage** — the first would move the thesis more than all the corpus's existing citations combined. Each is designed so a real result could *break* the thesis, not decorate it.

### Q1 — The matched-comparator behavioral study (the one that matters most) **[re-derived at this tier; the central falsifier]**

**The question.** Measured on **behavioral** outcomes — reversion, tenure, observed role-abandonment — rather than surveys, do matched high-achievement **non-rotation** professions show *equal* failure rates to software's IC→management boundary?

**Why it's the keystone gap.** This is `R2` **F1**, and it is the study the corpus's retracted "the behavioral data closes the measurement-artifact null" claim *pretended was already resolved* (`R1` Claim B; `R3` Pillar 1). It is not resolved. The corpus's behavioral anchor — the ~50% reversion rate — is **cross-industry** (CEB/Gartner n≈30,000 spans all sectors), so it proves the boundary is hard *everywhere*, not that software is distinctively broken. Closing the *distinctiveness* null requires the comparator arm: behavioral failure rates for clinician→administrator, associate→partner, etc. **The whole "software is uncushioned, not just documented" thesis rests on this comparison, and it has never been pulled.** *(Inherited as Industry `R4` Q0.3, which found the comparator data "largely does not exist in published form" — this is the same gap, sharpened to the IC→management boundary specifically.)*

**How it could actually be run.** Define matched cohorts at the analogous boundary: software engineers crossing IC→EM vs. physicians crossing clinician→administrator vs. lawyers crossing senior-associate→partner-track, same vintage, tracked to a terminal event. Code each as *crossed-and-stayed / reverted / plateaued / exited.* The denominator is the trick: you must include those who never returned to the craft *and* those who did, or you rebuild survivorship bias. Behavioral signals only (employment/licensure records, role-title histories) — **never** sentiment surveys, which software over-produces and the artifact null feeds on.

**What each result would mean.**
- Comparators fail *less* than software at the matched boundary → the cushion thesis is *measured*, not asserted; the distinctiveness null dies; the thesis is vindicated on its central wager.
- Comparators fail *equally* → software is better-*documented*, not less-*cushioned*; the structural claim reduces to "this transition is universally hard" (`R1` Claim B). The thesis would have to retreat to Pillar 3 (misattribution), which survives regardless.
- *Either way the corpus wins epistemically* — for once the result could go against it. That is what makes it worth more than the existing corpus.

**Unstudiable residue:** even a clean comparison won't isolate *which* cushion does the work (label vs fallback vs scaffold) — that needs Q3.

### Q2 — Does a funded IC track at startup scale still yield ~50% reversion? **[native — the area's signature unknown]**

**The question.** Where a **respected, well-resourced IC track exists at startup scale**, does the IC→EM reversion rate still sit near ~50% among engineers who chose management?

**Why it's load-bearing and native.** This is `R2` **F2**, and it is the falsifier for Pillar 2's mechanism: the thesis says people revert partly because the craft-track fallback is *absent* (the unanchored-identity mechanism, Axis 5). If a well-supported startup IC track *still* produces ~50% reversion, the missing fallback is *not* the cause and the mechanism must change. The borrowed Industry `R4` named the large-company cousin (its Q1.3: "does the IC dual-track reduce reversion?") but **not the startup-scale version** — which is the dev-ladder area's *actual scope claim* ("the correction hasn't reached startups"). The corpus asserts the startup no-cushion case by *inference* (`05_` open question #3: "the startup context remains unstudied"); this is the study that would test it.

**Why it's hard.** "Startup-scale IC track" is rare almost by definition (the thesis's own claim). Finding enough instances to measure reversion is the problem. The large-company version is more tractable but tests a weaker claim.

**How it could be run.** Identify seed/Series-A companies that ran an explicit, respected Staff/Principal IC ladder early (rare but non-zero); measure IC→EM reversion among their engineers vs. matched composite-ladder startups. Confound to manage: companies that build IC tracks early differ (better-funded, more org-sophisticated) — needs funding-matched pairs.

**What it would mean.** ~50% reversion *with* a funded fallback → Axis 5 (unanchored identity / missing fallback) is not the mechanism; the thesis loses Pillar 2's causal story (keeps the descriptive comparison). Reversion *drops* with the fallback → the mechanism is confirmed at the scope the thesis actually claims.

### Q3 — The cushions-help study (which cushion, and does any?) **[re-derived at this tier]**

**The question.** Holding funding constant, do organizations that provide the **three cushions** (honest labeling, craft-track fallback, scaffolded transition) at the first rotation show *better* transition survival than structure-blind orgs — and *which* cushion does the work?

**Why it matters.** `R2` **F3**. The corpus's Pillar 2 says *uncushioned* rotation is the harm. If cushioned orgs do no better (funding held constant), the harm is *under-resourcing in general*, not the missing cushions specifically — and the structural diagnosis weakens toward "startups are just hard." The "which cushion" sub-question is the dev-ladder version of the Industry `R4`'s "minimum viable stabilizer" question (`08_` open question #2 already poses it: "is there a single axis condition that, if present, would significantly reduce the compound harm? The military comparison suggests honest labeling alone may be sufficient"). That is a *commissionable* question, and answering it changes the policy implication entirely.

**How it could be run.** Match seed/mid-market firms on funding, sector, headcount; classify by how many cushions they provide at the IC→EM rung; compare 24-month transition retention and eng-org attrition. Ideally vary the cushions independently to isolate which matters (the military's revealed answer: honest labeling).

**Unstudiable residue:** orgs that provide cushions differ in unobservable ways (sophistication) that drive outcomes independently — always quasi-experimental, never randomized.

### Q4 — The construct-validity (inter-rater) study **[native — the gap the borrowing most hid]**

**The question.** Given software career histories and **blinded to the rotation framing**, can independent raters reliably segment rungs into "craft-deepening" vs "identity-rotation" — and do the lower rungs (Junior→Mid, Mid→Senior) code as deepening as often as rotation?

**Why it matters and why it's native.** `R2` **F5**, and the single falsifier most missing from the area. `R1` Claim A is the construct-validity attack — *is "rotation at every rung" a discovered structure or an imposed lens?* — and the borrowed Industry track **never ran it here** (the Industry `R1` attacked "software refused to specialize," not the per-rung sequence). This is the dev-ladder equivalent of the CTO `R4` Q5 inter-rater study, and it should arguably be run **first**, because it is cheap and gating: if raters can't agree where the rungs are deepening vs rotating, the expensive cohort studies (Q1, Q2) are measuring an artifact.

**How it could be run.** Standard content-analysis protocol: 2–3 trained raters, a sample of real career histories (LinkedIn + leveling-rubric data), code each rung-transition as deepening/rotation/mixed, compute Cohen's/Fleiss' κ. Cheap relative to Q1–Q3.

**What it would mean.** High agreement *and* lower rungs coding as rotation → "rotation at every rung" earns the strong form (the corpus would be vindicated, and could *un-narrow* `R1` Claim A). Low agreement, or lower rungs coding as deepening → the per-rung sequence is an imposed lens; `R3`'s demotion to "one seam + recurring pattern" becomes mandatory, not precautionary.

### Q5 — The CTO-tier transformation mechanism, at the engineer tier **[re-derived at this tier]**

**The question.** Do successful IC→EM transitions actually proceed via offload-and-acquire (physical disengagement + role-identity imprinting + psych-safety/value-fit), or do some engineers succeed by *other* paths (e.g., the pendulum — staying partly technical while leading)?

**Why it matters.** `R2` **F-adjacent** / `R1` Claim C. MW2018/VL2023 establish the mechanism *in founders*; the engineer-specific application is the corpus's extension (`DRAFT` §2b states this honestly). This study earns or revokes the corpus's right to apply its two best citations to engineers. The CTO `R4` Q6 proposes the same study one rung up; this is its dev-ladder sibling and is *more tractable* (engineers are a larger, more accessible population than founding CTOs).

**How it could be run.** MW2018's own method: inductive interviews with ~30–45 engineers across IC→EM success/failure/reversion trajectories, coded for whether the transition followed offload-and-acquire or something else. The template exists, so this is the most replicable item.

**Unstudiable residue:** identity-investment self-report (U3 below) limits how clean the coding can be.

### Q6 — The reversion-meaning study **[native]**

**The question.** Of the ~50% who revert, what share are *failed transitions* vs *healthy pendulum swings* vs *genuine preference* vs *org-eliminated roles*?

**Why it matters.** `R2` **F7**; `03_` open question #4 admits "the reversion number is cited without examining what reversion means." The thesis reads the reversion as *failure*; if a substantial share are healthy pendulum returns (Majors) or genuine preference, the "~50% failure" framing inflates a number that is partly success (`R1` Claim B point 4). This is a *cheap* study (follow-up on a reverter cohort) that would tell the corpus how much of its load-bearing number means what it claims.

**How it could be run.** Track a cohort of reverters 24–36 months post-reversion: did they thrive as ICs, stall, or swing back to management? Code reversion *type*. Even n in the low hundreds, honestly typed, beats the current zero.

---

## Part II — The data the corpus already knows it needs (smaller, specific gaps)

These don't test the thesis; they firm up specific load-bearing numbers the corpus flagged itself. All are answerable by access/effort, not epistemics.

- **Staff-promotion rates by org** (`04_` open question #1; **[inherited]** from Industry `R4` Q1.2). What fraction of Seniors reach Staff? Would give the *quiet fracture* an actual number. Hard because it's internal HR data; `08_CITATIONS` (Industry) confirmed "not published by companies; no industry survey found."
- **The plateau population, made measurable** (`04_` open question #1; **native**). The size *and composition* (preference vs failed-transition) of the permanent-Senior population. This is the data that would let Q-falsifier F6 run — see U2 below for why the *composition* half is partly unstudiable.
- **The unverified figure-verification pass** (`06_`, README). The half-life figures, the 52.7% imposter (trace the ResearchGate/Clance primary), the Intuit 82%, the Peter Principle arXiv preprint. **None are in `CTO/07_APPENDIX`** (they don't feed the flagship). Until traced, they stay illustrative (`R2` Bias 6). Mechanical: trace IEEE half-life estimates to primaries; replace content-site citations.
- **The Larson archetype distribution** (`04_` open question #2; **native**). Larson's emergence timings (~100 / ~1,000 eng) are for large orgs; how the four archetypes collapse at smaller scale is unknown and bears on whether the undifferentiated Staff role is the "budget composite" the thesis claims.

---

## Part III — The questions no citation can ever close (the permanent caveats)

This is the part most research agendas omit and the part intellectual honesty most requires. Some dev-ladder questions are not *unstudied* — they are *unstudiable*, and pretending a future grant will close them is its own overclaim. **[The frame is inherited from both siblings' `R4`; the instances are re-cut for the career-ladder tier.]**

### U1 — The person-vs-structure counterfactual

The thesis's core causal claim — *the structure, not the person, produces the failure* — requires a counterfactual that cannot be observed: the same engineer, same company, same moment, *with* cushions. You cannot run the person twice. Even Q3 (cushions-help) compares *different* orgs, not the same engineer counterfactually resourced. **The person-vs-structure attribution is permanently underdetermined for any individual case.** This is exactly why `R3` is careful to claim only *misattribution* (the field's *default* reaches for the individual explanation) and never "the structure *caused* this person's reversion." Pillar 3 is built to survive U1; any draft sentence that says an engineer reverted *because of* the structure is claiming a counterfactual it cannot have.

### U2 — The plateau's composition floor (survivorship's mirror)

The Senior→Staff plateau (`04_`, `R1` Claim D) has two halves. The *size* is answerable (Part II: Staff-promotion rates). The **composition** — what share are failed-and-unnamed transitions vs. genuine preference — is **partly unstudiable**, because it depends on a counterfactual ("would this person have reached Staff if it had been made legible?") and on self-report about one's own motives, *after* the outcome is known. A permanent-Senior engineer asked "did you choose this or fail it?" answers through the lens of a decade of having-not-been-promoted. `07_`'s 3-layer model handles the *success* side of this well; the plateau's failure side is the mirror and is structurally harder, because the plateau population leaves *no event* to study (`R1` Claim D point 3). F6 can move the *size* and the gross preference split; it cannot fully resolve the composition. **The honest stance: the plateau illustrates the illegibility mechanism; it can never establish its own size-and-cause cleanly.**

### U3 — Identity investment is self-report about the self

The identity mechanism (Axis 5; `DRAFT` §2b) and the "identity reframe" success factor (`07_` Factor 2) both hinge on a person's *degree of identity fusion* with their craft — accessible only through self-report, and self-report about one's own identity is where motivated distortion is worst. `07_` Factor 2 *already concedes this*: the reframe "cannot be verified by self-report" and is "a *consequence* of the transition succeeding, not a cause." **The mechanism may be real and still be permanently unmeasurable cleanly**, because the instrument (the person's self-account) is part of the phenomenon. Q5 mitigates by coding behavior (did they offload?) rather than felt identity, but the identity-fusion variable itself stays out of clean reach.

### U4 — "Smart people should learn everything" is a normative diagnosis, not an empirical one

The thesis's titular move — naming the belief as a *misattribution mechanism* — is partly a values claim about *where the burden should sit* (on the structure or the person). Data can show the transition is *costly to the person* and *efficient for the company*; it cannot adjudicate whether attributing the cost to the individual is "right." `R3`'s discipline — keep "misattribution" (descriptive: the field's default attribution) and drop any implication that the structure is *irrational* (normative) — is the only honest resolution. No citation closes a normative gap. *(Inherited from the CTO `R4` U4 / Industry's "irrational" caution; the dev-ladder version attaches to "smart people should learn everything" rather than "irrational composite.")*

### U5 — The ladder is a moving target (AI)

The thesis describes the 2014–2026 software ladder. `06_` open question #2 already flags it: AI-assisted coding may shorten the knowledge half-life (tooling turns over faster) *or* lengthen it (AI handles surface frameworks, making durable architectural judgment more valuable). If AI collapses or transforms the "Builder"/IC layer, the IC→management boundary itself may shift — and the rotation taxonomy may be describing a configuration that is dissolving as it's documented. **A thesis about a structure in flux has a shelf-life.** This is not a flaw to fix; it is a scope condition to state. *(Inherited from CTO `R4` U5.)*

---

## Part IV — The legibility claim's own falsifier (the one the corpus must not skip)

Pillar 3 (`DRAFT` §4c) makes a *forward, falsifiable* claim that deserves its own line in the agenda, because it is the contribution and it is testable:

> **Q-legibility — Do structure-aware organizations intervene better than structure-blind ones?**

The corpus stakes Pillar 3 on a falsifiable position (`DRAFT` §4c): legibility is *necessary-but-not-sufficient* — "if structure-aware organizations intervened no more effectively than structure-blind ones, the legibility claim would fail." **This is the legibility claim's own falsifier, and the corpus states it but never names the study.** It is Q3 (cushions-help) viewed from the *intervention* side: classify orgs by whether they *name* the rotation structurally vs. attribute to the individual, and measure whether the structure-aware orgs actually resource transitions better and get better outcomes. If naming changes nothing, the "you cannot resource a transition you cannot name" sentence — the load-bearing claim of the whole contribution — is wrong. **A public draft must commission this, because it is the test of the one pillar that survives everything else.**

---

## Priority order for the next pass

1. **Q4 (construct validity / inter-rater)** — gating and cheap; if "rotation at every rung" fails here, Q1/Q2 measure an artifact. **[native; run first.]**
2. **Q1 (matched-comparator behavioral)** — the central falsifier; closes-or-kills the distinctiveness null the corpus wrongly claimed closed. Highest leverage; hardest data problem — start by scoping whether the comparator behavioral data exists at all.
3. **Q-legibility (structure-aware vs structure-blind)** — tests the one pillar that survives everything; the corpus already named the falsifier and owes the study.
4. **Q2 (funded startup IC track)** — tests Pillar 2's mechanism at the scope the thesis actually claims. **[native signature unknown.]**
5. **Q6 (reversion meaning)** — cheap; tells the corpus how much of its load-bearing number means what it claims.
6. **Everything else** — opportunistic; close if data surfaces, otherwise honestly mark as boundary-of-knowable (Part III).

The through-line: the corpus is strong on *what it claims* and thin on *what would prove it wrong in practice* — and the borrowing made it *look* tested when its native claims were not. None of the Part I studies can be closed by finding another supporting citation; that is exactly why they are still open after a citation pass (and a borrowed adversarial pass) that closed everything they touched. **The single most valuable next step:** run Q4, then Q1. Q4 tells you whether the modes are real enough to count; Q1 is the only study that could tell the authors the comparators match — i.e., that the thesis is wrong. A confirmation-oriented process (and a borrowed-rigor one) leaves exactly those two for last.

---

## Summary table

| ID | Question | Tag | Type | Could break the thesis? | Cost |
|---|---|---|---|---|---|
| Q1 | Matched-comparator behavioral failure rates | re-derived | Answerable (cohort) | **Yes — central (distinctiveness null)** | High |
| Q2 | Funded startup-scale IC track → still ~50% reversion? | **native** | Answerable (quasi-exp) | Yes (Pillar 2 mechanism) | High |
| Q3 | Cushions-help, funding held constant; which cushion | re-derived | Answerable (quasi-exp) | Yes (Pillar 2) | Medium |
| Q4 | Inter-rater validity of "rotation at every rung" | **native** | Answerable (content-analysis) | Yes (construct) | **Low** |
| Q5 | IC→EM transformation mechanism (offload-and-acquire?) | re-derived | Answerable (qualitative) | Yes (mechanism reach) | Medium |
| Q6 | What reversion *means* (failure vs preference vs pendulum) | **native** | Answerable (follow-up) | Yes (anchor interpretation) | Low |
| Q-leg | Structure-aware vs structure-blind orgs intervene better? | **native** | Answerable (org study) | **Yes — kills Pillar 3 if null** | Medium |
| Part II | Staff-promotion rates, plateau size, figure verification, Larson distribution | inherited+native | Answerable (access/effort) | No — firms up existing claims | Low–Med |
| U1 | Person-vs-structure counterfactual | inherited | **Unstudiable** | — (permanent caveat) | — |
| U2 | Plateau composition (survivorship's mirror) | **native** | **Unstudiable cleanly** | — | — |
| U3 | Identity investment is self-report | inherited | **Unstudiable cleanly** | — | — |
| U4 | "Smart people should learn everything" is normative | inherited | **Not empirical** | — | — |
| U5 | The ladder is a moving target (AI) | inherited | **Scope condition** | — | — |

---

## The honest closing

The dev-ladder area's most valuable property, revealed across `R1`–`R4`, is that it **left its seams visible** *and* that its `DRAFT_SYNTHESIS` already states four falsifiers and the founders-not-engineers boundary in the authors' own voice — ahead of where both siblings started. The promotion to a native R-track extends that honesty one level deeper: from *"here are the citations we haven't verified"* (which the corpus does well) and *"here is the Industry review we inherited"* (which audited the wrong altitude) to *"here are the studies that could prove **this tier** wrong, and we haven't run them."*

A thesis that names the experiment that would kill it — Q1 for the distinctiveness null, Q4 for the construct, Q-legibility for the contribution — commits to running it, and states plainly which questions *no* experiment can ever close (Part III), is the difference between a framework and a finding. The dev-ladder corpus is a strong framework with one genuinely load-bearing behavioral anchor. Q1, Q4, and Q-legibility are what would let it earn the word "finding" for the one or two claims that can bear it; Part III is the list of claims that must, honestly, stay "consistent with" forever — including the person-vs-structure counterfactual at the very center of the thesis.

---

*Concludes the independent adversarial review track for the Software Developer career-ladder tier. Companion: `R1_ADVERSARY_strongest_counterevidence.md`, `R2_FALSIFICATION_and_bias_audit.md`, `R3_STEELMAN_strongest_form.md`. Parent agenda extended: `../Software Industry/R4_OPEN_RESEARCH_agenda.md`. Form template: `../CTO/R4_OPEN_RESEARCH_agenda.md`. Verification source of truth: `../CTO/07_APPENDIX_citation_review.md`.*
*Framework developed in collaboration with Claude (Anthropic). Research conducted June 2026.*
