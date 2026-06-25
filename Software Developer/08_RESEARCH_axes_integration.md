# The Five Axes: Integrating the Structural Variables Into the Dev-Ladder Findings
## Research Note: What the Industry Thread Explains That the Dev-Ladder Thread Could Not

**Research date:** June 25, 2026
**Status:** Active research — integration document
**Relationship to corpus:** The Software Industry thread (`../Software Industry/00_AXES_SUMMARY.md`, `01_`–`04_MMM_*`) identified five structural axes and a root cause (the fungibility assumption) that explain *why* software specifically produces the failure patterns this thread documented. This file maps each axis to the dev-ladder findings, identifies what each axis explains that the dev-ladder research had named but not fully grounded, and notes the steel-manning challenges each axis must survive.

**The integration thesis:**
> *The dev-ladder research documented what happens and where. The industry thread identified why software specifically. Together they establish that the software career ladder's failure pattern is not an accident of design — it is the predictable consequence of building a rotation-demanding, deceptively-labeled career structure on top of a craft that was never stable enough to anchor the identities it was asking people to give up.*

---

## The Five Axes, Applied to the Dev-Ladder Findings

### Axis 1: Craft-Deepening ↔ Identity Rotation
**Source:** `../Software Industry/03_MMM_transformation_expectation.md`, `05_RESEARCH_cross_industry.md`

**What the dev-ladder research found without this axis:**
- Every significant rung of the software ladder requires a different kind of worker (`01_RESEARCH`)
- The IC→EM transition fails ~50% of the time even with support (`03_RESEARCH`)
- The Senior→Staff transition fails quietly — plateau rather than reversion (`04_RESEARCH`)
- Most other professions never built this problem (`05_RESEARCH`)

**What Axis 1 adds:**
The axis names the structural variable that predicts whether a career ladder produces manageable transitions or population-scale failure. It is not that software transitions are *hard* — consulting transitions are harder by some measures. It is that software transitions are *identity rotations disguised as craft deepenings*. The title says "engineer." The job has left engineering. The axis makes that structural distinction precise rather than descriptive.

**Dev-ladder mapping:**

| Transition | Axis 1 position | Evidence |
|---|---|---|
| Junior → Mid | Near craft-deepening | Modest mismatch, skills adjacent |
| Mid → Senior | Moving toward rotation | Influence-without-authority is a different cognitive mode |
| Senior → Staff | Identity rotation, unlabeled | Larson: four different jobs behind one title; `04_RESEARCH` |
| IC → EM | Full identity rotation, loud | ~50% reversion; `03_RESEARCH` |
| EM → Director → VP Eng | Identity rotation, compounding | "Not a promotion — a career change"; `01_RESEARCH` |

**Steel-manning challenge for Axis 1:** The rotation claim requires that the skills at each level are genuinely *distinct in kind* rather than just *different in degree* — note this is **no longer** an "incompatible skills" claim (retired corpus-wide; the engineer/manager pendulum shows positive transfer, `../CTO/18_RESEARCH_modes_not_incompatible.md`). The steelman says: senior engineers do develop influence skills; Staff engineers still write code occasionally; EMs still think technically. If the skills are complementary rather than competing, "rotation" overstates the discontinuity. The response (from `08_DRAFT_skills_divergence_thesis.md`): the divergence is in *focus*, not just scope — the object of the skill moves from the product, to people, to the market. An EM who writes code is doing their old job inside their new role; the jobs compete for *time and identity within one role*, not as inherently opposed skills. The divergence is real even if the boundary is not a cliff — and `R1` Claim A confirms this holds for the *one corroborated seam* (IC→management), while demoting "rotation at every rung" to a descriptive lens over that seam.

---

### Axis 2: Honest Labeling ↔ Deceptive Labeling
**Source:** `../Software Industry/03_MMM_transformation_expectation.md`

