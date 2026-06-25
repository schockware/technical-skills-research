# TODO / Backlog — CTO Area

Tracked open items that span sessions. Each carries enough context to resume cold. Worked items move to a `## Done` section with the commit that closed them, so this file + `git log` are the running record.

---

## Open

### T1 — `08_DRAFT_skills_divergence_thesis.md` obsolescence pass ✅ DONE (2026-06-25, commit below)
**Type:** corpus hygiene · **Priority:** medium (do before any public fork; not blocking synthesis increments)
**Resolution:** Demote-in-place (option a). Added a SUPERSEDED-AS-BUILD-TARGET banner to `08_DRAFT` (with the "discoveries kept changing our assumptions" framing + the "irrational" retirement called out in its own title); fixed the ~5 stale "lead/current/spine" framings (`README` ×2, `CTO_RESEARCH_MAP`, `DRAFT_GAP_MAP` ×2 — the latter marked largely-fulfilled since `DRAFT_SYNTHESIS` is now the clean version it was planning toward). Left the ~15 content-source/anchor/provenance references intact (they still accurately cite `08_DRAFT` as the *source* of material, not the build target). Verified: zero stale lead framings remain. **Original task text retained below for the record.**

---
*(original task, now closed:)*

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

**Fed by T4 (cultural expectations of intelligent people).** T4 supplies the *where's-the-line* framework — the doctor thought-experiment ("surgery + colonoscopies + taxes + drive an 18-wheeler + launch rockets — where does it cross into absurd?") that shows the reasonable/absurd line is *culturally drawn, not capacity-drawn.* If T4 holds, T2's answer sharpens: the irrationality isn't in the CTO demand per se, but in the **cultural permission** that lets us pile incompatible demands on engineers while the same list for a doctor is self-evidently absurd. T4 maps the line; T2 locates the CTO on it. See T4.

**Possible home:** a new research file (`18_RESEARCH_expectation_irrationality.md`) once researched; may then feed a `DRAFT_SYNTHESIS` §3.5 or sharpen §3. Do NOT fold into the draft until researched + adversarially checked.

---

### T3 — Propagation sweep (pre-publication) ✅ DONE (2026-06-25, commit below)
**Type:** corpus hygiene · **Priority:** low now, **required before public fork**
**Resolution:** Swept every recurring figure across the corpus for (a) cross-file agreement and (b) match to the appendix-verified value. **Two logged-but-unpropagated corrections found and closed:** (1) the **78% Index figure** still in its old "founding CTOs at seed" form in `01_ARTIFACT` + `05_FULLTEXT` (the appendix had flagged these exact files for fix; `00` got done, these didn't) → corrected to "founding CTO *or* technical CEO, 210-company dataset." (2) the **fabricated 2.5yr tenure** still asserted in `EVALUATIONS/14_PROMPT` + `15_SPEC` (the superseded quiz) → strike-flagged with retraction pointer (not rewritten, since the quiz is superseded). **Confirmed consistent, no drift:** 50% / n≈30k, 8–15yr, 18–24mo, 4–6:1, $1.1M, 35yr — each appears across many files and all agree + match the appendix. **Lesson:** a correction logged in the appendix is not a correction applied — propagation must be verified, not assumed. Recommend re-running this sweep once more right before any public fork.

---
*(original task, now closed:)*

Surfaced by the "four letters → three letters" catch (commit `6452990`): factual micro-errors (counts, dates, figures) propagate silently through incremental docs because they're grammatically/semantically plausible. Do a dedicated sweep: grep every number / count / date that appears in multiple files and confirm (a) they agree with each other, and (b) they match their cited source. Known prior catches of this class: 2.5yr tenure (fabricated), CMO "40 months" (wrong), Index 78% (rephrased), "four letters." Assume more remain. **Pair with T1** (same kind of cross-file pass).

---

### T4 — Cultural expectations surrounding intelligent people (separate study; feeds T2)
**Type:** thesis-level research, *separate study* · **Priority:** high (it may resolve where the "irrational" claim legitimately lives)

**The question, stated as the author framed it:**
> *Can we expect a doctor to learn how to perform surgery, perform colonoscopies, do taxes, file insurance claims, drive an 18-wheeler, and launch rockets? Where does it cross the line of irrationality?*

**Why this is the crux, not just an illustration.** Everyone *instantly* knows the doctor list is absurd — no argument required. That immediacy is the data: it shows the line between "reasonable to demand of a smart person" and "absurd" is **real, sharp, and culturally drawn — not capacity-drawn.** Each item on the doctor list is individually learnable; the absurdity isn't difficulty or even quantity. It's that the culture *refuses permission* to pile incompatible demands on a doctor — while it *grants* that permission for engineers/CTOs ("smart people should be able to learn anything"). **The irrationality T2 is hunting may not be in the CTO role at all — it may be in the cultural permission structure that lets us make of *some* intelligent people demands we'd laugh out of the room for others.**

**This is the locus R1 never tested — and may recover the retired word.** R3 retired "irrational" because the *role design* is a rational budget equilibrium (`§4`). But "the culture irrationally extends 'learn anything' permission to engineers and not to doctors, with no principled basis for where the line falls" is a claim about **belief**, not org design — and R1's role-design rebuttal does not touch it. *(Author's own note: the original "irrational" claim was made "because we hadn't filled out all the spaces yet" — i.e., before the role-design locus was tested and found rational. T4 proposes the irrationality was real but **mislocated**: it lives in the expectation/permission, not the role.)*

