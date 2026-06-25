# R4: The Open Research Agenda
## What Is Still Genuinely Unknown — The Hard Research the Corpus Cannot Close by Citation

**Research date:** June 25, 2026
**Series:** Software Industry — Human Capacity Research Thread — **Review track** (`R1`–`R4`)
**Predecessors:** `R1_ADVERSARY`, `R2_FALSIFICATION`, `R3_STEELMAN`; verification in `08_CITATIONS_gap_closure.md`
**Purpose:** Separate *closed* from *open*. The last verification wave (`08`) closed every **citation** gap the review track raised. It did **not** close the **research** gaps — the questions that no amount of source-hunting can answer because the data doesn't exist yet, or because answering them requires original analysis rather than a literature pass. This file is the standing list of that hard research, written so the next pass (human or model) knows exactly what remains and why each item is hard.

> **The distinction this file enforces.** A *citation gap* is "we asserted X; find the primary source." A *research gap* is "we don't actually know X, and finding out requires data nobody has published or analysis nobody has done." `08` was a citation pass and was excellent at it. Everything below is the second kind. Do not let a future verification pass mistake these for citation gaps and "close" them by finding a tangentially related paper — that would be the confirmation-bias failure mode `R2` Bias 1 warns about, in a new costume.

---

## Tier 0 — The load-bearing falsifiers (highest priority)

These come straight from `R2`'s falsification protocol. `08` confirmed that **none of them have been run or found in the literature.** They are the difference between a thesis that is *defensible* (survives argument) and one that is *tested* (survives evidence). Until at least one is addressed, the corpus is the former, not the latter.

### 0.1 — The seed-stage role-split natural experiment
**Question:** Do organizations that split the CTO / VP-Eng role **from seed** (funding held constant) show *better* technical-leadership survival than composite-CTO orgs?

**Why it's load-bearing:** This is the direct test of the thread's central claim — that the harm is *uncushioned rotation*, not rotation itself. If splitting the role early doesn't help once you control for funding, the structural account weakens badly.

**Why it's hard:** Requires a matched-pair design (split vs. composite) with funding/stage/market held constant, and a survival/tenure outcome. The confound is brutal: orgs that *can* split early are usually better-funded, so any naive comparison measures funding, not structure. The `14_RESEARCH_success_exceptions.md` stub already flagged this ("was it the split or the funding that allowed it?"). Needs either a funding-controlled cohort or an instrument for the split decision.

**What would count as an answer:** A cohort of seed-stage companies, split-vs-composite, funding-matched, with technical-leadership tenure measured at 24–36 months. Even n=20 per arm with honest confounander discussion beats the current zero.

### 0.2 — Does a startup-scale IC track still produce ~50% reversion?
**Question:** Where a respected, well-supported IC track exists **at startup scale**, does the IC→EM reversion rate still sit near ~50%?

**Why it's load-bearing:** The thread's mechanism is *identity-anchoring* — people revert because the IC track is the only identity anchor they have (`04`, `R3` Pillar 2). If a well-supported startup IC track *still* yields ~50% reversion, anchoring isn't the mechanism and the explanation must change.

**Why it's hard:** "Startup-scale IC track" is rare almost by definition (the thread's own claim is that the correction hasn't reached startups). Finding enough instances to measure reversion is the problem. The large-company version (0.5 below) is more tractable but tests a weaker version of the claim.

### 0.3 — Behavioral outcomes in matched non-rotation professions (the artifact-null killer)
**Question:** Measured on **behavioral outcomes** (reversion, tenure, role-abandonment) rather than sentiment surveys, do comparator professions show equal or lesser rotation-failure pathology than software?

**Why it's load-bearing:** This is the empirical form of the **measurement-artifact null hypothesis** (`R2`, deepest blind spot) — the most economical competitor to the entire thesis ("software isn't uniquely broken, just uniquely *documented*"). `R3` rebuts it with an argument (lean on behavior, not sentiment). That rebuttal is currently *unbacked* — the comparator behavioral data has not been pulled.

**Why it's hard:** Behavioral outcome data for medicine/law role-transitions (e.g. clinician→administrator reversion rates) largely **does not exist in published form** — `08` Gap 5 explicitly found "specific data on burnout reversion rates for physicians who moved to administrative roles… remains an open gap." So this requires either a data source nobody has surfaced or a proxy (e.g. administrator-to-clinical return rates from licensure/employment records).

---

## Tier 1 — The HANDOFF's unanswered research questions

The sibling's `HANDOFF_claude_code.md` listed five gaps. `08` closed *citations*, not these. They remain open.

### 1.1 — The consulting puzzle (the sharpest open question)
**Question:** Why doesn't management consulting (MBB) generate the same "irrational composite" critique software does, despite running a *harder, faster* up-or-out rotation?

**Why it matters most of the five:** This is a *diagnostic* question, not a data-gathering one. The answer would tell you **precisely what makes software's rotation uniquely harmful** — by isolating the variable consulting lacks. Candidate differentiators already in the corpus: (a) consulting *honestly labels* the rotation (`03` Category C-but-explicit); (b) consulting has a *stable craft* underneath (`04` — the analytic/communication toolkit doesn't have a 2.5–5yr half-life); (c) consulting has *exit infrastructure* (the alumni network as designed off-ramp). Resolving which of these does the work is the highest-value conceptual research left.

