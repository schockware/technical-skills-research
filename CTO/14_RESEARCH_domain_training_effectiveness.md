# Can Domain Expertise Be Trained? The Effectiveness of Domain Knowledge Acquisition
## Research Finding: The Structural Barriers to Expert Domain Switching

**Research date:** June 24, 2026  
**Status:** Supporting research — extends the domain-centric CTO typology  
**Relationship to corpus:** `13_RESEARCH_domain_centric_CTO.md` established that domain identity investment predicts mode transition failure. This document investigates whether training can close that gap — specifically, whether an expert in one domain can acquire genuine competence in another, and how long it takes.

---

## The Question

The training solution to the CTO composite problem (Solution 1 in `12_RESEARCH_rational_solutions.md`) has already been shown to fail for people skills — the IC→EM→VP Engineering path takes 8–15 years and has a ~50% reversion rate even in optimal conditions.

The parallel question for domain expertise: **Can a domain-expert CTO acquire genuine competence in a new domain? Can a generalist CTO acquire domain depth when the company enters a domain-heavy market?**

This matters because:
- A domain-expert CTO in a general tech company might theoretically be trained to lead outside their domain
- A generalist CTO hired into a HealthTech or regulated FinTech company might theoretically develop domain depth over time
- Both represent the training solution applied to the domain axis rather than the people skills axis

---

## Finding 1: The Curse of Expertise — Prior Knowledge Actively Interferes

The most important finding is not that domain training is slow. It is that deep expertise in one domain actively impairs learning in adjacent ones.

**The curse of knowledge** (Camerer, Loewenstein & Weber, 1989 — foundational paper, 2,200+ citations) is a cognitive bias in which an expert's internalized frameworks make it structurally difficult to reason from a beginner's position. The expert has reorganized their cognition around domain-specific mental models that fire automatically and efficiently within the domain — and misfire outside it.

This is not a motivational problem. It is structural:

> "You can't unlearn what you've learned, and you can't see it with fresh eyes anymore."
> — UserTesting Research

> "Mental models compound the curse. Experts develop sophisticated frameworks for understanding their domains — interconnected webs of concepts that let them quickly categorize problems and apply solutions. These models are incredibly efficient for expert thinking but nearly impossible to transfer intact."
> — Science Array

The critical insight: **prior expertise doesn't just fail to transfer — it creates interference.** Experts enter new domains with confident but miscalibrated pattern recognition. They recognize surface similarities to their home domain, apply their domain-specific causal models, and produce confident but structurally wrong conclusions. This is the curse of expertise operating at the *learning* level, not just the reasoning level. <!-- APPENDIX-REF: AX-CURSE — Camerer 1989 + expertise reversal effect; human-domain mechanism, supersedes the TEE framing. See 07_APPENDIX. -->

Research on the expertise reversal effect (meta-analysis, 2025) confirms this robustly: the same instructional methods that help novices learn actually impede experts because experts' existing knowledge structures conflict with the new material. The effect is durable across contexts.

---

## Finding 2: Domain Expertise Takes Years to Acquire — Even Without Interference

Setting aside the interference problem, acquiring genuine domain expertise from scratch requires sustained deliberate practice measured in years, not months.

Ericsson's deliberate practice research (the basis for the "10,000 hours" concept, though widely misunderstood) established several findings relevant here:

- Expertise acquisition in complex domains typically requires 6,000–10,000 hours of **deliberate practice** — not passive exposure, not coursework, but goal-oriented practice with rapid feedback loops
- A 2014 meta-analysis found deliberate practice accounts for ~26% of performance variation in games and ~21% in music — meaning it is necessary but not sufficient
- The age-of-starting correlation is robust: experts who start younger reach higher performance ceilings, suggesting that adult domain acquisition has structural limits

**The timeline implication:** 10,000 hours at 40 focused hours per week is ~5 years of nothing else. At realistic part-time domain acquisition (10 hours/week alongside a full CTO role), it is 20 years. These numbers are not precise, but the order of magnitude is.

For a domain-expert CTO in a general tech company attempting to develop competence in adjacent domains: the training timeline is incompatible with the company's growth trajectory. The company will hit its mode transition boundary long before domain training produces genuine competence.

---

## Finding 3: Expert Unlearning Is a Separate Problem — And Harder Than Learning

The physician unlearning research (Gupta, Boland & Aron, 2017 — Implementation Science) provides the most directly relevant empirical evidence for what happens when experts try to change domain-specific behavior.

Context: physician practice change is one of the best-studied examples of expert behavior change, with decades of intervention research. The findings are consistent and sobering.

The **17-year evidence-to-practice gap** (Balas & Boren, 2000; updated to ~15 years in 2021) measures how long it takes for established clinical evidence to become standard practice. This is not about ignorance — physicians are aware of new evidence. It is about the difficulty of replacing habituated expert behaviors with new ones.

The qualitative finding from Gupta et al.'s 15 physician interviews: practice change disturbs a "status quo equilibrium." Changing clinical practice requires **unlearning** old practices, not just learning new ones. Rushmer and Davies distinguish between:
- **Routine unlearning**: modest adjustments to existing practice
- **Deep unlearning**: "a substantive break with previous modes of understanding, doing, and being"

The domain-expert CTO encountering a new technical domain requires deep unlearning. Their existing frameworks don't just need updating — they actively generate wrong answers, confidently delivered.

> "Experts suffer from the 'curse of expertise,' making them unable to unlearn things they already know even when the situation demands it. They are slow to respond to situational changes... even when such responses become incompatible with the new situation."
> — Camerer et al. (1989), cited in PMC literature review on expertise humility

