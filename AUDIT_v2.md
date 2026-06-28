# AUDIT v2 — Post-Cleanup Re-Review & Fix Log (CTO, Software Developer, Software Industry)

**Date:** 2026-06-27
**Supersedes (for current state):** `AUDIT.md` — which is left intact as the historical first-pass record.
**What this file is:** A verification log covering three layers of change since `AUDIT.md`: (1) what an earlier cleanup session had already fixed; (2) the ten must-fix items applied in this pass; and (3) what was deliberately left and why. Every "resolved" claim below was confirmed by re-reading the file after editing; new line text is quoted as evidence.

> **Note on version control:** the repo's git index was corrupt/locked at edit time, so all changes are plain filesystem edits. Nothing here is committed; the user will commit later. No git operations were attempted.

---

## Summary

All ten flagged items are now resolved at the file level. The dominant defect across all three tracks in `AUDIT.md` — a disciplined synthesis sitting on top of source files that still asserted the retired/overclaimed versions — has been closed for the specific items flagged. Where a figure could not be *verified* (it can only be verified with external primary sources), it has been made *non-misleading*: clearly marked unverified / not-citable, with the argument re-routed to state direction rather than the number. Two stale audit-trail notes were also corrected.

---

## Layer 1 — What the earlier cleanup session had already fixed (confirmed still in place)

- **CTO `README.md`** "argument in one pass" fully reconciled: step 3 "The under-resourced condition," scope-vs-kind softened, investor-causal hedged, citations marked illustrative, ~4–6:1 flagged unverified, ~50% flagged cross-industry; prominent retirement note at lines 5–17.
- **CTO "incompatible" sweep** genuinely executed across onramp/legacy files (e.g. `00_RESEARCH_CONTEXT.md` line 100 "⟦not 'incompatible'; retired, `18_RESEARCH`⟧").
- **SW Developer `01_RESEARCH` line 94** already corrected to "consistent with structural mismatch… not established as accurate self-assessment"; 52.7% quarantined (flagged ⬜ unverified, demoted to corroborating) across `DRAFT`, `09_`, `08_`, `AUDIENCE_DERIVATION_PROMPTS`, academic-derived.
- **SW Industry `02b`** Aristotle framing already clean (title "The 10x Myth and **Project Aristotle**" / "What Google Actually Found"); `08_CITATIONS_gap_closure.md` already diagnosed the CHAOS demotion and the ISBSG conflation; `DRAFT_SYNTHESIS.md` already demoted CHAOS to illustrative.

---

## Layer 2 — The ten must-fix items applied this pass

### CTO

**1. `00_RESEARCH_CONTEXT.md` retired language swept — ✅ RESOLVED.**
- Line 64 now: *"**The under-resourcing is temporally concentrated:** … The under-resourced condition exists only in the window pre-seed through Series A … ⟦'irrationality' retired here — the role is *under-resourced*, not irrational; see README lines 5–17.⟧"*
- Line 105 (arguing-from-silence) now: *"The research gap itself (management literature has a blind spot for early-stage leadership). ⟦Note: this absence is *consistent with* Builder mode's structural invisibility but does **not** by itself prove it — absence of research is not evidence of a finding; treat as a gap to be explained, not as confirmation.⟧"*
- Line 104 now "independently **resolve the under-resourcing**"; line 123 retitled "The **under-resourced** composite … ⟦'irrational composite' … retired⟧". No bare "irrational" assertions remain (all occurrences are now explicitly retired/marked).

**2. `07_APPENDIX_citation_review.md` made non-misleading — ✅ RESOLVED (figures still unverified, now clearly non-citable).**
- Header (line 4) changed from "In progress — ratings to be filled in" to: *"**Partial** — many ratings decided, ~19 citations still unverified. This is a *working verification log, not a clearance.* … do not read the 'in progress' framing as 'pending but probably fine.'"*
- New top-of-file **🚫 NOT-CITABLE register** lists `AX-COMPRESSION` (~4–6:1), `AX-VPENG-TIMELINE` (8–15yr vs 18–24mo), and the retracted `AX-CTO-TENURE`. Each entry also carries an inline "🚫 NOT CITABLE until verified" note instructing the draft to state direction, not the number.

**CTO audit-trail note — ✅ RESOLVED.** `AUDIENCE_DERIVATION_AUDIT.md` addendum now opens with "**✅ RESOLVED (2026-06-27)**…" and the `CTO/README.md` subsection is retitled "**✅ FIXED (2026-06-27)**," so it no longer reads as an open hand-off.