**Why it's hard:** It's a comparative-institutional analysis, not a statistic. Risk of just-so storytelling. Needs the differentiators stated as *competing* hypotheses with something that would distinguish them.

### 1.2 — Staff Engineer promotion rates
**Question:** What fraction of Senior engineers actually reach Staff?

**Status:** `08` confirmed "not published by companies; no industry survey found." Would give the *quiet fracture* (`03`) an actual number, which it currently lacks. Hard because it's internal HR data.

### 1.3 — Does the IC dual-track reduce the ~50% reversion rate?
**Question:** At companies with 10+ years of explicit Staff tracks (Google, Meta), has reversion declined relative to the no-track baseline?

**Status:** Open; requires internal longitudinal HR data. This is the *large-company* cousin of 0.2 — more tractable, weaker claim. If even directional data leaked through engineering blogs or talks, it would move the needle.

### 1.4 — QA / Test Engineering fracture: direct evidence
**Question:** Does the QA Lead → Quality Manager fracture show the same reversion/plateau pattern as IC→EM?

**Status:** Asserted in `03` by *structural inference* only. No direct evidence (reversion rates, plateau stats, practitioner accounts). The weakest-evidenced of the four ladders. Honest move: either find evidence or downgrade the QA claim to explicitly-inferred.

### 1.5 — Principal PM adoption rate outside large tech
**Question:** How widespread is the Principal PM track beyond FAANG-scale? Is it growing?

**Status:** `05_MMM_ray_of_hope.md` flags it `⬜`. Practitioner sources only. Hard because no industry survey exists at this specificity.

---

## Tier 2 — Conceptual debts (analysis, not data)

These don't need new data — they need the corpus to *do work it hasn't done.*

### 2.1 — Apply the verified narrowings to `01`–`06`
Not research — **editing** — but it's the gating step before any of the above lands cleanly. `08` verified the sources for the narrowings; the substantive `MMM` files still state the *over-claimed* versions. Specifically (from `R2` triage):
- `04`: "no stable craft" → "the *credited* layer is unstable; the durable layer is uncredited" (DORA now backs this, `08` Gap 1).
- `01`/`02`/`13`: demote CHAOS to illustrative, promote ISBSG (`08` Gaps 3–4).
- `13`: retire "imposter 52.7% = structural diagnostic"; adopt the base-rate framing (`08` Gap 6 — healthcare 62% > software).
- `03`/`13`: concede comparator professions' own rotation pathologies (`08` Gap 5 — physician craft→admin drift).

Flagged here because **the open research above will collide with the un-narrowed text** if the edit pass doesn't happen first.

### 2.2 — The within-individual variance finding deserves to be the spine of `02b`
`R3` Pillar 1 notes Nichols' within-individual finding is the single most leveraged empirical point (it refutes 10x-as-trait, explains the performance-review pathology, *and* reframes imposter syndrome). It currently shares billing with Aristotle in `02b`. This is a restructuring judgment, not new research — but it's the highest-leverage *framing* change available.

### 2.3 — Pre-register the success-case test (close the unfalsifiability loop)
`R2` Bias 4 / the `14_` standing instruction: a success case may only be ruled `[CONTEXT/LUCK]` *after* failing a **pre-registered** test for genuine structural success. That test is not yet written down. Until it is, the success-case thread is unfalsifiable-in-practice. Writing the test is a half-day of conceptual work and closes the corpus's last open methodological flank.

---

## What is NOT on this list (and why)

To keep the agenda honest, these are explicitly *not* pending:

- **Citation verification** — done in `08`. Don't re-open.
- **The fungibility refutation** — `R1` Claim 2 verdict was HOLDS; the falsifier (0.6 in `R2`'s table) "looks safe" because ramp-cost + n(n-1)/2 + ISBSG already foreclose it. Not worth research budget.
- **Whether the thesis is "true"** — wrong frame. The agenda is about *what would test it*, not about accumulating more confirming evidence. More confirmation is not research; it's the bias `R2` Bias 1 names.

---

## Priority order for the next pass

1. **2.1 (apply narrowings)** — gating; do first, it's editing not research, and everything else collides with the un-narrowed text.
2. **1.1 (consulting puzzle)** — highest conceptual value, needs no new data, isolates the harm-causing variable.
3. **0.3 (artifact-null behavioral data)** — closes the deepest blind flank; hardest data problem; start by scoping whether the data exists at all.
4. **0.1 (seed-stage role-split)** — the central falsifier; design the funding-controlled comparison even if you can't yet populate it.
5. **2.3 (pre-register success test)** — cheap, closes the unfalsifiability loop.
6. **Everything else** — opportunistic; close if data surfaces, otherwise honestly mark as boundary-of-knowable.

The through-line: the corpus is strong on *what it claims* and thin on *what would prove it wrong in practice.* The hard research is all on the second axis. None of it can be closed by finding another supporting citation — which is exactly why it's still open after a citation pass that closed everything it touched.

---

*Review track: `R1` (counterevidence) → `R2` (bias + falsification) → `R3` (steelman) → `R4` (open agenda). Verification: `08_CITATIONS_gap_closure.md`.*
*Framework developed in collaboration with Claude Opus 4.8 (Anthropic). Research conducted June 2026.*
