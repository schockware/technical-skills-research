# Quality Audit — CTO, Software Developer, and Software Industry Tracks

**Date:** 2026-06-27
**Scope:** A rigorous, critical quality review of three research tracks in this repository — `CTO/`, `Software Developer/`, and `Software Industry/`. Each track was read in depth (research files, syntheses, R1–R4 adversarial review passes, and derived audience drafts), and the sharpest findings were verified directly against the files.
**Assessment dimensions:** (1) factual accuracy, (2) citation integrity, (3) internal consistency, (4) writing quality, (5) completeness/gaps.

---

## Executive summary: the propagation pattern

All three tracks share one architecture and one defining failure.

The architecture is strong: raw research → synthesis → adversarial self-audit (`R1` adversary, `R2` falsification, `R3` steelman, `R4` open agenda) → audience-tailored derived drafts. The self-audit layer is genuinely good. These corpora catch their own fabricated statistics, misattributions, and overclaims more honestly than most published work does.

The defining failure is **propagation hygiene**: corrections were applied to the polished synthesis and the derived drafts, but almost never pushed back into the source files (READMEs, numbered research files, gap maps). The result, repeated in all three tracks, is a defensible "spine" sitting on top of research files that still assert the retired, overstated claims. In two tracks the corpus marks the propagation sweep "done" when it demonstrably is not.

The practical consequence: **a reader entering through a README or a numbered research file gets a materially stronger, less defensible argument than the synthesis actually makes.** Anyone citing the source files rather than the spine will cite claims the corpus itself has retired.

---

## Quality ranking

1. **CTO** — deepest research, best citation audit, most polished deliverables. Loses points because its self-contradiction is the starkest and its own audit *falsely claims* to have fixed it.
2. **Software Industry** — cleanest checkable citations and the most honest gap-closure file, but knowingly ships overstated source files and a confirmation-rigged falsification stub.
3. **Software Developer** — solid drafts, but the softest citation integrity (the "62%" collision, an AMA misattribution, a dual-sourced 52.7%) and the same unpropagated contradictions, with less verification scaffolding than the other two.

The gap between the three is narrow. All three would rank substantially higher if the synthesis-level corrections were propagated to the source files.

---

## Track 1 — CTO

### Verdict
The flagship deliverables (`DRAFT_SYNTHESIS.md`, the five derived drafts, and the R1–R4 adversarial track) are rigorous, faithful to each other, and honest about their limits. The corpus's self-criticism — catching a fabricated tenure stat, a misapplied AI paper, and inverted/misattributed stats, and retracting "irrational"/"survivor-proof" — is better than most published work. The real weakness is propagation: corrections were applied to the spine but not to the onramp/legacy files, and the corpus's own audit marked the fix "done" and left the contradictions in place. The publishable spine is in good shape; the surrounding corpus contradicts it and should not be shipped or cited until reconciled.

### Factual accuracy
The current synthesis and derived drafts are disciplined. The factual-accuracy problems live in the older files the README still points readers to:

- **`README.md` lines 89–91 ("The argument in one pass")** assert, in the corpus's own voice, three claims the same file (lines 5–17) formally retired: "**Irrational condition**," the "**scope-vs-kind keystone (why only the CTO is catastrophic)**," "**Confirmed by Greiner, Carta/Crunchbase, Kruze**," and "**~4–6:1 cash compression**." This is the sharpest factual contradiction in the repo — the index contradicts itself within one file.
- **`00_RESEARCH_CONTEXT.md` line 103** still treats the *absence* of research as proof: "the research gap as evidence (management literature's blind spot for early-stage leadership confirms Builder mode's structural invisibility)." The citation appendix itself named this arguing-from-silence move the "strongest offender" and recommended cut/downgrade; it survives intact.
- **`00_RESEARCH_CONTEXT.md`** also still carries the retired heading "The irrational composite thesis" and "The irrationality is temporally concentrated."
- **`DRAFT_GAP_MAP.md`** lists the fabricated "Spencer Stuart 2.5yr" CTO-tenure figure as a "strong source, quick win" despite its retraction in the appendix.

