# Research Capture — The Knowledge Legibility Pipeline
**Date:** June 26, 2026
**Status:** New finding — candidate structural condition
**Connects to:** Axis 1 (cognitive invisibility); Axis 6 (feedback loop); 05_RESEARCH_feedback_loop_paradox.md; 06_RESEARCH_rational_degradation_pattern.md

---

## The Core Finding

Domain knowledge exists in people's heads in a form that cannot be directly acted on by someone without context. The specification failure in software is not a process failure — it is a **knowledge legibility failure.** The knowledge required to build the system exists; it exists in the wrong form for the people who need to act on it.

The solution is not a better process for extracting requirements. It is a pipeline that converts knowledge from the form it naturally exists in (conversation, tribal knowledge, customer service experience) into a form legible enough that someone without context can act on it.

---

## The Process — A Legibility Pipeline

**Step 1 — Unstructured conversation, transcribed by AI.**
Seniors and junior developers talk about the problem. Not trying to abstract it. The AI transcribes; nobody is simultaneously understanding the problem AND translating it into specification language. The dual-task load is broken into two sequential passes.

*What this does cognitively:* Domain knowledge is captured in the form it actually exists in people's heads — narrative, contextual, example-driven — before anyone has tried to compress it into requirements language. Abstraction is deliberately deferred.

**Step 2 — Synthesize onto existing structure.**
The transcript becomes raw material; synthesis is a separate pass. The gap between "what people know" and "what the system needs" becomes visible as a specific artifact rather than living in someone's head.

**Step 3 — Fill gaps from customer service.**
When a specification gap exists on an existing page, call the customer service team and talk about how people actually use the page. Derive the specification from that conversation.

*What this does:* Closes the feedback loop at the cheapest possible point. The customer service team has been absorbing the gap between what the system does and what users actually need, every day, in real time. They hold the tacit knowledge the specification needs; they just haven't been asked in a form that produces a specification artifact.

**Step 4 — Test the specification against a Junior Developer or Claude Code.**
If a junior developer or an LLM can produce something rapidly from the specification, it has achieved sufficient legibility. If they can't, the gap is in the specification, not the builder.

*What this does:* The junior developer / Claude Code test is the specification's unit test. Legibility is validated before committing to build.

---

## Why It Works — The Unified Mechanism

Every step converts knowledge from the form it naturally exists in to a form that can be acted on by someone without context:

| Step | Knowledge form (input) | Conversion tool | Knowledge form (output) |
|---|---|---|---|
| 1 | Tribal knowledge, mental models | AI transcription | Raw narrative transcript |
| 2 | Transcript + system structure | Synthesis pass | Draft specification |
| 3 | Customer service experience | Guided conversation | Gap-filled specification |
| 4 | Specification | Junior dev / Claude Code | Working implementation OR specification gap identified |

The pipeline is a **tacit-to-explicit knowledge conversion process** applied to software specification. Each step makes previously inaccessible knowledge accessible to someone further from the source.

**Theoretical grounding:** Nonaka and Takeuchi (1995), *The Knowledge-Creating Company* — named the tacit-to-explicit knowledge conversion problem (SECI model: Socialization → Externalization → Combination → Internalization). The pipeline above is a specific implementation of the Externalization and Combination steps applied to software specification.

---

## The Senior / Junior Split — What It's Actually Measuring

Junior developers found the output more cohesive than alternatives. Senior developers provided a cross-comparison baseline.

**Why juniors responded more strongly:**
Seniors compensate for an illegible specification using their pattern libraries. They fill gaps automatically from experience. Juniors can't — an illegible specification stops them cold. The pipeline produces a specification legible enough that juniors don't need the pattern library to proceed.

**What the senior/junior gap is measuring:**
The legibility of the specification output, not the quality of the methodology. The gap between senior and junior response is the size of the pattern library required to compensate for a specification that hasn't been through the pipeline. A specification that seniors and juniors respond to equally has achieved full externalization — no pattern library required to act on it.

**Connection to the experience gap finding (06_RESEARCH):**
The pipeline artificially closes the experience gap. The senior developer's pattern recognition is the natural mechanism for filling specification gaps. The pipeline is a synthetic mechanism that produces the same result — gap-filled specification — without requiring the pattern library. This is why AI tooling was the inflection point: it made the transcription step cheap enough to run routinely, which made the whole pipeline viable.

