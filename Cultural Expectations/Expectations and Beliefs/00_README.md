# Expectations and Beliefs — Folder Map

This folder holds the **language layer** of the Cultural Expectations research: the precise definitions, gradients, and guards that keep the work from becoming the weapon it studies. Everything here serves **one fence** (from [[__DISCLAIMERS_EXPECTATIONS_AND_BELIEFS]]): *the verdict lands on the expectation or the process — never on the person, group, or belief.*

## The two pillars

The docs split into two parallel pillars. Both govern words that *describe* but quietly *prescribe*; both serve the one fence.

### Pillar 1 — Failure words (how an expectation fails)
Governs **illogical / irrational / unreasonable** — the verdict on an *expectation's fit with reality*.

- **[[00_TAXONOMY]]** — the canonical core. Two axes (Realm × Word), the grid, the fence, the reasonable/not-reasonable structure, the "default to not-reasonable" rule, and §4.1 (grammatical migration as the fence's mechanical detector). *Everything else cites this.*
- **[[01_FINDING_THE_GRADIENT_FOR_WORD]]** — the grading experiment. Two independent graders scored 9 practitioners × 11 activities; proved the words are *irreducibly ambiguous* (both graders right) and that the gradient's job is to make the ambiguity legible, not to remove it. Contains the calibration-quiz generation prompt.

### Pillar 2 — Characterization words (how a person/group gets labeled)
Governs **normal, failure, and the person-targeting vocabulary** — the words that slide from describing a state toward sentencing a person.

- **[[common_vs_normal_definition_doc]]** — "common" (frequency, descriptive) vs. "normal" (prescriptive). The second word-pair gradient, parallel to Pillar 1. Holds the **Access Restriction Loop** (restriction → outcome gap → gap cited as incapacity → restriction omitted) and its hidden-labor variant (ENIAC, Harvard computers, Hidden Figures, Hopper).
- **[[failure_language_framework]]** — "failure" as feature (SDLC) vs. event (systems) vs. verdict (person). Home of the **grammatical-migration** landscape (promoted to 00_TAXONOMY §4.1) and the **Junior/Senior Divide** (failure-as-verdict is a rational read of a punishing environment).
- **[[witch_hunting_vs_process_gaps]]** — process-first accountability. The operational form of guard #3: "find the gap the verdict is pointing to, and document that instead." Applies identically to SDLC incidents and historical research.

### The enforcement tool (serves both pillars)
- **[[language_auditor_prompt]]** — a runnable AI auditor flagging prescriptive language and omission patterns. Its "flag for inspection, never declare wrong" stance *is* guard #6 (flag, don't sentence) and guard #2 (cannot self-certify) made executable.

## How it all connects to one fence

```
                 THE FENCE (disclaimers)
        verdict on the expectation/process, NEVER the person
                          │
        ┌─────────────────┴─────────────────┐
   PILLAR 1: failure words          PILLAR 2: characterization words
   (00_TAXONOMY, gradient expt)     (common/normal, failure, witch-hunting)
        │                                   │
   "not-reasonable, not              "common, not normal";
    not-rational"                    "find the gap, not the person"
        └─────────────┬─────────────────────┘
                      │
        §4.1 grammatical migration = the shared mechanical detector
        (3rd-person-stable stays on system; migrates to 1st/2nd = targets person)
                      │
              [[language_auditor_prompt]] enforces all of it
```

## Cross-area links
- Disclaimers / weaponization guards: [[__DISCLAIMERS_EXPECTATIONS_AND_BELIEFS]] (the *spear* — aimed verdicts), [[__DISCLAIMERS_INHERITED_LANGUAGE]] (the *arrow* — inherited/reflexive words; this is the *why* behind the whole language pillar — detect, then de-inherit), [[___DISCLAIMERS]]
- Lived specimens that practice the fence: `../Author's Experiences/` (and its `00_COVERAGE_TRACKER`)
- The axis framework these expectations feed: `../00_AXES_SUMMARY.md`

---
*Map maintained as the folder grows. Two pillars, one fence.*