### Citation integrity
`07_APPENDIX_citation_review.md` is the strongest single artifact in the repository. It self-flags real problems:

- **Fabricated stat:** "2.5yr average CTO tenure (Spencer Stuart)" — marked NOT SUPPORTED, no source, contradicted by Korn Ferry (~4.3yr). Caught and retracted.
- **Domain mismatch:** "Mars (2026) TEE" is a real arXiv paper about AI model routing, not human psychology, yet was used as the load-bearing human-failure mechanism. Caught, demoted to metaphor.
- **Misattributions:** "McKinsey 3.1x" is actually Bain (HBR 2016); micromanagement stats are inverted Paul Zak trust data; the EQ "70%/155K/22%" figures were not found; "Index 78%" over-narrowed; the CMO "40mo/decade-low" figure is wrong (actual ~4.2yr).
- **Source-class weakness:** the entire `10_`/`11_`/`12_` economic-wave argument rests on content/marketing sites (`ctaio.dev`, `wtt-solutions`, `icanpitch`); the appendix concedes none are peer-reviewed. Only Kruze, Mathias & Williams (2018), and Van Lancker et al. (2023) are verified primaries.

Remaining gaps: the appendix header still reads "Status: In progress — ratings to be filled in," with many empty confidence cells. By the corpus's own publish-gate rule, the load-bearing `AX-COMPRESSION` ($1.1M / ~4–6:1, High load-bearing, unverified) and `AX-VPENG-TIMELINE` (High, unverified) remain unverified. The spine correctly declines to lean on these, but `README.md` and `00_RESEARCH_CONTEXT.md` still cite them as load-bearing.

### Internal consistency
The spine and the five derived drafts are faithful and mutually consistent — `AUDIENCE_DERIVATION_AUDIT.md` independently grep-verified that no derived draft restores a retired claim. That part is clean.

But the corpus's own audit documents a contradiction it did not fix. `AUDIENCE_DERIVATION_AUDIT.md` states that the README files "still carry the pre-retirement language the spine retired… they contradict [the drafts]," and a sweep is marked "✅ SWEEP EXECUTED" — yet `README.md` lines 89–91 still contain the flagged contradictions. **A false "done" that hides the defect.** This is the single most dangerous item in the track because it disguises an open problem as a closed one.

Additional unreconciled items:
- `08_DRAFT` (≈ line 162) and `09_RESEARCH` (≈ line 115) still contain the un-hedged causal sentence "*The irrational composite was institutionalized by the very party whose job is to evaluate execution risk*," which `RISK-INVESTOR-CAUSAL` and both R1 and R2 explicitly said to cut.
- `CTO_RESEARCH_MAP.md` (≈ line 39) and `DRAFT_GAP_MAP.md` (≈ line 36) still call the no-triple-mode finding "Survivor-proof result" in their own voice — the exact term R1/R2 said to retract.

### Writing quality
- **Severe redundancy.** The Must-Not-Claim table, the §3a misattribution quotes, the CRO/VP-Sales exhibit, and the §4 "accidental concession" are restated near-verbatim across the spine and all five derived drafts. The "Plain form (for derivation)" blocks duplicate the prose immediately above them.
- The **academic derived draft overruns its brief** (~5,500 words against a stated 1,800–3,000 ceiling — roughly 2x).
- **Heavy meta/jargon scaffolding** (`AX-`, `RISK-`, `GAP-`, `XR-`, "motte-and-bailey," "Mill's method") makes the research files read as apparatus about the argument rather than the argument.
- **Hedging density** in the spine is extreme — intellectually honest but tonally exhausting.