### Software Developer

**3. `03_RESEARCH_ic_em_transition.md` line 43 reconciled — ✅ RESOLVED.**
- Now reads (in part): *"The ~50% is not an indictment of *bad training* specifically … which means the boundary itself is genuinely hard … That is **not** the same as saying it is 'not an organizational design flaw.' The thesis is exactly that the organizational design *compounds* a hard boundary: the structural defect … is … the **absence of honest labeling, runway, and a cushion around an already-hard transition** … Both are true; do not read this line as denying the structural argument."* The flat denial of the org-design framing is gone.

**4. `06_RESEARCH_knowledge_obsolescence.md` imposter section reframed — ✅ RESOLVED.**
- Heading (line 102) now: *"## The Imposter Syndrome Connection: **Consistent With Structural Mismatch (Not Established as Accurate Self-Assessment)**"* with a "⚠️ Claim narrowed" banner.
- The three "accurate"/"correctly perceiving" passages (formerly lines ~112/118/178) are rewritten to "*consistent with* … but 'consistent with' is the ceiling of the claim," with the base-rate disconfirmation (healthcare ~62% > software 52.7%) stated explicitly and the ~50% reversion named as the behavioral anchor.

**5. `05_RESEARCH_cross_industry.md` AMA misattribution + 62% collision fixed — ✅ RESOLVED.**
- Line 44 adds a citation-caution: the ~62% burnout figure "traces to **Medscape's** physician surveys, **not** the AMA — the AMA/Mayo collaborative … nearer ~41.9% … do not attribute the 62% to the AMA," and explicitly disambiguates it from the healthcare **imposter-syndrome** ~62% ("the two ~62% figures are numerically similar by coincidence and must not be used interchangeably").
- The source table (line 241) is corrected to re-attribute the ~62% to Medscape and flag the burnout-vs-imposter distinction.

**SW-Dev audit-trail notes — ✅ RESOLVED.** Both reconciliation notes that said "`01_`/`06_` still state the strong causal version" (in `DRAFT_SYNTHESIS.md` line 261 and `derived/DRAFT_SYNTHESIS_academic.md` line 182) now read "**Propagation status, 2026-06-27: `01_` … and `06_` … now both carry the 'consistent with' framing — this reconciliation is complete.**"

### Software Industry

**6. `01_MMM_brooks_original_argument.md` line 142 — CHAOS demoted — ✅ RESOLVED.**
- The sentence "**Fifty years of empirical confirmation that Brooks was right**" is removed. Now: the figures are "*(Cited illustratively, not as proof …)*" with the Jørgensen & Moløkken-Østvold / Eveleens & Verhoef criticisms and the redirect to Rodríguez 2012, ending "The pattern this figure gestures at is consistent with Brooks … " — illustrative, not load-bearing.

**7. `04_MMM_unstable_craft.md` keystone restated — ✅ RESOLVED.**
- New "⚠️ Keystone restated" banner (line 14) declaring "software has no stable craft to master" overstated; defensible form: "**the *credited* skill layer … is unstable; the durable layer is real but largely *uncredited*.**"
- Heading (line 30) changed from "Software Has No Stable Craft to Master" to "**Software's *Credited* Craft Layer Is Unstable (the Durable Layer Is Real but Uncredited)**." The thesis line (18) and the summary line (173) are reworded to the credited-layer framing.

**8. `13_RESEARCH_software_industry_structural.md` causal imposter claim hedged — ✅ RESOLVED.**
- Exhibit 2 retitled "**as a Candidate Industry Diagnostic**" with a "⚠️ Claim narrowed" banner. "they are **accurately perceiving** a real mismatch" → "the feeling is *consistent with* engineers perceiving a real mismatch … The data here cannot establish that the perception is veridical." 52.7% now marked "reportedly … ⬜ unverified." "It **is** an organizational diagnostic" → "*consistent with* an organizational-design problem … not a conclusion the prevalence figure proves."

**9. `14_RESEARCH_success_exceptions.md` de-rigged — ✅ RESOLVED.**
- The "anti-recipe writes itself / most successes are `[CONTEXT/LUCK]` by definition" pre-classification is removed and replaced with a "⚠️ Classification discipline" note: cases are "collected first and classified *afterward*," with `[STRUCTURAL-EXCEPTION]`, `[CONTEXT]`, `[LUCK]`, and `[GENUINE-COUNTEREXAMPLE]` all live, and a genuine counterexample explicitly named as something that "would **force a thesis revision**, not something to explain away." Candidate angles reworded from assertions to open questions.