**What the dev-ladder research found without this axis:**
- The Senior→Staff transition is invisible as a failure because it produces plateau, not reversion (`04_RESEARCH`)
- The IC→EM transition is the "loud" fracture while Senior→Staff is "quiet" (`04_RESEARCH`)
- Academia independently generated the same "bait-and-switch" critique (`05_RESEARCH`)

**What Axis 2 adds:**
The deception is the specific harm — not the rotation itself. Consulting rotates harder (up-or-out, 5–10% reach Partner). The military rotates explicitly (Warrant Officer track, Functional Area track). What makes software's historical version specifically damaging is that people navigate a transformation they were never told they were making. They cannot prepare for it, cannot seek appropriate support, cannot attribute failure to structure rather than to themselves.

**The empty cell clarifies the argument:**

| | Honest labeling | Deceptive labeling |
|---|---|---|
| **Craft-deepening** | Medicine, Law | — (nothing to deceive about) |
| **Identity rotation** | Military, Consulting | **Academia, Historical Software, Startup Software** |

The empty cell is the analytical pivot: deceptive labeling is only harmful when there is a rotation to disguise. Medicine doesn't need to honestly label its advancement because there is no rotation happening. Software's deception is harmful precisely because the rotation is real and significant.

**Dev-ladder mapping:**
- The Senior→Staff plateau population (`04_RESEARCH`) is the direct consequence of Axis 2: the transition is never named as a career change, so failures are attributed to the individual ("not leadership material") rather than to structural mismatch. No postmortem occurs because no visible failure event occurred.
- The ~50% IC→EM reversion partially escapes the deception because the track change is visible enough to name. But even here, "becoming an engineering manager" is framed as promotion, not career change — which is why the preparation offered (management training, 1:1 frameworks) targets the surface version of the transition while the identity transformation goes unsupported.

**Steel-manning challenge for Axis 2:** The steelman says software's labeling is not that deceptive — everyone knows the EM job is different, the Staff job requires more influence, the IC track versus management track distinction is widely discussed. The deception claim may be overstated. Response: the labeling of the *existence* of different roles is increasingly honest (particularly at large companies post-2010s). What remains deceptive is the labeling of the *magnitude* of the transition — "promotion" rather than "career change," "deepening" rather than "rotation," the implicit promise that technical excellence is the relevant preparation. The deception is not about hiding that the job changes. It is about hiding how fundamentally the identity must change.

---

### Axis 3: Direct Output ↔ Multiplied Output
**Source:** `../Software Industry/03_MMM_transformation_expectation.md`, CTO corpus

**What the dev-ladder research found without this axis:**
- The feedback loop loss is one of the four failure mechanisms at IC→EM (`03_RESEARCH`)
- Staff engineers must accept that their excellence is expressed through organizational influence, not personal output (`04_RESEARCH`)
- The identity reframe required at IC→EM is from "I produce excellent work" to "my excellence is expressed through others" (`07_RESEARCH`)

**What Axis 3 adds:**
It names the specific cognitive and motivational shift that the feedback-loop-loss description was pointing at. The transition from direct to multiplied output is not just a change in *what you do* — it is a change in *how you know you are doing well*, *what produces satisfaction*, and *where your sense of professional identity lives*. The identity reframe required by the transition is not optional context — it is the transition itself.

**The Red Baron effect (named mechanism, not a full axis):**
The selection mechanism compounds Axis 3 in a specific way. The engineers selected for EM and Staff roles are the ones with the deepest direct-output identity investment — the best IC performers, whose identity is most thoroughly built around doing excellent work themselves. They are precisely the population least prepared for the multiplied-output transition: the most practiced at solving problems directly, the least practiced at expressing excellence through others, the most resistant to stopping direct contribution under pressure.

**Dev-ladder mapping:**
- The ~50% reversion (`03_RESEARCH`) is the population-level signal of the Direct→Multiplied transition failing. The reversion under pressure is the engineer reaching for direct output because the multiplied-output feedback loop hasn't formed yet and the direct-output one is still there.
- The Mathias & Williams imprinting mechanism (`AX-MW2018`) is the successful version of the Axis 3 transition: the founder physically disengages from direct output while retaining the identity — keeping the meaning, dropping the activity. The transition from direct to multiplied output succeeds when that separation is achieved.
- The Van Lancker success conditions (psych safety + value fit, `AX-VL2023`) are the structural requirements for the multiplied-output mode to function: the new EM can only express excellence through their team if the team is empowered to take ownership (psych safety) and the EM believes the team cares about the work (value fit).