### Completeness / gaps
- **Central empirical gap, openly stated:** `GAP-CTO-TRANSITION` — no study measures the founding-CTO Builder→Multiplier success rate. The thesis is "shaped around a number it has never measured." Honestly handled.
- **Thesis-level open TODOs:** `TODO.md` items T2 (is the irrationality in the cultural *expectation*?) and T4 (cultural-permission/collective-akrasia) are substantial unresolved directions the README leans on rhetorically but which do not yet exist as research.
- **Appendix unfinished:** still "In progress," ~19 citations unverified, multiple empty confidence cells.
- **Propagation sweep (T3) marked DONE but demonstrably incomplete** — the "✅" status is itself a completeness defect.

### Top issues (severity-ranked)
1. **(High)** `README.md` lines 89–91 contradict the same file's lines 5–17 — asserts "Irrational condition," "scope-vs-kind / why only the CTO is catastrophic," "Confirmed," and "~4–6:1" as fact.
2. **(High)** Sweep marked "✅ SWEEP EXECUTED" in `AUDIENCE_DERIVATION_AUDIT.md` (and TODO T3) but not executed — false completion hiding the defect.
3. **(High)** Un-hedged investor-causal sentence still verbatim in `08_DRAFT` (~162) and `09_RESEARCH` (~115), which R1/R2 said to cut.
4. **(Med-High)** Arguing-from-silence survives at `00_RESEARCH_CONTEXT.md` line 103 ("confirms Builder mode's structural invisibility") — the appendix's named "strongest offender."
5. **(Med-High)** Load-bearing economic numbers (`AX-COMPRESSION`, `AX-VPENG-TIMELINE`) rest on content-site sourcing and remain unverified; README/00 still cite them as load-bearing.
6. **(Med)** Stale contradictions: `DRAFT_GAP_MAP.md` lists the fabricated 2.5yr figure as a "strong source"; `CTO_RESEARCH_MAP.md`/`DRAFT_GAP_MAP.md` still say "Survivor-proof."
7. **(Med)** Pervasive redundancy; academic draft ~2x its word ceiling; anchor/meta jargon dominates research files.
8. **(Low-Med)** Promised-but-undelivered cultural-expectation/akrasia research (T2/T4) leaned on in the README but not yet written; citation appendix unfinished.

---

## Track 2 — Software Developer

### Verdict
A rigorous, heavily self-audited corpus whose draft and derived drafts are largely defensible and faithfully scoped. But the rigor is uneven: the underlying research files (`01_`, `03_`, `06_`) still assert the strong causal claims the draft says were retired, so the README's "propagated/reconciled" status is overstated. Citation integrity is the softest dimension of any track — the "62%" figure is used for two different metrics with a mis-attribution to the AMA, and the load-bearing 52.7% and half-life figures remain unverified while circulating at full strength.

### Factual accuracy
- **The central number is cross-industry, but half the corpus still treats it as software-specific.** The ~50% IC→EM reversion rate is, per the corpus's own `03_RESEARCH` (≈ line 64), the cross-industry baseline for new-manager failure (CEB/Gartner, n≈30,000). The draft correctly demotes it to "boundary-difficulty, not distinctiveness." But `01_RESEARCH` line 23 still calls the structure "the origin of the ~50% IC→EM reversion rate."
- **`03_RESEARCH_ic_em_transition.md` line 43** asserts the ~50% "is a human capacity constraint, **not an organizational design flaw**" — which directly negates the draft's entire structural (missing-cushion) thesis. A live, unreconciled contradiction inside a load-bearing research file.
- **"7–10 hours/week of deliberate learning = two additional degrees over a career"** (`06_RESEARCH` ≈ line 58; `01_` ≈ line 74) is presented as a finding but is, by the file's own admission (≈ line 60), "a derived figure based on the half-life math, not a directly sourced figure." It is a speculative inference stacked on unverified inputs.
- **All knowledge half-life figures are unverified** (`06_RESEARCH` table, ≈ line 33: every row marked directional-only, "specific paper not yet traced"). The 1920s≈35yr / 1960≈10yr / 1991<3yr / current 2.5–5yr progression is asserted with specific numbers but no traced primary source — and still appears bare in `01_`.

