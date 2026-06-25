# The Axes: A Summary
## Structural Variables Discovered Across the Software Industry Research Thread

**Date:** June 25, 2026
**Purpose:** Quick reference for synthesis work. Each axis is named, defined, and connected to the file where it emerged.

---

## Axis 1: Craft-Deepening ↔ Identity Rotation
**Source:** `03_MMM_transformation_expectation.md`, `05_RESEARCH_cross_industry.md`

**Definition:**
- **Craft-deepening:** Seniority means becoming more excellent at the defining work of the role. The work at the top of the ladder is a deeper, more complex version of the work at the bottom. Identity is continuous and accumulates.
- **Identity rotation:** Seniority means becoming a fundamentally different kind of worker. The work at the top requires different cognitive modes, different feedback relationships, different sources of meaning. Identity must be abandoned and rebuilt.

**Why it matters:** Predicts whether a career ladder produces manageable transitions or population-scale failure.

**Cross-industry calibration:**
| Industry | Position |
|---|---|
| Medicine, Law | Craft-deepening |
| Military, HR | Rotation with honest labeling |
| Academia, Historical software | Rotation with deceptive labeling |
| Startup software (now) | Rotation with deceptive labeling, maximum compression |

---

## Axis 2: Honest Labeling ↔ Deceptive Labeling
**Source:** `03_MMM_transformation_expectation.md`, `05_RESEARCH_cross_industry.md`

**Definition:**
- **Honest labeling:** The transition is named as what it is — a career change, a different kind of work, a separate track. Consulting's up-or-out is brutal but explicit. The military's Warrant Officer track is a labeled choice.
- **Deceptive labeling:** The rotation is framed as natural deepening, promotion, or advancement. Nobody says "you are becoming a different kind of worker." The academic bait-and-switch. The software "promotion" to Engineering Manager.

**Why it matters:** The deception is the specific harm — not the rotation itself. People navigating a transformation they were never told they were making cannot prepare for it, cannot seek appropriate support, and attribute failure to themselves rather than to the structural mismatch.

**The key finding:** Craft-deepening professions have nothing to deceive about. Deceptive labeling only compounds harm when combined with rotation. Software combines both.

---

## Axis 3: Direct Output ↔ Multiplied Output
**Source:** `03_MMM_transformation_expectation.md`, CTO corpus `08_RESEARCH_rational_solutions.md`

**Definition:**
- **Direct output:** Performance is individual and attributable. You wrote the code. You found the bug. You closed the deal. Feedback is fast and concrete.
- **Multiplied output:** Performance is collective and diffuse. Your team shipped the feature. Your org built the capability. Attribution is ambiguous. Feedback is slow and indirect. Your excellence is expressed through others, not by you.

**Why it matters:** The IC→EM transition, Senior→Staff transition, and CTO Builder→Multiplier transition all require moving from direct to multiplied output. Nothing in the earlier career stages prepares for this. The feedback loop loss alone produces disorientation severe enough to drive ~50% reversion even with organizational support.

**The Red Baron connection:** The best direct-output practitioners are selected for multiplied-output roles (Red Baron effect). But excellence at direct output actively interferes with multiplied output — the instinct is always to do it yourself, which is exactly wrong for the new role.

---

## Axis 4: Stable Craft ↔ Unstable Craft
**Source:** `04_MMM_unstable_craft.md`

**Definition:**
- **Stable craft:** The domain has a durable theoretical foundation, accumulated evidence base, and broadly agreed standards of practice. What counts as excellent is defined and relatively stable across time. Mastery compounds.
- **Unstable craft:** The domain lacks a stable theoretical foundation, has no broadly accepted theory, and cycles through methodological fashions. What counts as excellent is contested and changes faster than expertise can accumulate. Mastery decays.

**The software evidence:**
- No generally accepted theory exists in software engineering (Wohlin et al., cited in peer-reviewed empirical SE literature)
- The field is "gravely hampered by the prevalence of fads more typical of the fashion industry than of an engineering discipline" (Jacobson, SEMAT)
- Only 4 of 10 major Agile methods have any empirical support for their claims
- Software knowledge half-life: 2.5–5 years

**Why it makes software uniquely worse:** Every other problem compounds from this. Identity rotation is harder when there is no stable craft identity to rotate from. The Red Baron effect is worse when the Baron's expertise is simultaneously decaying. The fungibility assumption is worse when there is no stable knowledge to diffuse. The deceptive labeling is worse when the craft being "deepened" has no stable foundation.

---