**10. ISBSG de-laundered in `02_` and the DRAFT — ✅ RESOLVED.**
- `02_MMM_fungibility_assumption.md` line 111 no longer says "A 2012 empirical analysis of over 1,000 projects." It now splits the claim into "**two distinct studies**": Rodríguez et al. (2012), peer-reviewed, 951 ISBSG instances → ≥9 degrades; and Putnam (1997), non-peer-reviewed QSM article, 491 projects → 3–5 optimal — explicitly noting the earlier phrasing "conflated the two."
- `DRAFT_SYNTHESIS.md` line 56 changed from "the **ISBSG team-size curve** (1,000+ projects: 3–7 optimal, ≥9 degrades)" to "the **team-size evidence** (two separate studies, cited as such … Rodríguez et al. 2012 … → ≥9 degrades; Putnam 1997 … → 3–7 optimal, with the 'optimal' figure the weaker non-peer-reviewed leg)."

---

## Layer 3 — Deliberately left (with reasons)

- **CTO economic figures remain unverified.** `AX-COMPRESSION` (~4–6:1) and `AX-VPENG-TIMELINE` (8–15yr vs 18–24mo) are *not verified* — verification requires external comp-survey primaries (Levels.fyi / Pave / Radford / Kruze) not done in this pass. They are now marked **🚫 NOT CITABLE until verified** and the draft already states direction rather than the number. This is honesty, not verification; the open data need is logged in `07_APPENDIX`.
- **52.7% imposter figure remains unverified** in both the SW-Dev and SW-Industry tracks ("ResearchGate 2024" is a host, not a citation). It is now uniformly flagged ⬜ unverified and demoted to corroborating everywhere; tracing the primary is still owed.
- **ISBSG "3–5 optimal" still rests on the non-peer-reviewed Putnam (1997).** Not fixable by editing — it is the only source for that specific number. The fix here is *disclosure* (the weaker leg is now labeled as such), not substitution.
- **Residual descriptive CHAOS mention in `02_` line 109** ("The 2015 CHAOS Report analyzed thousands of projects…") was left as descriptive context; it is not used as "empirical confirmation," so it is not load-bearing. Flagged here for transparency; a future pass could add the same illustrative caveat for consistency.
- **The broader "incompatible" propagation to `08_` and other Industry/Dev files** (tracked separately in the CTO audit as `R2` Bias 7) was out of scope for these ten items and is not claimed as done.

---

## Files edited this pass

CTO:
- `CTO/00_RESEARCH_CONTEXT.md`
- `CTO/07_APPENDIX_citation_review.md`
- `CTO/AUDIENCE_DERIVATION_AUDIT.md`

Software Developer:
- `Software Developer/03_RESEARCH_ic_em_transition.md`
- `Software Developer/06_RESEARCH_knowledge_obsolescence.md`
- `Software Developer/05_RESEARCH_cross_industry.md`
- `Software Developer/DRAFT_SYNTHESIS.md`
- `Software Developer/derived/DRAFT_SYNTHESIS_academic.md`

Software Industry:
- `Software Industry/01_MMM_brooks_original_argument.md`
- `Software Industry/04_MMM_unstable_craft.md`
- `Software Industry/13_RESEARCH_software_industry_structural.md`
- `Software Industry/14_RESEARCH_success_exceptions.md`
- `Software Industry/02_MMM_fungibility_assumption.md`
- `Software Industry/DRAFT_SYNTHESIS.md`

---

## Final status per track

- **CTO — In good shape.** README spine and onramp now consistent; remaining gap is unverified economic figures, which are clearly fenced as not-citable rather than asserted. Citable as-is provided the not-citable figures stay out of any published number.
- **Software Developer — In good shape.** Drafts, derived drafts, and the three previously-contradicting source files (`03_`, `06_`, `05_`) now align with the structural thesis; only external citation verification (52.7%, half-lifes) remains, and those are flagged, not load-bearing.
- **Software Industry — Substantially repaired.** The substantive files (`01_`, `04_`, `13_`, `14_`, `02_`) now match the synthesis: CHAOS illustrative, keystone narrowed to the credited layer, imposter claim hedged, success stub de-rigged, ISBSG de-laundered. The "synthesis contradicts its sources" defect is closed for the flagged items; residual unverified figures are disclosed, not asserted.
