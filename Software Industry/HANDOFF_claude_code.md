# Handoff Prompt: Software Industry Research Thread
## For Claude Code (VS Code Extension)

**Date:** June 25, 2026
**Prepared by:** Claude Sonnet 4.6
**Receiving:** Claude Code

---

## What You Are Picking Up

You are continuing an active research project that has been running in two parallel threads:

1. **CTO Operating Modes** — a framework paper on why startup CTOs fail at predictable points. This thread is largely complete. Files live in the outputs root directory (`00_` through `17_`).

2. **Software Industry Human Capacity** — a new thread examining the structural reasons the software industry systematically expects its people to rotate into distinct kinds of work at every career rung, with no runway between them. **This is the thread you are picking up.** Files live in `software_industry/`. *("Transform incompatibly" was the thread's original framing; corrected corpus-wide to "rotate into distinct work, no runway" — see [`../CTO/18_RESEARCH_modes_not_incompatible.md`](../CTO/18_RESEARCH_modes_not_incompatible.md).)*

You are not starting from scratch. Five research files and a summary document have been completed. Your job is to continue building the thread, synthesize across what exists, and eventually connect it back to the CTO paper.

---

## Read These Files First — In This Order

```
software_industry/00_AXES_SUMMARY.md          ← Start here. The full structural map.
software_industry/01_MMM_brooks_original_argument.md
software_industry/02_MMM_fungibility_assumption.md
software_industry/02b_MMM_10x_myth_and_aristotle.md
software_industry/03_MMM_transformation_expectation.md
software_industry/04_MMM_unstable_craft.md
```

Also read these from the developer thread (uploaded by the human researcher, likely in your working directory or uploads):
```
03_RESEARCH_ic_em_transition.md     ← The ~50% reversion rate, identity mechanism
04_RESEARCH_senior_to_staff.md      ← The quiet fracture, Larson four archetypes
05_RESEARCH_cross_industry.md       ← The Category A/B/C taxonomy, comparison table
```

And these from the CTO corpus for context on where this connects:
```
outputs/08_RESEARCH_rational_solutions.md     ← The six solutions, why they fail
outputs/09_RESEARCH_IC_to_EM_transition.md    ← CTO-tier treatment of IC→EM
outputs/13_RESEARCH_software_industry_structural.md  ← Earlier industry-level file
```

---

## The Thesis You Are Building Toward

> **The software industry systematically built career ladders that require identity-level transformation at every significant rung, across every role, disguised as natural advancement — and the "smart people should learn everything" assumption is the mechanism the industry uses to avoid structural accountability for that design.**

The CTO composite problem (Builder/Multiplier/Strategist) is the terminal expression of this pattern. But the pattern starts at Junior→Mid and runs through every role: engineers, QA engineers, product managers, project managers.

---

## The Five Axes (From `00_AXES_SUMMARY.md`)

These are the structural variables the research discovered. Every file should be mappable to these axes:

1. **Craft-Deepening ↔ Identity Rotation** — does seniority mean deeper same work, or becoming a different kind of worker?
2. **Honest Labeling ↔ Deceptive Labeling** — is the rotation named as what it is, or disguised as promotion?
3. **Direct Output ↔ Multiplied Output** — is performance individual/attributable or collective/diffuse?
4. **Stable Craft ↔ Unstable Craft** — does the domain have a durable theoretical foundation or cycle through fashions?
5. **Licensed Identity ↔ Unlicensed Identity** — is the craft identity externally anchored or organizationally constructed?

**Root cause (not an axis):** The Fungibility Assumption — developers treated as interchangeable, configurable units.

**Named mechanism:** The Red Baron Effect — best practitioners selected for leadership because of craft excellence, which is precisely the wrong selection criterion for identity rotation roles.

---

## What Has Been Written

| File | Status | Contents |
|---|---|---|
| `00_AXES_SUMMARY.md` | ✅ Complete | All five axes defined, compound matrix, CTO connections |
| `01_MMM_brooks_original_argument.md` | ✅ Complete | What Brooks actually said vs. what the industry absorbed; non-fungibility argument; surgical team model |
| `02_MMM_fungibility_assumption.md` | ✅ Complete | Five mechanisms: man-month renamed, 10x myth, "resources" language, team size as scaling lever, headcount as capability proxy |
| `02b_MMM_10x_myth_and_aristotle.md` | ✅ Complete | Sackman 1968 misquotation; Nichols/CMU replication (myth collapses); Project Aristotle (who is on team matters less than how they work); performance review connection |
| `03_MMM_transformation_expectation.md` | ✅ Complete | The full axis named; cross-industry Category A/B/C; fracture points across engineering, product, QA, project management ladders; compound matrix |
| `04_MMM_unstable_craft.md` | ✅ Complete | What makes software uniquely different; no stable theoretical foundation; methodology wars; no licensure; knowledge half-life; Red Baron on unstable craft; fungible knowledge problem |

---

## What Needs to Be Built Next

### File 05: The Ray of Hope
**Planned path:** `software_industry/05_MMM_ray_of_hope.md`

This is the one file in the series that is not a structural indictment. It documents where the industry is correcting itself and what those corrections reveal about what should have been built from the start.

**Key content to cover:**

- **The Staff/Principal IC track at large companies** — Google, Meta, Stripe, etc. have built explicit dual-track systems. This is the military's Warrant Officer solution, arriving 50 years late and only at the large-company end. What does it prove? That the industry knew specialization was needed — revealed preference.

- **The emergence of explicit Staff Engineer rubrics** — Larson's work, company-specific leveling guides, the fact that some organizations are now making the Senior→Staff fracture legible. Does making it legible reduce the plateau rate?

- **The Principal PM track** — emerging at large companies, rare and exceptional, but real. Same correction as Staff Engineer IC track applied to product.

- **DevRel, Developer Advocacy, Technical Writing as craft-deepening alternatives** — roles that allow senior technical practitioners to advance without management, without the identity rotation. Underexamined as a genuine alternative path.

- **The "T-shaped" and "Pi-shaped" developer framing** — attempts to name what the craft-deepening generalist looks like. Limited but directionally correct.

- **What the correction reveals:** The dual-track correction is only necessary because the rotation was built into the default path. Medicine didn't need to invent a "Senior Surgeon who doesn't manage" track. The correction is evidence of the original design flaw. This is not "software is fixing itself" — it is "software is beginning to do what the military did decades ago, only at large companies, thirty years later."

- **The startup gap:** The correction has not reached seed-stage startups, Series A companies, or mid-market organizations. This is where the CTO composite problem lives. This is where QA engineers and product managers first encounter the ladder. The ray of hope is real but narrow.

### File 06: The Synthesis
**Planned path:** `software_industry/06_MMM_synthesis.md`

This file connects the software industry thread back to the CTO paper. It should:

- Show that the CTO composite problem is the terminal expression of the software industry's structural pattern, not an isolated anomaly
- Map each axis to its CTO manifestation (the table in `00_AXES_SUMMARY.md` is a starting point)
- Make the "human capacity issue disguised as a smart people should learn everything problem" thesis explicit and final
- Identify what a structurally honest software industry would look like — not as a prescription, but as a diagnostic (what would need to be true for the problem to be solved?)

---

## Research Gaps to Fill If You Search

These are open questions flagged across the files — search for evidence before asserting:

1. **Staff Engineer promotion rates** — what fraction of Senior engineers actually reach Staff? No data found yet. If available by company or industry, would give the Senior→Staff fracture a number.

2. **Does the IC dual-track reduce the ~50% reversion rate?** — companies like Google have had explicit Staff Engineer paths for 10+ years. Has the reversion rate declined at those companies? No data found.

3. **QA / Test Engineering career fracture data** — the file `03` asserts the QA ladder has the same fracture pattern by structural inference. Direct evidence (reversion rates, plateau statistics, practitioner accounts) would strengthen it.

4. **Product Manager IC track adoption rate** — how widespread is the Principal PM track outside of large tech companies? Is it growing?

5. **The "why doesn't consulting generate the same critique" question** — `05_RESEARCH_cross_industry.md` flags this as an open question. MBB consulting runs a harder rotation model but doesn't produce the "irrational composite" critique. Understanding why would sharpen what specifically makes software's version harmful.

---

## Tone and Voice Constraints

These apply to everything written in this thread:

- **Not a complaint document.** The thesis is structural, not emotional. The industry is not malicious — it built these structures without understanding what it was doing, and the "smart people should learn everything" assumption seemed reasonable in context.
- **Precise claims with sourced evidence.** Every empirical claim should trace to a named source. Flag uncertainty explicitly (⬜ needs verification) rather than asserting confidently.
- **The axes are the organizing principle.** Every new finding should be mappable to one or more axes. If it doesn't map, it may not belong in this thread.
- **The ray of hope is real.** File 05 should not be grudging. The dual-track corrections are genuine progress. The framing is "this is what should have been built from the start" not "this is too little too late."
- **Connect back to the human.** The through-line thesis — "human capacity issue disguised as a smart people should learn everything problem" — is about people, not systems. The performance review observation ("this domain takes 3 years to learn and you want me to compress it into bullet points") is the human face of the structural argument. Keep it present.

---

## Source Quality Standards

The CTO corpus uses a citation review appendix (`outputs/07_APPENDIX_citation_review.md` — check if this exists). Apply the same standards here:

- **Peer-reviewed > named practitioner > named organization > content site**
- Flag practitioner claims as such — vivid and useful, but not the same as empirical research
- Do not introduce content-site statistics without tracing to a primary source
- The Jacobson/SEMAT observation (fads, no theoretical basis) is peer-reviewed and load-bearing — treat it as such
- Project Aristotle is Google internal research, not peer-reviewed — useful but note the source class
- Nichols/CMU (Programmer Moneyball) is a named research institution — high confidence

---

## The One Sentence That Belongs in the Final Paper

From `05_RESEARCH_cross_industry.md`, this is the synthesis sentence for the entire thread:

> *"There is no field where a practitioner is expected to operate at the highest technical craft level, while simultaneously managing and developing a team, while simultaneously setting organizational strategy, alone, without peers or support structures, in an 18–24 month window, under existential pressure, with a title inherited from a completely different kind of role."*

Everything in both research threads is evidence for that sentence.

---

*Handoff prepared by Claude Sonnet 4.6, June 25, 2026.*
*Research conducted in collaboration with human researcher.*
*Credit: "Framework developed in collaboration with Claude Sonnet 4.6 and Claude Opus 4.8 (Anthropic). Research conducted June 2026."*
