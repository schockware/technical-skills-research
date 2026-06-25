# CTO Research Map — Briefing for the Software Developer Research Thread

**Purpose:** Hand the Software Developer research a running start. The CTO area is the flagship case study; the dev-ladder area is the *generalization* (the same structural mismatch one level down, where the CTO problem actually originates). This document says **what each CTO file found** and — more importantly — **what patterns and guardrails to carry into the dev research from day one**, so you approach it knowing what to look for instead of rediscovering it.

**Read order:** skim §1 (the through-line) → §2 (per-file map) → §3 (what to look for in dev-land) → §4 (methodology guardrails — these are non-negotiable).

**Numbering note:** the CTO area went through two numbering schemes; trust *this* map, not cross-references inside older files. Current map: `12_`=solutions, `15_`=evaluation, `16_`=success-cases, `EVALUATIONS/16_`=why-we-didn't-build-the-quiz.

---

## §1 — The through-line (the one-paragraph thesis)

The CTO role is an **irrational composite**: it demands one person be excellent at three sequentially-incompatible skill sets — **Builder** (product/craft) → **Multiplier** (people/team) → **Strategist** (market/board) — that diverge in *kind*, not degree. Each transition is a **transformation** (offload the old role + acquire a new one, in tension), not a promotion. Failure clusters *at the boundaries between modes*, not within them. The dev-ladder research matters because **this is not unique to the CTO** — it's the terminal, concentrated expression of a mismatch that begins at the *first* promotion (Junior→Mid) and runs the whole ladder. The CTO just gets it worst: all three modes, pre-scale, alone, in 18–24 months instead of 15+ years.

---

## §2 — What each CTO file researched

### Foundation / framing
| File | What it established |
|---|---|
| `00_RESEARCH_CONTEXT.md` | Master handoff. The locked taxonomy (Builder/Multiplier/Strategist), the central claim, key sources, open questions. **Start here for the framework itself.** |
| `05_FULLTEXT_working_document.md` | The original 11-section paper (failure-first framing). The etymology (CTO title coined ~late-80s for the Strategist mode at enterprise scale, mis-applied to startup Builders), Greiner alignment, the irrational-composite + Larson convergence. |
| `08_DRAFT_skills_divergence_thesis.md` | **The current lead thesis** (skills-first reframe). §1 the transformation model; §2 divergence is real (IC/management split); §3 the irrational condition + etymology + scope-vs-kind keystone + investor signaling; §4 failure clusters at transformations. |
| `04_RESEARCH_classification_table.md` | ~35 research threads mapped to the taxonomy. Where the "0 Strategist findings" asymmetry lives (and the warning not to use absence as evidence). |
| `01/02/03/06_*` (artifacts) | Summaries + full text of the working doc, the skills compendium (skills × mode × transfer-type), and the practitioner transition brief. Reference, not narrative. |

### The core findings (the argument's load-bearing research)
| File | What it found — and the transferable mechanism |
|---|---|
| `09_RESEARCH_cross_role_pattern.md` | **CTO vs other C-roles.** Every C-suite title was coined at scale for its mature mode; migrating any to a startup is irrational — but only the CTO is *catastrophic*, because only the technical function's skill **rotates direction** (the IC/management bifurcation exists in no other discipline). **"Every other title imported a mismatch of *scope*; the CTO imported a mismatch of *kind*."** Also: the investor-signaling cause (the title was *installed*, not just inherited). |
| `10_RESEARCH_who_does_cto_work.md` | **The economics.** Distributing the CTO's work across market-rate hires ≈ **$1.1M**; the founding CTO is paid ~$177K cash → **~4–6:1 cash compression**. The composite persists because it's optimal for everyone *except* the CTO (revealed-preference chain). |
| `11_RESEARCH_IC_to_EM_transition.md` | **★ MOST RELEVANT TO DEV RESEARCH.** The IC→EM→VP path *is* the dev-ladder. **~50% IC→EM reversion even with org support** (CEB/Gartner-corroborated); full IC→VP path takes **8–15 years**; the CTO is asked to do it in 18–24 months. The reversion happens because the transition is **identity-level, not skill-level**. |
| `12_RESEARCH_rational_solutions.md` | **Solution taxonomy.** 6 industry attempts (train, switch CTOs, role-bifurcation, fractional CTO, founding-CTO role-transition, mode-aware diligence). Only 3 hit root cause, and all 3 *require the framework as a prerequisite to execute*. |
| `13_RESEARCH_domain_centric_CTO.md` | **The second axis.** Domain *identity investment* (not skill level) predicts *which* CTOs fail. 2×2: domain-depth-of-identity × market-domain-dependency. A domain-expert in a general-tech company is highest-risk. |
| `14_RESEARCH_domain_training_effectiveness.md` | **Can expertise be trained across domains? No.** The **curse of expertise** (Camerer 1989, Hinds 1999, Gupta 2017 — all peer-reviewed): prior expertise *actively interferes* with adjacent-domain learning, and awareness doesn't fix it (experts resist debiasing). |
| `15_RESEARCH_evaluation_isolation.md` | **Why the CTO can't self-diagnose.** Every valid measurement needs an anchor *above* or safely *below*; the CTO structurally has neither → **epistemological isolation**. The HiPPO effect makes the feedback signal *decay with tenure*. **The framework's contribution is legibility, not a cure.** |
| `16_RESEARCH_success_cases.md` | **★ The success search collapsed the category.** Looked for a founding CTO who navigated all 3 modes as a continuous tenure → **found none.** Every "success" = 1–2 modes + graceful exit. Survivor-proof result. Three patterns: external naming was always required; success = selective scope-narrowing not full replacement; terminal outcome is usually departure. |

