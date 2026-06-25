# Prompt: CTO Mode Assessment Quiz
## Instructions for Opus — Build a Mode Mismatch Diagnostic Tool

**Document purpose:** Source-controlled prompt for building the CTO self-assessment quiz. Cross-compare Opus output against this prompt and the Sonnet cautions at the bottom before finalizing.

**Date:** June 24, 2026  
**Status:** Ready for Opus execution  
**Companion output:** Quiz artifact (React or structured document TBD)

---

## Context

You are working within an ongoing research project developing the CTO Operating Modes Framework. Before building anything, read the following context files which are available in the outputs directory:

- `00_RESEARCH_CONTEXT.md` — master context
- `05_FULLTEXT_working_document.md` — full paper text
- `10_RESEARCH_domain_centric_CTO.md` — domain axis (hidden variable)
- `01_RESEARCH_software_developer_career.md` — structural career mismatch context
- `13_RESEARCH_software_industry_structural.md` — industry-level structural context

**Your task:** Build a CTO self-assessment quiz that surfaces mode mismatch — the gap between what mode the company requires and what mode the CTO is operating in.

---

## Critical Design Constraints — Do Not Violate These

### 1. Measure behavior, not aspiration
Do not ask "how good are you at X?" Ask what the CTO actually does with their time, what decisions they make, what drains or energizes them. Self-assessed skill ratings are unreliable. Behavioral and identity signals are the empirical predictors.

### 2. The Mathias & Williams distinction is load-bearing
The key identity signal is not skill level — it is whether the CTO perceives their role as "give up the hats" or "wear all the hats." Questions must surface this orientation without naming it. Do not ask "do you delegate well?" Ask questions whose answers reveal the orientation indirectly.

### 3. Measure company stage separately from CTO behavior
Section 1 assesses what mode the *company* requires, using objective signals (team size, funding stage, revenue, product maturity, external partnership complexity). The CTO's perception of what stage they're in is not the input — observable facts are.

### 4. The output is a gap score, not a grade
The quiz does not tell the CTO they are good or bad. It tells them whether their operating mode matches what their company currently requires. A Builder CTO is not a failure — a Builder CTO at a Series A company is a mismatch risk. Frame accordingly.

### 5. The domain axis must be captured
Include a short section (4–6 questions) that surfaces whether the CTO is domain-centric or adaptable generalist, and whether the market the company operates in is domain-dependent (HealthTech, regulated FinTech, DeepTech) or domain-agnostic. This produces a second risk flag independent of the mode gap.

### 6. Do not name the modes in the questions
The questions should not use the words Builder, Multiplier, or Strategist. Those words prime the CTO to answer what they think they should be rather than what they are. Name the modes only in the output/results section.

### 7. The ~50% IC→EM reversion finding applies
Questions assessing Multiplier-mode orientation should be calibrated to the known difficulty of this transition. Do not make Multiplier-mode questions easy to answer "correctly" — the whole point is that Builder CTOs systematically misidentify themselves as ready for Multiplier mode.

---

## Quiz Structure

### Section 1 — Company Stage (8 questions)
Objective signals only. Scoring maps to:
- Pre-seed/Seed → Builder mode required
- Seed→A / Series A → Multiplier mode required
- Series B+ → Strategist mode required
- Mixed scores → Transition zone (highest risk — flag explicitly)

**Signals to probe:**
- Engineering team size
- Whether the CTO has direct reports who are themselves managers (vs. all ICs)
- Funding stage and time since last round
- Whether revenue is pre-product, pre-scale, or scaling
- Whether the CTO's primary external relationships are investors, customers, or partners/ecosystem
- Whether the company's primary technical risk is "will it work?" vs. "can we ship fast enough?" vs. "can we scale this?"

---

### Section 2 — How You Actually Spend Time (10 questions)
Behavioral. Ask about last week, last month — not "in general."

**Signals to probe:**
- What percentage of time spent writing/reviewing code vs. in 1:1s vs. in external meetings
- When a critical technical decision came up last week, who made it and how
- When an engineer on the team struggled last month, what did the CTO do
- When the last board/investor meeting was and what the CTO's role in it was
- Whether the CTO can name the top 3 things blocking their team right now without checking a system
- Whether the CTO's "optimal week" looks like their actual week (the Mathias & Williams calendar assessment applied directly)

---

### Section 3 — Identity and Energy Signals (8 questions)
The Mathias & Williams mechanism. Surfaces "give up the hats" vs. "wear all the hats" orientation without naming it.