---

## Connection to the Feedback Loop Paradox (05_RESEARCH)

The specification-first / waterfall failure is a feedback loop failure:
- Waterfall assumes knowledge exists before the loop opens
- The knowledge only exists after partial engagement with the problem
- The loop that generates the knowledge (building) is also the loop that makes errors expensive

The pipeline solves this by opening a **cheap feedback loop** (conversation → transcript → synthesis → legibility test) before committing to the **expensive feedback loop** (code → test → deploy → customer response). The fast loop runs in language; the slow loop runs in code. Errors caught in the language loop cost a conversation to fix; errors caught in the code loop cost weeks.

---

## The Algebra Framing — Follow-Up Research Item

**Research question:** How does framing affect the accessibility of abstract reasoning?

Early algebra education research: the same mathematical operations that students fail as abstract symbols succeed when framed in concrete, familiar contexts.

- *"3x + 2x = 5x"* — fails for many students
- *"3 boxes + 2 boxes = 5 boxes; each box has 5 jelly beans; how many jelly beans?"* — succeeds for the same students

The operation is identical. The legibility of the problem is not. The concrete framing makes the abstract structure visible to someone who doesn't yet have the pattern library for algebraic notation.

**The connection to the pipeline:**
The unstructured conversation step (Step 1) is the "jelly beans" move — it captures the domain knowledge in the concrete form it exists before anyone has translated it into abstract specification notation. The synthesis step (Step 2) is the translation into notation. Doing them in sequence, rather than simultaneously, is what makes the output legible to juniors.

**Research to pursue:**
- Kamii (1985, 1989) — constructivist mathematics education; children construct mathematical understanding through concrete manipulation before abstract notation
- Sfard (1991) — "On the Dual Nature of Mathematical Conceptions" — operational (process) understanding precedes structural (object) understanding; direct parallel to domain knowledge preceding specification
- Willingham (2009) — *Why Don't Students Like School?* — abstract reasoning requires concrete prior knowledge; the brain doesn't process abstractions without grounding examples
- Look up: current research on early algebra instruction (kindergarten / 1st grade) — specifically whether concrete-first framing produces durable abstract reasoning capability or only surface performance

**The implication for Axis 1:**
Cognitive invisibility (the complexity is invisible to decision-makers) may be partly a legibility problem, not just a tangibility problem. The complexity isn't invisible because it can't be seen — it's invisible because it's being presented in a form (abstract specification, technical architecture diagrams) that requires a pattern library the decision-maker doesn't have. Concrete framing might make the complexity visible to the same people who can't see it in abstract form.

---

## Follow-Up Research Items

1. **Nonaka and Takeuchi (1995) SECI model** — verify the tacit-to-explicit framing applies cleanly; check whether software specification is an established application of the model or a novel one.

2. **Early algebra / concrete-first instruction research — CITED:** Kibbe, M.M. & Feigenson, L. (2015). "Young children 'solve for x' using the Approximate Number System." *Developmental Science*, 18(1), 38–49. DOI: 10.1111/desc.12177. Finding: preschoolers (ages 4–6) failed to solve for an unknown addend when problems were presented symbolically but succeeded on identical problems presented non-symbolically (concrete object collections). The Approximate Number System — an innate capacity — was already performing the algebraic operation; the symbolic notation was the barrier, not the math. **Implication for the pipeline:** Domain knowledge is already present in operational form in people's heads. The pipeline doesn't teach the domain — it externalizes what people already know in a form that doesn't block access to it. The abstract specification notation is the barrier, not the complexity.

3. **Is there SDLC research on specification legibility as a distinct variable?** Most SDLC research measures process compliance, velocity, or defect rates. Specification legibility — can someone without context act on this? — may not be a named variable. If it isn't, that's itself a finding: the field measures the wrong thing.

4. **The AI transcription inflection point.** The pipeline became viable when AI transcription made Step 1 cheap. Is there research on how tool cost affects knowledge externalization practice? The implication: the pipeline was always epistemically correct; it was economically unviable before cheap transcription.
