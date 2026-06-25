# The Under-Resourced CTO
## A skill discontinuity the software industry made institutional — and asks one person to cross, alone, before the company has scaled

**Draft status:** Synthesis in progress, built in committed increments (this is the rigorous-spine version; audience-specific derivations follow from the appendix map). **Built on `R3_STEELMAN_strongest_form.md` and `17_PREMISES_load_bearing_assumptions.md` — not on the rhetorical high points of `08_DRAFT`.**

**Increment log:** see `git log` for `DRAFT_SYNTHESIS.md` — each section is a separate commit, so the progression is itself part of the record and open to critique.

> **What this draft is.** The *rigorous public* version — the one written to survive a hostile-but-fair reviewer. Every claim is stated at the strength it can defend; every concession is made before a skeptic raises it; every falsifier is named. Four other audience versions (CTOs/eng-leaders, founders/CEOs, investors/board, job-boards/recruiters) **derive from this one** — softening losslessly downward. The fan-out is specified in the [Audience Map](#audience-map-derivation-key) appendix; this spine is their common ancestor.

---

## §0 — The thesis, stated at defensible strength

> **The founding-CTO role asks one person, before the company has scaled and largely alone, to cross the one skill discontinuity the software industry itself made institutional — the individual-contributor-to-manager rotation it split into two separate, separately-evaluated career tracks — on a compressed timeline and without the fallbacks, honest labels, and scaffolded transitions that make the same rotation survivable in every other profession that rotates. The role is best described not as "irrational" but as *structurally under-resourced at the worst possible moment*; and because its failures are slow and hard to attribute, they are read as individual inadequacy rather than as what the structure would predict for almost anyone.**

That sentence is the whole paper. Everything below either supports one of its clauses or concedes one of its limits.

**What this thesis deliberately does *not* say** (and why the draft is stronger for it):

- Not "three modes that diverge in *kind*" → **one** institutionally-real discontinuity, plus a useful three-mode *lens* for the arc. Only the Builder→Multiplier (IC→management) seam is externally corroborated; the rest is descriptive framework.
- Not "uniquely the CTO, a different *kind* of role" → the **most severe case** of a craft→strategy rotation the whole C-suite shares.
- Not "an irrational / dominated demand" → **under-resourced**. The composite may be a *rational* bet for the company (most startups die before mode-3 matters); the harm to the *person* is real without the *system* being irrational.
- Not "survivor-proof," not a hard "~4–6:1 ratio," not "investors *caused* it" → these are the corpus's weakest quantitative/causal claims and the draft does not lean on them. (See the [Must-Not-Claim table](#the-must-not-claim-discipline).)

---

## §0.1 — The contribution, stated honestly (so the reader knows the size of the claim)

This draft does **not** argue "the CTO role is an irrational composite." Stripped to what survives adversarial review, the contribution is:

> **A precise, non-pejorative vocabulary for a real, institutionally-grounded skill discontinuity that the founding CTO is asked to cross under-resourced — so that a difficulty the field currently narrates as personal failure ("he's not scaling") can instead be named as structural ("we're at a Multiplier stage and resourced no transition for it"), which is the prerequisite to resourcing it.**

It rests on four things, and only four:
1. **One hard institutional fact** — the IC/management career-track split (verifiable without the framework). *(§1)*
2. **One large-sample behavioral number** — the ~50% IC→EM reversion rate, corroborated at n≈30,000. *(§2)*
3. **One peer-reviewed mechanism** — identity-gated role offload, established *in founders*; the CTO application is this corpus's stated extension. *(§2)*
4. **One honest reframe** — shifting attribution from person to structure. *(§3)*

A draft built on exactly those four, conceding everything in the must-not-claim table, is the version worth publishing.

---

## The Must-Not-Claim Discipline

*Carried directly from `R3`. Every section below obeys this. It is also the **conversion key** for the derived audience versions — the left column is what every derived version must also avoid; the right column is the sayable form.*

| Do not write | Write instead |
|---|---|
| "Three modes diverge in kind" | "One institutionally-real IC→mgmt discontinuity, plus a descriptive three-mode lens" |
| "A mismatch of *kind*, uniquely the CTO" | "The most severe case of a rotation the whole C-suite shares" |
| "Irrational / dominated demand" | "Structurally under-resourced at the worst moment" |
| "Survivor-proof" (no-triple-mode) | "Consistent with rarity; the systematic study is unrun" |
| "MW2018/VL2023 ground the CTO model" | "They ground the *mechanism* in founders; CTO severity is our extension" (Premise 1) |
| "~4–6:1 compression" (as a number) | "Splitting the composite is unaffordable pre-Series-A" (qualitative) |
| "Investors *caused* the failure" | "Consistent with the title functioning as an investor signal" |
| "Failure clusters at boundaries (a *prediction*)" | "Consistent with difficulty concentrating at company-stage transitions" |

---

## §1 — The one fact this rests on: software split the career into two tracks

Everything in this paper that an outside reviewer can check, without first accepting our framework, reduces to a single institutional fact:

> **The software industry built two formal, separately-laddered, separately-evaluated career tracks — individual contributor and management — and told engineers to choose between them. No other major profession formalized that split the way software did.**

This is not a finding we produced. It predates this research, it is visible in the published career ladder of essentially every technology company, and it was not surfaced by a search that went looking to confirm a thesis. A skeptic who rejects everything else in this paper still has to account for it. It is the floor.

Two things follow from it, and only these two are load-bearing.

**First: the split is the industry's own admission that the two are different work.** You do not build separate ladders, separate titles, separate promotion rubrics, and separate performance criteria for *the same job done at different levels*. You build them when the work itself diverges — when being excellent at the first thing stops predicting excellence at the second. Medicine did not split "senior doctor who treats patients" from "senior doctor who manages doctors" into two formal tracks, because in medicine the senior version is *more of the same craft*. Software did split it, which is the industry telling us, in the structure of its own org charts, that individual technical excellence and the management of technical people are different enough to require choosing.

**Second: the founding CTO is asked to span exactly that boundary — and to span it pre-scale and alone.** The split exists so that most engineers never have to be both at once: you pick the IC ladder or the management ladder, and the organization staffs the other side. The founding CTO is the one role positioned where the organization has not yet staffed either side. They are the IC *and* the manager *and* (the title implies) the executive, before the company is large enough to have separated any of them. The institutional split that protects everyone else from holding both at once is precisely the protection the founding CTO does not have.

### The cleanest external exhibit: the CRO, the CTO's closest C-suite equivalent

If the claim is "the industry recognizes this rotation and acts on it everywhere except engineering's founding seat," the single clearest piece of evidence is the **closest C-suite equivalent to the CTO** — a peer executive role facing the same craft→strategy rotation, in the same founding-company, investor-facing context — and asking whether *it* got a cushion the CTO did not.

That role is the revenue leader, and it is the closest equivalent for reasons that matter: like engineering, sales has a hands-on craft (closing) that is genuinely different work from running the organization that does the craft; like the CTO, the senior sales leader is a founding-stage, board-visible, revenue-critical executive. The same craft→organization→strategy rotation appears — the person who personally closes deals is not doing the same job as the person who builds and runs a revenue organization. And the industry resolved it by **splitting the title**: the VP of Sales carries the building/operating load, and the **Chief Revenue Officer** is the strategic, market-and-board-facing role. The split happened because the composite was visibly too much for one person to hold well, and naming it as two roles was the fix.

This is what makes the comparison damning rather than incidental: the CRO is not a distant analogy reached for to make a point — it is the *nearest structural peer the CTO has in the C-suite*, and even the nearest peer got a cushion engineering's founding seat never did. A skeptic cannot dismiss it as "sales is just different," because sales is precisely the *least* different case.

Engineering's equivalent split — a clean, industry-standard separation of the hands-on technical leader from the strategic technical executive, available *from the founding stage* — never happened. The CTO title is asked to be both, and the VP-Eng split, where it exists at all, typically arrives only once the company can afford it (post-Series A), by which point the founding-stage span has already been demanded and, often, already failed.

This is one comparator role and one uncontested structural fact. It needs no anecdote, no survey, and no proprietary data. It is the strongest single exhibit in the paper precisely because a skeptic can verify it in an afternoon: *the industry split the CRO from the VP of Sales, and never gave engineering the same founding-stage split.* <!-- APPENDIX-REF: AX-CRO-SPLIT — CRO (strategic/board-facing) vs VP Sales (operational) distinction; the split arrives at org-maturity, not founding stage. Verified 2026-06-25 across multiple recruiting/sales sources (convergent, content-class but consistent). The structural fact (the split exists; eng never got the founding-stage version) is what's load-bearing, not any single source. See 07_APPENDIX. -->

*(Source note: the CRO/VP-Sales distinction is corroborated across multiple independent industry sources — strategic/multi-quarter vs. operational/short-horizon, the split appearing at org-maturity rather than founding. Verified 2026-06-25 that this is a genuine **rotation**, not mere scaling: industry sources describe VP-Sales→CRO as "fundamentally different from a typical promotion" (execution → revenue-system), and document sales leaders **failing** the transition for lack of the new skill set — the same failure pattern the CTO thesis describes, in the nearest peer role. This verification also retired the corpus's earlier overclaim that "only the CTO's focus rotates" — see `09_RESEARCH` superseded note. The load-bearing element remains the bare structural fact: sales got a founding-vs-strategic split that engineering never did.)*

### The discipline this section holds to

Two narrowings, stated so they cannot be quietly widened later:

1. **One discontinuity, not three.** This section establishes that *one* skill boundary — individual-contributor-to-manager — is institutionally real and externally verifiable. It does **not** establish "three modes that diverge in kind." The three-mode lens (Builder → Multiplier → Strategist) is a useful description of the arc, but only this first seam is corroborated by a fact outside the framework. The Multiplier→Strategist seam is carried as plausible framework, not as a second proven discontinuity.

2. **Most severe, not different in kind.** The next section concedes that other C-suite roles rotate too. The CTO's distinction is not that it rotates while others don't — it is that it rotates across the *one boundary the industry formalized into separate tracks*, which sharpens the rotation in a way the CFO's and CMO's do not face. "Most severe case of a shared pattern," never "a different kind of thing." *(Premise 2 also applies: this structural fact holds regardless of the title's etymology — see `17_PREMISES`.)*

> **Plain form (for derivation):** *Software made engineers choose between "do the work" and "manage the people who do the work" — two separate career tracks. The founding CTO is the one job forced to be both at once, before the company is big enough to split them. We know the industry sees this rotation because it split the CRO off from the VP of Sales — and never gave engineering the same split at the founding stage.*

---

## §2 — Crossing that boundary is an identity transition, and the CTO crosses it without cushions

§1 established that one skill boundary is institutionally real. §2 establishes three things about *crossing* it: it is hard in a measurable way, it is hard for a specific reason (identity, not skill), and the founding CTO crosses it stripped of the supports that make the same crossing survivable elsewhere.

**This is the section that leans hardest on evidence about populations other than CTOs.** That is deliberate and licensed — but the license has terms, stated here once and honored at every claim: the founding CTO is, by construction, *doing the IC engineer's work and making the IC-to-manager move* (Premise 1, component-equivalence). So evidence about that move is evidence about the component transition the CTO must make. What that evidence does **not** do is measure the CTO-specific *compression* (all of it at once, pre-scale, alone) — that severity is this corpus's extension, argued, not the source papers' finding. Every claim below is tagged accordingly.

### 2a. The boundary is measurably hard — the behavioral anchor

The load-bearing number is the **IC-to-engineering-manager reversion rate: roughly half of newly promoted engineering managers return to individual-contributor work.** It is the paper's strongest empirical fact for one reason — it is *behavioral*, not sentiment: it measures what people *did* (returned to IC), across a population that includes both those who succeeded and those who didn't, in a large sample.

- The vivid practitioner statement of it (a Figma engineering leader's "at least half the time") is **corroborated by large-sample management research**: CEB/Gartner finds ~50% of new managers/executives fail within 18 months (n≈30,000), and McKinsey reports a ~40% failure rate for newly promoted executives. *(`AX-REVERSION`, verified.)*

> **The boundary in this stat is the *exact* boundary §1 identified as institutionally real** — IC→management. The number is *not* about CTOs specifically; it is about the transition the CTO-Builder must make. We use it as **the measured difficulty of the boundary**, not as proof of a CTO-specific failure rate. *(Discipline per `R3` Pillar 2; the CTO-specific rate is unmeasured — see §5 / `GAP-CTO-TRANSITION`.)*

A competing explanation — "engineers just need better management training" — predicts the reversion rate should fall sharply with support. It does not: the ~50% holds *at companies with dedicated management-development programs*. That is what makes it look structural rather than a training deficit. (Stated as what the number is *consistent with*, not as proof; the controlled study isn't ours.)

### 2b. Why it's hard: identity, not skill (the peer-reviewed mechanism)

The reason the boundary resists training is that crossing it is an **identity transition, not a skill upgrade.** This is the one place the paper has *peer-reviewed* grounding — and the one place the boundary on that grounding must be stated most carefully.

Mathias and Williams (2018, *Journal of Business Venturing*) and Van Lancker et al. (2023, same journal) — the corpus's two full-text-verified anchors — establish, **in founders**, that:
- Role transitions are a matter of which roles one will *give up, retain, and adopt* — and the hard part is **giving up a self-defining role**, because it is an identity loss, not a task hand-off (Mathias & Williams).
- Successful offload runs through *physical* disengagement without *psychological* disengagement (you stop doing the work without ceasing to value it), and through **role-identity imprinting** — seeing your stamp on the person you handed the work to (Mathias & Williams).
- The offload *sticks* only under specific conditions: **psychological safety and value-fit** in the receiving team (Van Lancker et al.).

> **The boundary on this evidence (stated, per Premise 1 + `R3`):** these papers study **founders/entrepreneurs in general — the *buffered*, CEO-analog case** with support infrastructure the CTO lacks. They establish the *mechanism* — that role transition is identity-gated and offload-conditional. They do **not** study CTOs, and they do **not** establish the CTO-specific severity. The claim this paper makes is: *the mechanism is peer-reviewed in founders; the founding CTO faces the same mechanism with fewer of the conditions that let it succeed.* That last clause is our extension, and it is argued in 2c — not borrowed from the papers.

### 2c. The CTO crosses it uncushioned — the comparative move

Every other profession that rotates provides at least one cushion that makes the rotation survivable. The founding CTO, pre-scale, gets none:

- **Honest labeling:** the military names the Warrant Officer track; consulting's up-or-out is explicit. The CTO title signals *continuity* ("still the technical person") while the role demands a career change — the rotation is unlabeled. *(Borrowed, correctly, from the sibling Industry thread — `CROSS_REFERENCES` link; the labeling axis is theirs.)*
- **A respected fallback:** the surgeon stays licensed and operating; the professor keeps researching. The founding CTO has **no external license** to fall back on — the "technical leader" identity was constructed entirely by doing the work, so when the work stops, the identity has nothing to hold (the Industry thread's *unlicensed-identity* axis). This is *also* the mechanism behind 2a's reversion: reverting to IC is reaching for the only identity anchor that exists.
- **A scaffolded timeline:** residencies, pupillage, officer academies are multi-year supported transitions. The founding CTO gets "new title, new expectations" on the company's funding clock — and the offload conditions Van Lancker identifies (psychological safety, value-fit, a capable receiving team) are exactly what a pre-scale startup has *least* of.

The synthesis: the boundary is real (§1), measurably hard (2a), hard because it is identity-gated (2b), and the founding CTO crosses it stripped of every condition that makes it survivable elsewhere (2c). That is the defensible meaning of "under-resourced at the worst possible moment" — not a metaphor, a list of specific missing supports.

> **Plain form (for derivation):** *About half of new engineering managers go back to being engineers — even at companies that train them well. It's not a skills gap; it's that becoming a manager means giving up being the person who does the work, and that's an identity loss, not a promotion (this is peer-reviewed — in founders; the CTO is our extension of it). Every other field that asks people to make this kind of switch gives them a cushion — an honest name for it, a way back, a real timeline. The founding CTO, alone and pre-scale, gets none of them.*

---

## §3 — The harm is not the difficulty; it is who gets blamed for it

The previous two sections describe a hard, under-resourced transition. By itself, that is not yet a problem worth a paper — *many* roles are hard. The contribution is what happens **after** the predictable difficulty arrives: it is read as the individual's failure, the structure is never examined, and so the structure is never resourced — which guarantees the next person in the seat hits the same wall. This section is the load-bearing one, and notably it is the one that needs the *least* evidence: it does not require the CTO to be uniquely broken, or the reversion rate to be CTO-specific, or any contested number. It requires only that **the attribution is misdirected** — and that is observable directly.

### 3a. The misattribution pattern

When a founding CTO hits the boundary, the language that follows is remarkably consistent, and remarkably personal:

- *"He's not scaling."*
- *"She's not strategic enough."*
- *"The company outgrew him."*
- *"Management just wasn't for them."*

Each of these is individually plausible — which is exactly why the pattern is hard to see. Any one case can be a genuine individual shortfall. But the *consistency* of the framing across cases, companies, and decades is the tell: a difficulty that the structure would produce **for almost anyone placed in it** is being recorded, every time, as a fact about the person. The structure is never in the sentence. *(This is the corpus's M5 axis — the failure is slow, internal, and hard to attribute, which is precisely what lets the personal reading go unchallenged; `15_RESEARCH`.)*

This is not a claim that the CTO never under-performs. It is a claim about **default attribution**: when the structural and the individual explanation are both available, the field reaches reflexively for the individual one — and because it does, it never asks the structural question, and never builds the structural fix.

### 3b. Why the misattribution is self-perpetuating

The misattribution is not merely a description error; it is **load-bearing for the structure's persistence.** The causal loop is short:

1. The structure produces predictable difficulty at the boundary (§1–§2).
2. The difficulty is attributed to the individual ("not scaling").
3. The remedy applied is therefore individual — replace the person, coach the person, hire "a stronger CTO."
4. The replacement enters the *same* unstructured boundary, with the *same* missing cushions.
5. Return to step 1.

The de-facto industry solution — cycle CTOs at the boundary until one happens to fit, then cycle again — *is* this loop. It is expensive (lost institutional knowledge, and the practitioner literature's estimate of a 12–24 month strategic gap per displacement — practitioner-sourced, not primary-verified) and it never converges, because each iteration treats the recurring structural failure as a fresh individual one. The replacement pattern is not evidence the structure works; it is evidence the misattribution is preventing the structure from ever being seen.

### 3c. The contribution: legibility as the prerequisite to resourcing

This is where the paper's actual deliverable sits, and it must be stated as a *forward* claim, not a retreat. The contribution is **not** "the CTO role is irrational" (the de-escalated claims live in §5). The contribution is:

> **A precise, non-pejorative vocabulary that re-attributes the difficulty from the person to the structure — so that a difficulty currently narrated as personal failure ("he's not scaling") can instead be named structurally ("we are at a stage that requires a different mode, and we resourced no transition for it"), which is the prerequisite to resourcing it.**

The load-bearing sentence, stated plainly and defended rather than hedged: **you cannot resource a transition you cannot name.** As long as the difficulty is "he's not scaling," the only available move is to replace him. The moment it is "we're at a Multiplier stage and provided no transition support," a *different* set of moves becomes available — a VP-Eng hire timed to the boundary, an explicit mode hand-off, a named fallback — none of which are reachable while the problem is described as a person.

This is a deliberately bounded claim, and the boundary is the source of its strength:

- It does **not** claim the vocabulary *solves* the structural problem. The under-resourcing, the funding constraints, the unstaffed founding seat — naming them does not dissolve them. (§4 addresses why the structure persists even when understood.)
- It does **not** retreat to "we only offer words" when pressed. Naming is claimed as *necessary-but-not-sufficient* — a falsifiable position: if mode-aware organizations intervened no more effectively than mode-blind ones, the legibility claim would fail. *(This is the discipline `R2` Bias 7 demands: legibility stated as a forward prerequisite, not a motte retreated to after stronger claims are challenged.)*

The honest size of the contribution: it converts a difficulty the field currently spends on *serial replacement* into one the field could spend on *transition design* — by changing the sentence said about it. That is smaller than "we diagnosed an irrational composite," and more durable, because it survives every open question in §5.

> **Plain form (for derivation):** *When a founding CTO hits the wall, everyone says some version of "he couldn't scale." Said once, that's a person. Said every single time, across every company, for decades — that's a structure nobody is looking at, because the words keep pointing at the person. The fix isn't a better CTO; it's a better sentence: "we hit a stage that needed a different kind of leadership and we set up no way to get there." You can't resource a transition you won't name. Naming it doesn't fix the structure — but it's the only thing that makes fixing it possible.*

---

## Planned structure (increment roadmap)

| § | Section | Source | Status |
|---|---|---|---|
| §0–0.1 | Thesis + contribution + discipline | R3 thesis / contribution | ✅ done |
| §1 | The institutional fact: the IC/management split | R3 Pillar 1 + CRO exhibit (`09_`) | ✅ done |
| §2 | The rotation is identity-gated & uncushioned | R3 Pillar 2 + `AX-REVERSION` + Premise 1 | ✅ this increment |
| §3 | The misattribution is the harm (the legibility contribution) | R3 Pillar 3 + `15_` | ✅ this increment |
| §4 | The accidental concession (objection → support) | R3 §strongest-objection | ⬜ |
| §5 | Concessions & falsifiers, in the draft's own voice | R3 concessions + falsifiers + `R4` | ⬜ |
| App. | Audience-map derivation key | this file | ⬜ skeleton below |

---

## Audience Map (derivation key)

*The rigorous spine is the common ancestor; each audience version is a projection of it. This table will be filled per-section as the spine is built — each cell says what that audience needs from that section, and what it must drop. Fan-out happens here, once, rather than by rewriting five drafts.*

| Section → / Audience ↓ | §1 Institutional fact | §2 Rotation/reversion | §3 Misattribution | §4 Accidental concession | §5 Falsifiers |
|---|---|---|---|---|---|
| **CTOs / eng leaders** | "you were told to pick a track; the founding seat made you skip the choice" | "half of new EMs revert *even when trained* — it's not your skills, it's an identity switch you got no cushion for" | "'he couldn't scale' is the structure talking, not a verdict on you" | _(tbd)_ | _(usually dropped)_ |
| **Founders / CEOs** | the split exists for a reason; your CTO is spanning it unsupported | provide the cushions (honest label, fallback, timeline, a capable receiving team) *before* the boundary | replace the sentence before you replace the person; serial replacement never converges | _(tbd)_ | _(light)_ |
| **Investors / board** | the VP-Eng split you defer is the cushion you removed | ~50% reversion at the boundary you fund across; mode-aware diligence | stop penalizing the failure you select for; the replacement loop is a cost you're paying | the signal you require installs the gap | _(tbd)_ |
| **Academic / researcher** | the verifiable seam (the one claim needing no framework) | the behavioral anchor (n≈30k) + the unrun *CTO-specific* cohort study (`GAP-CTO-TRANSITION`) | the falsifiable form: do mode-aware orgs intervene better than mode-blind? | — | **the payload** (F1–F4) |
| **Job boards / recruiters** | the JD writes the composite; the CRO/VP-Sales split is the template you don't apply to eng | "hands-on AND strategic" demands both sides of a boundary half the field can't cross once | the JD that demands the composite is the first link in the misattribution loop | — | — |

---

*Spine source: `R3_STEELMAN_strongest_form.md` (defensible form), `17_PREMISES` (P1 component-equivalence, P2 etymology-contingent). Adversarial basis: `R1`/`R2`. Open agenda: `R4`. This file is the rigorous ancestor; derived audience drafts are downstream.*
