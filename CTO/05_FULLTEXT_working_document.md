# CTO Operating Modes Framework — Working Document
## Full text rendering of CTO_Operating_Modes_Working_Document.docx

**Status:** Working draft — not for citation without author permission  
**Collaboration:** Human researcher + Claude Sonnet 4.6 (Anthropic)  
**Date:** June 2026

---

# The CTO Title as Structural Misnomer:
## Why Three Distinct Roles Share One Title, and What Happens When Nobody Names the Difference

---

## Abstract

The title "Chief Technology Officer" is applied uniformly across all stages of startup development despite describing three structurally distinct operating modes that require different skills, produce different outputs, and fail in different ways. We propose a taxonomy of three modes — CTO-Builder, CTO-Multiplier, and CTO-Strategist — grounded in the observation that failure clusters at mode boundaries rather than within modes. We further argue that the CTO title is a structural misnomer inherited from its 1980s enterprise origin, where it was coined specifically to describe what we term the Strategist mode, and subsequently applied unchanged to the Builder mode when startups adopted the title during the dot-com era. This inheritance error has persisted for 35 years without formal correction. The framework is supported by convergent evidence from organizational growth theory, leadership research, startup survival data, and engineering career ladder literature. We identify the implications for hiring, performance evaluation, compensation design, and succession planning, and propose a set of team-level skills that must be present for each mode transition to succeed.

**Keywords:** CTO, startup leadership, organizational growth, role taxonomy, mode transition, Greiner model, Multiplier leadership, engineering team, succession planning, title etymology

---

## 1. Introduction

No other C-suite role is expected to be three fundamentally different jobs within a single tenure. The CFO manages capital at seed stage and still manages capital at Series B. The CMO owns brand and growth at Series A and still owns brand and growth at Series C. The Chief Technology Officer — uniquely among executive titles — is expected to transform their entire operating identity multiple times, without any formal acknowledgment that the job has changed, and without the language to name what the change requires.

This paper argues that the confusion is structural rather than personal. CTOs do not fail at mode transitions because they lack capability. They fail because the industry has never given them a map. The title "CTO" implies a single continuous role. The actual job is three distinct roles that share a name for historical reasons unrelated to functional equivalence.

We begin with the etymological argument — where the title came from and what it originally described — because the history is the problem. We then develop the taxonomy, establish the failure evidence, map the skills that need to exist at the team level, and close with implications for practice.

The central claim is simple: the CTO title has always described the Strategist mode. It was coined in that context, by enterprises that already had hundreds of engineers running beneath the person receiving the title. When startups adopted it during the dot-com era, they applied it to someone who was often the only engineer in the room — a Builder, not a Strategist — and then expected that person to traverse the entire distance to Strategist over the course of a single company's life, without ever naming the distance or the transitions along the way.

### 1.1 The Misnomer Stated

The title "CTO" is a misnomer in startup contexts in three senses. **First**, it emphasizes the wrong skill: "Technology" centers technical depth as the primary qualifier, but as we document, technical depth is a threshold requirement at every mode, not the differentiating skill at any of them. **Second**, it implies singularity: one title, one job, one continuous role. The data shows three structurally distinct jobs, with failure clustering at the transitions between them rather than within any mode. **Third**, and most consequentially, the title was borrowed from an enterprise context where it described the Strategist mode, and applied without modification to startup contexts where it describes the Builder mode. The same three letters have meant opposite things for 35 years, and nobody has formally named that gap.

Nathan Myhrvold, Microsoft's CTO and one of the few people whose role closely resembled the original enterprise definition of the title, captured the ambiguity plainly when asked to name great CTOs: "many of the people who actually were great CTOs didn't have that title, and at least some of the people who have that title arguably aren't great at it."

The confusion Myhrvold observed is not accidental. It is what the title was structurally designed — by omission — to produce.¹⁰

---

## 2. The Origin and Migration of the CTO Title

### 2.1 Enterprise Origin: Late 1980s

The CTO title was created in the late 1980s by large industrial corporations as their R&D Laboratory Director roles evolved into positions requiring a seat at the executive table. The first formal academic documentation came from Adler and Ferdows in 1990, who identified 25 self-identified CTOs in a study of 100 of the most successful US industrial companies. The paper was seven pages long.¹

