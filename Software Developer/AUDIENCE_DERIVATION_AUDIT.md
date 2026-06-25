# Audience Derivation Audit — the "after all five" post-pass (dev-ladder tier)

**Date:** 2026-06-25
**Auditing:** the five derived drafts in `Software Developer/derived/` against the spine `Software Developer/DRAFT_SYNTHESIS.md`.
**Method:** the post-pass specified in `AUDIENCE_DERIVATION_PROMPTS.md` §"After all five" — every derived claim must trace to a spine section (§0–§6) or a brief-authorized source file; a restored retired claim (do-not-build-on left column, or anything the spine's §6 concessions / `R3`'s do-not-build-on table retired) is a defect; grep each draft for the do-not-build-on phrases and confirm every hit is a *denial*, not an assertion. This is the dev-ladder sibling of `../CTO/AUDIENCE_DERIVATION_AUDIT.md`.

**The eight do-not-build-on phrases grepped (case-insensitive, plus the distinctiveness-overclaim family):**
`rotation at every rung` · `incompatible` · `closes/close/closing the null` · `purest case` · `larger than reversion` · `accurate self-assessment` · `prior expertise is a liability` · `irrational` — and the family `uniquely/distinctively broken`, `proves software`, `closes the measurement[-artifact null]`.

## Verdict

**No regressions found in any of the five.** Every do-not-build-on phrase that appears does so as a denial, a demotion, a reproduced/retracted table row, or the objection's own quoted words — never as an assertion. Every substantive claim traces to a spine section or a brief-authorized source (`R3`, `R4`, `R2`, `07_RESEARCH`, `04_RESEARCH`). The single highest-risk trap at this tier — restoring the reversion number as *closing the measurement-artifact null / proving software distinctiveness* (concession 8 / `R1` Claim B) — is handled correctly in all five: every draft that cites the ~50% number explicitly flags it as a **cross-industry** rate (boundary-difficulty, not distinctiveness) and routes distinctiveness to the missing-cushions comparison.

| Draft | Verdict | Notes |
|---|---|---|
| `engineers` | Clean | No do-not-build-on hits at all. Reversion held as boundary-difficulty ("rate holds even when trained"); plateau carried as possibility, not "purest case." |
| `engineering_managers` | Clean | No do-not-build-on hits. Cross-industry caveat explicit; F3 carried as the EM's own experiment; "good management does not eliminate the ~50%" honest-promise guard intact. |
| `founders_ceos` | Clean | "Irrational" appears only as a denial ("not 'your company is run irrationally'… 'Under-cushioned,' not 'irrational'"). Pre-emptive-replacement trap inverted, not just avoided. |
| `academic` | Clean (1 scope note) | Closest-to-spine version: reproduces the retired phrases legitimately as retractions (concessions 8 & 9 foregrounded). Rigor intact; runs long (see note). |
| `recruiters` | Clean | Both "incompatible" hits are explicit denials. Larson four-archetype table used as the operational core; ~50% correctly bounded as cross-industry. |

## Per-draft detail

### `engineers` — clean
No do-not-build-on phrase appears anywhere in the draft. Every claim traces (the four misattributed sentences → §4; ~50% reversion "even when trained" → §2a; identity-not-skill / surgeon anchor → §2b; structural-support-not-grit → §2c/`07_RESEARCH`; "object of the work rotates" → §1; accidental concession → §5; "pattern not prophecy" tone → §6 honest tone). Borrowed-evidence boundary held verbatim ("peer-reviewed, though in founders, not engineers; applying it to you specifically is the paper's extension, not borrowed fact" — `R1` Claim C). The Senior→Staff plateau is carried as a **possibility** for *some* people and explicitly *not* as "most plateaued Seniors washed out" (`R1` Claim D), with the chose-the-craft reframe — exactly the brief's honest note. Falsifiers (§6b) dropped, honest tone kept. No-recipe / `RISK-SURVIVORSHIP` guard explicit ("any '5 habits to make Staff' list is just the survivors mistaking their luck for a method"); reversion-isn't-failure pendulum honored.

### `engineering_managers` — clean
No do-not-build-on phrase appears. All claims trace (loud vs. quiet rotation → §1/§2; ~50% behavioral anchor → §2a; identity loss → §2b; the four org-conditions → §2c/`07_RESEARCH` with `AX-VL2023` correctly cited as peer-reviewed; misattribution / "stop writing 'not ready'" → §4; the four Monday cushions → §2c + §1 Larson; accidental concession not over-pressed). Cross-industry caveat stated plainly ("does **not** prove software is uniquely broken… distinctive is the missing cushions"). Mechanism flagged once as a founders-population extension. **F3** carried as "the experiment you're actually positioned to run," with the honest "if they don't help, that's a real finding — report it" framing — within the brief's "keep F3." Both "Never" rules honored: no guarantee-recipe (necessary-not-sufficient stated), and the ~50% is explicitly *not* claimed to be eliminated by good management ("you can change the conditions and the sentence," not the throughput limit). Pre-emptive-management-out trap explicitly refused.