### The integrity moves (read these — they model the rigor bar)
| File | What it decided |
|---|---|
| `EVALUATIONS/16_RESEARCH_why_we_didnt_build_it.md` | **We declined to ship a CTO self-diagnostic quiz** — the research showed it would harm (isolation + corrupted inputs + identity-crystallizing labels + weaponizable across a power gradient). The honest artifact is a *shared-vocabulary reference*, not a scoring tool. |
| `07_APPENDIX_citation_review.md` | The **citation verification log** + the publish-gate. Every stat rated for load-bearing weight and traced to a primary. Several were caught fabricated/misattributed/domain-mismatched and corrected. |
| `CONVENTIONS.md` | The greppable-anchor scheme (`AX-`/`RISK-`/`GAP-`/`XREF-`). Use it. |

---

## §3 — What to look for in the dev-ladder research (apply the CTO findings)

The dev research already knows the answers' *shape*. Look for these specific things — each is a CTO finding to confirm/refine one level down:

1. **The rotation at every rung.** Junior→Mid→Senior→Staff→EM→VP. For each, name *what got you here vs. what the next level needs* — and whether they're adjacent (a deepening) or divergent (a rotation). Expect: first rung modest, **Senior→Staff and IC→EM are the fracture points** (the CTO's Builder→Multiplier, one level down).

2. **The ~50% IC→EM reversion is your anchor stat** (`11_RESEARCH`). It's corroborated (CEB/Gartner). This is the dev-ladder's hardest number — build around it. The **missing failure cell is *large and documented* here**, unlike the CTO tier — which makes dev success-claims *more* checkable.

3. **Identity, not skill, is the barrier** (Mathias & Williams 2018, verified). The engineer's identity is "I am technically excellent"; management requires giving up *enacting* that. Look for: does the dev literature frame plateaus/reversion as skill gaps (wrong) or identity transitions (right)?

4. **Knowledge half-life / obsolescence** (already surfaced in the dev draft). Software uniquely works *against* skill accumulation — the engineer is perpetually a novice at the current stack while being asked for senior confidence. This is a dev-tier finding the CTO area *doesn't* have; it's yours to own.

5. **Imposter syndrome as accurate self-assessment, not distortion.** The 52.7% figure. The structural reframe: it's correct perception of a real mismatch. (CTO-tier parallel: the evaluation-isolation finding — neither can get a valid read on themselves.)

6. **The Peter Principle "high-mismatch regime."** Software is named worst-case; academia (craft deepens) is best-case. This is the dev-tier's version of the scope-vs-kind keystone — the *kind* of skill change is what makes software pathological.

7. **What actually works = received structural support, not individual heroics.** The success-case finding (`16_`) + Van Lancker (psych-safety + value-fit). Hypothesis to test in dev-land: durable transitions correlate with *what the org provided*, not *what the individual did*. If true, it's the anti-recipe — and it loops straight back to "stop blaming the individual."

---

## §4 — Methodology guardrails (carry these in; they're non-negotiable)

The CTO research earned its credibility by *not overclaiming*. The dev research must hold the same bar or it weakens the whole study:

- **Absence ≠ evidence** (`RISK-ASYMMETRY`). If a population isn't studied, that's a gap, not proof. Don't reframe "no research found" as confirmation.
- **Presence ≠ evidence** (`RISK-SURVIVORSHIP`). Success cases are survivors; the people who did the same thing and failed are invisible. Every success factor needs a *missing-cell note*. **Never produce a success checklist.**
- **"Consistent with," not "caused."** Where the data is correlational or narrative, say so. The CTO area got burned reaching past its evidence once and corrected it — don't repeat it.
- **Rate sources by class.** Peer-reviewed > named-firm data > practitioner/named > content-site/blog. Flag content-site stats as illustrative until traced to a primary. (The CTO appendix caught several fabricated/misattributed numbers this way — assume dev-land has them too.)
- **Verify before load-bearing.** A finding can be *collected* on weak sources but shouldn't enter the draft until its sources are verified. Tag, don't bury.
- **The contribution is legibility, not a cure.** The dev research isn't obligated to solve the ladder — naming the mismatch precisely is the win. (Don't drift into "and here's how to fix your career," which is the survivor-recipe trap.)

---

## §5 — The one-sentence handoff

> *The CTO is the worst case of a structural mismatch that starts at the first promotion; the dev-ladder research's job is to show the pattern runs all the way down — with the same rigor (absence isn't evidence, presence isn't evidence, legibility not cure) that made the CTO case credible.*

---

*Generated for the Software Developer research thread. Source of truth for the CTO area: the files above + `README.md`. Framework: human researcher + Claude, June 2026.*