The companies that first created the role — GE, Allied-Signal, ALCOA — were not startups. They were large industrial organizations with established engineering functions, hundreds or thousands of technical employees, and an existing VP of Engineering (or equivalent) already managing day-to-day delivery. The CTO was created to sit *above* that function — to own technology strategy, R&D vision, long-horizon platform bets, external scientific relationships, and patent portfolio management.²

In our taxonomy, the original enterprise CTO was a Strategist from day one, operating at a company that had already passed through Builder and Multiplier stages decades earlier. The title described a specific operating mode — the most senior, most outward-facing, least hands-on mode — at a specific organizational scale.

### 2.2 Startup Migration: 1990s Dot-Com Era

During the dot-com boom of the 1990s, startups adopted the CTO title wholesale. The adoption was understandable — the title signaled technical credibility to investors and partners, and the industry had no alternative vocabulary for "senior technical person with equity."

But the title migrated without its role definition migrating with it. A startup CTO in 1998 was typically a technical co-founder — the only engineer in the room, or one of two or three. They were writing code, selecting a stack, building the MVP, and making every technical decision directly. They were, in our taxonomy, a Builder operating at maximum intensity with minimum support.

This is structurally the opposite of the enterprise CTO the title was coined to describe. The enterprise CTO had an entire engineering organization running beneath them. The startup CTO had no team at all. The title was applied to both, and the distance between them was never named.

### 2.3 The Inheritance Error

The consequence of this migration is that every startup CTO since 1990 has inherited a title with three layers of embedded confusion:

- The title implies their primary qualification is technical depth, when the differentiating skills at every transition point are organizational and interpersonal.
- The title implies a single continuous role, when the actual job changes structurally two to three times during a typical startup journey.
- The title describes the endpoint of the journey (Strategist) while being applied to the starting point (Builder), creating a permanent gap between what the title says and what the job currently requires.

This inheritance error has persisted because it is invisible to the people experiencing it. A CTO-Builder who does not know they are being asked to become a CTO-Multiplier has no framework for understanding why the things that made them successful are now producing failure. The confusion looks like a personal failing. It is a structural one.

---

## 3. The CTO Operating Modes Taxonomy

We propose three operating modes that describe the structurally distinct jobs contained within the CTO title across startup growth stages. The modes answer the question: *how does the CTO work?* Each describes a different mechanism of contribution rather than a different level of seniority.

| Mode | Stage | How the CTO works | Primary output | Failure mode |
|---|---|---|---|---|
| **CTO-Builder** | Pre-seed through Seed | Directly — hands on product, architecture, code, decisions | The product | Builder becomes bottleneck, never transitions |
| **CTO-Multiplier** | Seed→A transition through Series A | Through amplifying others — coaching, delegating, installing infrastructure | Team capability | Reverts to Builder under pressure (TEE, alignment trap, burnout) |
| **CTO-Strategist** | Series B through B+ | Through vision and influence — board, external, long-horizon bets | Direction | Stays in Multiplier mode, still managing internally when job has gone external |

### 3.1 CTO-Builder

The Builder operates through direct action. The primary contribution is the product itself. At this mode, the CTO is typically the most technically capable person in the company, and that capability is the company's primary technical asset.

The Builder's skills — architectural judgment, stack selection, rapid iteration, technical decision-making under uncertainty — are appropriate and necessary for the stage. The failure mode is not incompetence. It is continuation: a Builder who does not transition to Multiplier when the organization requires it becomes a bottleneck, not because they are doing anything wrong, but because the organization has outgrown the mode.

### 3.2 CTO-Multiplier

The Multiplier operates through amplification. The primary contribution is team capability. The name is grounded in Wiseman's research across 150 executives and 35 companies, which found that Multiplier leaders consistently extract 2x the output from the same team as Diminisher leaders — not through harder work, but through better use of the intelligence already present.⁴

