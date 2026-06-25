# R4: The Open Research Agenda

## What Is Genuinely Unknown — The Questions No Citation Can Close

**Review date:** 2026-06-25
**Series:** CTO Operating Modes — independent adversarial review track (`R1`–`R4`)
**Predecessors:** `R1_ADVERSARY` (external attack), `R2_FALSIFICATION_and_bias_audit` (bias audit + falsifiers F1–F8), `R3_STEELMAN` (the defensible form).
**Purpose:** `R1`–`R3` repeatedly hit the same wall: the corpus's strongest claims rest on studies that *do not exist yet.* This file names those missing studies precisely enough to be commissioned — and separates them from the questions that are not "unstudied" but **unstudiable**, where no citation will ever close the gap and intellectual honesty means saying so.

> **The organizing distinction.** Two kinds of "open" get conflated in research like this:
> - **Open-but-answerable** — a study could be run; the gap is effort and access, not epistemics. (Most of Part I.)
> - **Open-and-structurally-hard / unanswerable** — the question resists measurement by its nature (survivorship, base-rate invisibility, identity self-report, counterfactuals). No future citation closes these; the honest move is to hold them as permanent caveats, not promissory notes. (Part III.)
>
> A corpus that lists only the first kind implies the thesis is one research grant from proven. A corpus honest about the second kind admits some of its claims will *never* be more than "consistent with." This file insists on the difference.

---

## Part I — The answerable studies (commission these; they would settle the thesis)

These are the falsifiers from `R2` Part III, restated as a forward program. Each is designed so a real result could *break* the thesis, not just decorate it. They are ordered by leverage: the first would move the thesis more than all the corpus's existing citations combined.

### Q1 — The base-rate cohort study (the one that matters most)

**The question.** Of founding CTOs, what fraction successfully crosses the Builder→Multiplier (IC→management) boundary as a continuous tenure — and what fraction spans all three modes? What predicts which?

**Why it's the keystone gap.** This is `GAP-CTO-TRANSITION`, and it is the number the entire thesis is shaped around and has never measured. `R1` Claim 3 showed the "survivor-proof / no-triple-mode" finding is currently five anecdotes; `R2` F1 named this the central falsifier. Every other finding is a description of the *difficulty*; this is the only one that measures the *outcome.*

**How it could actually be run.** A defined cohort (e.g., all U.S. seed-funded startups with a titled technical co-founder in vintages 2014–2017), tracked via Carta/PitchBook/LinkedIn to a terminal event (Series C, acquisition, shutdown, or CTO departure). Code each CTO's trajectory: stayed-and-led / replaced-at-boundary / promoted-out / departed / company-died-first. The denominator is the trick — you must include the companies that *died*, or you rebuild survivorship bias. n in the low thousands is plausible from cap-table data.

