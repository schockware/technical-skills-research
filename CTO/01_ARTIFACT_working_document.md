# Artifact: CTO_Operating_Modes_Working_Document.docx
## Summary for Claude instances

**Type:** Research working paper (Word document)  
**Status:** Working draft — 11 sections, ~238 paragraphs, 14 footnotes  
**Purpose:** Citable research artifact for publication  

---

## Document structure

| Section | Content |
|---|---|
| 1. Introduction | The misnomer stated in three versions. Core claim established. |
| 2. Etymology | Title origin at GE/Allied-Signal/ALCOA (late 1980s). Adler & Ferdows (1990). Dot-com migration. Inheritance error named. |
| 3. Taxonomy | Three modes with summary table. Builder, Multiplier, Strategist defined. |
| 4. Failure clustering | Evidence for both transition boundaries. Greiner crisis mapping. Carta/Crunchbase survival data. |
| 5. Greiner alignment | Independent validation table. Phases 1-5 mapped to modes. |
| 6. Mode names | Selection rationale for each name. Steelman for each. Naming as invitation to peer review. |
| 7. Team skills | Layer 1: skills compendium. Layer 2: role rubric. Layer 3: transition gates with failure signals. |
| 8. Implications | Hiring, performance evaluation, compensation, succession planning, investor case. |
| 9. Limitations | Survivorship bias, empirical validation needed, Multiplier sub-transition, domain variation, research agenda. |
| 10. Irrational composite | IC/management track bifurcation. Sequential incompatibility. Larson convergence table. Temporal concentration argument. Central claim restated. |
| 11. Conclusion | Full synthesis. Every CTO who experienced transition failures was not failing — they were doing one job when the company needed a different one. |

---

## Footnotes (14)

1. Adler & Ferdows (1990) — first CTO documentation
2. Smith (2002) via Jasinski (2018) — GE/Allied-Signal/ALCOA origin
3. Greiner (1972, 1998) — organizational growth model
4. Wiseman & McKeown (2010) — Multipliers, 2x output gap
5. Google Project Oxygen — technical skill ranked last
6. Carta/Crunchbase (2024-2025) — survival data
7. First Round CTO Summit — Strategist failure modes
8. Kruze Consulting (2024) — compensation gap
9. Mars (2026) — Transitive Expert Error
10. Myhrvold, N. — "many people who were great CTOs didn't have that title"
11. Index Ventures — 78% successful companies had founding CTOs at seed
12. Ewing, R. — IC vs management track divergence
13. HR Oasis (2026) — technical skill atrophy within 2-3 years of management
14. Larson, W. (2021) — Staff Engineer archetypes, emergence timing

---

## Key tables in document

- **Mode summary table** (Section 3): Mode / Stage / How / Primary output / Failure mode
- **Greiner alignment table** (Section 5): Phase / Growth through / Crisis at end / CTO mode
- **Larson convergence table** (Section 10): Archetype / Emerges at / CTO mode / What it distributes

---

## What is NOT in this document (covered elsewhere)

- Full skills compendium with transfer types → `team-skills-compendium.html`
- Role-based rubric (CTO vs VP Eng vs EM vs Tech Lead) → `team-skills-compendium.html`
- Transition gate checklists → `team-skills-compendium.html`
- Individual CTO transition brief → `cto-transition-brief.html`
- Research classification table (34 threads mapped to taxonomy) → generated in session, not yet formalized

---

## How to update this document

The document was built with a Node.js script (`build_research_doc_v2.js`) using the `docx` npm library. To add sections, modify the script and re-run with `node build_research_doc_v2.js`. The script is in `/home/claude/` in the container — not persistent across sessions. Recreate from the source if needed.

To add footnotes: insert into the `footnotes` object with the next sequential number, and add `new FootnoteReferenceRun(N)` at the appropriate inline location.