### Citation integrity (softest dimension in the repo)
- **The "62%" collision.** Two different 62% figures exist: physician **burnout** 62% (`05_RESEARCH` ≈ lines 44/241, attributed to "AMA Burnout Report") and healthcare **imposter syndrome** 62% (Salari et al. 2025 meta-analysis, sourced only in `../Software Industry/08_CITATIONS_gap_closure.md`). The adversarial files and draft repeatedly cite "healthcare ~62% > software 52.7%" as an *imposter* comparison, but `05_RESEARCH` — the only cross-industry file in this folder — carries 62% solely as *burnout*. Worse, the AMA's own burnout figure is 41.9% (per Industry `08_CITATIONS` ≈ line 155); the 62% is Medscape, not AMA. So `05_RESEARCH` line 241's "62% … AMA Burnout Report (✅ HIGH confidence)" is **mis-attributed**.
- **The 52.7% imposter figure has two incompatible attributions.** Dev-track files cite "Clance Impostor Phenomenon Scale, ResearchGate 2024" (`01_` ≈ line 88; `06_` ≈ line 201). The Industry citation file attributes the equivalent claim to "Guenes et al. (2024), ICSE, DOI 10.1145/3639475.3640114, n=624." "ResearchGate 2024" is a hosting platform, not a citation, and is flagged unverified — yet the number is reused throughout as if anchored.
- **The Peter Principle arXiv model (2025) and Benson et al. (200+ firms)** are cited with specific findings (`01_` ≈ lines 100–106; `06_` ≈ lines 160–168) but flagged "preprint, not peer-reviewed" / "unverified." `01_` states the arXiv finding as established fact; `06_` more honestly hedges it — the same citation at two confidence levels in one folder.
- The well-anchored citations (Larson 2021; Mathias & Williams 2018; Van Lancker 2023; ISBSG/Rodríguez 2012 with DOI) are real and correctly used. The corpus is honest about which is which — but the unverified ones still circulate at full strength in `01_`/`06_`.

### Internal consistency
- **The draft's own status notes admit the research files were never fully reconciled.** `DRAFT_SYNTHESIS.md`'s reconciliation footer and the academic derived draft both say `01_`/`06_`/`08_` "still state the strong causal version — propagation owed, R2 Bias 6." Confirmed: `06_RESEARCH` line 102 still has the heading "The Imposter Syndrome Connection: Accurate Self-Assessment," and ≈ lines 110–120 still state the strong causal claim ("Both perceptions are *accurate*… an accurate read of a structural condition") — the exact claim R1, the draft, and the README say was retired. The README (≈ line 37) asserts the correction was "propagated into 06_," but only a warning banner was added to the top while the body and a section heading still assert the retired claim. **The README overstates completion.**
- **Derived drafts are faithful on the high-risk items.** Every derived draft flags ~50% as cross-industry; no draft restores it as "proving software distinctiveness." On spine-faithfulness, the derived drafts are the strongest part of the corpus.
- **The academic derived draft is ~5,593 words against a stated 1,800–3,000-word ceiling** (~85% over). `AUDIENCE_DERIVATION_AUDIT.md` files this as a "scope note (not a defect)" — a generous reading.

### Writing quality
- **Severe redundancy across derived drafts.** The surgeon-anchor identity passage, the cross-industry caveat, the serial-replacement loop, and the "you cannot resource a transition you won't name" line recur near-verbatim across the engineers/managers/founders drafts. Within the spine, the three-cushion list, the "the correction is the confession" argument, and the accidental-concession move each appear in §3, §5, §6, and again in `09_SYNTHESIS`. The corpus is roughly 30–40% longer than its content.
- **Meta-commentary bloat.** A large fraction is the documents talking about their own rigor ("stated so they cannot be quietly widened later," provenance stamps, reconciliation footers). `DRAFT_SYNTHESIS.md` spends its first ~600 words on framing-about-framing before reaching §1.
- **Occasionally self-congratulatory** despite a stated "do not praise own rigor" discipline ("logically airtight," "the strongest rhetorical asset").

