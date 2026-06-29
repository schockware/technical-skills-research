# Technical Skills Analysis

**A version-controlled research study on a structural problem in software careers: the industry systematically constructs roles that demand *distinct* skill sets on compressed timelines — with no on-the-job runway to learn the next one — then attributes the predictable failures to individuals.**

The flagship case is the startup **CTO**, where the pattern is most acute. But the same structure runs the entire software career ladder and reflects an industry-wide failure to specialize. This repo holds the research across all three scope levels.

**Status:** Active research, **published in the open while still under verification.** The seams between what is solid and what is provisional are *marked, not hidden* — see "How to read this study" below.

**Collaboration:** Human researcher + Claude (Sonnet 4.6 / Opus). Research conducted June 2026.

---

## The three scope levels

The same structural mismatch, viewed at three altitudes — widest to sharpest:

| Area | Folder | Scope | Core claim |
|---|---|---|---|
| **Software Industry** | [`Software Industry/`](Software%20Industry/) | Widest | The industry builds roles exceeding human cognitive capacity at every level; **specialization** is the solution every other mature profession applied and software hasn't. |
| **Software Developer** | [`Software Developer/`](Software%20Developer/) | Career ladder | Every promotion (Junior→Mid→Senior→Staff→EM→VP) is a skill *rotation*, not a deepening. The mismatch starts at the first promotion. |
| **CTO** ⭐ | [`CTO/`](CTO/) | Sharpest / flagship | The pattern concentrated into one role at the worst moment: a seed-stage CTO must cross the IC→EM→C transitions — each a clearly-defined, distinct skill set — pre-scale and unsupported. The skill sets aren't inherently incompatible; the industry just gives no chance to learn them naturally on the job. |

**The CTO area is the flagship use case** — the most developed, most evidenced, most publishable. It answers the natural objection "if it's so irrational, why only the CTO?" — and the Cultural Expectations comparator program (2026-06) **proved** the answer: it's *not* only the CTO. The composite is **C-suite-wide**, so the underlying findings (T2, T4) are general; the CTO is **unique, not isolated** — the clearest *use case* of a broader pattern, not a one-off. See [`Cultural Expectations/2.1d_COMPARATOR_ABSTRACT.md`](Cultural%20Expectations/2.1d_COMPARATOR_ABSTRACT.md).

Start with [`CTO/README.md`](CTO/README.md) for the developed argument; the other two areas are research notes that broaden it.

---

## CTO argument — by audience

The CTO argument has one rigorous spine, [`CTO/DRAFT_SYNTHESIS.md`](CTO/DRAFT_SYNTHESIS.md), and **five audience-specific versions derived from it** — each re-voiced and re-weighted for a different reader, never adding a claim the spine doesn't license. Pick the one that fits you:

| If you are… | Read | What it gives you |
|---|---|---|
| A **CTO / engineering leader** | [`DRAFT_SYNTHESIS_cto_eng_leaders.md`](CTO/derived/DRAFT_SYNTHESIS_cto_eng_leaders.md) | The non-pejorative reframe: the ~50% isn't you, it's an identity switch the structure gave you no cushion for. |
| A **founder / CEO** | [`DRAFT_SYNTHESIS_founders_ceos.md`](CTO/derived/DRAFT_SYNTHESIS_founders_ceos.md) | Name the mode, don't blame the person — resource the transition *before* the boundary, because serial replacement never converges. |
| An **investor / board member** | [`DRAFT_SYNTHESIS_investors_board.md`](CTO/derived/DRAFT_SYNTHESIS_investors_board.md) | The diligence question isn't "do they have a CTO" but "what mode does the company need, and is the CTO in it." |
| An **academic / researcher** | [`DRAFT_SYNTHESIS_academic.md`](CTO/derived/DRAFT_SYNTHESIS_academic.md) | The falsifiers as the deliverable: the unrun cohort study and the open research agenda, citation-precise. |
| A **recruiter / talent / job-board owner** | [`DRAFT_SYNTHESIS_recruiters.md`](CTO/derived/DRAFT_SYNTHESIS_recruiters.md) | The JD that demands the composite is the first link in the misattribution loop — what to put in the req at each stage. |

All five are projections of the same spine and were audited for consistency against it — see [`CTO/AUDIENCE_DERIVATION_AUDIT.md`](CTO/AUDIENCE_DERIVATION_AUDIT.md).

---

## Cultural Expectations — the synthesis and its fence

The **Cultural Expectations** area asks where the "irrationality" attributed to the CTO role actually lives, and why the culture grants "smart people can learn anything" to software but withholds it from licensed professions. After a clean-chat adversarial pass (R1→R2→R3), the synthesis was rebuilt into a deliberate A/B pair so the trade-off it surfaces is visible rather than buried:

