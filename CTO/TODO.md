# TODO / Backlog — CTO Area

Tracked open items that span sessions. Each carries enough context to resume cold. Worked items move to a `## Done` section with the commit that closed them, so this file + `git log` are the running record.

---

## Open

### T1 — `08_DRAFT_skills_divergence_thesis.md` obsolescence pass
**Type:** corpus hygiene · **Priority:** medium (do before any public fork; not blocking synthesis increments)

`08_DRAFT` was the *lead thesis* through the incremental research phase. It has since been **superseded as the build target** by `R3_STEELMAN` + `DRAFT_SYNTHESIS` (the public draft is built on R3, explicitly *not* on `08_DRAFT`'s rhetorical high points). But `08_DRAFT` still:
- carries de-escalated/retired claims in their *original strong form* (e.g. the rhetoric R3's must-not-claim table forbids);
- is referenced as "lead draft / current spine" in **~20 files** (README, CONVENTIONS, CTO_RESEARCH_MAP, DRAFT_GAP_MAP, the research files, the R-track, plus Software Developer files) — those pointers are now stale.

**The task:** decide `08_DRAFT`'s status and apply it consistently. Options:
- **(a) Demote-in-place** — add a SUPERSEDED banner (like we did for the old quiz SPEC + `09_` line 43): "prior failure-first framing; the defensible form is `R3_STEELMAN`, the public draft is `DRAFT_SYNTHESIS`." Keep as historical record. Update the ~20 "lead/spine" references to point at R3/DRAFT_SYNTHESIS.
- **(b) Retire** — move to an `_archive/` or annotate heavily; riskier (it's still cited as the source of real material like §1–§3 content).
- **Recommended: (a).** It's the pattern we've used elsewhere and it preserves provenance.

**Scope note:** this is a ~20-file reference sweep, not a one-file edit. Pairs naturally with the **propagation sweep** already on the backlog (numbers/dates/counts agreeing across files) — do them in one pass.

**Watch for:** don't break the §1–§3 lineage — `DRAFT_SYNTHESIS` material *derives from* `08_DRAFT` content (transformation model, etc.), so the banner must say "superseded as the *build target*," not "wrong."

---

### T2 — Is the irrationality actually in the *cultural expectation*, not the role design?
**Type:** thesis-level research question · **Priority:** high (may relocate the framework's core claim)

**The prompt (verbatim):** *"The dysfunction is driving a cultural misunderstanding of CTO failure. We need to explore if that is where the irrationality really is. Going into a company, do you expect a CTO to transition all 3 modes?"*

**Originating firsthand observation (author, disclosed 2026-06-25):** the study began from the author's personal knowledge of **four CTOs who could not make the transition — and whose organizations expected them to transition *or step down on their own.*** That second clause is the demand-side pattern T2 names: the organizations located the burden in the *individual* (transform-or-self-eliminate) and never asked whether the demand itself was coherent. This is `§3` misattribution observed in the wild, and it is the literal seed of T2's question. **Discipline:** it is n=4, author-selected, failure-only — the *motivating observation, not evidence* (recorded as a disclosed bias in `R2` Bias 8; the load-bearing evidence is independent of these four). T2's job is to test whether the *expectation* pattern these four exhibit generalizes — not to treat the four as proof that it does.

**Why this matters — it may recover the word the steelman retired.** `R3` deliberately downgraded "irrational" → "under-resourced," because `R1`/`R2` showed the *role design* may be a rational equilibrium (efficient under budget constraint; §4 accidental-concession). That retirement is correct **for the locus the corpus tested: the structure.** But this note proposes a *different locus*: the irrationality may live not in the role's design but in the **expectation held by the people who judge the CTO** — the CEO, board, investors, recruiters, the CTO themselves.

The diagnostic question — *"do you actually expect one person to transition all three modes?"* — splits the answer in a revealing way:
- If the honest answer is **"no, of course not"** → then the expectation the CTO is *evaluated against* is one nobody actually holds on reflection. That gap — judged against a standard no one would defend out loud — is a candidate for where the *irrationality* genuinely sits. Not "the role is impossible" (R1 killed that) but "**we evaluate CTOs against an expectation we don't actually endorse.**"
- If the honest answer is **"yes, we do expect it"** → then the expectation is sincerely held *and* (per §1–§4) exceeds one person's reach — which is irrationality in the believer, not the budget. Either branch relocates the irrationality from structure to belief.

**Why this is potentially stronger than the retired claim.** "The role is irrational" was attackable (the equilibrium can be efficient). "**The cultural expectation of CTO success is irrational — it judges against a standard that is either unendorsed-on-reflection or sincerely-held-but-impossible**" is harder to demolish, because it's a claim about *belief and attribution* (the corpus's most defensible ground — see §3 misattribution), not about org design. It may be the version of "irrational" that survives R1.

**Connection to existing work:**
- This is the **demand-side** complement to §3 (`DRAFT_SYNTHESIS`). §3 says the *harm* is misattribution ("he's not scaling"). T2 asks: misattribution *against what expectation?* — and proposes the expectation itself is the irrational object.
- `15_RESEARCH` (evaluation isolation) is adjacent — the CTO can't be validly evaluated, AND (T2) the thing they're evaluated *against* may be incoherent. Two failures stacked.
- `AX-NO-TRIPLE-MODE` (`16_`) is the latent evidence: if no documented CTO traverses all three modes as continuous tenure, then *expecting* it is expecting the unobserved — which sharpens "do you actually expect it?"

**The research to run (independent chat, adversarial discipline):**
1. **The expectation audit.** What do CEOs/boards/investors/recruiters *say* they expect of a CTO across stages — and does it implicitly demand all three modes? (Job descriptions, diligence questions, board-review criteria, "why we let our CTO go" post-mortems.) The JD is the artifact: does "CTO" JD language demand hands-on + people + strategic at once?
2. **The reflection gap.** Is there evidence the expectation collapses under direct questioning — i.e., people *judge* against the composite but, asked plainly, *don't endorse* it? (This is the irrationality-in-belief test.)
3. **Locate the irrationality precisely.** Structure (rational-under-budget, per §4) vs. expectation/attribution (candidate irrational locus). State which, and stake a falsifier.

**Caution (carry the corpus discipline):** this must NOT become a backdoor to re-assert "the role is irrational" after R3 retired it. The claim has to be about the *expectation/attribution*, cleanly separated from the role-design claim §4 conceded. If it can't be cleanly separated, it doesn't survive — flag that honestly.

**Possible home:** a new research file (`18_RESEARCH_expectation_irrationality.md`) once researched; may then feed a `DRAFT_SYNTHESIS` §3.5 or sharpen §3. Do NOT fold into the draft until researched + adversarially checked.

---

### T3 — Propagation sweep (pre-publication)
**Type:** corpus hygiene · **Priority:** low now, **required before public fork**

Surfaced by the "four letters → three letters" catch (commit `6452990`): factual micro-errors (counts, dates, figures) propagate silently through incremental docs because they're grammatically/semantically plausible. Do a dedicated sweep: grep every number / count / date that appears in multiple files and confirm (a) they agree with each other, and (b) they match their cited source. Known prior catches of this class: 2.5yr tenure (fabricated), CMO "40 months" (wrong), Index 78% (rephrased), "four letters." Assume more remain. **Pair with T1** (same kind of cross-file pass).

---

## Done

*(none yet — items move here with their closing commit hash)*