### Completeness / gaps
- **Open placeholders in the published spine.** `DRAFT_SYNTHESIS.md`'s "Audience Map (derivation key)" is marked "⬜ STUB … Do not treat the cells below as final copy," and the Appendix row is "⬜ stub — to fill" — yet the five derived drafts were already built from that stub.
- **The plateau population is admitted as having no data** (`04_RESEARCH` ≈ line 180, "⬜ No data found") — a structurally important leg of the §4 argument rests on an explicit non-measurement.
- **Acknowledged-but-unclosed propagation debt** to `01_`/`06_`/`08_` (R2 Biases 6–7), in a corpus the README describes as "published while under verification."

### Top issues (severity-ranked)
1. **(High)** Unreconciled contradiction at `03_RESEARCH` line 43: "~50% … is a human capacity constraint, **not an organizational design flaw**" negates the draft's structural thesis. `01_` line 23 still credits the structure as "the origin of the ~50% reversion." README claims these were reconciled; they were not.
2. **(High)** The "62%" collision: physician *burnout* 62% (`05_`, mis-attributed to AMA — actual 41.9%) vs. healthcare *imposter* 62% (Salari, sourced only outside this folder), used interchangeably in argument.
3. **(High)** Partial propagation the README calls complete: `06_RESEARCH` line 102 still carries the heading "Accurate Self-Assessment" and the full strong-causal claim (≈ 110–120) — only a top banner was added.
4. **(Medium)** Load-bearing-adjacent figures unverified but circulated at strength: half-life numbers, the 7–10 hr/week "two degrees" inference, the 52.7% figure ("ResearchGate 2024" is not a citation), Peter Principle arXiv, Benson — flagged in some files, asserted bare in `01_`.
5. **(Medium)** 52.7% has conflicting source attributions (Clance/ResearchGate 2024 in dev files vs. Guenes et al./ICSE/DOI in the Industry file); never reconciled.
6. **(Medium)** Heavy redundancy/bloat; large volume of meta-commentary about rigor.
7. **(Low-Medium)** Academic derived draft ~5,600 words vs. a 1,800–3,000 brief; the audit waves it through as "not a defect."
8. **(Low-Medium)** The spine's Audience Map is a labeled STUB, yet all five derived drafts were already produced from it; appendix "to fill."

---

## Track 3 — Software Industry

### Verdict
The track's citation scholarship is genuinely strong where it touches the checkable book (Brooks quotes are real and accurate, the 10x myth is correctly traced to Sackman 1968, Project Aristotle verifies), and the R1/R2/`08` review apparatus is an unusually honest self-audit. But the track has a fatal execution gap: it diagnosed its own most serious flaws — the overstated keystone (file 04), CHAOS as load-bearing, imposter-as-diagnostic, unfalsifiability, "incompatible" phrasing — and then explicitly declined to fix them in the substantive files, leaving a publication-ready synthesis that contradicts the research files it cites. It is a corpus that knows what is wrong with itself and shipped anyway, relying on the reader to apply corrections mentally.