---

## Finding 4: Awareness Doesn't Fix It

Experts cannot correct cross-domain errors simply by thinking more carefully — deliberate reasoning uses the same domain-specific frameworks that produce the error. (An earlier draft attributed this point to the "TEE paper," Mars 2026 — an AI-systems paper; the human-cognition evidence below makes the same point on solid ground.)

Hinds (1999) — "The Curse of Expertise" — found that experts were **worse** predictors of novice performance than intermediates, and were **resistant to debiasing techniques** specifically designed to reduce their underestimation. When explicitly told about the bias and asked to correct for it, experts adjusted less than expected and remained more miscalibrated than novices.

The implication: domain training programs that rely on awareness and self-correction as the mechanism are structurally insufficient. The expert needs external structural constraints (diverse team, designated dissenter, domain boundary protocols) not internal recalibration.

---

## Finding 5: Short-Format Training Has No Durable Effect

The bootcamp and short-format training literature (relevant because most executive domain training is short-format) reaches a consistent conclusion.

A large-scale study of boot camps and short training formats across 53 US institutions across 115 variables found "no evidence of effectiveness." The conclusion: "boot camps and other short formats may not durably impact student outcomes." (Feldon et al., cited in BioRxiv 2023 consensus paper)

UNESCO's 5th Global Report on Adult Learning and Education (2022) found that only 60% of participating EU countries even use learning outcomes as a quality measure for adult education — and notes that quality assessment is structurally difficult because of the diversity of learner aims and decentralized delivery.

The mechanism: SFT instructors are typically chosen for domain expertise, not pedagogical skill. They often cannot adapt to learner preparedness. The content is bespoke, transient, and hard to replicate.

Applied to domain training for CTOs: a 3-day HealthTech regulatory bootcamp, an accelerator program, or a domain orientation course produces awareness but not competence. The domain knowledge required to lead credibly in a regulated market takes years of operational experience to build — not weeks of structured exposure.

---

## The Compound Problem: Parallelism with People Skills Training

The pattern across both training dimensions is now clear:

| Training Target | Timeline to Competence | Failure/Limitation Rate | Key Barrier |
|---|---|---|---|
| IC → Engineering Manager | 8–15 years (full path) | ~50% reversion at first step | Identity threat; skill incompatibility |
| Domain expert → cross-domain | Years of deliberate practice | Interference from prior expertise; debiasing-resistant | Curse of expertise; deep unlearning required |
| Generalist → domain expert | 6,000–10,000 hours deliberate practice | Structural ceiling effects for adult learners | Acquisition timeline incompatible with company growth |

In each case, training is the industry's optimistic answer. In each case, the mechanism makes full prevention structurally hard. In each case, the timeline is incompatible with what the company needs.

---

## What This Means for the Hiring Decision

The domain training research reinforces the hiring thesis from `13_RESEARCH_domain_centric_CTO.md`:

**You cannot reliably train your way out of a domain mismatch after hiring.**

If a domain-expert CTO is hired into a general tech company, the expectation that they will organically develop cross-domain leadership over 12–18 months is not supported by the evidence. The interference from prior expertise, the timeline required for genuine domain acquisition, and the debiasing resistance of expert cognition all work against it.

If a generalist CTO is hired into a domain-heavy market, the expectation that they will develop domain depth sufficient for Strategist-mode credibility — regulatory fluency, clinical relationships, enterprise compliance knowledge — within the company's growth window is similarly unsupported.

**The correct intervention is at hiring, not after.** The question is not "how do we train the CTO we hired" but "did we hire the CTO whose baseline profile matches the mode and market demands this company faces?"

---

## The One Partial Exception: Domain Exposure with Structural Support

The research does identify one condition under which domain acquisition is meaningfully accelerated:

**Embedded operational experience with structured feedback** — not coursework, not bootcamps, but genuine accountability for domain outcomes in an environment designed to produce rapid feedback.

This maps to the Van Lancker et al. (2023) finding about psychological safety as a condition for role-crafting. A CTO in a domain-heavy market who has a domain expert (VP Engineering, Chief Medical Officer, Chief Compliance Officer) as a structural partner — with explicit license to challenge domain judgments — can develop domain competence faster than one working in isolation.

But this is the paired org design solution (Solution 3 from the rational solutions taxonomy) applied to domain acquisition. It still requires recognizing the gap at hiring time. It does not rescue the post-hoc situation.

---

## Implications for the Paper

The domain training finding strengthens the irrational composite thesis in a specific way:

The thesis currently argues that the three CTO skill sets (technical craft, people infrastructure, strategic vision) are sequentially incompatible — each mode's success behaviors actively interfere with the next mode's requirements.

The domain training research adds a second layer: **within the technical craft dimension itself**, domain depth and domain breadth are in tension. An expert cannot simply acquire adjacent domain competence through awareness and effort — the prior expertise creates interference that debiasing cannot correct.

This means the composite is not just irrational across modes. It is irrational within the Builder mode, if the Builder's domain identity is narrow: the skills that make a domain-expert CTO excellent at founding a HealthTech company are the same skills that make them dangerous when that company expands into adjacent markets.

The irrational composite has a hidden dimension the original taxonomy doesn't capture. The domain axis is that dimension.

---

*Companion documents: `13_RESEARCH_domain_centric_CTO.md` (domain typology), `11_RESEARCH_IC_to_EM_transition.md` (people skills training limits), `12_RESEARCH_rational_solutions.md` (solution taxonomy)*  
*Framework developed in collaboration with Claude Sonnet 4.6 (Anthropic). Research conducted June 2026.*