## Axis 5: Licensed Identity ↔ Unlicensed Identity
**Source:** `04_MMM_unstable_craft.md`

**Definition:**
- **Licensed identity:** The craft identity is externally anchored by an institutional credential. The surgeon is licensed regardless of organizational role. The license persists through role changes. The practitioner can return to the craft because the craft has an institutional home independent of employment.
- **Unlicensed identity:** The craft identity is organizationally constructed. It exists only as long as the organization validates it through the work it gives you. When the role changes, the identity has no external anchor.

**Why it matters for the ~50% reversion rate:** The engineer who "reverts to IC under pressure" is not failing — they are reaching for the only identity anchor they have. There is no license to hold onto. The identity can only be maintained by doing the work. Management stops them from doing the work. The reversion is rational.

**Why it matters for the CTO:** The founding CTO has no license that says "I am a technical leader." The identity was constructed by the work of building the product. When the company moves to Multiplier stage and the building stops, the identity has nothing to hold onto.

---

## The Compound Matrix

Two axes produce the cell that describes software's historical position and the startup context now:

| | **Honest Labeling** | **Deceptive Labeling** |
|---|---|---|
| **Craft-Deepening** | Medicine, Law | — (empty — nothing to deceive about) |
| **Identity Rotation** | Military, Consulting | **Academia, Historical Software, Startup Software (now)** |

Software lives in the bottom-right cell. The only cell where all five axis problems compound simultaneously.

---

## The Red Baron Effect (Named Mechanism, Not a Full Axis)
**Source:** Conversation, `03_MMM_transformation_expectation.md`

**Definition:** The organization's assumption that the best practitioner will make the best leader of practitioners. Excellence at the craft is used as the selection signal for leadership of the craft.

**Why it is a distinct problem from the rotation axis:** The rotation axis explains *what* the transition requires. The Red Baron effect explains *who gets selected for it* — and why that selection is systematically wrong.

**The compounding mechanism:**
1. Best practitioners have the deepest craft identity investment (hardest to give up)
2. Best practitioners have the least experience expressing excellence through others (always did it themselves)
3. Best practitioners' technical authority is most threatened by obsolescence (most to lose from the knowledge half-life)

The selection mechanism and the transition requirement work directly against each other. The person *most* promoted is the person *least* prepared for what promotion requires.

---

## The Fungibility Assumption (Root Cause, Not an Axis)
**Source:** `02_MMM_fungibility_assumption.md`, `02b_MMM_10x_myth_and_aristotle.md`

**Definition:** The belief that software developers are interchangeable, configurable units of cognitive output. Adding units increases output. Swapping units maintains output after ramp-up. Reconfiguring units produces new capabilities.

**Why it is the root, not an axis:** The fungibility assumption generates all the axes. Craft-deepening vs. rotation becomes invisible when people are units — units don't have identities to rotate. Honest vs. deceptive labeling becomes irrelevant when units don't have identities to deceive. The Red Baron effect feels reasonable when units are configurable. The unstable craft problem is masked when units are expected to continuously reconfigure anyway.

**The empirical refutation:**
- Sackman/Nichols: productivity differential is contextual, not intrinsic — a developer who is 10x on one task is not 10x on another
- Project Aristotle: who is on the team matters far less than how the team works together — performance is relational, not compositional
- ~50% IC→EM reversion: units cannot be reconfigured for management on an employer's schedule

---

## How the Axes Connect to the CTO Paper

| Axis | CTO Manifestation |
|---|---|
| Craft-Deepening ↔ Identity Rotation | Builder→Multiplier→Strategist are three identity rotations, not three levels of deepening |
| Honest ↔ Deceptive Labeling | The CTO title signals continuity; the role demands three career changes |
| Direct ↔ Multiplied Output | The Builder succeeds by direct output; Multiplier and Strategist require multiplied output — nothing in the Builder stage prepares for this |
| Stable ↔ Unstable Craft | The Builder's technical craft has a 2.5-5 year half-life; they are being asked to build an identity on an eroding foundation |
| Licensed ↔ Unlicensed Identity | The CTO has no license to hold onto when the organizational role demands they stop building |
| Red Baron Effect | The CTO was promoted because they were the best builder — precisely the profile least prepared for the Multiplier transition |
| Fungibility Assumption | Investors demand "a CTO" as if the role is a configurable slot; the entire market treats technical co-founders as fungible |

---

*Developed in collaboration with Claude Sonnet 4.6 (Anthropic). Research conducted June 2026.*
*For full context: software industry thread files `01`–`04`, CTO corpus files `00`–`17`.*