### Citation integrity (strongest where checkable)
Verified against primary sources:
- **Brooks's Law** ("Adding manpower to a late software project makes it later") is quoted correctly; the file correctly notes Brooks called it "an outrageous oversimplification."
- The **"divided by seven … 200 people … coordinating only 20 minds"** passage in `01_MMM_brooks_original_argument.md` is a verbatim, accurate Brooks quote (woven into prose unquoted rather than set off).
- **No Silver Bullet**, essential/accidental complexity, the four essential difficulties, the surgical-team model, and the n(n−1)/2 communication formula are all represented accurately.
- The **Sackman/Erikson/Grant (1968)** material in `02b` is correctly sourced to the real origin (12 programmers; the study was actually about online-vs-offline programming; the genuine "no correlation with experience" finding).
- **Project Aristotle** (2012, ~180 teams, psychological safety as top factor) verifies.
- `08_CITATIONS_gap_closure.md` is a genuine gap-closure file, not a paper-over: it demotes the track's weakest sources, flags non-peer-reviewed status honestly (Putnam 1997, DORA-as-trade-book), and corrects its own overstatement ("1,000+ projects" → "951 instances").

### Factual accuracy — specific problems
- **The "Aristotle" in the `02b` title is a bait-and-switch.** `02b_MMM_10x_myth_and_aristotle.md` invokes "Aristotle" but the content is entirely about Google's "Project Aristotle" — the philosopher never appears. The title trades on an ambiguity the content does not earn.
- **"Knowledge half-life 2.5–5 years" is unverified and repeated as if multiply-sourced** across `00_`, `03_`, `04_`, and `13_`. R2 calls this out directly ("Repetition makes one unverified figure read as four pieces of evidence"). The historical comparison figures in `13_` Exhibit 3 ("1920s: ~35 years … 1991: <3 years") have false precision and no source.
- **The 10x → Nichols framing slightly overstates.** `02b` says Nichols showed "a lack of evidence to support the idea that some developers are naturally more efficient." Even the skeptical literature (Construx/McConnell) holds that after correcting Sackman's flaws the data still shows a >10x best-to-worst spread. R1 Claim 2 catches this, but `02`/`02b` still assert the stronger collapse.
- **`13_` Exhibit 4 deploys "Peter Principle Revisited (2025, arXiv)" and "Darshan et al., 2013"** as load-bearing for a stress claim, even though the README admits both are "Unverified pending a dedicated pass; treat as illustrative."

### Citation integrity — beyond the clean core
- **The CHAOS Report (61%/11%/6%) is still load-bearing in `01_`, `02_`, and `13_`** despite the track's own R1/R2/`08` verdict that it is "the most methodologically criticized dataset in software engineering" and must be demoted to illustrative. `01_` still calls it "Fifty years of empirical confirmation that Brooks was right." Diagnosed but not applied — the single biggest live citation liability.
- **The 52.7% imposter figure is still asserted causally in `13_`** ("It is an organizational diagnostic … they are accurately perceiving a real mismatch"), even though `08_` and R1 Claim 5 establish it is not a software outlier (healthcare 62%, law 50–83%) and the causal claim must be retired.
- **Brooks's "ramp-up 3–6 months … confirmed empirically by NASA Software Engineering Laboratory"** (`01_`) — the NASA SEL attribution is asserted without a specific citation and does not appear in `08_`'s verified list. Suspicious precision.
- **The ISBSG "3–5 optimal" number is laundered.** `02_`/`04_`/`DRAFT` cite "ISBSG, 1,000+ projects, 3–7 optimal, ≥9 degrades" as one finding, but `08_` reveals "≥9 degrades" comes from Rodríguez 2012 (peer-reviewed, 951 instances) while "3–5 optimal" comes from Putnam 1997 (unreviewed industry article, different 491-project dataset). The DRAFT merges them into one clean-sounding claim.

### Internal consistency — the central structural problem
**The DRAFT_SYNTHESIS and the substantive MMM files (01–06, 13) directly contradict each other, and the track admits it.** The README "Stabilization note" and `08_`'s closing line both state plainly that "`08` verified the sources but deliberately did NOT rewrite 01–06."