**Steel-manning challenge for Axis 3:** The steelman says many professions involve multiplied output at senior levels — the Chief of Surgery doesn't personally operate on every patient. Why is the direct→multiplied transition uniquely hard in software? Response: the timeline and the identity investment. The Chief of Surgery became Chief after 20+ years of operating, with a licensed identity that persists through the role change. The software EM makes the transition after 5–10 years, without a license, on an employer's schedule, while their technical craft is simultaneously depreciating. The transition itself is not unique; the conditions under which it happens are.

---

### Axis 4: Stable Craft ↔ Unstable Craft
**Source:** `../Software Industry/04_MMM_unstable_craft.md`

**What the dev-ladder research found without this axis:**
- Software knowledge has a 2.5–5 year half-life (`06_RESEARCH`, flagged ⬜ unverified)
- The depreciation interacts with career-ladder rotation to produce a compound burden (`06_RESEARCH`)
- Imposter syndrome in software is *consistent with* structural mismatch — a candidate explanation, not established as accurate self-assessment (`06_RESEARCH`; narrowed per `R1` Claim H — healthcare ~62% > software 52.7%, so it is not software-specific)

**What Axis 4 adds:**
The half-life is a symptom, not the root. The root is that software has no stable theoretical foundation. The methodological instability (only 4 of 10 major Agile methods have empirical support), the consensus problem (Jacobson: "fads more typical of the fashion industry"), the licensure problem (ACM opposed licensing in 1999 because the field cannot define what a competent practitioner should know) — these are structural properties of the craft, not contingent features of the current technological moment.

