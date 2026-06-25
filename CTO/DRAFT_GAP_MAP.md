# Draft Gap Map — what's in `08_DRAFT` vs staged in research

**Purpose:** Track which findings are integrated into the lead draft (`08_DRAFT_skills_divergence_thesis.md`) and which are still staged in research files, and propose the section order for the eventual clean/publishable version. **Planning only — no prose written here.**

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