- The DRAFT and derived draft are built on the narrowed, defensible claims (R3 steelman: "the *credited* layer is unstable"; CHAOS demoted; imposter as corroborating-not-load-bearing).
- The MMM files 01–06 and 13 still contain the un-narrowed versions. `04_MMM_unstable_craft.md` line 28 still leads with the keystone "The Evidence: Software Has No Stable Craft to Master." The README (≈ line 17) even annotates file 04 inline as "**over-stated — see R1**" — i.e., the track is knowingly shipping a file it has flagged as wrong.

So the synthesis does not faithfully represent its own research files — it represents a corrected version the files were never updated to match. A reader moving from DRAFT back to the cited sources finds the opposite strength of claim.

- **The unfalsifiability problem is real and unresolved.** R2's table routes every outcome to confirmation (revert = rational refusal; succeed = luck; plateau = invisible failure). `14_RESEARCH_success_exceptions.md` embodies exactly this: it is a 25-line stub that pre-classifies findings as `[CONTEXT/LUCK]` before collecting any ("most industry-level 'successes' are `[CONTEXT/LUCK]` — they didn't beat the structure, they operated where the structure happened not to bite"), and ends "No cases entered."
- **The "incompatible → distinct/no-runway" correction is half-propagated.** The README claims it was pushed into `01/03/04/06/13`, yet the DRAFT itself notes "this tier's core files still say 'incompatible' — that is the retired phrasing."

### Writing quality
- **Severe bloat and redundancy.** The five-axis apparatus, the "surgeon stays licensed / engineer has no anchor" passage, and the "~50% reversion = rational refusal" set-piece recur near-verbatim across `00_`, `04_`, `06_`, the DRAFT, and the derived draft. The "compress three years into bullet points" anecdote appears in `02b` and `04` in near-identical form.
- **`DRAFT_SYNTHESIS.md` is meta-text-heavy** to the point of obscuring the argument ("This is the widest of three sibling spines," "softening losslessly downward," "increment log: see git log").
- **R2 itself names the tone problem** ("totalizing language … second-person grievance voice") and the tells persist unfixed in `02`, `02b`, `04` ("The myth collapses," "Every word is wrong for software").

### Completeness / gaps
- **`14_RESEARCH_success_exceptions.md` is a stub** ("No cases entered") — and the disconfirming half of the entire track lives there. The falsification rests on a file that contains nothing.
- **The DRAFT Audience Map and Appendix are explicit stubs.** Only 1 of 6+ planned audience derivations (engineers) exists in `derived/`.
- **`08_`'s open-gaps table is honestly unresolved but large** (Staff promotion rates, whether dual-track reduces reversion, all five falsification natural-experiments — none answerable from public data).
- **`HANDOFF_claude_code.md` is stale.** It lists files 01–04 as "what has been written" and 05/06 as "to be built," predating the now-existing 05, 06, 08, and the entire R-track. It still propagates the unverified "2.5–5 year half-life" and CHAOS as authoritative and pre-commits the success thread to `[CONTEXT/LUCK]`. Anyone following it would rebuild the already-diagnosed problems.

### Top issues (severity-ranked)
1. **(Critical)** Synthesis contradicts its own source files by design. DRAFT/derived use narrowed claims; files 01–06/13 retain the overstated originals. README and `08_` both admit "did NOT rewrite 01–06."
2. **(High)** CHAOS Report still load-bearing in `01_`/`02_`/`13_` ("fifty years of empirical confirmation") despite the track's own verdict to demote it.
3. **(High)** 52.7% imposter figure still asserted causally as an "organizational diagnostic" in `13_`, contradicting `08_`/R1.
4. **(High)** Unfalsifiability structural and unresolved: `14_` is a stub that pre-labels all future success cases `[CONTEXT/LUCK]` before collecting them.
5. **(Medium)** "2.5–5 year half-life" unverified but repeated 4× as data; historical half-life figures in `13_` have false precision and no source.
6. **(Medium)** "Aristotle" title misdirection in `02b` — invokes the philosopher, delivers a Google HR study.
7. **(Medium)** ISBSG team-size claim laundered — merges peer-reviewed Rodríguez with unreviewed Putnam into one citation in the DRAFT.
8. **(Low)** `HANDOFF_claude_code.md` stale and would regenerate fixed problems; DRAFT buries claims under provenance scaffolding and cross-file redundancy.

