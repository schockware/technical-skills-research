# Audience Derivation Audit — the "after all five" post-pass

**Date:** 2026-06-25
**Auditing:** the five derived drafts in `CTO/derived/` against the spine `CTO/DRAFT_SYNTHESIS.md`.
**Method:** the post-pass specified in `AUDIENCE_DERIVATION_PROMPTS.md` §"After all five" — every derived claim must trace to a spine section (§0–§5); a restored retired claim (must-not-claim left column, or anything §5's concessions retired) is a defect; grep each draft for the must-not-claim phrases and confirm every hit is a *denial*, not an assertion. One independent auditor per draft, each given the spine, the must-not-claim table, the audience brief, and that audience's "Never" rules.

## Verdict

**No regressions found in any of the five.** Every must-not-claim phrase that appears does so as a denial, a demotion, a reproduced table row, or the objection's own quoted words — never as an assertion. Every substantive claim traces to a spine section or a brief-authorized source file (`R4`, `R2`, `12_RESEARCH`, `17_PREMISES`). The two highest-risk traps — the investor-causal claim (investors draft) and a unicorn-hiring recipe / three-distinct-modes table (recruiters draft) — are both handled with explicit guardrails.

Two items are worth a second look, both **scope/style, not rigor** — see "Items to consider" below. Neither is a defect under the post-pass definition.

| Draft | Verdict | Notes |
|---|---|---|
| `cto_eng_leaders` | Clean (1 style nit) | One rhetorical line sits near the retired ratio; stays qualitative. |
| `founders_ceos` | Clean | Actively argues *against* the pre-emptive-replacement trap. |
| `investors_board` | Clean | Highest-risk for investor-causal; explicit denial + "co-author/consistent-with" throughout. |
| `academic` | Clean (1 scope nit) | Rigor intact; prose runs well over the brief's length ceiling. |
| `recruiters` | Clean | Per-stage hiring table and ~50% number both correctly guarded. |

## Per-draft detail

### `cto_eng_leaders` — clean, one style nit
Every claim traces (misattribution quotes → §3a; track-split → §1; ~50% "even when trained" → §2a; identity-not-skill → §2b; three cushions → §2c; "four roles when affordable" + CRO → §4; "can't resource what you won't name" → §3c; "pattern not prophecy" → §5 tone). Borrowed-evidence boundary held ("peer-reviewed — in founders; the CTO is our extension"). Falsifiers correctly dropped, honest tone kept. All three "Never" rules honored, including §3c's "naming is necessary-but-not-sufficient" (stated explicitly).
- **Style nit:** "**You were doing a four-person job at a one-person price.**" The four-role count traces to §4, and no ratio or dollar figure is asserted, so it does **not** restore the retired "~4–6:1 as a number." It is simply the closest the draft comes to the line — kept here only so a future editor knows it was checked and cleared.

### `founders_ceos` — clean
All claims trace (diagnostic sentence + "can't resource what you won't name" → §3c; loop + 12–24mo gap, correctly hedged → §3b; cushions → §2c; accidental concession → §4; the three honest limits → §5 concessions 1/3/5). "Irrational" appears only as a denial ("not claiming… your company is badly run"). No hard numbers, no kind-claim, no causal-investor.
- **Trap handled correctly:** the audience "Never" rule (don't imply pre-emptive firing) is not just avoided but inverted — "the answer is *not* to pre-emptively fire or replace faster. That's the loop running *harder*"; "Don't fire faster; resource earlier."

### `investors_board` — clean (highest-risk draft)
The investor-causal claim is the sharpest trap, and it is handled with an explicit denial ("We are not claiming investors *caused* the failures") plus consistent "signal / co-author / consistent-with / select-for" framing at every later touch. The $1.1M figure is named only to be declared number-independent; the revealed-preference "split-when-affordable" argument carries the load (per §4 + §5 concession 4). Reversion number kept as boundary-difficulty, not a CTO-specific rate. F2 foregrounded as the actionable portfolio experiment, F1 kept as central/unrun — both within the brief's "one or two falsifiers."
- **Nit (not a defect):** the 12–24-month strategic-gap figure is leaned on three times; it carries its "practitioner-sourced, not primary-verified" hedge on first use, matching §3b. A future edit should keep that hedge attached.

### `academic` — clean on rigor, one scope nit
The closest-to-spine version: keeps §5 in full, reproduces the must-not-claim table (legitimately), and expands the research agenda from authorized sources (`R4` U1–U5/Q1–Q7, `R2` Bias 8, `TODO` T2/T4). Framework-vs-finding discipline intact throughout (established items 1–3 vs. the falsifiable attribution reframe). The bias disclosure (n≈4 firsthand origin) is foregrounded as a credibility asset, per the brief. Critically, the added open-question material does **not** smuggle a retired claim back as established: U4 ("'irrational' is normative"), T2 (cultural-expectation), and T4 (collective akrasia) each carry their discipline guard and are framed as open/candidate, with an explicit note that they "must not become a backdoor to re-assert the 'irrational' claim concession 3 retired." Every "irrational" occurrence is a denial, the objection's words, or the §5-concession-3 open-question parenthetical.
- **Scope nit:** prose runs to ~5,500 words by raw `wc -w` against a brief ceiling of 1,800–3,000. The count is inflated by four reproduced tables and markdown/anchor tokens, and the brief explicitly licenses this version to "run longer" and "expand the research agenda" — but the prose body is still materially above the stated ceiling. Flagged for a length-trim decision; not a rigor issue.

### `recruiters` — clean
All claims trace (composite-JD → §1 + Audience Map; ~50% reversion, correctly bounded → §2a; identity change → §2b; CRO template → §1/§4; "budget compromise" → §4; misattribution + "can't write a req for a transition you won't name" → §3; concession-2 reassurance → §5). The authorized `12_RESEARCH` "mediocre-at-both" point is used within bounds; the "~15–20 engineers" threshold traces to `12_RESEARCH`.
- **Both risk zones guarded:** (1) the unicorn-recipe trap is refused explicitly ("no recipe here for finding someone who *can* do all three… That's the unicorn hunt"); (2) the Builder/Multiplier/Strategist hiring table presents three *operational profiles for which req to write at which stage* — a different person per mode, the opposite of a unicorn recipe — and anchors only the corroborated Builder→Multiplier seam, so it does not restore "three modes diverge in kind."

## Items to consider (neither is a post-pass defect)

1. **`academic` length.** ~5,500 words vs. a 1,800–3,000 ceiling. The brief licenses "longer," but a trim of the prose (the reproduced tables can stay) would bring it nearer intent. *Decision for the author — flagged, not a defect.*
2. **`cto_eng_leaders` "four-person job at a one-person price."** Stays qualitative and traces to §4; cleared. Noted only so the rhetorical proximity to the retired ratio is on record.

## Grep confirmation
A direct grep of all five drafts for the must-not-claim phrases (`irrational`, `mismatch of kind`, `diverge in kind`, `survivor-proof`, `investors caused`, `4–6:1`, `$1.1`, `three modes`, `dominated`) returns hits only as: denials, demotions ("demoted from 'survivor-proof'", "retires the earlier 'mismatch of kind'"), reproduced must-not-claim table rows (academic), the quoted objection, or a local non-role use ("that diligence reflex is not irrational" — about investor pattern-matching, a different referent, and stated as a denial). No hit is a regression.

---

## Addendum — README files contradict the must-not-claim discipline (for the other chat to fix)

> **✅ RESOLVED (2026-06-27).** The `CTO/README.md` "argument in one pass" hand-off below has been applied: step 3 is now "The under-resourced condition," the scope-vs-kind keystone is recast as most-severe-case (not "only the CTO is catastrophic"), "Confirmed" was softened to "consistent with," and "~4–6:1" is now flagged unverified/load-bearing rather than used as a number. `00_RESEARCH_CONTEXT.md` was also swept (lines 64/105/123). This addendum is retained for history; the specific items it lists are no longer open. *Remaining: the citation appendix (`07_APPENDIX`) is still partial — its load-bearing-unverified figures are now marked 🚫 NOT CITABLE rather than verified.*

*Found while wiring audience links into the root README. The five derivations are clean; the **README files** that frame them still carry the pre-retirement language the spine retired (`R3` must-not-claim table; `DRAFT_SYNTHESIS.md` §5 concessions). These are not derivation defects — they are stale framing in the index/onramp docs, which now sit one click from the disciplined drafts and contradict them. Handing off to the other Opus chat to reconcile.*

**The rule being violated** (same one the derivations were audited against): the *role* is **under-resourced, not "irrational"**; it is the **most severe case of a shared rotation, not a "mismatch of kind, uniquely the CTO"**; failure-clusters-at-boundaries is **"consistent with," not a confirmed prediction**; **"~4–6:1" is not used as a number**. `CTO/README.md` lines 5–17 already state this retirement note correctly — the body below it does not yet comply.

### Root `README.md`
- **Line 21** (CTO scope-row): *"must traverse all three 'operating modes' … — **sequentially incompatible skill sets** — pre-scale, unsupported."* — **"incompatible skill sets" is the wrong claim**, not just an overstatement. We have research showing the skill sets are **not inherently incompatible**; the real claim is that the IC→EM→C transitions are **clearly-defined, distinct skill sets** and the industry gives **no on-the-job runway to learn them naturally**. ✅ **Already fixed in root README** (2026-06-25) to: *"must cross the IC→EM→C transitions — each a clearly-defined, distinct skill set — pre-scale and unsupported. The skill sets aren't inherently incompatible; the industry just gives no chance to learn them naturally on the job."*

### ⚠️ Bigger finding: "incompatible" is a corpus-wide claim-level defect, not a README wording nit

The word **"incompatible"** (and "sequentially incompatible") is woven through the corpus and **asserts more than the evidence supports.** The corrected claim is: *the IC→EM→C skill sets are **distinct and clearly defined**, and **research indicates they are not inherently incompatible** — the failure is that the industry provides **no opportunity to learn them naturally on the job** (no runway, compressed timeline), not that the skills cannot coexist in one person.*

This is **already the rigorous corpus's own stated direction**, which is why this is a correction to *propagate*, not a new position to argue:
- The spine `DRAFT_SYNTHESIS.md` **already avoids "incompatible"** — it says "different work," "discontinuity," "identity-gated," "under-resourced." The retired-claim discipline already pushed this out of the spine.
- `R2_FALSIFICATION_and_bias_audit.md` line 184 (**Bias 1, severity High**) already prescribes the fix: *"Commission a 'why the modes might **not** be incompatible' file."* The user's instruction is that correction landing.
- "Incompatible" is also load-bearing for **already-retired** claims — it props up "dominated demand," "irrational in the precise sense," "kind mismatch," and "a track the industry declared **uncrossable**." Those are exactly the phrases the `R3` must-not-claim table retired. So fixing "incompatible" and finishing the "irrational"/"kind" retirement are the **same edit** in many spots.

**Handling rule for the other chat:** this is a **claim rewrite, not a find-replace.** Do **not** blanket-swap "incompatible" → "distinct." Three cases:
1. **Describing the skill sets themselves** → rewrite to "distinct / clearly-defined skill sets that the industry gives no on-the-job runway to learn." (The skills *can* coexist; the structure denies the learning opportunity.)
2. **"the industry split the tracks because the skills are incompatible"** → soften to "…because the two are **different work** / **diverge** enough to require choosing." (The split proves *divergence*, not *incompatibility*.)
3. **"incompatible" used to prop a retired claim** ("dominated," "irrational," "kind mismatch," "uncrossable") → these need the full retirement treatment, not just the word swap (see the must-not-claim items above).

> **✅ SWEEP EXECUTED (2026-06-25, commit below).** The disconfirming research is written ([`18_RESEARCH_modes_not_incompatible.md`](18_RESEARCH_modes_not_incompatible.md), commissioned by `R2` Bias 1) and **confirms the fix is mandatory**: the engineer/manager pendulum + skill-transfer evidence show the modes are *distinct but can coexist* (positive transfer, not interference). **CTO area: swept** — all index/onramp docs + the case-3 retired-claim props (`00_CONTEXT` ×5, `08_DRAFT` 110/152, `09_` 58/180/231, `12_` 164, `14_` 146, `05_FULLTEXT` 304/335, root + CTO + CROSS_REFERENCES indexes) rewritten per the 3-case rule. **Software Industry/Developer: flagged, not rewritten** — those areas have their own R-tracks; a reconciliation pointer was added to both their READMEs directing the fix to their next revision (their `08_…:217` already poses it correctly as the open question, which `18_RESEARCH` now answers). *Timeline*-incompatible uses left as-is (different sense). Original inventory retained below for the record.

**Inventory of "incompatible" occurrences (grep `-i incompatible`, 2026-06-25)** — triaged by the three cases above:

- **Index / onramp (highest priority — user-facing):**
  - `README.md` (root) line 3 ("demand incompatible skill sets"), line 21 ✅ fixed.
  - `CTO/README.md` line 88 ("It already declared them incompatible") — case 2 (divergence, not incompatibility).
  - `Software Industry/README.md` line 5; `Software Developer/README.md` line 5 — case 1/2.
- **CTO rigorous-adjacent:**
  - `CTO/00_RESEARCH_CONTEXT.md` lines 13, 15, 50, 52, 100 — multiple; mix of case 1 and case 2 ("formally recognized as incompatible by splitting…" is case 2).
  - `CTO/09_RESEARCH_cross_role_pattern.md` lines 58, 115, 180, 231 — **mostly case 3** (these are the "irrational/dominated/uncrossable" props).
  - `CTO/12_RESEARCH_rational_solutions.md` line 164 — case 3 ("irrational composite … incompatible expectations").
  - `CTO/14_RESEARCH_domain_training_effectiveness.md` lines 55, 73, 110, 112, 146 — **note:** several here mean *timeline* incompatible ("training timeline incompatible with growth"), which is **fine** (different sense — leave). Line 146 ("sequentially incompatible … actively interfere") is case 1/3 and needs rewrite.
  - `CTO/05_FULLTEXT_working_document.md` lines 304, 331, 335; `CTO/08_DRAFT_skills_divergence_thesis.md` lines 110, 152 — case 3 (the original "dominated/kind-mismatch" home).
- **Software Industry / Developer corpus:** `Software Industry/01_…` lines 13, 135, 158, 170; `03_…` 181; `04_…` 185; `06_…` 23, 155; `13_…` 21, 114, 166. `Software Developer/01_…` 6, 90; `06_…` 164; `08_…` 203, 217 (217 is *already* the open question "are they genuinely incompatible, or just different in degree?" — good anchor); `README.md` 5.
- **Already-correct / leave:** `CTO/R2_…` line 184 (names the fix), `Software Developer/08_…` line 217 (poses it as the open question), and the `CTO/14_…` *timeline*-incompatible uses.

**The other chat should apply the corrected framing wherever case 1/2/3 applies, treat `R2` Bias 1 as the governing rationale, and reconcile — or explicitly mark as superseded — the older `08_DRAFT`/`09`–`16` sources that still assert it as load-bearing.**
- **Line 23**: *"the natural objection **'if it's so irrational, why only the CTO?'**"* — restates both retired phrasings ("irrational" + "only the CTO"). The denial it sets up ("it's *not* only the CTO") is fine, but the premise is stale. → Suggest: "'if it's so hard, why is the CTO the flagship case?' with 'because it's where the shared pattern is most severe and most visible — not because it's unique.'"

### `CTO/README.md` — ✅ FIXED (2026-06-27)
The top-of-file retirement note (lines 5–17) is correct and strong. The body has now been brought into line with it (the items below are retained as the record of what was changed):
- **Line 89** ("The argument in one pass", step 3): *"**Irrational condition** … §3.2 **scope-vs-kind keystone (why only the CTO is catastrophic)**."* — asserts "Irrational" as a step heading and "scope-vs-kind / only the CTO" as a keystone, both retired. (This is the sharpest contradiction with the same file's own lines 5–17.) → Reframe step 3 to "Under-resourced condition" and recast the keystone as "most-severe-case (the IC/management split sharpens the rotation), not unique-in-kind."
- **Line 90** (step 4): *"failure **clusters at the transformations** … **Confirmed** by Greiner, Carta/Crunchbase, Kruze."* — states the boundary-clustering *prediction* as confirmed; spine carries it as "consistent with difficulty concentrating at company-stage transitions" (confounded with funding-round stress, `R1` C5). → Soften "Confirmed" → "consistent with."
- **Line 91** (step 5): *"**~4–6:1 cash compression** makes it optimal …"* — uses the retired ratio as a load-bearing number (§5 concession 4). → Recast qualitatively: "splitting the composite is unaffordable pre-Series-A."
- **Line 87** (step 1) and **line 99**: line 99 *already* self-labels the old "irrational composite" framing as superseded ("see retirement note above") — good model for how the others should be hedged or rewritten. Line 87's "transformation / offload+acquire" is consistent with the spine (§2b) and needs no change.

**Scope note for the fix:** the *retirement note and line 99 are already correct* — the work is to propagate that same discipline into root-README lines 21/23 and CTO-README lines 89–91. No derivation file needs editing.

---

*Audited against `DRAFT_SYNTHESIS.md` (spine §0–§5) per the `AUDIENCE_DERIVATION_PROMPTS.md` "after all five" protocol. Five independent per-draft auditors, one shared spine + must-not-claim discipline. README-contradiction addendum added 2026-06-25 for handoff.*
