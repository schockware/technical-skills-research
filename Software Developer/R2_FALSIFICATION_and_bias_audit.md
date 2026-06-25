# R2: Falsification & Bias Audit

## Where the Dev-Ladder Corpus Reasoned Toward Its Thesis — And What Would Prove It Wrong

**Review date:** 2026-06-25
**Series:** Software Developer career-ladder — independent adversarial review track (`R1`–`R4`)
**Predecessor:** `R1_ADVERSARY_strongest_counterevidence.md` (attacks the claims from outside; this file audits the authors' own reasoning from inside).
**Reviewer stance:** Independent, no stake. This file is deliberately uncharitable about *process*, not conclusion: not "is the thesis true?" but "did the way this corpus was built — and the way it borrowed its rigor from a sibling area — bias it toward its conclusion, and would the authors have noticed if it were false?"
**Predecessors read in full:** the dev-ladder corpus (`01`, `03`–`09`, `DRAFT_SYNTHESIS.md`, `README.md`); the parent **Software Industry** `R1`–`R4`; the **CTO** `R1`–`R4`; `CONVENTIONS.md`; `CTO/07_APPENDIX_citation_review.md`; `CTO/18_RESEARCH_modes_not_incompatible.md`.

> **The two jobs of this file.**
> 1. **Bias audit** — name every place the corpus reasons *toward* its thesis rather than *at* the evidence: overclaim, motivated reasoning, cherry-picking, asymmetric scrutiny, and the subtle tell — *flagging a problem and proceeding as if flagging fixed it.* Each rated **Severity: high / medium / low.**
> 2. **Falsification protocol** — state concretely what observations would prove the thesis (and each pillar) wrong. A thesis with no falsifier is a worldview. Produced as a numbered battery (F1, F2, …).
>
> Throughout I treat every `RISK-` anchor and every "adversarial review" / "open flank" note as a **hypothesis to be tested, not a credit to be banked.** The question for each flag: *did the mitigation change the argument, or did the argument proceed unchanged with a disclaimer attached?*

> **The promotion-specific job.** This area inherited its R-track from Software Industry. So a distinctive bias lives here that exists in neither sibling: **borrowed-rigor laundering** — the corpus can *cite* the Industry's adversarial review as if its own claims had been through it, when the Industry review audited the *Industry's* claims at a wider altitude. Where a dev-ladder move was waved through on inherited authority, I mark it **[borrowed-rigor]** and judge whether the inherited mitigation actually reaches this tier's version of the claim.

---

## The bottom line up front

The dev-ladder corpus is **strong on its one verified behavioral anchor and disciplined in its `DRAFT` — and then systematically over-reaches in the research files (`01`, `06`) and in two specific escalations the `DRAFT` itself commits.** It is closer to publishable than the CTO corpus was, because the Industry R-track already forced several narrowings (Axis 4, CHAOS→ISBSG, comparator asymmetry) and the `DRAFT` absorbed them. But three biases are native and unaddressed, and one is a *promotion artifact*: the corpus banks the Industry review's rigor on claims that review never actually examined. Ranked by damage potential:

1. **Borrowed-rigor laundering** (the promotion's signature bias) — citing the inherited adversarial review as cover for dev-ladder-native claims it never audited. *High.*
2. **The "closes the null" overclaim** — escalating the Industry's *open flank* into a *closed* one. *High.*
3. **Arguing-from-silence on the plateau population** — invisibility used as evidence of size and cause. *High.*
4. **Confirmation-oriented collection + no disconfirming-mechanism search at this tier.** *High.*
5. **Asymmetric scrutiny** — the verified reversion stat promoted, threatening base-rate data (healthcare 62%) "consistent-with"-ed away. *Medium-high.*
6. **Unverified figures doing quiet load-bearing work** despite disclaimers. *Medium.*
7. **Residual "incompatible" overclaim** the README is still reconciling. *Medium.*

None is fatal. All are fixable without surrendering the thesis. The point of naming them honestly is that `R3` survives because `R1`/`R2` did not pull punches.

---

## Part I — The Bias Audit

### Bias 1 — Borrowed-rigor laundering: the inherited R-track is cited as if it audited *this* tier **[the promotion's signature bias]**

**The pattern.** `08_RESEARCH_axes_integration.md` imports the Industry's five axes *and* its adversarial review wholesale, and `09_SYNTHESIS` declares "Every word of that survives the adversarial review (`../Software Industry/05_ADVERSARY`, `06_FALSIFICATION`)." `DRAFT` §0 says the spine is "written to survive a hostile-but-fair reviewer." But the Industry review attacked *Industry-altitude* claims: "software has no stable craft," "the fungibility assumption is refuted," "others specialized, software refused," "CHAOS proves Brooks." It **never attacked** the dev-ladder-native moves — the per-rung rotation sequence, the plateau population, the Larson load, the reversion anchor *as the closing pillar*. The corpus then writes as though those had passed an adversary, because a document with "ADVERSARY" in its name is in the lineage.

**Why it's the biggest exposure.** It is invisible precisely because it *looks* like rigor. A reader sees "survives the adversarial review" and a five-axis steelman challenge in `08_`, and concludes the area is stress-tested. It is stress-tested *at the wrong altitude.* `R1` is the first document to attack the per-rung sequence (Claim A), the plateau (Claim D), Larson-as-structure (Claim F), and the reversion anchor's reach (Claim B) — and three of those NARROW or partly FALL. **The borrowing didn't transfer rigor; it transferred the *appearance* of rigor while skipping the claims that most needed it.**

**The tell.** `08_`'s own "Steel-Manning Summary" and "Adversarial Review" sections are framed as *challenges the Industry steelmanning already answered* — e.g., "Axis 1: are the skills genuinely incompatible? … The response (from `08_DRAFT_skills_divergence_thesis`): the divergence is in focus." That is the corpus answering its own challenge by citing *another corpus's draft*, not by running the challenge against the dev-ladder evidence. Deciding a dev-ladder challenge is met by pointing at a CTO draft is borrowed-rigor laundering in one sentence.

**Fix.** This file and `R1` are the start. Every place the corpus says "survives the adversarial review," it must now say *which* review and *at what altitude* — and for native claims (per-rung sequence, plateau, Larson-load, reversion-as-closer) cite *this* track, not the parent. The honest header: *"inherited from Software Industry/Rn, confirmed at career-ladder scope"* vs *"first reviewed here."*

**Severity: high.** It is the bias a referee names first once they notice the R-track is borrowed.

### Bias 2 — Escalating the inherited *open flank* into a *closed* one (the "closes the null" tell) **[borrowed-rigor]**

**The pattern.** The Industry `R2` named the measurement-artifact null its **deepest blind spot**, verdict **OPEN — highest-priority gap**, and said only that the behavioral data is *where to fight it* — "but only if the thread leans on the behavioral data" (Industry `R1` final section). `08_`'s "open flank" section repeats this correctly: "This flank is not closed by the axes. It is closed by the behavioral/organizational data — *and the dev-ladder corpus has the right data to close it.*" Then `09_` Pillar 1 and `DRAFT` §2a complete the escalation: "This is the number that **closes** the measurement-artifact null hypothesis."

**Why it's motivated reasoning, not progress.** The corpus took an *inherited OPEN verdict* and converted it to CLOSED *without adding the evidence that would close it.* As `R1` shows (Claim B, null section): the reversion rate is **cross-industry** (the corpus's own `03_` says so), so it proves boundary-difficulty, not software-distinctiveness; closing a *distinctiveness* null needs *comparator* behavioral rates that are *lower*, which the corpus does not have (`05_` concedes they're "not quantified"). The escalation is the corpus *wanting* the null closed and writing it closed. This is the cleanest single example of reasoning-toward-the-thesis in the area: an open question the parent left open became, on inheritance, a settled win — with no new data.

**The tell that the mitigation didn't take.** `08_` *flags* the null as an open flank and then, four sentences later, asserts the corpus has the data to close it — and `DRAFT` bumps "has the data to close it" to "the number that closes it." The flag was raised and then overridden by the same file. Flagging the flank did not discipline the conclusion; it decorated it.

**Fix.** Retract "closes the null" in `09_` Pillar 1 and `DRAFT` §2a. Restore the parent's honest form: behavioral data neutralizes the *sentiment* version of the null and is the right battlefield; the *distinctiveness* version stays OPEN until comparator behavioral rates are pulled (a falsifier — F1 below).

**Severity: high.** It is the area's signature overreach and the most quotable.

### Bias 3 — Arguing from silence: the plateau population **[never reviewed by the inherited track]**

**The pattern.** `04_` builds the Senior→Staff "quiet fracture" on a population it concedes is unmeasured ("⬜ No data found"; "structural inference, not a measured figure; should be presented as such, not as a statistic") — and then `DRAFT` §4a promotes it to "**the purest case**" of the misattribution harm and "**almost certainly larger** than the reversion population."

**Why it's the same failure mode the corpus polices elsewhere.** This is the **mirror of the Industry/CTO `RISK-ASYMMETRY` move** — arguing from silence. In the CTO corpus, "0 Strategist findings" was illegitimately read as confirmation; the appendix flags it (`RISK-ASYMMETRY`). Here, "we can't see the plateau failures" is read as "therefore they are numerous and structural." **The invisibility that makes the plateau rhetorically powerful is exactly what makes it evidentially empty** (`R1` Claim D). The corpus inherited a *named* anti-pattern from its siblings and then committed it on a native claim — precisely the gap borrowed rigor leaves: the parent's `RISK-ASYMMETRY` flag governs the *Industry's* silence, and nobody pointed it at the dev-ladder's plateau.

**Cherry-pick within the bias:** `04_` concedes "some chose it deliberately… a legitimate choice," then asserts "a significant portion… is not there by genuine preference" with no estimate — assigning the unmeasured population to the thesis-favoring cause by default. And the rise of respected IC tracks (the corpus's own celebrated cushion) *predicts* the plateau fills with genuine choosers, which would convert plateau-as-failure into plateau-as-success (`R1` Claim D point 2).

**Fix.** Demote the plateau to "structural hypothesis, unmeasured" everywhere it currently reads as a population fact; strike "larger than reversion" and "purest case." The harm survives on the *visible, measured* reversion case.

**Severity: high.** Load-bearing for `DRAFT` §4a and self-refuted by `04_`'s own source note.

### Bias 4 — Confirmation-oriented collection, and no disconfirming-mechanism search at this tier

**The pattern.** Like both siblings, the dev-ladder files were assembled to support the thesis: every research file (`01`, `03`–`07`) retrieves evidence *for* rotation-harm and stops there. The CTO corpus eventually *fixed* its version of this — `R2` Bias 1 there commissioned `18_RESEARCH_modes_not_incompatible.md`, a disconfirming-search file. **The dev-ladder area has no equivalent.** It *imports* the conclusion of `18_` (retire "incompatible" → "distinct skills, no runway") but never ran "evidence the rungs are *not* rotations" at *its own* altitude.

**Why it matters here specifically.** The construct most in need of a disconfirming search is the dev-ladder-native one: *rotation at every rung* (`R1` Claim A). A genuine disconfirming search would ask: *which seams are actually craft-deepening? where does excellence at rung N predict rung N+1? does the engineer/manager pendulum (positive transfer) mean the lower rungs aren't rotations at all?* The corpus's own cells already answer partway (Junior→Mid "near craft-deepening") — but no file is dedicated to pressing it, so the "every rung" framing survived unchallenged into `DRAFT` §1. **A thesis that imports its sibling's disconfirming file but never runs its own has outsourced its falsification one area over.**

**The subtle tell.** `08_` line 217 poses the disconfirming question correctly as an *open question* ("are the skills genuinely incompatible, or just different in degree?") — and the README points to this as "the anchor." But posing a question in a steel-manning list and *answering it with a citation to a CTO draft* is not running the search. The question is live; the corpus treats it as resolved because a *different* area resolved a *related* version.

**Fix.** Commission the dev-ladder disconfirming file `R4` will name: *"evidence the rungs are not rotations"* — testing the per-rung sequence against positive-transfer, continuum-of-scope, and the craft-deepening lower rungs.

**Severity: high.** It is the original sin, partially laundered by the sibling's fix.

### Bias 5 — Asymmetric scrutiny: the verified anchor is promoted; the threatening base rate is "consistent-with"-ed away

**The pattern.** Watch what happens to evidence by direction.

- Evidence *for* the thesis with strong sourcing is made the spine and stretched past its reach: the ~50% reversion (✅ verified, Confidence 4) is correctly promoted — but then asked to "close the null" and to prove *software-distinctiveness*, jobs a cross-industry rate cannot do (`R1` Claim B). Strong source, over-extended conclusion.
- Evidence *against* the thesis is acknowledged and then neutralized by reframing: the imposter base-rate data — **healthcare 62% > software 52.7%** (verified in the Industry's `08_CITATIONS_gap_closure`, cited in `DRAFT` §6 concession 6) — is genuinely threatening (the highest imposter rate is in a *craft-deepening, licensed* field the thesis predicts should be lowest). The corpus handles it by saying imposter data is "consistent with the thesis… does not prove it" and demoting it to corroborating. That is the *right* move for using it as support — but it quietly avoids the *adversarial* reading: that the base rate *cuts against* the "imposter = accurate perception of rotation/obsolescence" claim, because the worst rate is in the no-rotation field. The threatening datum is filed as "corroborating-but-not-load-bearing" instead of "actively disconfirming for one sub-claim."

**The cleanest example.** `06_`/`01_` assert "imposter syndrome in software is **accurate self-assessment of structural mismatch**" while `DRAFT` §6 concession 6 *and* the verified base rate say elevated imposter rates "appear across all high-achievement populations regardless of rotation structure." The same corpus holds the causal claim (in the research files) and its refutation (in the draft's concessions). Asymmetric scrutiny is what lets both survive: the causal version is stated where it helps, the base-rate refutation is quarantined to a concession.

**Fix.** State the base-rate datum as what it is for the strong claim: *disconfirming.* The "imposter = accurate perception" claim should be cut, not demoted to corroborating — see F4.

**Severity: medium-high.**

### Bias 6 — Unverified figures doing quiet load-bearing work

The README and `06_` are admirably honest that several figures are ⬜ unverified. The question `R2` must press: *do any do load-bearing work despite the disclaimer?* Verified against `CTO/07_APPENDIX` (none of these are logged there — they don't feed the flagship, so they remain unverified):

| Figure | Status | Disclaimed? | Does it do load-bearing work anyway? |
|---|---|---|---|
| **52.7% imposter** (Clance, 2024) | ⬜ unverified | Yes (`06_`, `DRAFT` §6) | **Borderline.** `01_` uses it to assert software produces imposter syndrome "at majority rates," which carries the "accurate self-assessment" causal claim. `DRAFT` correctly demotes it. *In the research files it still loads; in the draft it doesn't.* |
| **Knowledge half-life 2.5–5yr** | ⬜ LOW–MEDIUM | Yes (`06_`) | **Yes, in `06_`.** The "obsolescence compound" and "expertise = depreciating liability" (`06_` title) *require* the half-life to bite. `06_` says "build on the mechanism, not the numbers" — but the mechanism (Axis 4) doesn't need `06_`'s numbers, so what `06_` adds *beyond* Axis 4 is exactly the unverified part. |
| **Intuit 82%** (balancing team vs mgmt) | ⬜ verify | Yes (`03_`) | **Low.** Used as texture for the feedback-loop-loss mechanism; the mechanism stands without it. Safe as long as it's not cited as a finding. |
| **Peter Principle arXiv (2025)** | ⬜ LOW, preprint | Yes (`06_`, `01_`) | **Medium in `01_`.** `01_` uses "software is explicitly named as the worst-case regime" to assert software-distinctiveness — a load-bearing claim resting on an unverified preprint. Demote to illustrative. |
| **7–10 hr/week maintenance** | ⬜ LOW, derived | Yes (`06_`) | **Low.** Explicitly an inference; fine as texture. |

**Finding.** The disclaimers are real and mostly honored *in the `DRAFT`.* But in `01_` and `06_` the unverified numbers still carry distinctiveness claims (imposter "majority rates," Peter Principle "worst-case," half-life "liability"). The discipline the `DRAFT` applies has not propagated back to the research files — so a reader of `01_`/`06_` meets load-bearing unverified figures the `DRAFT` would not allow.

**Fix.** Propagate the `DRAFT`'s demotion back to `01_`/`06_`: every distinctiveness claim resting on an unverified figure becomes "candidate/illustrative." The behavioral/sentiment line (below) is the tool.

**Severity: medium.** Mechanical, but the research files are where a fact-checker starts.

### Bias 7 — The residual "incompatible" overclaim the README is still reconciling

**The pattern.** The README flags it directly (2026-06-25): "incompatible" still appears in `01_` (lines 6, 90), `06_` (164), `08_` (203), README line 5 — to be narrowed to "distinct skill sets with no on-the-job runway." The `DRAFT` and `09_` have corrected it; the research files have not. So the corpus simultaneously holds "the skills are in active tension / incompatible" (`01_`) and "distinct but coexist, positive transfer" (`DRAFT` §0, citing `CTO/18_`).

**Why it's a bias and not just a stale edit.** "Incompatible" is the word that makes the per-rung rotation read as *sharp* (`R1` Claim A point 4). While it survives in `01_`/`06_`/`08_`, the rotation-at-every-rung construct reads stronger than the corpus can now defend — and the strong reading is the one that flows into casual summaries. The reconciliation is "pending"; until done, the corpus's strongest-stated version of its core claim rests on a word it has officially retired.

**Fix.** Execute the README's own reconciliation: narrow "incompatible" → "distinct skill sets with no on-the-job runway" in `01_` (6, 90), `06_` (164), `08_` (203), README (5). `08_` line 217 already poses it correctly as the open question; that's the anchor.

**Severity: medium.** Known, scoped, and the README already owns it — but it props up the area's most overstated framing until done.

---

## Part II — Did the flags actually mitigate, or just alibi?

The corpus's defenders will point to its inherited `RISK-` anchors and its "adversarial review" notes as evidence of rigor. I judged each load-bearing flag by one standard: **after the flag, did the argument change — or did it proceed unchanged with a disclaimer bolted on?**

| Flag / note | What it admits | Did the argument change? | Verdict |
|---|---|---|---|
| **Axis 4 narrowing** (`08_`, from Industry `R1` C1) | "no stable craft" overstates → "credited layer unstable / durable uncredited" | **Yes.** `08_` Axis 4 restated; `DRAFT` §6 concession 1 carries it; the performance-review argument is genuinely sharper. | **Genuine mitigation [inherited, correctly applied].** The model the others should follow. |
| **CHAOS → ISBSG demotion** (`08_`, from Industry `R1` C4) | CHAOS is the field's most-criticized dataset | **Yes.** `08_` demotes CHAOS to illustrative, promotes ISBSG, footnotes Jørgensen & Moløkken. | **Genuine mitigation [inherited].** Free fix, executed. |
| **Comparator-asymmetry correction** (`05_`, `08_`, from Industry `R1` C3) | comparators shown at their best | **Yes, in `05_`/`08_`.** Law re-graded Category A/B hybrid; medicine 45–55% burnout conceded; the compound table footnotes the pathologies. | **Genuine mitigation [inherited].** But watch `DRAFT` §3b for quiet re-idealization (`R1` Claim E). |
| **"Open flank" = measurement-artifact null** (`08_`) | the deepest competing explanation | **No — overridden.** Flagged open, then declared closable by behavioral data, then `DRAFT` declares it closed (Bias 2). | **Alibi → reversal.** The flag was raised and then used to license the opposite conclusion. |
| **`RISK-SURVIVORSHIP`** (`07_`) | success cases = presence-as-evidence | **Partially.** `07_` genuinely applies the 3-layer model per-factor (real scaffolding, the area's best rigor) — *but* the same anti-pattern recurs un-flagged at the plateau (`04_`/`DRAFT` §4a), where invisibility is read as size (Bias 3). The flag governs `07_`'s success cases and exempts `04_`'s plateau. | **Genuine in `07_`, absent where also needed.** Mitigates the parts, not the conclusion. |
| **"Incompatible" reconciliation** (README) | the word is retired but still present | **No (not in prose).** The README *names* the fix as pending; `01_`/`06_`/`08_` still say it. | **Alibi until the prose is cut** (Bias 7). |
| **Unverified-figure disclaimers** (`06_`, README) | half-life/imposter/Peter unverified | **In the `DRAFT`, yes; in `01_`/`06_`, no.** The research files still load-bear on them (Bias 6). | **Partial.** Disclaimed where read carefully, load-bearing where read first. |

**The pattern.** The dev-ladder flags are **genuine when the fix was inherited, cheap, and already executed by the parent's edit** (Axis 4, CHAOS, comparator asymmetry — the Industry R-track did the work, the dev-ladder files absorbed it). They become **alibis exactly where the claim is dev-ladder-native and the fix would cost a headline** (the null, the plateau, "incompatible," the unverified distinctiveness claims). This is the borrowed-rigor signature again: **inherited mitigations took; native mitigations did not.** The flag system is real rigor on the *imported* axis and a partial alibi on the *native* axis — because the imported fixes were already made by someone else, and the native ones require the authors to cut their own strongest sentences.

---

## Part III — The Falsification Protocol

A thesis is a finding only if it can lose. The dev-ladder corpus has the beginnings of one — `08_` open question #4 lists three candidate falsifiers (inherited from the Industry protocol), and `DRAFT` §6b states four (F1–F4) in the authors' own voice, which is genuinely good and ahead of where the CTO corpus started. This section restates them as a numbered battery, adds the ones the corpus is missing, and ties each to the `R1` verdict and the bias it would test. Every `RISK-`/flag is treated as a hypothesis to test, not a credit to bank.

### Falsifiers for the whole thesis

**F1 — The matched-comparator behavioral falsifier (the central one; closes-or-kills the null).**
*If* matched high-achievement **non-rotation** professions, measured on **behavioral** outcomes (reversion, tenure, observed role-abandonment) rather than surveys, showed **equal** failure rates to software → software is better-*documented*, not less-*cushioned*; the measurement-artifact null wins; the structural claim reduces to "this transition is hard" (which `R1` Claim B shows the cross-industry reversion rate already concedes). *This is `DRAFT` §6b F1, and it is the falsifier the corpus's own "closes the null" claim (Bias 2) pretends is already resolved. It is not — the comparator arm has never been pulled (`05_`). The thesis bets the comparators won't match; it must admit the bet is open.*

**F2 — The funded-IC-track falsifier.**
*If* a **well-resourced IC track at startup scale** still produced ~50% IC→EM reversion among engineers who chose it → the absence of a craft-track fallback is not the cause; the no-cushion mechanism (Pillar 2 / Claim E) is not doing the work. *This is `DRAFT` §6b F2 and inherited from the Industry protocol; it remains unrun (the corpus's own claim is that funded startup IC tracks are rare). Tests the "uncushioned rotation is the harm" pillar directly.*

**F3 — The cushions-don't-help falsifier.**
*If* organizations that provided the **three cushions** at the first rotation (honest label, fallback, scaffold), funding held constant, showed *no better* transition survival → "uncushioned rotation is the harm" weakens toward "under-resourcing in general," not the *missing cushions specifically.* *This is `DRAFT` §6b F3. The confound is brutal (orgs that can afford cushions differ); needs funding-matched pairs — see `R4`.*

**F4 — The base-rate falsifier for the imposter/structure link (already half-failing).**
*If* elevated imposter/burnout rates in software are **no higher than** matched high-achievement non-rotation populations (and the data already shows **healthcare 62% > software 52.7%**) → "imposter syndrome is accurate self-assessment of *rotation/obsolescence*" falls; it is achievement-pressure generally, not software's structure. *This falsifier is partly **already returning the disconfirming value** — the verified base rate runs against the strong claim (Bias 5). The honest move is to treat F4 as **substantially failed for the strong causal version** and retire it to corroborating, which `DRAFT` §6 concession 6 does and `01_`/`06_` do not.*

### Falsifiers per native pillar (the ones the borrowed track never stated)

**F5 — The construct-validity falsifier for "rotation at every rung" (Claim A).**
*If* an independent rater, given software career histories and **blinded to the rotation framing**, could not reliably segment them into "deepening" vs "rotation" rungs (low inter-rater agreement), *or* if the lower rungs (Junior→Mid, Mid→Senior) coded as **craft-deepening** as often as rotation → the per-rung rotation sequence is an imposed lens, not a discovered structure, and `R1` Claim A's NARROWS becomes mandatory. *Never stated by the corpus; it is the dev-ladder equivalent of the CTO `R2` F5 inter-rater study. This is the single falsifier most missing from the area.*

**F6 — The plateau-composition falsifier (Claim D).**
*If* the Senior→Staff **plateau population**, once measurable, turned out to be **dominated by genuine preference** (engineers who chose the IC craft) rather than failed-and-unnamed transition → the "quiet fracture" is mostly legitimate choice, not structural illegibility; `DRAFT` §4a's "purest case" falls. *This is `DRAFT` §6b F4 — credit the corpus for stating it. `R1` Claim D shows it is currently assumed the other way without data.*

**F7 — The reversion-meaning falsifier (Claim B).**
*If* a study of what reversion *means* found that a **substantial share of reversions are healthy pendulum swings or genuine preference** rather than failed transitions → the "~50% failure" reading inflates a number that is partly success (`03_` open question #4 admits this is unexamined). Tests whether "reversion = structural failure" is the right interpretation of the anchor.

**F8 — The Larson-load falsifier (Claim F).**
*If* "Staff Engineer" is **not** experienced as a rotation by the engineers in it — i.e., if Staff work is reported as continuous with Senior craft rather than a shift to "what other people do" → the Larson finding supports *role heterogeneity* (which it verifies) but not *rotation* (which the corpus infers). Tests the slide from "four jobs / orgs differentiate at scale" to "the individual faces a rotation."

### The honesty test the corpus should adopt

For every load-bearing claim, carry a one-line **"this is wrong if:"** clause *at the claim site*, not in an appendix. `DRAFT` §6b already does this for F1–F4 — generalize it to F5–F8, and put F5 (construct validity) and F1 (the null) in the draft body in the authors' own voice. **The single highest-leverage honesty repair:** state, in `DRAFT` §2a where "closes the null" currently lives, the opposite — *"the behavioral data is where we would close the measurement-artifact null, but the comparator arm has never been measured; we bet it won't match, and that bet is open."* A thesis that names the study that would kill it, and admits the study is unrun, converts from advocacy into a falsifiable claim.

---

## Part IV — What the bias audit does *not* find

Adversarial honesty cuts both ways. The dev-ladder corpus is **not** guilty of:

- **Fabrication.** Where figures are weak, they are labeled weak (`06_` is the most-disclaimed file in the corpus; the README leads with verification status). The verified anchor (`AX-REVERSION`) is genuinely verified.
- **Hiding the borrowed-evidence problem on MW2018/VL2023.** `DRAFT` §2b *states* the founders-not-engineers boundary in the authors' own voice ("that last clause is our extension — not borrowed"). That is exactly the discipline the CTO corpus had to be *forced* into by its `R1`; the dev-ladder `DRAFT` does it unprompted. Real credit.
- **Ignoring survivorship.** `07_` builds a genuine 3-layer model and produces an *anti-recipe*, not a success checklist — the hardest discipline in success-case work, done well.
- **Refusing falsifiers.** `DRAFT` §6b states four in the authors' own voice — ahead of where both siblings started.

The corpus's problem is not dishonesty. It is **a disciplined draft sitting on top of over-reaching research files, plus a structural over-trust in borrowed rigor** — the authors are careful about citations and about the `DRAFT`, and careless about the gap between "the Industry review cleared this" and "this tier's version was ever reviewed." The flag system polices the inherited axis far better than the native one, because the inherited fixes were already made elsewhere.

---

## Summary: the bias audit in one table

| # | Bias | Tag | Severity | Cheapest honest fix |
|---|---|---|---|---|
| 1 | Borrowed-rigor laundering (inherited R-track cited as if it audited this tier) | promotion artifact | **High** | Label every "survives the adversarial review" by altitude; cite *this* track for native claims |
| 2 | "Closes the null" — open flank escalated to closed | borrowed-rigor | **High** | Retract in `09_` Pillar 1 / `DRAFT` §2a; restore parent's OPEN form (F1) |
| 3 | Arguing from silence on the plateau population | never reviewed | **High** | Demote plateau to "unmeasured hypothesis"; strike "larger / purest case" (F6) |
| 4 | Confirmation collection + no native disconfirming-mechanism search | original sin (laundered) | **High** | Commission "evidence the rungs are not rotations" (F5; `R4`) |
| 5 | Asymmetric scrutiny (promote anchor, "consistent-with" the base rate) | partly inherited | Med-High | State healthcare-62% as *disconfirming* for the strong imposter claim (F4) |
| 6 | Unverified figures load-bearing in `01_`/`06_` despite disclaimers | native | Medium | Propagate the `DRAFT`'s demotion back to the research files |
| 7 | Residual "incompatible" overclaim | native, README-owned | Medium | Execute the README's reconciliation in `01_`/`06_`/`08_` |

**The single highest-leverage honesty repair:** put F1 *and* F5 in the `DRAFT` body in the authors' own voice, and reverse the "closes the null" sentence to name the unrun comparator study. That converts the area's two signature overreaches (Bias 2, Bias 4) into the two falsifiers that would test them — which is the difference between an inherited worldview and a native finding.

---

*Companion: `R1_ADVERSARY_strongest_counterevidence.md` (the external attack this audits from inside), `R3_STEELMAN_strongest_form.md` (the version that survives both), `R4_OPEN_RESEARCH_agenda.md` (F1–F8 as a forward research program). Parent track: `../Software Industry/R1`–`R4`. Form template: `../CTO/R1`–`R4`. Verification source of truth: `../CTO/07_APPENDIX_citation_review.md`.*
*Framework developed in collaboration with Claude (Anthropic). Research conducted June 2026.*