The Multiplier's failure mode is the most consequential in the taxonomy because it is the most common and the most misattributed. When a CTO-Builder reverts to Builder mode under Series A scaling pressure — micromanaging, retaining decision authority, refusing to delegate — the failure looks like a personal character flaw. It is actually a rational response to ambiguity in the absence of a transition framework. The person is doing more of what made them successful, precisely when the company needs them to do less of it.

The Transitive Expert Error (TEE) framework provides mechanistic support for why this failure is predictable rather than exceptional: domain expertise actively creates vulnerability at domain boundaries, because the same pattern-recognition systems that produce high accuracy within a domain confidently misfire when applied to structurally different adjacent domains.⁹

### 3.3 CTO-Strategist

The Strategist operates through influence. The primary contribution is direction. The failure mode documented at the First Round CTO Summit is precise: a Strategist who remains in Multiplier mode — still managing the engineering organization directly — when the job has shifted to board communication, external representation, and long-horizon platform vision. The engineering organization loses strategic coherence while the CTO loses the board's confidence in both.⁷

Note that the Strategist mode most closely resembles the original enterprise CTO role described by Adler and Ferdows in 1990. This is not coincidental. The enterprise CTO title was coined to describe exactly this function. The taxonomy is, in part, a recovery of that original meaning — extended backwards to account for the two modes that precede it in the startup context.

---

## 4. Failure Clustering at Mode Boundaries

The central empirical prediction of the taxonomy is that CTO failures should cluster at mode boundaries rather than being evenly distributed across stages. We examine the available evidence for both transition points.

### 4.1 Builder to Multiplier Boundary

The Builder→Multiplier boundary corresponds to the Seed→Series A transition, which Carta and Crunchbase data identifies as one of two distinct high-attrition points in the venture lifecycle.⁶

This maps directly to what Greiner (1972) identified as the "leadership crisis" — the first revolutionary period in organizational growth, triggered specifically by the transition from creativity-led growth to direction-led growth. Greiner's description of the crisis is precise: "the entrepreneur may not solve these problems effectively because they may not be suited for the kind of job or they may not be willing to handle such problems." The CTO-Builder who cannot become a CTO-Multiplier is experiencing Greiner's leadership crisis.³

Project Oxygen's finding that technical skill ranked last among differentiating manager behaviors supports this mechanistically: the skills that make a Builder successful are not the skills that determine Multiplier effectiveness. The transition requires acquiring an entirely different capability set, not improving on the existing one.⁵

### 4.2 Multiplier to Strategist Boundary

The Multiplier→Strategist boundary corresponds to the Series A→B transition. Among startups that secure Series A funding, approximately half reach Series B — the failure rate at this boundary is comparable to the Builder→Multiplier boundary but receives less research attention because the failures are less visible: a Multiplier who cannot become a Strategist produces a company that stalls rather than one that collapses.

The failure mode at this boundary is distinct: the Strategist who remains a Multiplier produces an engineering organization that loses external alignment. The board sees a CTO who is still managing internally when the company needs technology vision at the strategic level. The engineering organization loses its connection to external market forces. The failure accumulates slowly and is often attributed to strategy rather than leadership mode.

### 4.3 Within-Mode Stability

Within each mode, the evidence suggests relative stability. A CTO operating in the appropriate mode for their company's stage does not typically fail at that mode's primary function. The failures that appear to occur within modes — poor architecture decisions, team culture problems, missed delivery — are better explained as mode mismatches: a Builder operating at a company that requires a Multiplier, or a Multiplier operating at a company that requires a Strategist.

This within-mode stability is the key structural prediction of the taxonomy. It distinguishes our framework from general competency models, which predict that better CTOs outperform weaker ones at all stages. The taxonomy predicts instead that mode-appropriate CTOs outperform mode-mismatched ones regardless of individual capability — a highly capable Builder in Multiplier-stage conditions will produce worse outcomes than a moderately capable Multiplier in the same conditions.

---

## 5. Independent Validation: The Greiner Alignment

Greiner's organizational growth model (1972, revised 1998) was developed independently of any CTO-specific research and is not cited in the CTO literature. Its convergence with the three-mode taxonomy is therefore noteworthy rather than circular.

