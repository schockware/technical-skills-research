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

**The CTO area is the flagship** — the most developed, most evidenced, most publishable. The other two are *supporting* material that generalizes it: they answer the natural objection "if it's so irrational, why only the CTO?" with "it's *not* only the CTO — that's just where it's most visible."

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
