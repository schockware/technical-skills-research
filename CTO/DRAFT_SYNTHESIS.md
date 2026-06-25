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

## Planned structure (increment roadmap)

| § | Section | Source | Status |
|---|---|---|---|
| §0–0.1 | Thesis + contribution + discipline | R3 thesis / contribution | ✅ this increment |
| §1 | The institutional fact: the IC/management split | R3 Pillar 1 + CRO exhibit (`09_`) | ⬜ next |
| §2 | The rotation is identity-gated & uncushioned | R3 Pillar 2 + `AX-REVERSION` + Premise 1 | ⬜ |
| §3 | The misattribution is the harm (the legibility contribution) | R3 Pillar 3 + `15_` | ⬜ |
| §4 | The accidental concession (objection → support) | R3 §strongest-objection | ⬜ |
| §5 | Concessions & falsifiers, in the draft's own voice | R3 concessions + falsifiers + `R4` | ⬜ |
| App. | Audience-map derivation key | this file | ⬜ skeleton below |

---

## Audience Map (derivation key)

*The rigorous spine is the common ancestor; each audience version is a projection of it. This table will be filled per-section as the spine is built — each cell says what that audience needs from that section, and what it must drop. Fan-out happens here, once, rather than by rewriting five drafts.*

| Section → / Audience ↓ | §1 Institutional fact | §2 Rotation/reversion | §3 Misattribution | §4 Accidental concession | §5 Falsifiers |
|---|---|---|---|---|---|
| **CTOs / eng leaders** | _(tbd)_ | the reframe: "the ~50% isn't you" | "you're under-resourced, not inadequate" | _(tbd)_ | _(usually dropped)_ |
| **Founders / CEOs** | _(tbd)_ | resource the transition before the boundary | name the mode, don't blame the person | _(tbd)_ | _(light)_ |
| **Investors / board** | _(tbd)_ | mode-aware diligence | stop penalizing the failure you select for | the signal you require installs the gap | _(tbd)_ |
| **Academic / researcher** | the verifiable seam | the unrun cohort study | — | — | **the payload** (F1–F4, `GAP-CTO-TRANSITION`) |
| **Job boards / recruiters** | the JD writes the composite | "hands-on AND strategic" attracts mediocre-at-both | — | — | — |

---

*Spine source: `R3_STEELMAN_strongest_form.md` (defensible form), `17_PREMISES` (P1 component-equivalence, P2 etymology-contingent). Adversarial basis: `R1`/`R2`. Open agenda: `R4`. This file is the rigorous ancestor; derived audience drafts are downstream.*