Greiner identified five phases of organizational growth, each ending in a specific crisis that must be resolved before the next phase can begin. The first three phases map precisely onto the three CTO operating modes:³

| Greiner phase | Growth through… | Crisis at end | CTO mode |
|---|---|---|---|
| Phase 1 | Creativity | Leadership crisis | **Builder** |
| Phases 2–3 | Direction, then Delegation | Autonomy crisis, then Control crisis | **Multiplier** |
| Phases 4–5 | Coordination, then Collaboration | Red-tape crisis, then Internal solutions crisis | **Strategist** |

The alignment is not exact — Greiner collapses what we distinguish as two separate Multiplier sub-phases (direction and delegation), and his model covers organizational growth broadly rather than CTO roles specifically. But the structural correspondence is strong enough to treat as independent validation: a framework developed in 1972 from organizational data produces the same three functional zones as a framework developed in 2026 from CTO failure data.

---

## 6. The Mode Names: Selection Rationale

The three mode names — Builder, Multiplier, Strategist — were selected to answer the question: *how does the CTO work?* Each name describes a mechanism of contribution rather than a level of seniority or a domain of expertise.

### 6.1 Builder

Builder describes direct contribution. The CTO works by making things: product, architecture, early hires, culture baseline. The name is universally legible across all actor types — investors, board members, technical candidates, and CEOs all read it without ambiguity.

*Steelman:* Builder could imply the CTO works alone, which slightly undersells the informal people management that exists even at seed stage. This is a minor limitation accepted in favor of legibility.

### 6.2 Multiplier

Multiplier describes amplification through others. The CTO works by making the team more capable — coaching, delegating authority, installing feedback infrastructure, setting development standards. The name is grounded in Wiseman's empirically validated leadership research and carries a specific, testable meaning: a Multiplier produces 2x the output from the same team as a Diminisher.⁴

The Multiplier name does more theoretical work than Builder or Strategist. The Wiseman research defines a specific failure type — the Diminisher — that maps directly onto the control-collapse pattern we observe at the Builder→Multiplier boundary. A domain-expert CTO who micromanages, retains decision authority, and creates dependency is not failing to be a Multiplier. They are being a Diminisher, which is the defined opposite of the Multiplier mode.

*Steelman:* Multiplier requires one beat of processing from actors unfamiliar with Wiseman's research, and could be misread as a financial or mathematical term. Mitigated by brief definition wherever the taxonomy is used. The theoretical precision justifies the minor legibility cost.

### 6.3 Strategist

Strategist describes influence through vision. The CTO works at a distance — board relationships, external credibility, long-horizon technical bets, representing the company's technical identity to investors and market. The name is immediately legible to senior audiences and accurately describes the *how* of the mode.

*Steelman:* Strategist could be claimed prematurely — a CTO-Multiplier is already doing some strategic thinking. The counter is that all modes contain elements of adjacent modes; the subtitle names the dominant *how*, not the exclusive one.

### 6.4 Naming as Invitation to Peer Review

The mode names are working titles. The taxonomy's structural claim — that the CTO role contains three functionally distinct modes with failure clustering at boundaries — is separable from any particular choice of names. If peer review produces better names that survive the actor test more cleanly, that is a refinement, not a refutation.

---

## 7. Team-Level Skills and Mode Transitions

A CTO cannot successfully transition modes until the team has the capacity to receive what the CTO is handing off. This is the load-bearing principle of the skills framework. Most failed transitions occur not because the CTO lacks the will to change modes, but because the organizational infrastructure to support the change does not yet exist.

Two transfer mechanisms:
- **People-delegation:** skill transfers to a specific person (VP Eng, EM, Tech Lead). Creates key-person risk.
- **System-institutionalization:** skill bakes into process, tool, or documented standard. More resilient to turnover.

### 7.1 Builder to Multiplier: Gate 1
*Typically ~10–20 engineers, post-PMF*

**Technical readiness:**
- Architecture documented beyond the CTO's head — at least one engineer can explain the system independently
- CI/CD pipeline exists and is understood by team
- On-call rotation possible without CTO always present
- Technical debt is catalogued, not just experienced