---

## Prioritized top-fixes (repo-wide)

The single highest-leverage action is **propagation**: apply the synthesis-level retractions back to the READMEs, the numbered research files (`00`/`01`/`03`/`04`/`06`/`13`), and the gap maps — and stop marking sweeps "done" before verifying them.

1. **Fix the CTO `README.md` self-contradiction (lines 89–91)** so the "argument in one pass" matches the retirements at lines 5–17. (Highest single-file risk.)
2. **Remove the false "✅ SWEEP EXECUTED" status** in the CTO `AUDIENCE_DERIVATION_AUDIT.md` / TODO T3 until the README and `00_RESEARCH_CONTEXT.md` are actually reconciled. A false "done" is more dangerous than an open TODO.
3. **Resolve the Software Developer "62%" collision** — separate burnout-62% from imposter-62%, correct the AMA attribution in `05_RESEARCH` line 241 (AMA's burnout figure is 41.9%; the 62% is Medscape), and reconcile the dual-sourced 52.7% (Clance/ResearchGate vs. Guenes et al./ICSE).
4. **Demote the CHAOS Report from load-bearing to illustrative** in Software Industry `01_`/`02_`/`13_`, as the track's own `08_`/R1/R2 already instruct; restate file `04`'s keystone from "no stable craft" to "the credited skill layer is unstable; the durable layer is uncredited."
5. **Reconcile the load-bearing research-file contradictions**: Software Developer `03_RESEARCH` line 43 ("not an organizational design flaw") and `01_` line 23 ("origin of the ~50% reversion") against the structural thesis; Software Developer `06_RESEARCH` heading "Accurate Self-Assessment" and the strong-causal body (≈ 110–120).
6. **Either populate or clearly quarantine the falsification stubs** — Software Industry `14_RESEARCH_success_exceptions.md` and CTO `16_RESEARCH_success_cases.md` — and remove the pre-classification of unseen cases as `[CONTEXT/LUCK]`, which is the confirmation-bias tell R2 flagged.
7. **Finish the CTO citation appendix** (still "In progress"); verify or visibly down-rate the load-bearing economic figures (`AX-COMPRESSION`, `AX-VPENG-TIMELINE`) currently resting on content-site sourcing.
8. **Trim redundancy and meta-scaffolding** repo-wide; bring the CTO and Software Developer academic drafts within their stated word ceilings (both run ~2x).
9. **Fix smaller integrity items**: the `02b` "Aristotle" title misdirection; the laundered ISBSG team-size citation; the unsourced "NASA SEL" attribution in Software Industry `01_`; remove or date-stamp the stale `HANDOFF_claude_code.md`.

---

## Scope caveat — internal vs. external citation verification

This audit was primarily an **internal-consistency** check: whether numbers, sources, and quotes match across files within and between the three tracks, and whether the syntheses and derived drafts faithfully represent the underlying research.

**External verification was performed only for the Software Industry track's checkable book material** — the Brooks (*Mythical Man-Month*) quotes, the Sackman/Erikson/Grant (1968) origin of the 10x claim, and Google's Project Aristotle were confirmed against primary/secondary sources, and all verified accurately.

The economic, psychological, and labor-market statistics in the **CTO and Software Developer tracks were not independently re-verified against external primary sources.** Where those figures are flagged here as dubious, fabricated, or misattributed, that finding rests either on the tracks' own citation appendices (which already flag most of them as unverified) or on internal contradictions between files. A full external citation audit of those two tracks — tracing each statistic to its named primary source and confirming the number and attribution — remains outstanding and is recommended before any of this material is published or cited. That the corpora's own appendices already flag so many figures as unverified is itself one of the central findings of this review.