**Signals to probe:**
- What the CTO would do with an unexpected free day (build something vs. think about org vs. external relationship)
- What recent accomplishment made them most proud (shipped feature vs. engineer they developed vs. strategic win)
- What they find hardest to let go of in their current role
- How they feel when a strong engineer joins who is better than them at something technical
- What "the company needing a different kind of CTO" would mean to them
- Whether they feel more like a craftsperson, a coach, or a navigator right now

---

### Section 4 — Domain Profile (6 questions)
Surfaces domain-centric vs. adaptable generalist, and market domain dependency.

**Signals to probe:**
- How deep is the CTO's expertise in the company's specific technical domain vs. adjacent domains
- Whether the company's primary buyers/partners require domain credibility to engage
- Whether the CTO has successfully led technical initiatives outside their primary domain in the last 12 months
- Whether the company's scope is expanding into adjacent markets or staying domain-focused
- Whether the CTO's domain expertise is a hiring signal or a credibility signal for the company's go-to-market

---

## Output Format

Produce four outputs for each quiz taker:

### Output 1: Company Mode
"Your company is currently in [Mode] stage, based on [2–3 specific signals from their answers]."

### Output 2: CTO Operating Mode
"You are currently operating in [Mode] mode, based on [2–3 specific behavioral/identity signals from their answers]."

### Output 3: Gap Assessment

**Match:**
"Your operating mode aligns with what your company currently needs. Key watch item: [specific signal that warrants monitoring]."

**Lagging gap:**
"Your company has moved into [Mode B] territory but you are still operating in [Mode A] mode. This is the highest-risk configuration. Specific signals: [2–3 named behaviors from their answers]."

**Leading gap:**
"You are operating ahead of your company's current stage. This can work if [condition], but risks [specific named risk]."

### Output 4: Domain Risk Flag (if triggered)
"Your domain profile suggests [domain-centric risk / market expansion risk / no flag]. Specifically: [1–2 sentences]."

---

## Tone Constraints

- **Practitioner-facing.** Plain language. No academic jargon.
- The quiz should feel like it was written by someone who has been a CTO, not by someone who studies CTOs.
- Results should feel precise and earned, not generic. If two CTOs get the same mode output, the explanation should still feel specific to their answers.
- **Do not moralize.** The quiz is diagnostic, not prescriptive. A Builder CTO in Builder mode is not being told to become a Multiplier — they are being told what to watch for at the horizon.
- **Preserve discomfort where it is earned.** If a Builder CTO in a Series A company answers honestly, the gap assessment should land with some weight. Do not soften it into meaninglessness.

---

## Sonnet's Cautions — Cross-Check List

When comparing the Opus output against this prompt, flag if Opus:

- [ ] Makes the Multiplier questions too easy to answer "correctly"
- [ ] Removes the domain axis or collapses it into the mode assessment
- [ ] Softens the gap language into career-advice platitudes
- [ ] Names the modes in the questions rather than the output
- [ ] Asks about skills rather than behaviors and identity signals
- [ ] Produces a "grade" rather than a gap score
- [ ] Loses the Mathias & Williams identity orientation as the key signal
- [ ] Allows a CTO to self-assess their company stage (must be objective signals only)
- [ ] Merges Section 1 (company) and Section 2 (CTO behavior) — these must stay separate
- [ ] Loses the transition zone flag (mixed Section 1 scores = highest risk, must be called out explicitly)
- [ ] Produces generic result language that doesn't reference the specific answers given
- [ ] Frames the domain axis as secondary or optional rather than a parallel risk dimension

---

## Design Rationale (for Opus context)

The quiz is built on two empirical findings that must survive into the artifact:

**Finding 1 (Mathias & Williams, 2018):** The success predictor for founder role transitions is not skill level — it is identity orientation. Founders who perceive their role as "give up the hats" grow their ventures. Founders who perceive it as "wear all the hats" don't. The quiz must surface this orientation, not skill self-assessment.

**Finding 2 (CTO tenure data, Spencer Stuart 2023):** Average CTO tenure is 2.5 years — almost exactly one mode. The industry is cycling through CTOs at mode-boundary intervals without naming what it is doing. The quiz exists to make that cycle visible before it becomes a crisis.

The quiz is not a personality test. It is a structural diagnostic. The output should feel like looking at an X-ray, not reading a horoscope.

---

*Prompt authored in collaboration with Claude Sonnet 4.6 (Anthropic). Framework developed June 2026.*