**People readiness:**
- At least one senior engineer capable of technical leadership
- Hiring process documented — not purely CTO-network-dependent
- Engineers can complete work without daily CTO input
- First EM hire made or imminent
- No single engineer is a key-person risk other than CTO

**Process readiness:**
- Sprint cadence exists in some form
- Code review process established
- Basic onboarding documentation exists
- CTO has started saying "let X decide" in technical discussions
- At least one process runs without CTO involvement

> **Failure signal:** CTO delegates authority before the team has capability to receive it. Engineers escalate everything back up. CTO returns to Builder mode under pressure. Transition fails leaving a trust deficit.

### 7.2 Multiplier to Strategist: Gate 2
*Typically ~50–100 engineers, Series B readiness*

**Leadership readiness:**
- VP Engineering or Head of Engineering in place and effective
- EMs running 1:1s and performance reviews without CTO prompting
- Career ladder in use — promotions happen without CTO as sole decision-maker
- At least one EM could step up into VP Eng role temporarily
- Engineering culture survives CTO absence of 2+ weeks

**Process readiness:**
- DORA metrics or equivalent tracked and improving
- Incident response runs without CTO for P1/P2
- Technical roadmap exists independently of product roadmap
- Quarterly planning process runs consistently

**Strategic readiness:**
- CTO has presented to board independently at least once
- CTO can articulate 2-year technology vision to non-technical audience
- At least one strategic vendor/platform relationship owned by CTO
- CTO spends <30% of time on operational engineering decisions
- CTO has external presence — conference, writing, or industry network

> **Failure signal:** CTO moves into Strategist activities before VP Eng is strong enough. Engineering org loses direction. CTO gets pulled back in. Board loses confidence in both CTO and engineering function simultaneously.

---

## 8. Implications for Practice

### 8.1 Hiring
A company hiring a CTO should be hiring for a specific mode. Builder interview criteria: almost entirely technical and product-focused. Multiplier criteria: predominantly people and organizational. Strategist criteria: primarily strategic and communicative.

Conflating these produces: hiring a CTO-Strategist for a Builder-stage company (can't contribute at hands-on execution level), or hiring a CTO-Builder for a Multiplier-stage company (can't build organizational infrastructure).

### 8.2 Performance Evaluation
A CTO should be evaluated against the criteria for their current mode. A CTO-Builder evaluated on board communication skills appears to be failing at something irrelevant. A CTO-Multiplier evaluated on lines of code appears to be disengaging from their technical role when they are actually succeeding at their actual job.

The mode transition itself should be an explicit performance milestone, not an informal expectation.

### 8.3 Compensation
Founding CTOs earn $57K–$116K less than hired CTOs at equivalent stages.⁸ The equity offset is speculative — most startups do not reach liquidity — and standard four-year vesting does not reflect the step-function nature of CTO value creation at mode boundaries.

The taxonomy suggests: phase-completion equity with explicit transition milestones rather than time-based vesting alone. A CTO-Builder who successfully navigates the Builder→Multiplier transition has delivered a step-function increase in organizational value.

### 8.4 Succession Planning
Key questions to ask proactively:
- What mode is the current CTO operating in?
- What mode does the company currently require?
- Is there a gap? Skill gap or willingness gap?
- What support structures — coaching, VP Eng hire, board advisor — would make the transition viable?
- What is the planned succession if the transition is not viable?

### 8.5 The Investor Case
The taxonomy provides a diligence framework: a CTO operating in a mode that does not match the company's current stage is a material risk, regardless of individual capability. A founder who can articulate their CTO's current mode, the transition criteria for the next mode, and the organizational readiness conditions for that transition is demonstrating leadership self-awareness that has no current equivalent in standard diligence practice.

---

## 9. Limitations and Future Research