**What each result would mean.**
- Low success rate (corpus's bet) → the rarity claim is *measured*, not asserted; the thesis is vindicated on its central empirical wager.
- Substantial success rate → the "structurally near-impossible" framing falls; the thesis reduces to "hard transition," which is unremarkable.
- *Either way the corpus wins epistemically* — because for once the result could have gone against it. That is what makes it worth more than the existing corpus.

**Unanswerable residue:** even a clean base rate won't isolate *why* (selection vs. structure vs. support) — that needs Q2.

### Q2 — The early-bifurcation natural experiment

**The question.** Holding funding constant, do startups that split CTO/VP-Eng from seed show better technical-leadership survival, team outcomes, or company outcomes than composite-CTO startups?

**Why it matters.** The corpus calls bifurcation "the cleanest structural solution" (`12_RESEARCH` Solution 3) with *zero* comparative outcome data. `R2` F2: if early-split orgs do no better, the thesis's claim that *the composite specifically* is the problem weakens toward "under-resourcing in general." This is the study that distinguishes "the composite is the wound" from "startups are just hard."

**How it could be run.** Match seed-stage startups on funding, sector, and headcount; compare those that hired CTO+VP-Eng early against composite-CTO controls. Outcome measures: 24-month technical-leadership retention, eng-org attrition, time-to-Series-B, post-mortem cause-of-death coding. Confound to manage: companies that *can* afford an early split differ systematically (better-funded, more sophisticated) — needs funding-matched pairs or an instrument.

**Unanswerable residue:** founders who split early may differ in unobservable ways (org sophistication) that drive outcomes independently. True randomization is impossible; this will always be quasi-experimental.

### Q3 — The matched-comparator study (does the keystone survive?)

**The question.** Do founding CFOs and CMOs experience rotation-driven replacement at the same stage boundaries, at comparable rates, to founding CTOs?

**Why it matters.** `R1` Claim 2 showed the scope-vs-kind keystone is built on an *unmatched* four-row table and that the CFO/CMO arguably rotate too. `R2` F3: a like-for-like cohort (founding finance/marketing/tech leads, same vintages, tracked across the same transitions) would test whether the CTO is categorically different or merely the most severe case on a shared continuum. The corpus's own CMO data (short tenure, weak cross-stage overlap) predicts the latter.

**How it could be run.** Same cap-table cohort method as Q1, run in parallel for all three founding functional roles. Compare replacement-at-boundary rates and tenure curves.

**What it would mean.** If CFO/CMO rotation-replacement ≈ CTO → the keystone narrows to "worst case on a continuum" (the `R3` steelman already concedes this). If CTO is a clear outlier → the keystone is *partially* rehabilitated (still not "kind vs scope," but "uniquely severe" earns its keep).

### Q4 — The documentation-artifact test (is it severity or visibility?)

**The question.** Once measurement legibility is controlled, is CTO failure *behaviorally* worse than other C-suite failure, or just less visible?

**Why it matters.** `R1` Rival B and `R2` F4: the corpus's M5 axis concedes CTO failure is "invisible/slow/blamed on the individual." A skeptic reads that as "CTO failure is *ordinary executive turnover that's hard to see*," not "uniquely severe." The thesis never tests which.

**How it could be run.** Use only *behavioral* signals that don't depend on the failure being narrated: involuntary-departure rates, tenure distributions, re-employment trajectories (does the ex-CTO land a bigger or smaller next role?), board-minute language where available. Compare across C-roles. The discipline (from the sibling thread): lean on behavior, never on sentiment/blog/survey data, which software over-produces.

**Unanswerable residue:** "voluntary vs. forced" departure is often genuinely ambiguous even in the data; some severity/visibility confound will persist.

### Q5 — The construct-validity (inter-rater) study

**The question.** Given CTO career histories and *blinded to the three-mode scheme*, can independent raters reliably segment them into Builder/Multiplier/Strategist phases?

**Why it matters.** `R1` Claim 1 / `R2` F5: the whole taxonomy's status as "discovered vs. imposed" turns on this, and it has never been tested. High inter-rater agreement → the modes carve reality at a joint. Low agreement → they're an authorial overlay, and the `R3` steelman's demotion to "descriptive lens" becomes mandatory rather than precautionary.

**How it could be run.** Standard content-analysis protocol: 2–3 trained raters, a sample of CTO histories, code phase boundaries, compute Cohen's/Fleiss' κ. Cheap relative to Q1–Q4. Should arguably be run *first* — if the construct fails here, the expensive cohort studies are measuring an artifact.

### Q6 — The CTO-specific transformation-mechanism study

**The question.** Do successful CTO transitions actually proceed via offload-and-acquire (physical disengagement + role-identity imprinting), or do some succeed by *other* paths (e.g., never offloading — staying technical while leading effectively)?

**Why it matters.** `R1` Claim 4: MW2018/VL2023 establish the mechanism *in founders*, not CTOs. `R2` F6: if CTOs succeed by paths the model forbids, the model is one route, not the structure. This is the study that earns (or revokes) the corpus's right to apply its two best citations to the CTO.

**How it could be run.** Qualitative, MW2018's own method: inductive interviews with ~30–45 CTOs across success/failure trajectories, coded for whether the transition followed offload-and-acquire or something else. This is the most *replicable* of the set because the template exists.

### Q7 — The domain-axis effect study (does the elegant mechanism have an effect?)

**The question.** Do domain-expert CTOs in general-tech companies fail/underperform at higher rates than generalist CTOs?

**Why it matters.** `13`/`14` build an elaborate, peer-reviewed-*mechanism* story (curse of expertise, cross-domain interference, debiasing-resistance — all verified) and attach it to a *CTO-level effect that is entirely unmeasured.* `R2` F8: a verified mechanism in physicians/lab settings is not an effect in CTOs. This is a mechanism in search of an outcome.

**How it could be run.** Within the Q1 cohort, code each CTO for domain-identity-narrowness (proxy: years in a single technical domain pre-founding) and company domain-dependency; test interaction with transition outcome. The data structure piggybacks on Q1.

---

## Part II — The data the corpus already knows it needs (smaller, specific gaps)

These are narrower than Q1–Q7 — they don't test the thesis, they firm up specific load-bearing numbers the corpus flagged itself.

- **The full founding-CTO equity package** (`AX-COMPRESSION` OPEN DATA NEED). Grant size at seed/A, dilution schedule, liquidity-probability discount. Without it, the compression "ratio" can't become a defensible single figure and the break-even-multiple question (`10_RESEARCH` OQ1) stays uncomputable. Sources exist (Carta, Index *Rewarding Talent*, AngelList) — this is access/effort, not epistemics.
- **The distributed-cost numerator on a comp-survey primary.** The ~$1.1M rests on content-site medians; re-derive against Levels.fyi/Pave/Radford, or rebuild from the *verified* Kruze figures (`R1` Claim 6). Mechanical.
- **Carta/Crunchbase attrition, verified.** `07_APPENDIX` #7 is still `⬜` — "verify these are real, separate transition points." The boundary-clustering claim (`08_DRAFT` §4) leans on this; until verified it's an asserted prop (`R1` Claim 5).
- **The Adler & Ferdows "25 CTOs / 100 firms" figure.** The paper is confirmed; the specific count is not, and the etymology section "parades" it (`07_APPENDIX` #1). Confirm from the PDF or stop citing the number.
- **The five no-triple-mode cases, independently confirmed.** Before `AX-NO-TRIPLE-MODE` goes load-bearing in any draft, confirm each case says what's claimed (esp. that each ended in departure, not sustained tenure) — `16_RESEARCH` flags this and it's undone.

---

## Part III — The questions no citation can ever close (the permanent caveats)

This is the part most research agendas omit and the part intellectual honesty most requires. Some of the thesis's questions are not *unstudied* — they are *unstudiable*, and pretending a future grant will close them is its own form of overclaim.

### U1 — The counterfactual: "would this person have succeeded under a different structure?"

The thesis's core causal claim — *the structure, not the person, produces the failure* — requires a counterfactual that cannot be observed: the same CTO, same company, same moment, with cushions. You cannot run the person twice. Even Q2 (early bifurcation) compares *different* companies, not the same one counterfactually resourced. **The person-vs-structure attribution is permanently underdetermined by data**; it can be made *more or less plausible* (Pillar 3 of `R3` is careful to claim only "misattribution," not "the structure caused this specific failure"), but never proven for an individual case. Any draft that says "this CTO failed *because of* the structure" is claiming a counterfactual it cannot have.

### U2 — The survivorship floor on all success-case work

`16_RESEARCH` built an excellent 3-layer model for this and it remains *structurally* unbeatable: the CTOs who did exactly what the survivors did and failed are *not in any sample, ever*, because failure is not documented. No future study fixes this for famous-founder cases — you cannot interview the invisible failure cell. Q1's cohort method *partially* escapes it (by including the dead companies in the denominator), which is precisely why Q1 is the highest-leverage study. But the *narrative* success-case literature (Dadgar, Blecharczyk, et al.) is permanently survivorship-bound. **The honest stance: success cases illustrate, they never establish.**

### U3 — Identity investment is self-report about the self

The domain-identity axis (`13_RESEARCH`) and the role-identity mechanism (`08_DRAFT` §1) both hinge on a person's *degree of identity fusion* with their craft — a quantity accessible only through self-report, and self-report about one's own identity is exactly where motivated distortion is worst. A CTO who failed the offload will narrate their identity-attachment differently *after* the failure than before. **The mechanism may be real and still be permanently unmeasurable cleanly**, because the instrument (the person's self-account) is part of the phenomenon.

### U4 — "Irrational" is a normative claim, not an empirical one

Even with perfect base-rate data, whether the composite is "irrational" / "dominated" / "should not exist" is a *value* question about whose welfare counts (`R2` Bias 5). Data can show it's *costly to the CTO* and *efficient for the system*; it cannot adjudicate whether that trade is "irrational." No citation closes a normative gap. The `R3` steelman's move — drop "irrational," keep "under-resourced" (descriptive) and "individually costly" (measurable) — is the only honest resolution. The normative claim should be *argued* as values, explicitly, or dropped.

### U5 — The role itself is a moving target

The thesis describes the 2014–2026 startup CTO. But the role is being actively reshaped by forces the corpus notes in passing (`15_RESEARCH`: AI-generated code at 30–70% is already eroding some productivity metrics). If the IC/management boundary itself shifts — if AI tooling collapses or transforms the "Builder" mode — the entire taxonomy may be describing a configuration that is dissolving as it's documented. **A thesis about a structure in flux has a shelf-life**, and no amount of present study fixes a future that's structurally different. This is not a flaw to fix; it's a scope condition to state.

---

## Part IV — The single most valuable thing to do next

If only one thing gets done: **run Q1 (the base-rate cohort study), and run Q5 (inter-rater construct validity) first as its cheap precondition.**

The logic: Q5 is cheap and tells you whether the modes are real enough to count (if raters can't agree on phase boundaries, Q1 is measuring an artifact). If Q5 passes, Q1 is the study that converts the corpus's central wager from *asserted* to *measured* — and it is the one study designed to escape the survivorship floor (U2) by including the dead companies in the denominator. Together they cost a fraction of the corpus's existing effort and would do more for its credibility than any further supporting citation, because **they are the first studies in the whole program that could return a number the thesis doesn't want.**

Everything else — the equity package, the comp primaries, the matched comparators — firms up claims the thesis has already made. Q1+Q5 are the only items that could tell the authors they're wrong. That is exactly why they're the most valuable, and exactly why a confirmation-oriented research process (`R2` Bias 1) left them for last.

---

## Summary table

| ID | Question | Type | Could break the thesis? | Cost |
|---|---|---|---|---|
| Q1 | Founding-CTO base rate of mode-crossing | Answerable (cohort) | **Yes — central** | High |
| Q2 | Early-bifurcation outcomes (funding held constant) | Answerable (quasi-exp) | Yes | High |
| Q3 | Matched CFO/CMO/CTO rotation rates | Answerable (cohort) | Yes (keystone) | Medium |
| Q4 | Severity vs. visibility (behavioral only) | Answerable (behavioral) | Yes (whole-thesis null) | Medium |
| Q5 | Inter-rater validity of the 3 modes | Answerable (content-analysis) | Yes (construct) | **Low** |
| Q6 | CTO-specific transformation mechanism | Answerable (qualitative) | Yes (mechanism reach) | Medium |
| Q7 | Domain-expert CTO failure effect | Answerable (within Q1) | Yes (domain axis) | Low (rides Q1) |
| Part II | Equity package, comp primaries, Carta, the 5 cases | Answerable (access/effort) | No — firms up existing claims | Low–Med |
| U1 | Person-vs-structure counterfactual | **Unstudiable** | — (permanent caveat) | — |
| U2 | Survivorship floor on success cases | **Unstudiable** (Q1 partly escapes) | — | — |
| U3 | Identity investment is self-report | **Unstudiable cleanly** | — | — |
| U4 | "Irrational" is normative | **Not empirical** | — | — |
| U5 | The role is a moving target (AI) | **Scope condition** | — | — |

---

## The honest closing

The corpus's most valuable property, revealed across `R1`–`R4`, is that **it left its seams visible** — it flagged its weak sources, declined to ship a harmful tool, and corrected its own fabricated citations. That honesty is what made a sharp review possible. The natural next step is to extend the same honesty one level deeper: from *"here are the citations we haven't verified"* (which the corpus does well) to *"here are the studies that could prove us wrong, and we haven't run them"* (which it has only begun, at `GAP-CTO-TRANSITION`).

A thesis that names the experiment that would kill it, commits to running it, and states plainly which of its questions *no* experiment can ever close — that is the difference between a framework and a finding. The CTO corpus is a strong framework. Q1 and Q5 are what would let it earn the word "finding" for the one or two claims that can bear it; Part III is the list of claims that must, honestly, stay "consistent with" forever.

---

*Companion: `R1_ADVERSARY_strongest_counterevidence.md`, `R2_FALSIFICATION_and_bias_audit.md`, `R3_STEELMAN_strongest_form.md`. Concludes the independent adversarial review track.*
*Independent adversarial review, 2026-06-25.*