### `founders_ceos` — clean
"Irrational" appears **only** as a denial: line 62 ("this is not 'your company is run irrationally'… 'Under-cushioned,' not 'irrational'") and the provenance stamp restating the same — matching §5 / `R3`. No other do-not-build-on phrase appears. Claims trace (track-split as the corroborated seam → §1; one-seam-plus-pattern discipline held, Senior→Staff "carry it as a pattern, not a measured cliff" → `R1` Claim A; ~50% behavioral → §2a with cross-industry caveat → `R1` Claim B; identity loss → §2b; the never-converging serial-replacement loop → §4b; revealed-preference / "correction is the confession" → §3c + §5; accidental concession → §5). Mechanism flagged as founders-population extension. The audience "Never" rule (don't imply pre-emptive replacement) is **inverted, not merely avoided** — "cycling people through an uncushioned rotation until one happens to fit is the broken loop. You break it by resourcing the rotation, not by managing the person." Honesty footnote leans on concessions 3/5/7 per the brief.

### `academic` — clean on rigor, one scope note
The closest-to-spine version, and by design it **reproduces the retired phrases in order to retract them** — this is the licensed use, not a regression. Every occurrence checked:
- `incompatible` (L43) → "the skills are **not** incompatible… never 'incompatible'" (corpus-wide retirement; with an honest referee note that `01_`/`06_`/`08_` still carry the retired wording, reconciliation pending — `R2` Bias 7).
- `closes the null` / `close the null` (L20, L64, L68, L165, L236) → every instance is a denial or the named retraction ("It does **not close the null**"; "concession 8 stated as load-bearing"; "Reproducing that overclaim is a regression, not a strengthening").
- `purest case` / `larger than reversion` (L137) → explicitly refused as arguing-from-silence ("cannot be 'the purest case' or 'larger than reversion' on the strength of its own invisibility"; `R1` Claim D / concession 9).
- `accurate self-assessment` (L182, L197, L236) → demoted ("corroborating, not load-bearing — and not 'accurate self-assessment'"; the strong causal version treated as substantially failed, F4).
- `irrational` (L20, L153, L157, L167, L209, L220) → denial / the U4 normative-vs-descriptive boundary ("Keep 'misattribution'; drop 'irrational'").
- `rotation at every rung` (L183, L193, L220) → reproduced as the F5 construct test and the concession-set row (`R1` Claim A), framed as imposed-lens-to-be-tested, not discovered structure.
Framework-vs-finding discipline intact throughout (established = track split §1 + reversion anchor §2 read as boundary-difficulty; framework = "rotation at every rung", the MW2018/VL2023 mechanism in-founders, the plateau hypothesis). The two new concessions (8: behavioral data does not close the measurement-artifact null; 9: plateau is a hypothesis) are foregrounded as the brief requires. F5 correctly nominated as the gating, run-first construct test. Borrowed-rigor provenance (R-track promotion; `[inherited]`/`[re-derived]`/`[never-reviewed]` tags) stated honestly.
- **Scope note (not a defect):** the file runs materially above the brief's 1,800–3,000-word ceiling once prose is counted, though the brief explicitly licenses this version to "run longer" and to *expand* the research agenda, and much of the bulk is reproduced tables / anchors rather than new prose. Flagged for a length-trim decision only; rigor is not at issue.

### `recruiters` — clean
Both `incompatible` hits are explicit denials: L61 ("**Not 'the skills are incompatible.'** They aren't…") and the provenance stamp ("the 'incompatible' retirement… held"). No other do-not-build-on phrase appears. Claims trace (composite-JD as first link → §4b + Audience Map; "hands-on AND strategic" demands both sides of the rotation → §1/§2; ~50% reversion, bounded as cross-industry → §2a/`R1` Claim B; identity change → §2b; the misattribution loop → §4; "budget compromise dressed as a requirement" → §5/§3c; concession-7 reassurance → §6). The Larson four-archetype table is the authorized operational core (`04_RESEARCH`, `AX-LARSON` ✅ Conf 5) and is used within bounds. Both "Never" rules honored: the no-unicorn-recipe / `RISK-SURVIVORSHIP` guard is explicit ("a 'how to source a unicorn' playbook is the *exact inverse* of the message"), and skills are explicitly *not* called incompatible (problem framed as "no archetype and no runway").

## Cross-cutting checks

- **Distinctiveness / null discipline (the tier's signature correction, concession 8 / `R1` Claim B):** every draft that cites the ~50% number flags it as cross-industry boundary-difficulty and routes distinctiveness to the cushion comparison. No draft asserts the number proves software distinctiveness or "closes the null." This is the highest-risk regression for the tier and all five pass.
- **Borrowed-evidence boundary (`R1` Claim C):** the four practitioner drafts that invoke the identity-offload mechanism each flag it once as peer-reviewed *in founders*, with the engineer-severity stated as the paper's extension. Held in all four.
- **One-seam-plus-pattern (`R1` Claim A):** no practitioner draft asserts "rotation at every rung" as a measured per-rung cliff; Senior→Staff is consistently carried as a recurring pattern / hypothesis, not a measured population.
- **No-recipe / `RISK-SURVIVORSHIP`:** every draft whose brief flags it carries an explicit anti-recipe guard.
- **Provenance stamps:** all five carry `derived from DRAFT_SYNTHESIS.md @ c240d35` and the audience-map brief at the top, per the shared output spec.

## Result

The area now mirrors the CTO layout: one rigorous spine + five audience projections under `derived/`, the derivation key (`AUDIENCE_DERIVATION_PROMPTS.md`), and this consistency record. No fixes required.

*Auditor pass conducted 2026-06-25 against spine `DRAFT_SYNTHESIS.md` @ c240d35. Dev-ladder sibling of `../CTO/AUDIENCE_DERIVATION_AUDIT.md`.*