> ⚠️ **Axis 4 precision note (from adversarial review, June 25 2026):** The claim "software has no stable craft" overstates. Software has a foundation layer that is decades-stable: data structures, algorithms, complexity theory, type systems, concurrency primitives, networking fundamentals, relational theory (Codd 1970). The DORA/*Accelerate* research program (Forsgren, Humble, Kim) demonstrates that specific practices *do* transfer across organizations and predict performance — evidence that some craft is stable and replicable. The defensible claim, which is also the sharper one, is: **the *legible, credited, fashionable* layer of software skill is unstable — and that is the layer hiring, promotion, and performance-review systems measure. The durable foundation exists; the evaluation machinery does not credit it.** This narrowed version is more damning, not less: it explains the performance-review pathology precisely (the system credits the volatile surface, ignores the stable depth), and it survives the DORA objection because stable practice exists — it just isn't what careers are built on.

This is the axis that explains why software's version of every other problem is uniquely worse:

- **Identity rotation** is harder when the *credited* craft identity — the one evaluated and promoted — is built on the volatile surface layer rather than the stable foundation
- **The Red Baron effect** is doubly irrational: not only do you lose the best practitioner to management, you lose their *credited* craft authority to obsolescence anyway (while the durable foundation they also hold goes unrecognized)
- **Knowledge diffusion** through the management hierarchy fails three ways: the knowledge is tacit and contextual (Brooks), the credited-surface layer is decaying, and the methodology layer is contested
- **The deceptive labeling** is worse when the craft being "deepened" has no stable *credited* definition — the promotion to Staff Engineer promises deeper mastery of something the evaluation system cannot consistently define

**Dev-ladder mapping:**
- `06_RESEARCH_knowledge_obsolescence.md` documented the half-life and the compound burden. Axis 4 grounds it: the credited-layer decay is not an unfortunate property of a fast-moving field. It is the direct consequence of a field that built its evaluation systems on the volatile surface rather than the durable foundation.
- The imposter syndrome finding (`01_RESEARCH`, `06_RESEARCH`) is explained precisely by the Axis 4 narrowed version: the engineer is not practicing a craft with no stable knowledge. They are being evaluated and promoted against the volatile layer — frameworks, methodologies, fashions — while the durable layer they actually hold (algorithms, systems thinking, architectural reasoning) is not what the performance review credits. The imposter feeling is the accurate perception of being measured against the wrong layer.

**Steel-manning challenge for Axis 4:** The steelman says medicine has rapid knowledge turnover too, and DORA shows that transferable practice exists in software. Is software uniquely unstable? Response: the *narrowed* claim survives this. The distinction is not "software has no stable knowledge" — it does. The distinction is that software's *evaluation and promotion machinery credits the volatile surface*. Medicine's evaluation systems credit the stable foundation (anatomy, physiology, the evidence base). Software's promotion systems credit framework fluency, tool mastery, and methodology alignment — the fastest-moving layer. A developer who mastered the stable foundation but not the current framework is less promotable than one who knows the framework but not the foundation. That inversion has no medicine equivalent.

---

### Axis 5: Licensed Identity ↔ Unlicensed Identity
**Source:** `../Software Industry/04_MMM_unstable_craft.md`

**What the dev-ladder research found without this axis:**
- The IC→EM reversion is driven by identity investment in technical craft (`03_RESEARCH`)
- The identity reframe is necessary but not sufficient for the transition (`07_RESEARCH`)
- "Reverting to IC under pressure" is the most common failure mode (`03_RESEARCH`)

**What Axis 5 adds:**
The ~50% reversion is not just identity investment — it is the rational response to being asked to surrender an *unanchored* identity. The surgeon who becomes Chief of Surgery is still, legally and institutionally, a surgeon. The license persists through the organizational role change. The craft identity has an external anchor that the role change cannot remove. They can step back into clinical work; the identity is there waiting.

The software engineer who becomes Engineering Manager has no external anchor. The identity exists only in the doing. Management stops the doing. The identity has nothing to hold onto during the transition — no license, no institutional credential, no external definition of "software engineer" that persists through the role change. The reversion is not failure. It is the rational act of reaching for the only identity anchor that exists.

**The founding CTO version:**
The CTO has no license that says "I am a technical leader." The identity was constructed by the work of building the product. When the company grows past Builder stage and the building stops, the identity has no external anchor. This is why the evaluation-isolation finding (`../CTO/15_RESEARCH_evaluation_isolation.md`) is so acute for CTOs specifically: they cannot self-diagnose mode mismatch because the only thing that told them who they were was the work, and the work has changed in ways that make their prior self-knowledge unreliable.

**Dev-ladder mapping:**
- The ~50% reversion rate (`03_RESEARCH`) is reframed by Axis 5: the reversion is the rate at which engineers decline to surrender an unanchored identity. The ~50% who do not revert are either those for whom the org conditions provided an alternative anchor (the imprinting mechanism, `AX-MW2018`) or those who found a way to construct a management identity before the engineering identity fully eroded.
- The Senior→Staff plateau population (`04_RESEARCH`) is explained differently by Axis 5: the engineer who stays at Senior is not necessarily failing to make the Staff transition. They may be rationally declining to give up the only identity anchor they have for a role whose identity is even less defined and even more organizationally contingent.

**Steel-manning challenge for Axis 5:** The steelman says many unlicensed professions have stable professional identities — architects, designers, product managers, journalists. Lack of licensure alone doesn't explain identity instability. Response: Axis 5 interacts with Axis 4. An unlicensed identity built on a *stable craft* (architecture, design) can be maintained through practice and community even without formal licensure — the craft has enough consensus definition that the identity has something to anchor to. An unlicensed identity built on an *unstable craft* (software) has no external anchor AND no stable craft definition. The combination of Axes 4 and 5 is what produces the specific vulnerability. Neither alone is sufficient.

---

## The Root Cause: The Fungibility Assumption

The industry thread identifies the fungibility assumption as the root cause that generates all five axes. Applying it to the dev-ladder findings:

**The fungibility assumption states:** software developers are interchangeable, configurable units of cognitive output. Adding units increases output. Swapping units maintains output. Reconfiguring units produces new capabilities.

**The dev-ladder evidence against each claim:**

| Fungibility claim | Dev-ladder evidence against |
|---|---|
| Adding units increases output | ISBSG analysis (1,000+ projects): optimal team size 3–7; ≥9 degrades — and Brooks' communication overhead scales as n(n-1)/2 explains why. *(CHAOS Report figures are illustrative but methodologically contested per Jørgensen & Moløkken-Østvold 2006 — ISBSG is the load-bearing source here.)* |
| Swapping units maintains output | Project Aristotle: team performance is relational, not compositional; replacing a developer disrupts the relational context that produced performance |
| Reconfiguring units produces new capabilities | ~50% IC→EM reversion: units cannot be reconfigured for management on an employer's schedule; identity transformation is not a configuration operation |
| Units are interchangeable within type | Nichols/CMU (2019): 90% of developers fall within modest performance ranges; the 10x differential is within-individual across tasks, not between individuals — the differential is contextual, not intrinsic |

**Why the fungibility assumption generates the axes:**
- When developers are units, they have no identities to rotate (Axis 1 invisible)
- When developers are units, there is nothing to deceive them about (Axis 2 irrelevant)
- When developers are units, direct and multiplied output are equivalent (Axis 3 invisible)
- When developers are units, the stability of the craft doesn't matter (Axis 4 irrelevant)
- When developers are units, they have no identities to anchor (Axis 5 irrelevant)

The fungibility assumption is not just empirically wrong. It is the epistemic frame that makes all five axes invisible to management — which is exactly why the management infrastructure (performance reviews, headcount planning, career ladders, org design) was built without accounting for them. You cannot see a problem your model has defined out of existence.

---

## The Compound: Software Lives at the Intersection of All Five

Every other field with a rotation problem has at least one stabilizing factor:

| Field | Rotation | Honest labeling | Stable craft | Licensed identity | Stabilizing factor |
|---|---|---|---|---|---|
| Consulting | Yes | Partial | Yes | No | Honest enough labeling; stable craft |
| Law (partnership tier) | Partial† | Partial | Yes | Yes | Stable craft; licensed identity |
| Medicine (admin path) | Partial‡ | Partial | Yes | Yes | Stable craft; licensed identity |
| Academia | Yes | No | Yes | Yes | Stable craft; licensed identity |
| Military | Yes | Yes | Yes | Yes | All three stabilizers |
| **Historical software** | **Yes** | **No** | **No** | **No** | **None** |
| **Startup software (now)** | **Yes** | **No** | **No** | **No** | **None** |

*† Law partnership adds rainmaking rotation to craft deepening — more rotation than originally claimed (adversarial review, June 25 2026); labeling is more honest than software but the rotation is real. ‡ Medicine's clinician→administrator drift follows the Red Baron pattern with ~45–55% burnout in administrative roles; the craft-deepening categorization holds for the default advancement path, not for administrative tracks.*

Software is the only field in this comparison where all four risk factors apply to the **default** advancement path at **every** rung. The comparators have pathologies — medicine's administrative track, law's partnership tournament, academia's bait-and-switch — but in each case the pathology is confined to a subset of the advancement path, and the stable-craft, licensed-identity conditions provide at least partial protection. The argument is not "software has rotation and others don't." It is "software has rotation **without the fallbacks, the honest labels, and the stable-craft/licensed-identity conditions** that make rotation survivable elsewhere — and this applies to every rung, not just the top." The compound is not additive — each axis makes the others worse:

- Unstable craft (Axis 4) makes identity rotation (Axis 1) worse because there is no stable identity to rotate from
- Unlicensed identity (Axis 5) makes deceptive labeling (Axis 2) worse because the unanchored identity cannot survive the discovery of the deception
- The Red Baron effect ensures the most vulnerable to all five axes (deepest identity investment in an unstable, unlicensed craft) are the ones selected for the rotation
- The fungibility assumption prevents any of this from being visible to management until the failure is already occurring

**The "smart people should learn everything" assumption is not the problem. It is the symptom.** It is what the industry says when confronted with population-scale failure in a system that its own model predicts should work. The model predicts units can be reconfigured; the units fail to reconfigure; therefore the units were inadequate. The model is never examined because the model is invisible.

---

## What the Axes Add to the Dev-Ladder Draft (When We Get There)

The research files (`01_`–`07_`) documented the fracture points, the failure mechanisms, the reversion rate, the plateau population, the cross-industry contrast, and the success conditions. They answered *what* and *where*.

The axes answer *why specifically software*, which is what makes the argument publishable rather than just observational. Without the axes:

> "Software promotions require distinct skill sets with no runway and fail at high rates."

True, but not surprising. With the axes (stated at the strength that survives `R1`/`R2`):

> "Software built a career ladder whose one institutionally-real rotation — IC→management — is a default advancement step, surrounded by a recurring pattern of further rotations it labels as natural deepening, on top of a craft whose *credited* layer is unstable and whose identity has no institutional anchor — and then used the fungibility assumption to make all of this invisible to management. The ~50% IC→EM reversion rate is the behavioral measure of how hard that one boundary is (a cross-industry rate — boundary-difficulty, not software-distinctiveness; distinctiveness comes from the missing cushions). The population-scale imposter figures corroborate but do not carry. These are not failures of individual engineers; they are what the structure predicts."

That is a different argument. It is also the one Brooks' 1975 argument, ISBSG team-size data, Mathias & Williams (2018), Van Lancker (2023), Nichols/CMU (2019), and Project Aristotle all support. *(CHAOS Report figures have been demoted to illustrative throughout — see Jørgensen & Moløkken-Østvold 2006 critique; ISBSG is the load-bearing source for team-size claims.)* <!-- R1 Claims A & B propagated: "rotation at every rung" → one seam + recurring pattern; "no stable theoretical foundation" → credited layer unstable / durable compounds; reversion = boundary-difficulty not distinctiveness; imposter corroborating not load-bearing. -->

---

## Steel-Manning Summary: What Must Survive Review

The Opus steelmanning process should target:

1. **The rotation claim (Axis 1):** *Posed originally as:* are the skills genuinely incompatible, or just different in degree? Does "rotation" overstate the discontinuity? **→ Now answered:** *different, not incompatible* (`../CTO/18_RESEARCH_modes_not_incompatible.md`); and `R1` Claim A further narrows the discontinuity to **one corroborated seam (IC→management) plus a recurring pattern**, not a measured cliff at every rung. "Rotation" overstates *only if* read as per-rung incompatibility — which the corpus no longer claims.
2. **The deception claim (Axis 2):** Is the labeling actually deceptive, or is the magnitude of the transition just hard to communicate? Does the partial correction (Staff IC tracks) undermine the historical claim?
3. **The unstable craft claim (Axis 4):** Is software uniquely unstable, or is this a matter of degree shared with other fast-moving fields? Does the Agile empirical gap prove instability or just youth?
4. **The unlicensed identity claim (Axis 5):** Do other unlicensed professions show the same vulnerability? Is licensure the relevant variable or is it craft stability that matters?
5. **The fungibility assumption as root cause:** Is this causal or correlational? The assumption may be rationalization of economic incentives rather than a genuine epistemic frame driving decisions.
6. **The "no stabilizers" claim for software:** Does the partial large-company correction (Staff Engineer tracks, dual-track systems) undermine the claim? Answer: it corrects the deceptive labeling partially, at large companies, thirty years late — the other four axes remain.

---

## Adversarial Review: What the Steelmanning Changed (June 25 2026)

The Opus adversarial review (`../Software Industry/05_ADVERSARY_strongest_counterevidence.md`, `06_FALSIFICATION_and_bias_audit.md`) produced three changes to this file and one open flank that the dev-ladder corpus must address before drafting:

**Changes made:**
1. **Axis 4 narrowed** — "no stable craft" → "the credited layer is unstable; the durable layer is uncredited." More accurate, sharper, survives DORA. Updated above.
2. **CHAOS demoted** — ISBSG is now the load-bearing team-size source; CHAOS is illustrative with a footnote acknowledging the Jørgensen & Moløkken-Østvold 2006 methodological critique. Updated above.
3. **Comparator asymmetry corrected** — medicine and law's own rotation pathologies are now acknowledged in the compound table. The argument survives but is stated more precisely: the contribution is rotation *without the stabilizers*, not rotation *where others had none*.

**Open flank — the measurement-artifact null hypothesis:**
The steelmanning surfaces the deepest competing explanation for the entire evidence base: *software's dysfunction may not be categorically worse than other professions' — it is merely better documented.* Software is younger, more introspective, more online, and more surveyed than medicine or law. It is the profession that blogs about its feelings and publishes its imposter rates. The adversary reads software's visible pain as unique vocalness, not unique brokenness.

This flank is not closed by the axes. It is closed by the **behavioral/organizational data** — and the dev-ladder corpus has the right data to close it:
- The ~50% IC→EM reversion rate (AX-REVERSION: CEB/Gartner n≈30,000) is *not* self-report. It is organizational data on actual role reversions.
- ISBSG project outcomes are not surveys. They are delivery records.
- Larson's four Staff archetypes are derived from career-progression observation, not sentiment.

The draft must foreground this behavioral data and explicitly distinguish it from the sentiment/survey data (52.7% imposter, burnout rates), which are corroborating but not load-bearing. Until the draft makes that distinction clearly, the artifact null hypothesis has a clean walk-through. The sentiment data is consistent with the structural thesis; only the behavioral data *tests* it.

---

## Open Research Questions This Integration Surfaces

1. **The Axis 4 verification gap:** The claims about software's methodological instability and lack of theoretical foundation are cited from the empirical software engineering literature (Wohlin et al., Jacobson, SEMAT). These need the same verification pass as the half-life figures in `06_RESEARCH`. They are more defensible than the half-life numbers (they come from the research community's own self-assessment) but should be traced to primaries before the draft.

2. **The interaction effects:** The five axes interact. A research question that has not been addressed: is there a "minimum viable stabilizer" — a single axis condition that, if present, would significantly reduce the compound harm? The military comparison suggests honest labeling alone may be sufficient to make rotation survivable. If so, the policy implication changes.

3. **The partial correction question:** Large-company Staff Engineer tracks and dual-track systems address Axis 2 (honest labeling) and partially address Axis 1 (creating a craft-deepening path alongside the rotation path). They do not address Axes 4 or 5. Do the two addressed axes reduce harm significantly, or do the unaddressed axes dominate?

4. **Falsification clause (required before publication):** The corpus must state what would disconfirm the thesis. Candidates from the adversarial review: (a) orgs that split CTO/VP-Eng from seed with funding held constant and showed no better technical-leadership survival → structural account weakens; (b) a well-supported IC track at startup scale that still produced ~50% reversion → identity-anchoring is not the mechanism; (c) matched high-achievement non-rotation professions showing the same imposter/burnout rates on *behavioral* measures → it's achievement-pressure, not structure. Naming these is not a concession. It is the difference between a thesis and a worldview.

---

*Companion documents: `../Software Industry/00_AXES_SUMMARY.md` (axes reference); `03_RESEARCH_ic_em_transition.md`, `04_RESEARCH_senior_to_staff.md`, `05_RESEARCH_cross_industry.md`, `06_RESEARCH_knowledge_obsolescence.md`, `07_RESEARCH_success_exceptions.md` (the dev-ladder findings this integration grounds); `../CTO/08_DRAFT_skills_divergence_thesis.md` (the CTO-tier draft the axes must also inform); `../CTO/07_APPENDIX_citation_review.md` (verification log — the Axis 4 sources need a dedicated pass).*
*Framework developed in collaboration with Claude Sonnet 4.6 (Anthropic). Research conducted June 25, 2026.*
