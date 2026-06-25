# Draft Gap Map — what's in `08_DRAFT` vs staged in research

> **✅ LARGELY FULFILLED (2026-06-25).** This was the planning bridge from `08_DRAFT` (the incremental-phase draft) to "the eventual clean/publishable version." **That clean version now exists: [`DRAFT_SYNTHESIS.md`](DRAFT_SYNTHESIS.md)**, built not from this gap-map's `08_DRAFT`-integration plan but from the independent adversarial review (`R3_STEELMAN`). So this file is **historical**: it records what the incremental phase had integrated vs. staged, and its proposed section order is **superseded** by `DRAFT_SYNTHESIS`'s §0–§5 spine. The "staged findings" rows below remain a useful inventory of which research fed which synthesis section. Read as provenance, not as a live plan.

**Original purpose (historical):** Track which findings are integrated into the lead draft (`08_DRAFT_skills_divergence_thesis.md` — now superseded) and which are still staged in research files, and propose the section order for the eventual clean/publishable version. **Planning only — no prose here.**

**Created:** 2026-06-24

---

## Current state of `08_DRAFT` (skills-first thesis)

| Section | Content | Source finding | Status |
|---|---|---|---|
| §1 | Observation: product→people→market; transformation model; 3 failure modes | `08_DRAFT` original + `AX-MW2018` | ✅ In draft |
| §2 | Divergence is real: 2 tracks + role distribution + compendium offload | `08_DRAFT` + `02/06` compendium | ✅ In draft |
| §3 | The irrational condition (3-point contradiction argument) | `08_DRAFT` original | ✅ In draft |
| §3.1 | Etymology — why it went unnamed | `05_FULLTEXT` §2 | ✅ In draft |
| §3.2 | **Scope-vs-kind keystone** | `09_RESEARCH` | ✅ In draft |
| §3.3 | **Investor signaling — installed, not inherited** | `09_RESEARCH` (investor file) | ✅ In draft |
| §4 | Prediction: failure clusters at transformations | `08_DRAFT` + Greiner/Carta/Kruze | ✅ In draft |
| §5 | Downstream implications (hiring/eval/support/self-knowledge) | `08_DRAFT` | ✅ In draft |

---

## Staged in research — NOT yet in draft

| Finding | File | Anchors | Why it belongs in the draft | Proposed home |
|---|---|---|---|---|
| **Economic engine** — ~$1.1M distributed cost, 4–6:1 cash compression, revealed-preference chain | `10_RESEARCH` | `AX-COMPRESSION`, `AX-EQUITY-PREMIUM`, `RISK-COMPRESSION-RATIO` | Answers "why does it persist?" — the stability mechanism. Currently §3 says it's irrational but not why nobody fixes it. | **New §6 — Why it persists (the economics)** |
| **Solution taxonomy** — 6 attempts, only 3 root-cause, all need the framework | `12_RESEARCH` | `AX-CTO-TENURE`, `AX-BIFURCATION-COST` | The "so what / what now" — and the strategic close (framework is a prerequisite for the missing solution category). | **New §7 — What's been tried (and why it falls short)** |
| **Training stress-test** — ~50% IC→EM reversion, 8–15yr vs 18–24mo | `11_RESEARCH` | `AX-REVERSION`, `AX-VPENG-TIMELINE`, `GAP-CTO-TRANSITION` | Empirically tests the largest solution (training). The 50% number is the corpus's hardest falsification attempt. | **Subsection of §7** (training is Solution 1) OR its own **§7.1** |
| **Central empirical gap** — founding-CTO transition success rate unstudied | `11_RESEARCH` | `GAP-CTO-TRANSITION` | The honest limitations + research agenda. The falsifiable test. | **§8 — Limitations & research agenda** |
| **Evaluation isolation** — CTO can't be measured (no anchor above/below); HiPPO feedback decay | `15_RESEARCH` | `AX-CTO-ISOLATION`, `AX-HIPPO-DECAY`, `AX-OXYGEN-EVAL` | New axis: *why the CTO can't self-diagnose their mode.* The prior question the taxonomy assumes away; motivates the `EVALUATIONS/` tool. | **New §3.4 or its own short section** (sits under "the irrational condition") |
| **Legibility, not a cure** (the honest close) | `15_RESEARCH` | `AX-NOVELTY-BASELINE` | The framework's bounded contribution: makes mismatch *sayable* ("Multiplier stage, Builder CTO"), doesn't claim to solve it. The antidote to the "it's hopeless" read. | **★ INTENDED DRAFT CLOSER — final section of `08_DRAFT`.** Verify Berray 2002 + McKinsey baseline first. |
| **No triple-mode success case** | `16_RESEARCH` | `AX-NO-TRIPLE-MODE`, `RISK-SURVIVORSHIP` | Success-case search found *no* CTO who navigated all 3 modes as continuous tenure — success = graceful exit. Survivor-proof result; pre-empts the "but some CTOs make it" objection and confirms evaluation-isolation. | **§4 (prediction — even survivors don't beat it) + §8 (limitations).** Verify the 5 anecdotal cases before load-bearing. |

---

## Proposed section order for the clean version

A natural arc: *observe → establish → name → explain cause → predict → explain persistence → assess fixes → bound the claim.*

1. **§1 Observation** — the skill transformation (✅ exists)
2. **§2 Divergence is real** (✅ exists)
3. **§3 The irrational condition** + §3.1 etymology / §3.2 scope-vs-kind / §3.3 investor cause (✅ exists)
4. **§4 The prediction — failure clusters at transformations** (✅ exists)
5. **§5 Why it persists — the economics** ← **integrate `10_RESEARCH`** (NEW)
6. **§6 What's been tried — solution taxonomy + training stress-test** ← **integrate `12` + `11`** (NEW)
7. **§7 Implications** (move current §5 here; it's downstream actions) (✅ exists, renumber)
8. **§8 Limitations & research agenda** ← **`GAP-CTO-TRANSITION` headline** (NEW)
9. **§9 Closer — legibility, not a cure** ← **integrate `15_RESEARCH`** (NEW, ★). The framework makes the mismatch sayable; it does not claim to solve the structural problem. Honest, humble, and the right note to end on. Evaluation-isolation material (`15_`) can seed a §3.4 earlier in the arc.

*Note: current §5 (implications) should move to after the new economic/solutions sections — actions make more sense once persistence and failed fixes are established.*

---

## Pre-integration blockers

Per the convention, these resolve before the new sections enter a *publishable* draft (research staging is fine now):

- `RISK-COMPRESSION-RATIO` — ✅ framing fixed; ⬜ $1.1M numbers still unverified (`AX-COMPRESSION`).
- `AX-REVERSION` — ⬜ the 50% is a practitioner estimate; verify or reframe before it carries §6.
- `AX-CTO-TENURE` — ⬜ confirm Spencer Stuart 2.5yr figure (strong source, quick win).
- Content-site comp medians (`ctaio.dev` etc.) — ⬜ substitute a primary; they underpin both `AX-COMPRESSION` and `AX-BIFURCATION-COST`.
- `GAP-CTO-TRANSITION` — no citation needed; just state honestly.

**Gate command:** `grep -rnE "(APPENDIX-REF|RISK):" 10_RESEARCH* 11_RESEARCH* 12_RESEARCH*` lists every claim these new sections depend on.

---

*Companion to `README.md` (corpus index), `07_APPENDIX` (citation status), `CONVENTIONS.md` (anchors). Delete or fold into the draft once integration is complete.*