**The core research question — locate the line.** Why does the culture grant the "smart → learn anything" permission for technical roles but withhold it for medicine, law, aviation, etc.? Candidate factors to test:
- **Visible licensure / external credential** — medicine and aviation have hard licenses that *define* scope; engineering's identity is organizationally constructed (`00_AXES_SUMMARY` Axis 5, *unlicensed identity*). Does the *absence* of a license remove the cultural brake on scope-piling?
- **The IT-as-monolith folk model** — laypeople (and investors, CEOs, recruiters) may perceive "technical" as one undifferentiated competence ("he's technical, he can figure it out"), where they perceive medicine as obviously partitioned. The fungibility assumption (`02_MMM_fungibility_assumption`) at the cultural level.
- **The generalist-genius / "gifted kid" myth** — a broader cultural script that intelligence is *general-purpose* and infinitely transferable. (Gifted-kid burnout, polymath idealization, "10x engineer" lore.)
- **Domain *visibility of failure*** — a doctor's overreach kills someone visibly; a CTO's overreach decays a team slowly (`15_` M5). Does invisible failure *permit* the demand because the cost isn't legible?

**The diagnostic that ties it to T2:** the doctor list works because it's *over* the line. The T2 question ("do you expect a CTO to transition all 3 modes?") works because it's *near* the line — close enough that people *do* say yes, but on reflection wouldn't defend it. T4 maps the line; T2 locates the CTO on it. Together they answer: **is the irrationality in the demand, or in the cultural license to make it?**

**The strongest form of the "irrational" claim — collective akrasia (author, 2026-06-25):** the Mythical Man-Month is *simultaneously accepted and ignored* — the field agrees Brooks was right (adding people to a late project makes it later; people aren't fungible) and then staffs, scales, and writes JDs as if he were wrong. **Knowing-and-acting-against is irrational by the field's own lights** — the same structure as *"smoking is known to cause cancer and people still smoke."* This is the form of "irrational" that **R1 cannot rebut**, and it is why it succeeds where the role-design claim failed:
- R1 killed "the role is irrational" because the role *might* be an efficient bet (no demonstrated contradiction — just a hard tradeoff).
- R1 **cannot** kill "the field holds a belief it has itself disproven, and acts against it anyway," because that is a *demonstrated contradiction in the field's own commitments*, not a value judgment on a design. It's `RISK-INVESTOR-CAUSAL`-proof and value-judgment-proof: you're not calling anyone stupid, you're pointing at a belief-action gap the field already admits on one side.
- **The akrasia framing is the bridge from "under-resourced" (R3's retreat) back to a defensible "irrational"** — relocated from the *structure* to the *collective belief-action gap*. The smoking analogy is the public-facing handle for it.
- **Sibling-synthesis hook:** the Software Industry thread already has the MMM material (`01`–`02b`, fungibility) and the "accepted-and-ignored" observation. When that thread revisits cultural expectations, **this akrasia framing is the candidate spine for the sibling synthesis** — MMM-is-known-and-ignored as the industry-scale instance of the same belief-action gap T4 finds at the cultural level and §3 finds at the attribution level. Three scales, one irrationality: *the field knows better and does it anyway.*
- **Discipline (carry it):** "akrasia" is still a claim that needs the evidence both halves are real — (a) the field genuinely *accepts* MMM/non-fungibility (citable: it's canonical), and (b) it genuinely *acts against* it (the JD, the headcount-as-capability move, the composite CTO). Both are plausibly documentable; neither is yet *measured*. State as the strongest *available* form, falsifiable: if the field doesn't actually hold the belief (e.g., MMM is lip-service nobody really endorses), the akrasia claim weakens to "the field is just wrong," which is less interesting and less defensible.

**Scope:** explicitly a **separate study** (like Software Industry/Developer), because "cultural expectations of intelligent people" is its own literature (intelligence-as-general-purpose belief, credentialism, fungibility folk-models, gifted-kid/polymath scripts). Spin up as its own area when researched. **Carry the corpus discipline:** absence≠evidence, the doctor example is a *thought experiment that locates the question*, not proof of the answer; the actual claim needs the literature.

**Connection map:**
- **→ T2:** primary. T4 supplies the *where's-the-line* framework; T2 applies it to the CTO and tests the reflection-gap.
- **↔ Software Industry thread:** this *is* the "human capacity issue disguised as 'smart people should learn everything'" through-line (`R3_STEELMAN` / `HANDOFF`), attacked from the belief side. Strong cross-reference; may belong adjacent to that area.
- **↔ `00_AXES_SUMMARY` Axis 5 (unlicensed identity) + fungibility root cause** — both are structural; T4 asks whether they have a *cultural* parent (the permission structure).

**Possible home:** a new sibling area `Cultural Expectations/` (or similar) once researched; until then, this entry + a pointer from T2.

---

## Done

*(none yet — items move here with their closing commit hash)*