| Read | What it is |
|---|---|
| [`2.1d_COMPARATOR_ABSTRACT.md`](Cultural%20Expectations/2.1d_COMPARATOR_ABSTRACT.md) | **Start here for the result.** Findings abstract of the comparator program: **T2 and T4 are the standalone findings; the CTO is a *use case*, not the subject.** The composite is C-suite-wide (not CTO-specific — gap G-1 resolved); the CTO is **unique, not isolated** — distinctive only on the role-scaling axis (the one chief staffed during the IC phase; craft that churns faster than it can be banked). Evidence strength tagged on every claim; over-generalization and weaponization guards in place. |
| [`DRAFT_SYNTHESIS_A.md`](Cultural%20Expectations/DRAFT_SYNTHESIS_A.md) | **The synthesis to build on.** The post-adversarial residue: the not-reasonableness lives in the **legibility/attribution** applied to the role, not in its design. Falsifiable, fence-clean. §9.5 carries the three-axis distinctiveness model. |
| [`DRAFT_SYNTHESIS_COMPARE.md`](Cultural%20Expectations/DRAFT_SYNTHESIS_COMPARE.md) | **Read this first (for the A/B trade-off).** Holds Draft A against its stronger-sounding but weaponizable alternative, and shows why the punchier framing crosses the fence the area exists to guard. |
| [`2.1c_CSUITE_COMPOSITE_SYNTHESIS.md`](Cultural%20Expectations/2.1c_CSUITE_COMPOSITE_SYNTHESIS.md) | **The commensurability map.** Four C-suite roles × twelve dimensions, every cell tagged for evidence strength — the "apple / banana / potato" grid that shows which cross-role comparisons are supported and which are disqualified. |

> **Result, in one line:** the romantic form — *the CTO is special because its composite is uniquely demanding* — did not survive (the composite is **C-suite-wide**; the IC→manager rupture is **universal**). What survived is stronger: **T2 and T4 are general, industry-usable findings, and the CTO is their clearest use case — unique, not isolated.** Because the evidence is for T2 and T4 themselves, the result is usable by the software industry at large, with the over-generalization and weaponization guards explicitly recorded.

---

## Repository layout

```
Technical Skills Analysis/
├── README.md                  ← this file (study root)
├── .gitignore                 ← excludes purchased/copyrighted sources
├── CTO/                       ← flagship case study (full infrastructure)
│   ├── README.md              ← corpus index + status/limitations
│   ├── CONVENTIONS.md         ← greppable-anchor scheme
│   ├── 07_APPENDIX_…          ← citation verification log (the publish-gate)
│   └── 00–14_…                ← context, draft, research, artifacts
├── Software Developer/        ← career-ladder scope (lightweight notes)
│   └── README.md
├── Software Industry/         ← industry scope (lightweight notes)
│   └── README.md
├── Cultural Expectations/     ← where the "irrationality" lives (A/B synthesis + language fence)
│   ├── 2.1d_COMPARATOR_ABSTRACT.md      ← START HERE: the result (T2/T4 general; CTO = use case, unique not isolated)
│   ├── 2.1c_CSUITE_COMPOSITE_SYNTHESIS.md ← commensurability map (4 roles × 12 dims, evidence-tagged)
│   ├── 2.1b_COMPARATOR_*.md             ← protocol + coding results (G-1 resolved)
│   ├── DRAFT_SYNTHESIS_A.md       ← the synthesis to build on (§9.5 = three-axis model)
│   └── DRAFT_SYNTHESIS_COMPARE.md ← A vs B, held against the fence
├── Prompt Evaluations/        ← raw research-session transcripts (provenance)
└── DO NOT CHECK THIS IN/      ← purchased PDFs — GITIGNORED, never committed
```

**Infrastructure note:** the CTO area carries the full apparatus (citation appendix, anchor conventions, draft-gap map). The two newer areas are intentionally lightweight for now and cross-reference the CTO area via explicit `../Area/` relative paths rather than a shared anchor namespace. This can be promoted to a shared corpus later if the broader thesis is developed.

---

## How to read this study (the honest boundary)

This is active research. Treat the claims by tier:

- **Logical claims — solid, citation-independent.** The skill-divergence observation and the scope-vs-kind distinction are established by inspection and a method-of-difference argument. They survive even if every supporting statistic were struck.
- **Peer-reviewed anchors — verified full-text.** The transformation model (offload-and-acquire) rests on two *Journal of Business Venturing* papers read in full: Mathias & Williams (2018) and Van Lancker et al. (2023).
- **Supporting statistics — verify before relying.** Many secondary figures are still under verification. The CTO area logs every one in [`CTO/07_APPENDIX_citation_review.md`](CTO/07_APPENDIX_citation_review.md) with a load-bearing rating and a trace to a primary source. **Treat any unverified statistic as illustrative until that log clears it.** During verification, several stats were already caught as fabricated, misattributed, or domain-mismatched and corrected — the log records those too.

Each research area's appendix calls out its own weaknesses. That self-critique is public on purpose.

---

## Sources & licensing

Some claims are verified against **purchased, copyrighted journal articles** (Elsevier / ScienceDirect). Those PDFs, their licensing terms, and the purchase receipt live in `DO NOT CHECK THIS IN/` and are **excluded from version control** (see `.gitignore`). The research files quote only short excerpts for citation and record the verified facts — never the full text. If you are reproducing this study, you will need your own access to those primary sources.

---

## Working conventions

- **Greppable anchors** (CTO area): claims that depend on a citation, carry a framing risk, or mark a research gap are tagged with HTML-comment anchors (`AX-`, `RISK-`, `GAP-`, `XREF-`) that link bidirectionally to the citation log. See [`CTO/CONVENTIONS.md`](CTO/CONVENTIONS.md).
- **Commit discipline:** treat this like any version-controlled study — commit logical units (a finding, a verification pass, a correction batch) with descriptive messages. The citation log is the source of truth for verification status.

---

*Framework developed in collaboration with Claude (Anthropic). Research conducted June 2026.*