### 9.1 Survivorship Bias
Failure literature disproportionately represents unsuccessful transitions. Index Ventures data suggests 78% of successful companies had a founding CTO **or technical CEO**,¹¹ (a 210-company dataset — *not* "founding CTO at seed"; the disjunction means this is not evidence specifically about founding CTOs — corrected per `07_APPENDIX` #12 / `AX-INDEX78`) but longitudinal data on how many remained through Series B is not available.

### 9.2 Empirical Validation
The taxonomy is grounded in component-level evidence but has not been tested as an integrated framework. Direct empirical testing would require longitudinal tracking of CTO operating mode against company outcomes, with mode assessed independently of outcome.

### 9.3 Internal Multiplier Sub-Transition
The Multiplier mode collapses what Greiner treats as two separate phases (direction and delegation). The simplification is defensible for the actor test but means the Multiplier mode contains an internal transition: directing a team of 8 engineers is meaningfully different from delegating to a VP Eng and three EMs.

### 9.4 Domain and Industry Variation
Stage thresholds are approximate and based primarily on B2B SaaS data. Deep tech, biotech, hardware, and regulated industries may shift boundaries significantly.

### 9.5 Research Agenda
1. What proportion of founding CTOs successfully navigate both mode transitions within a single company, and what predicts success?
2. Does mode mismatch predict company outcomes independently of individual CTO capability?
3. What is the empirical distribution of mode transition timing across industries and funding stages?
4. Does explicit naming of mode transitions improve transition success rates?

---

## 10. The Irrational Composite: Why the CTO Skill Set Cannot Develop Naturally

The preceding sections establish that the CTO role contains three structurally distinct operating modes. This section advances a stronger claim: the skills required for each mode not only fail to develop together — they actively develop in opposition to each other.

### 10.1 The IC / Management Track Bifurcation

The engineering industry has formally recognized the incompatibility of deep technical skill and people management skill by creating two distinct, parallel career tracks.¹²

- The IC track rewards: technical depth, architecture expertise, cross-team technical influence
- The management track rewards: people leadership, organizational design, strategic execution

These tracks diverge meaningfully around the senior engineer level (typically 4–7 years into a career) and become increasingly difficult to traverse in either direction thereafter.

Within 2–3 years of moving to management, technical skills atrophy because people management demands displace deliberate technical practice.¹³ The CTO role at seed stage requires both simultaneously, at full intensity.

### 10.2 The Three Skills Are Sequentially Incompatible

**Builder → Multiplier:** The Builder's success depends on technical depth, decisive unilateral action, and direct ownership. The Multiplier requires releasing ownership, tolerating slower decisions made by others, and investing time in human development that produces no immediate technical output. Every habit that makes a great Builder actively interferes with becoming a Multiplier.

**Multiplier → Strategist:** The Multiplier's success depends on organizational presence, team relationships, and process visibility. The Strategist must reduce internal presence, invest in external relationships with no direct team benefit, and operate on 2–5 year horizons. Every habit that makes a great Multiplier actively interferes with becoming a Strategist.

This is not a failure of will or awareness. It is a structural property of the skill sets themselves.

### 10.3 Convergence with Larson's Staff Engineer Archetypes

Will Larson's Staff Engineer research — developed entirely without reference to CTO taxonomy literature — found that large engineering organizations solve the skill incompatibility problem by distributing the composite across distinct roles.¹⁴

| Larson archetype | Emerges at | CTO mode | What it distributes |
|---|---|---|---|
| Architect | ~100 engineers | **Builder** | Technical direction and quality within a critical domain |
| Solver | Variable | **Builder** | Crisis Builder — direct technical action on hardest problems |
| Tech Lead | Most teams | **Multiplier** | Guides team approach and execution without management authority |
| Right Hand | ~1,000 engineers | **M → S bridge** | Extends executive attention and authority back into the Multiplier layer |

Larson identified the same structural problem we identify in the CTO title: "most career ladders paper over several distinct roles hidden behind a single moniker."¹⁴

### 10.4 The Composite Demand is Temporally Concentrated

At Series B+, the Architect, Tech Lead, and VP Engineering exist as distinct roles. The CTO-Strategist is no longer expected to be a Builder or Multiplier. The composite has been distributed.

The irrationality is concentrated in pre-seed through Series A — when the company is most vulnerable, the CTO is most alone, the peer gap is widest, and the compensation model defers reward to an outcome statistically most companies won't reach.

The research classification exercise confirms this: of 35 research threads examined, the overwhelming majority map to Multiplier mode. Builder mode has almost no empirical research. Strategist mode has none. The irrationality is concentrated in the stages where research is thinnest — precisely because researchers study managers of existing teams, not people doing three structurally incompatible jobs simultaneously before any team exists.

### 10.5 The Central Claim, Restated

The CTO role at seed stage demands a composite of three skill sets — technical craft, people infrastructure, and executive strategy — that the industry's own career architecture has formally recognized as incompatible by splitting them into separate tracks and separate roles at scale.

The industry solution to this incompatibility at Series B+ is role distribution. The industry's non-solution at seed stage is to collapse the distribution into one person, give them a title coined for the third skill set, provide no framework for the transitions between skill sets, and attribute the resulting failures to individual inadequacy.

This is not a critique of any individual CTO. It is a description of a structural design failure in how the industry builds its earliest technical leadership layer — one that has persisted for 35 years because the title inherited from enterprise contexts carried no instruction manual, and the people experiencing the failure had no language to name what was happening to them.

---

## 11. Conclusion

The CTO title has been a structural misnomer since its adoption by startups in the 1990s. Coined to describe an enterprise executive operating in what we term the Strategist mode — outward-facing, board-communicating, vision-setting — it was applied unchanged to startup technical co-founders operating in the Builder mode — hands-on, code-writing, product-making. The same three letters have described opposite functions for 35 years.

The confusion this produces is not accidental. It is what the title, by structural omission, was guaranteed to produce. A CTO who has never been told their job has three distinct modes cannot be expected to navigate the transitions between them. The failure that results looks like personal inadequacy. It is organizational design failure.

The taxonomy proposed here — CTO-Builder, CTO-Multiplier, CTO-Strategist — is an attempt to name what has been unnamed. The three modes describe how the CTO works at each stage: directly, through amplifying others, and through vision and influence. The failure modes cluster at the boundaries between modes, not within them. The skills required for each mode are largely orthogonal to the skills required for the adjacent modes. And the team must be organizationally ready to receive what the CTO is handing off before any transition can succeed.

This framework will require empirical validation. The mode names may be refined by peer review. The stage thresholds may shift with industry-specific data. But the structural claim — that the CTO title contains three distinct jobs, that the industry has treated them as one, and that this conflation is the proximate cause of a predictable and preventable pattern of failure — is grounded in converging evidence from organizational theory, leadership research, survival data, and a 35-year inheritance error that is now nameable.

Every CTO who has experienced the transition failures described here was not failing at their job. They were doing one job when the company needed a different one, and nobody had ever given them the language to see the difference.

This document is an attempt to provide that language.

---

## References

1. Adler, P.S. and Ferdows, K. (1990). The Chief Technology Officer. California Management Review, 32(3), 55–62.
2. Smith, D.K. (2002). Cited in Jasinski, M. (2018). Hidden Chief Technology Officers. Triple Helix Journal, SpringerOpen.
3. Greiner, L.E. (1972, revised 1998). Evolution and Revolution as Organizations Grow. Harvard Business Review.
4. Wiseman, L. and McKeown, G. (2010). Multipliers: How the Best Leaders Make Everyone Smarter. HarperBusiness.
5. Google Project Oxygen (2009–2018). What Makes a Great Manager? Published via re:Work (rework.withgoogle.com).
6. Carta / Crunchbase (2024–2025). Venture Survival Rate Analysis.
7. First Round Capital CTO Summit (practitioner research).
8. Kruze Consulting (2024). Startup CTO Salary Guide. Payroll data from 250+ US VC-backed startups.
9. Mars, F. (2026). Transitive Expert Error and Routing Problems in Complex AI Systems. Preprint.
10. Myhrvold, N. (attributed). On the CTO title definition.
11. Index Ventures. Rewarding Talent. Cap table analysis across 73 portfolio companies.
12. Ewing, R. IC vs. Management Track.
13. HR Oasis (2026). Tech Career Paths: IC vs Manager.
14. Larson, W. (2021). Staff Engineer: Leadership Beyond the Management Track.

---

*Working document. Research in progress. Not for citation without author permission.*  
*Framework developed in collaboration with Claude Sonnet 4.6 (Anthropic). Research conducted June 2026.*
