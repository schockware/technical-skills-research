<!-- Derived from DRAFT_SYNTHESIS.md @ c240d35 (spine §0–§6 complete, reconciled to R1–R3). A projection for the Academics / researchers audience: closest-to-spine of the five — emphasis and research-agenda framing, not simplification. Keeps §6 in full, expands the agenda from R4. No claim added that isn't in the spine; no retired claim restored. -->

# The Rotating Ladder — Research Agenda Edition
## A structurally-grounded framework for the software career ladder, its one corroborated discontinuity, and the experiments that would confirm or break it

> **Audience brief (the Academic / researcher row of the spine's Audience Map).** §1 → *the verifiable observation (one corroborated seam, not "every rung")*; §2 → *the behavioral anchor (n≈30k) read as boundary-difficulty; the plateau as hypothesis*; §3 → *the cross-industry cushion comparison, narrowed*; §4 → *the falsifiable form: do structure-aware orgs intervene better?*; §5 → *the revealed-preference argument (cushion-when-affordable)*; §6 → **the payload — F1/F2/F3/F5 are the study designs; F5 (construct test) runs first.**

> **What this version is.** This is the projection that stays *closest to the rigorous spine* (`DRAFT_SYNTHESIS.md`). For this audience the job is not to soften — it is to foreground what a citing reader needs: the *framework-vs-finding* line drawn at every claim, the concessions kept in full, and the falsifiers promoted from a closing section to the deliverable. **The falsifiers are the deliverable.** Nothing below adds a claim the spine does not license; where the spine concedes, this version concedes harder, because this is the audience that *rewards* the concession.

---

## §0 — The claim, sized for a referee

> **The software career ladder makes its one institutionally-real skill discontinuity — the individual-contributor-to-manager rotation that the industry alone split into two separate, separately-evaluated career tracks — a *default* advancement step, and surrounds it with a recurring pattern of further rotations (Senior→Staff most clearly, via Larson) that the title structure labels as "deepening" rather than the change in the *kind* of worker they are. At the load-bearing rung, software at startup and mid-market scale provides none of the three cushions — honest labeling, a respected craft-track fallback, a scaffolded transition — that make the same rotation survivable in other rotating professions. The predictable, population-scale difficulty this produces is then read as individual inadequacy. "Smart people should be able to learn everything" is the belief that performs that attribution. It does not explain the difficulty; it explains away the structure.**

The honest one-line characterization of the epistemic state, stated up front so a reviewer can hold the whole claim at the right size:

> **Strong component grounding, an open distinctiveness question, and a central unrun construct test.**

That sentence governs everything below. The contribution is **a precise, non-pejorative vocabulary for a real, structurally-grounded pattern** — not a measured finding that software is distinctively broken, and emphatically not the claim that the ladder is irrational. A referee should read this as a framework with one load-bearing behavioral anchor, three named experiments that could break it, and a list of questions no experiment can ever close.

**Provenance disclosed honestly.** This area ran on the parent **Software Industry** adversarial track (`R1`–`R4`) until it was promoted to its own. The promotion exposed a bias the borrowing hid — *borrowed-rigor laundering* (`R2` Bias 1): the inherited review audited Industry-altitude claims and was cited as if it had audited the career-ladder-native ones (the per-rung sequence, the plateau, Larson-as-structure, the reversion anchor's reach). Three of those NARROW or partly fall under native review. The `[inherited]` / `[re-derived at this tier]` / `[never-reviewed]` tags carried through `R1`–`R4` are part of the audit trail, not decoration — they mark exactly which moves transferred clean and which got first-class native treatment.

---

## §1 — The established floor vs. the framework lens

The discipline a referee should hold the authors to is the **framework-vs-finding** line, and §1 is where it is sharpest. Two of this section's claims are *established* (verifiable without the framework); the rest is a *lens* (a defensible description of an arc, not a set of measured cliffs).

**Established — needs no framework.**

> **The software industry built two formal, separately-laddered, separately-evaluated career tracks — individual contributor and management — and told engineers to choose between them.** The IC→manager rotation is therefore not a reading imposed by this paper: the industry's own org charts attest it is a change in the *kind* of work. No other major profession formalized that split.

This is the one rung with an external, non-narrative witness — externally named (*"the transition to an EM is a role change, not a promotion"*, Pat Kua), witnessed by a hard behavioral fact (§2), and attested by the formal track split itself. A skeptic who rejects everything else must still account for it.

**Framework — a lens over an arc, explicitly not a per-rung finding (`R1` Claim A, the keystone re-cut).**

- **Senior→Staff** is a *second, weaker* instance: Larson's *Staff Engineer* (2021) finds "Staff Engineer" is four distinct jobs behind one title (Tech Lead, Architect, Solver, Right Hand) — *"most career ladders paper over several distinct roles hidden behind a single moniker."* This corroborates that the rotation *recurs inside* the IC track, but it rests on a single practitioner book, not a behavioral measure. *(`AX-LARSON`, ✅ Confidence 5 — the book is verified; the structural universality is not. The slide from "four jobs / orgs differentiate at scale" to "the individual faces a rotation" is exactly the inference F8 in `R2` is built to test.)*
- **The lower rungs** (Junior→Mid, Mid→Senior) the corpus's own cells concede are *near craft-deepening* shading toward rotation — adjacent skills, not measured discontinuities.

**The rival account, conceded, not waved away.** The same career data fits a *continuous scope-broadening* reading (steadily more influence-work as you advance) at least as well as discrete kind-rotations at the lower seams. The paper does **not** claim to have run the test that distinguishes the two — that test is **F5/Q4**, and it is unrun. "Rotation at *every* rung" is demoted from finding to framework: one real discontinuity, one weaker secondary, the rest a defensible arc. The argument needs only the *one* seam, and that one is not in dispute.

**The rotation, not incompatibility.** The *object* of the skill rotates (code → team → org → market); the skills are not incompatible. The engineer/manager pendulum shows positive transfer — they coexist in one person over a career. "Distinct skill sets with no on-the-job runway," never "incompatible." *(Corpus-wide retirement; `../CTO/18_RESEARCH_modes_not_incompatible.md`. Note for the referee: the research files `01_`/`06_`/`08_` still carry the retired "incompatible" wording — `R2` Bias 7, reconciliation pending; this draft and the spine do not.)*

---

## §2 — The behavioral anchor, scrupulously read as boundary-difficulty

This is the section where the audience's signature correction lives, and the one where overclaiming is the cardinal sin. The number is the corpus's strongest single asset; what it does and does not license must be stated with care.

### 2a. What the anchor is

> **The IC→Engineering-Manager reversion rate: roughly half of newly promoted engineering managers return to individual-contributor work.** Corroborated at large sample — CEB/Gartner ~50% of new managers/executives fail within 18 months (n≈30,000), ~60% within 24 months; McKinsey ~40% for newly promoted executives, stable over 15 years. *(`AX-REVERSION`, ✅ verified, Confidence 4. Use Weekes — "if this was the failure rate of a service, we would do a postmortem" — for vividness; anchor the number to CEB/Gartner.)*

It is the paper's strongest empirical fact for one reason: it is **behavioral, not sentiment.** It measures what people *did* (returned to IC), across a population including both successes and failures, at scale.

### 2b. What it does *not* do — the area's signature correction

**Be scrupulous about this; it is the regression a referee will hunt for.** The CEB/Gartner n≈30,000 is a **cross-industry** rate — the corpus's own `03_RESEARCH` calls it "the cross-industry baseline for new manager failure." A rate that is the same everywhere proves the *boundary* is hard (IC→management is hard for *everyone*), **not** that software is distinctively broken.

Mapped onto the measurement-artifact null (the deepest competing explanation: *software isn't more broken, just more online, more introspective, more surveyed*):

- It **neutralizes the weak form** — a population-scale *behavior* is not blog-post sentiment, so "it's all just software vocalizing its feelings" fails.
- It does **not close the null.** A reversion rate *the same across industries* is exactly what the null predicts: universal difficulty, software merely more vocal. Closing the null requires comparator-profession *behavioral* reversion rates *lower* than software's — never measured (`05_RESEARCH` concedes non-software reversion rates are unquantified; **F1**).

> **The distinctiveness claim does not live here. It lives in the cushion comparison (§3).** Lead with this number for *boundary-difficulty*; let §3 carry distinctiveness; let the imposter/burnout figures corroborate, never carry.

This is **concession 8** stated as load-bearing rather than buried: the behavioral data does *not* close the measurement-artifact null. The earlier "closes the null" framing (in `09_` Pillar 1 and the spine's pre-reconciliation §2a) was the area's signature overreach — an *inherited open flank* escalated to a *closed win* with no new data (`R2` Bias 2). **Reproducing that overclaim is a regression, not a strengthening.** The closure is a *bet* on F1, not a result.

One further seam to keep visible (`R1` Claim B point 3): the n≈30,000 *credibility* comes from the general-management sample, while the "the ~50% holds even with management training" *qualifier* belongs to a smaller, software-specific, **unmeasured** population. State "even with support" as a practitioner observation consistent with the structural reading, not as something inside the n≈30,000 data.

### 2c. The mechanism — peer-reviewed *in founders*, extended to engineers

This is the one place the argument has **peer-reviewed** grounding, and the one place the boundary on that grounding must be stated most carefully.

Mathias & Williams (2018, *JBV*) and Van Lancker et al. (2023, *JBV*) — the corpus's two full-text-verified anchors — establish **in founders** that role transitions turn on which roles one will give up, retain, and adopt; the hard part is **giving up a self-defining role** (an identity loss, not a task hand-off, `AX-MW2018` ✅); successful offload runs through physical-without-psychological disengagement and **role-identity imprinting**; and the offload *sticks* only under **psychological safety and value-fit** in the receiving team (`AX-VL2023` ✅).

> **The boundary on this evidence (`R1` Claim C):** these papers study **founders** — the buffered, CEO-analog case. They establish the *mechanism* (role transition is identity-gated and offload-conditional). They do **not** study engineers and do **not** establish dev-ladder severity. The claim is: *the mechanism is peer-reviewed in founders; the engineer crossing IC→EM faces the same mechanism with fewer of the conditions that let it succeed.* That last clause is the paper's extension, argued in 2d — **not borrowed.** A referee should read MW2018/VL2023 as grounding the mechanism, never the engineer-specific severity.

The identity diagnosis is reinforced by why the boundary is *unanchored* in software: the surgeon who becomes Chief of Surgery is still, institutionally, a surgeon (the license persists); the engineer-turned-manager has **no external anchor** — the "software engineer" identity was constructed entirely by *doing the work*, so when the work stops, the identity has nothing to hold. Reverting to IC under pressure is reaching for the only identity anchor that exists. *(Axis 5 — a mechanism hypothesis with a named falfsifier, F7 in the parent protocol, not proof.)*

### 2d. Who crosses durably — and the anti-recipe

Applying the three-layer rigor model to a heavily survivor-selected success literature (`07_RESEARCH`) yields a finding that points *away* from individual heroics:

> **The factors that most consistently distinguish durable transitions are organizational and contextual, not individual** — psychological safety in the receiving team (`AX-VL2023`, transferability 1/5, outside the individual's control), value fit, active manager-of-managers investment, a high-potential junior to imprint onto. The individual factors (identity reframe, "feeling ready") are necessary-not-sufficient: the reframe is the *outcome* the transition produces, not an installable input.

> The engineers who made durable transitions were not more committed or self-aware than those who reverted. They were more structurally supported. The ~50% is not the cost of insufficient effort; it is the **structural throughput limit** of a transition attempted without adequate organizational conditions.

*(`07_`'s 3-layer model and the anti-recipe are, per `R2`, the area's best native rigor — survivorship handled by producing an anti-recipe, not a success checklist.)*

---

## §3 — The cross-industry cushion comparison (narrowed under adversarial review)

This is where distinctiveness lives — and where the comparison must be read at **equal charity**, because the temptation to re-idealize the comparators is the residual crack `R1` Claim E flags.

### 3a. The three cushions

1. **Honest labeling** — the military names the Warrant Officer / Functional-Area track; consulting's up-or-out is explicit in recruiting materials. Software's promotion framing says "deepening" when the work is rotating.
2. **A respected craft-track fallback** — the surgeon stays licensed and operating; the professor keeps researching. Until large-company Staff/Principal IC tracks emerged (post-2010s, partial), software offered no path that said "staying technical is a legitimate advanced outcome"; for most practitioners at most companies it still doesn't.
3. **A scaffolded transition proportionate to the ask** — residencies, pupillage, officer academies are multi-year supported immersions. Software offers a title, a manager change, perhaps a course — on the company's funding clock, not the human's development clock.

### 3b. What the comparison establishes — and the charity discipline

> **Other rotating professions have at least one cushion at the point where most practitioners first hit the rotation. Software, at startup and mid-market scale, has none on the *default* path.**

**Not that other professions are clean** — they are not, and a referee should hold the authors to stating this at equal charity. Medicine's clinician→administrator drift follows the Red Baron pattern (~45–55% administrative burnout). Law's partnership tournament is a real rotation (lawyering→rainmaking), a Category A/B hybrid, not pure deepening. Academia's "bait-and-switch" is software's closest structural parallel and generated *the same critique independently*. The comparison does not need the comparators to be idylls — only to have **at least one cushion software lacks at the relevant scale.**

The compound is non-additive: unstable *credited* craft makes identity rotation harder (no stable identity to rotate *from*); an unlicensed identity makes deceptive labeling more damaging; and the **Red Baron selection effect** ensures the most vulnerable — the best ICs, whose identity is most built on direct output — are exactly those selected for the rotation.

**The two residual cracks, named (`R1` Claim E):** "startups have *no* cushion" is **inference, not measurement** (no startup-scale outcome data — F2/F3); and the comparators must be read at equal charity (medicine's admin track also rotates and burns out).

### 3c. The revealed-preference reinforcement

This does not live only in the logic — the industry *acts out* its belief that the composite exceeds one person:

- **It built the craft-track fallback the moment it could afford to** (Staff/Principal IC tracks, dual-track systems — corrections to a problem software created; medicine never needed them because it never built the rotation). *That software built the cushions at all is proof it knew they were needed. The correction is the confession.*
- **It distributes the composite the moment it can afford to** — Larson's archetypes emerge *as the org grows* (Architect ~100 engineers, Right Hand ~1,000). The undifferentiated "Staff Engineer" who must be all four is the budget compromise, not a considered design.

This rests on an uncontested *behavior* (orgs differentiate when funded), not a contested number — which is why it survives `R1`/`R2` intact and is the corpus's strongest rhetorical asset.

---

## §4 — Misattribution as the actionable harm — stated in its falsifiable form

This is the most defensible pillar precisely because **it does not require software to be uniquely broken** — the part the measurement-artifact null threatens. It requires only that the attribution is *misdirected*, which is observable directly.

### 4a. The pattern, and the discipline on it

When the rotation produces its predictable difficulty, the language is consistent and personal: imposter → "needs coaching"; reversion → "management wasn't for them"; plateau → "not ready for the next level"; churn → "culture fit." Each individually plausible — which is why the pattern is hard to see. The tell is the *consistency* across cases, companies, and decades: a difficulty the structure produces **for almost anyone placed in it** is recorded, every time, as a fact about the person.

> **The claim is about *default attribution*, not causation in the individual case.** When the structural and individual explanations are both available, the field reaches reflexively for the individual one — and because it does, never asks the structural question. This framing is deliberate and load-bearing: it survives **U1** (the person-vs-structure counterfactual is permanently underdetermined — you cannot run the same engineer twice). *Any draft sentence that says an engineer reverted* because of *the structure is claiming a counterfactual it cannot have.* Keep the framing exactly as "default attribution."

**The clearest *measured* case is the visible reversion** — "management wasn't for them" said over a person who is, by the n≈30,000 data, one of roughly half who make that move.

**The Senior→Staff plateau is a *hypothesized* additional instance, marked as such (`R1` Claim D; concession 9).** The failure leaves no reversion event, no postmortem, no statistic — rhetorically vivid and evidentially empty in the same stroke. Its size and composition are **unmeasured**, and it is over-determined by a benign cause (genuine preference for IC work) that the rise of respected IC tracks should *increase*. So it cannot be "the purest case" or "larger than reversion" on the strength of its own invisibility — that is arguing from silence, the mirror of the `RISK-ASYMMETRY` anti-pattern the corpus polices elsewhere (`R2` Bias 3). What survives is narrower and real: Staff-promotion criteria are demonstrably illegible (and if Larson is right, some engineers are evaluated against a target nobody named), so *some* quiet, misattributed non-promotions plausibly occur. **The mechanism (illegibility breeds misattribution) holds; the population estimate does not.** Its *composition* is, per **U2**, partly unstudiable — self-report about one's own motives after a decade of not-having-been-promoted.

### 4b. Why it self-perpetuates

The loop is short and never converges: structure produces difficulty → difficulty attributed to individual → remedy is individual (coach/replace/hire "someone more senior") → replacement enters the *same* uncushioned boundary → repeat. Serial replacement *is* this loop. It treats a recurring structural failure as a fresh individual one.

### 4c. The contribution, in its falsifiable form — the §4 payload for this audience

> **A precise, non-pejorative vocabulary that re-attributes the difficulty from the person to the structure — so that a difficulty narrated as personal failure ("not ready for the next level") can instead be named structurally ("the ladder demanded a rotation here and resourced no transition for it"), which is the prerequisite to resourcing it.**

The load-bearing sentence: **you cannot resource a transition you cannot name.** And — the part this audience must not miss — the contribution is staked on a **falsifiable position**, not a retreat to "we only offer words":

> **Q-legibility: do structure-aware organizations intervene better than structure-blind ones?** Naming is claimed as *necessary-but-not-sufficient*. If structure-aware organizations intervened no more effectively than structure-blind ones, the legibility claim would fail.

**This is the legibility claim's own falsifier — the corpus states the position but never names the study (`R4` Part IV).** It is the test of the one pillar that survives everything else, and a citable version must commission it. It is Q3 viewed from the *intervention* side: classify orgs by whether they *name* the rotation structurally vs. attribute to the individual, and measure whether the structure-aware orgs resource transitions better and get better outcomes. If naming changes nothing, the contribution is wrong.

The contribution does **not** claim the vocabulary *solves* the problem (naming the under-resourcing does not fund the fix), and it is **not** the claim that the ladder is irrational — see §5.

---

## §5 — The accidental concession (the revealed-preference argument), and the "irrational" line a referee must hold

A careful reader has the strongest rebuttal loaded; stating it concedes the argument.

> **The objection:** "You're describing growth, not a defect. Every career asks people to change as they advance — and startups can't *afford* residency-style transition programs; the lean ladder is an economic necessity, not a design flaw."

**Why it is a concession.** "We can't afford to support this transition" presupposes the transition genuinely *requires* support — that the rotation exceeds what an unsupported person reliably crosses. You do not say "we can't afford to scaffold it" about a transition people make comfortably alone. The objection's own logic concedes the capacity ceiling the thesis asserts, and pleads budget. And "it's just growth" collapses against §1's narrowing: growth is *more of the same craft, deeper*; the load-bearing rotation is a change in the *object* of the skill, which most careers do not impose on the default path — and the ones that do, cushion.

**Why this is the asset that survives everything:** it is **logically airtight independent of every contested number** — no half-life figure, no imposter rate, no "closes the null," no plateau estimate. It needs only one uncontested behavior: **organizations cushion and differentiate the ladder when they can afford to** (§3c's revealed preference). It does not depend on a single thing `R1` narrowed.

**The line a referee must hold (and U4):** the thesis does **not** claim the ladder is *irrational*. The lean structure may be a perfectly efficient bet for the company; the harm is to the *person*, and is real whether or not the *system* is rational. **"Under-cushioned," not "irrational."** This is not merely rhetorical hygiene — per **U4**, "smart people should learn everything" is a *normative* diagnosis (a values claim about where the burden should sit), and data can show the transition is costly-to-the-person and efficient-for-the-company without adjudicating whether attributing the cost to the individual is "right." Keep "misattribution" (descriptive); drop any slide to "irrational" (normative). No citation closes a normative gap.

---

## §6 — Concessions and falsifiers, in full (this is the deliverable)

For this audience §6 is not the closing section — it is the paper. The concessions are kept complete; the falsifiers are the study designs. **Foreground them.**

### 6a. Concessions, made up front

1. **Software has a stable foundation layer; prior expertise is not a blanket "liability."** Algorithms, data structures, type systems, networking, concurrency, relational theory (Codd 1970) are decades-stable; DORA/*Accelerate* shows transferable practice. The claim is *not* "nothing is stable" and *not* "expertise is a liability" (`R1` Claim H corrects the earlier obsolescence framing). It is: **the evaluation and promotion machinery credits the volatile, fashionable layer (which decays) while the durable foundation (which compounds) goes uncredited.** The single most important narrowing (Axis 4) — it makes the performance-review argument *sharper*. *(Half-life figures behind the decay claim are ⬜ unverified; the argument holds on the credited/durable split even if every number shifts.)*
2. **Rotation itself is not the harm; uncushioned rotation is.** The military rotates; consulting rotates harder. Done with a cushion, rotation is survivable and sometimes healthy.
3. **Other professions are not idylls.** Medicine ~45–55% admin burnout; law's partnership tournament is a real rotation; academia generated the same critique independently. The comparison needs only *one cushion software lacks at the relevant scale.*
4. **Performance differences are real and large — contextually.** The thesis is anti-*fungibility*, not anti-*differentiation*. "Non-fungible" (ISBSG team-size data, Brooks, Project Aristotle, Nichols/CMU) ≠ "unmeasurable."
5. **The large-company correction is genuine.** Dual-track IC paths work where they exist. The scope is the **startup/mid-market gap.**
6. **The imposter-syndrome figure is corroborating, not load-bearing — and not "accurate self-assessment."** The 52.7% (Clance, 2024) is ⬜ unverified; even verified, elevated imposter rates appear across all high-evaluation populations (**healthcare ~62% > software 52.7%**) regardless of rotation structure, so "imposter syndrome is the engineer accurately perceiving structural mismatch" is correlation read as causation (`R1` Claim H). It is *consistent with* the thesis; it does not prove it — and for the *strong causal* sub-claim the base rate is **actively disconfirming** (the highest rate is in a craft-deepening, licensed field the thesis predicts should be lowest; `R2` Bias 5, F4). The ~50% reversion carries the behavioral weight. *(`01_`/`06_` still state the strong causal version — propagation owed, `R2` Bias 6.)*
7. **"Rotation at every rung" is a recurring pattern, not a per-rung measured discontinuity — promoted from concession to thesis (`R1` Claim A).** Only IC→management is corroborated by a hard behavioral fact and the track split. Junior→Mid is near craft-deepening; the rest is a defensible arc, not five measured cliffs. Listed here to keep the concession set complete.
8. **The behavioral data does *not* close the measurement-artifact null.** The ~50% neutralizes the *sentiment* form but, being cross-industry, is consistent with the null's core (universal difficulty, software merely more vocal). Closing it requires comparator behavioral rates *lower* than software's — unmeasured (F1). The closure is a *bet*, not a result; distinctiveness is located in §3 instead. *(The area's signature correction — `R1` Claim B / `R2` Bias 2.)*
9. **The Senior→Staff plateau population is a structural hypothesis, not a measured fact.** Size and composition unknown; over-determined by genuine preference (which respected IC tracks should increase). Carried as a hypothesized instance, never the load-bearing or "purest" case — that role belongs to the visible reversion (`R1` Claim D).

### 6b. Falsifiers — the study battery (ordered by what runs first)

Each is a study a referee could commission; the predicted outcome and the claim it would retire are stated. **F5 runs first** — it is cheap and gating: if blinded raters cannot segment careers into "deepening" vs "rotation," the expensive cohort studies (F1/F2) measure an artifact.

| # | Study | If it came back this way… | …this claim falls | Cost |
|---|---|---|---|---|
| **F5 (construct — run first)** | Blinded raters segment career histories into "deepening" vs "rotation" rungs; compute inter-rater κ (LinkedIn + leveling-rubric data; 2–3 trained raters) | **Cannot reliably segment**, or lower rungs code as *deepening* as often as *rotation* | "Rotation at every rung" is an imposed lens, not a discovered structure (§1; `R1` Claim A). High κ + lower rungs coding as rotation would let the corpus *un-narrow* Claim A. | **Low (gating)** |
| **F1 (central)** | Matched high-achievement **non-rotation** professions, measured on *behavioral* outcomes (reversion, tenure, observed exits) at the analogous boundary — denominator must include both reverters and stayers, behavioral signals only, never surveys | Comparators fail at **equal** rates to software | Software is better-*documented*, not less-*cushioned*; the distinctiveness null wins; the structural claim reduces to "this transition is hard." *This is the study the retracted "closes the null" pretended was resolved (§2b). It is open.* | High |
| **F2** | A **well-resourced IC track at startup scale**; measure IC→EM reversion vs. matched composite-ladder startups (funding-matched pairs) | Still ~50% reversion among engineers who chose management | The absent craft-track fallback is not the cause; the no-cushion mechanism (Axis 5) is not doing the work. | High |
| **F3 / Q-legibility** | Orgs providing the **three cushions** (or *naming* the rotation structurally), funding held constant; compare 24-month transition retention — vary cushions to isolate which works | Cushioned/structure-aware orgs do **no better** | "Uncushioned rotation is the harm" weakens toward "under-resourcing in general"; and the legibility contribution (§4c) fails if *naming* changes nothing. | Medium |
| **F4 (already half-failing)** | Compare software imposter/burnout to matched non-rotation high-achievement populations | No higher than comparators (data already shows healthcare 62% > 52.7%) | "Imposter = accurate self-assessment of rotation" falls; it is achievement-pressure generally. *Treat as substantially failed for the strong causal version already.* | Low |
| **F6** | The plateau population, once measurable, typed by cause | **Dominated by genuine preference** | The "quiet fracture" is mostly legitimate choice; the §4a plateau hypothesis falls entirely (harm rests on the visible reversion alone). | Low–Med |
| **F7** | A cohort of reverters tracked 24–36 months, reversion *type* coded | A substantial share are **healthy pendulum swings / preference**, not failed transitions | "~50% failure" inflates a number partly composed of success (`R1` Claim B point 4). | Low |
| **F8** | Ask the engineers *in* Staff roles whether the work is experienced as continuous with Senior craft or a shift to "what other people do" | Reported as **continuous**, not a rotation | Larson supports *role heterogeneity* (verified) but not *individual rotation* (inferred). | Low |

### 6c. The questions no study can close (permanent caveats)

A citable version must state these as permanent, not as promissory notes:

- **U1 — the person-vs-structure counterfactual.** The core causal claim requires running the same engineer twice. Permanently underdetermined for any individual case; this is *why* §4 claims only *misattribution* (default attribution), never "the structure caused this reversion."
- **U2 — the plateau's composition floor.** The *size* is answerable; the *composition* (failed-and-unnamed vs. genuine preference) depends on a counterfactual and on motivated self-report after the outcome is known. The plateau can never establish its own size-and-cause cleanly.
- **U3 — identity investment is self-report about the self.** The identity mechanism (Axis 5) and the "identity reframe" success factor hinge on degree of identity fusion, accessible only through self-report — where motivated distortion is worst. The mechanism may be real and permanently unmeasurable cleanly; Q5 mitigates by coding *behavior* (did they offload?) not felt identity.
- **U4 — "smart people should learn everything" is normative.** Data cannot adjudicate whether attributing the cost to the individual is "right." Keep "misattribution"; drop "irrational" (§5).
- **U5 — the ladder is a moving target (AI).** The thesis describes the 2014–2026 ladder. AI-assisted coding may shorten the knowledge half-life *or* lengthen it (durable architectural judgment more valuable); if it transforms the IC layer, the IC→management boundary itself may shift. A thesis about a structure in flux has a shelf-life — a scope condition, not a flaw.

---

## §7 — The expanded research agenda (the citable forward program)

For this audience the §6 falsifiers map onto a commissionable program (from `R4`), ordered by leverage. The through-line: *the corpus is strong on what it claims and thin on what would prove it wrong in practice — and the borrowing made it look tested when its native claims were not.* None of these can be closed by finding another supporting citation; that is exactly why they remain open after a citation pass and a borrowed adversarial pass that closed everything they touched.

| ID | Question | Tag | Type | Breaks the thesis? | Cost |
|---|---|---|---|---|---|
| **Q4 = F5** | Inter-rater validity of "rotation at every rung" | **native** | Content-analysis | Yes (construct) | **Low — run first** |
| **Q1 = F1** | Matched-comparator behavioral failure rates | re-derived | Cohort | **Yes — central (distinctiveness null)** | High |
| **Q-leg = F3'** | Structure-aware vs structure-blind orgs intervene better? | **native** | Org study | **Yes — kills Pillar 3 if null** | Medium |
| **Q2 = F2** | Funded startup-scale IC track → still ~50%? | **native** | Quasi-exp | Yes (Pillar 2 mechanism) | High |
| **Q5** | IC→EM transformation mechanism (offload-and-acquire?) — MW2018's interview method, ~30–45 engineers | re-derived | Qualitative | Yes (mechanism reach) | Medium |
| **Q6 = F7** | What reversion *means* (failure vs preference vs pendulum) | **native** | Follow-up | Yes (anchor interpretation) | Low |
| Part II | Staff-promotion rates by org; plateau size; unverified-figure verification pass; Larson archetype distribution | inherited+native | Access/effort | No — firms up existing claims | Low–Med |

**Priority, stated plainly:** run **Q4 (F5)** first — it tells you whether the modes are real enough to count; then **Q1 (F1)** — the only study that could tell the authors the comparators match, i.e., that the thesis is wrong; then **Q-legibility** — the test of the one pillar that survives everything else. A confirmation-oriented process (and a borrowed-rigor one) leaves exactly those for last. This version puts them first.

---

## The contribution, restated for the citing reader

> **A precise, non-pejorative vocabulary for a real, structurally-grounded pattern — uncushioned rotation at the load-bearing rung (and recurring above it) — so that population-scale outcomes the field narrates as personal failure can instead be named structurally, which is the prerequisite to resourcing it.**

It rests on four things and only four: **one institutional fact** (the IC/management split, §1), **one large-sample behavioral number** (the reversion rate, read as boundary-difficulty, §2), **one peer-reviewed mechanism** (identity-gated offload, in founders, §2c), and **one honest reframe** (attribution from person to structure, §4). It needs no "rotation at every rung," no "closes the null," no plateau estimate, no "accurate self-assessment," no unverified half-life. The difference between a framework and a finding is whether the author names the experiment that would kill it, commits to running it, and states which questions no experiment can ever close. This version does all three. For the one or two claims that can bear it, F5, F1, and Q-legibility are what would let the area earn the word *finding*. Everything in Part III stays, honestly, "consistent with" — forever.

---

*Derived from `DRAFT_SYNTHESIS.md` (spine §0–§6, reconciled to `R1`–`R3`) @ c240d35. The Academics / researchers projection: the closest-to-spine of the five — §6 kept in full, the research agenda expanded from `R4_OPEN_RESEARCH_agenda.md`, the falsifiers promoted to the deliverable. No claim added that isn't in the spine; no retired claim restored. Behavioral anchor (n≈30,000 reversion, `AX-REVERSION`) read as boundary-difficulty, never distinctiveness; distinctiveness located in the §3 cushion comparison. Adversarial basis: `R1_ADVERSARY_strongest_counterevidence.md`, `R2_FALSIFICATION_and_bias_audit.md`, `R3_STEELMAN_strongest_form.md`, `R4_OPEN_RESEARCH_agenda.md`. Sibling: `../../CTO/derived/`. Framework developed in collaboration with Claude (Anthropic). Research conducted June 2026.*
