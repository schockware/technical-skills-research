# Artifact: team-skills-compendium.html
## Summary for Claude instances

**Type:** Interactive HTML document  
**Status:** Complete  
**Purpose:** Three-layer reference document mapping skills across modes, roles, and transition readiness

---

## Structure

### Layer 1 — Skills Compendium
Master list of all skills required across all three CTO operating modes, mapped by:
- Who owns the skill at each mode (CTO, VP Eng, EM, Tech Lead)
- How the skill transfers when the CTO changes modes

**Transfer types:**
- `→ people` — skill delegates to a specific person (creates key-person risk)
- `→ system` — skill bakes into process, tooling, or documentation (resilient to turnover)
- `→ both` — partially delegates, partially institutionalized

**Four skill domains covered:**

| Domain | Skills included |
|---|---|
| Technical Architecture | Stack selection, system architecture, technical debt, build/infrastructure, security posture |
| People & Team | Hiring judgment, 1:1s/feedback, career development, performance management, culture definition, psychological safety |
| Process & Delivery | Sprint/delivery process, engineering metrics, incident response, documentation standards, technical roadmap |
| Strategy & Business | Board communication, investor relations, make vs buy decisions, technology vision, emerging tech radar |

**Key transfer insight:** Skills that delegate to people create key-person risk. Skills that institutionalize into systems create organizational resilience. Mature mode transitions aim for system-institutionalization with people-delegation as a bridge.

---

### Layer 2 — Role-Based Rubric
Grid showing what each role owns at each mode:

| Role | Builder mode | Multiplier mode | Strategist mode |
|---|---|---|---|
| CTO | Owns everything technical | People infrastructure, org design, coaching | External/strategic, board narrative, 3-5yr vision |
| VP Eng | Does not yet exist | Delivery focus, headcount, cross-team coord | Owns engineering organization entirely |
| Engineering Manager | Does not yet exist | Team health, 1:1s, sprint execution | Team execution layer |
| Tech Lead / Staff | Senior engineer executes within CTO's architecture | Technical authority for domain | Principal: cross-org architecture; Staff: domain ownership |

**Notable:** In Builder mode, VP Eng and EM roles typically don't exist. The rubric makes this explicit rather than leaving it implicit.

---

### Layer 3 — Mode Transition Maturity Gates

**Gate 1: Builder → Multiplier**
*Typically ~10-20 engineers, post-PMF*

Technical readiness checklist:
- Architecture documented beyond CTO's head
- CI/CD pipeline understood by team
- At least one engineer can explain system architecture independently
- On-call rotation possible without CTO always present
- Technical debt catalogued

People readiness checklist:
- At least one senior engineer capable of technical leadership
- Hiring process documented (not purely CTO-network-dependent)
- Engineers can complete work without daily CTO input
- First EM hire made or imminent
- No single engineer is key-person risk other than CTO

Process readiness checklist:
- Sprint cadence exists
- Code review process established
- Basic onboarding documentation exists
- CTO has started saying "let X decide" in technical discussions
- At least one process runs without CTO involvement

**Failure signal if transition forced without readiness:** CTO delegates authority before team has capability to receive it. Engineers escalate everything back. CTO returns to Builder mode. Transition fails leaving trust deficit.

---

**Gate 2: Multiplier → Strategist**
*Typically ~50-100 engineers, Series B readiness*

Leadership readiness:
- VP Engineering or Head of Engineering in place and effective
- EMs running 1:1s and performance reviews without CTO prompting
- Career ladder in use — promotions happen without CTO as sole decision-maker
- At least one EM could step up into VP Eng role temporarily
- Engineering culture survives CTO absence of 2+ weeks

Process readiness:
- DORA metrics or equivalent tracked and improving
- Incident response runs without CTO for P1/P2
- Technical roadmap exists independently of product roadmap
- Quarterly planning process runs consistently
- Board can receive engineering update from VP Eng if needed

Strategic readiness:
- CTO has presented to board independently at least once
- CTO can articulate 2-year technology vision to non-technical audience
- At least one strategic vendor/platform relationship owned by CTO
- CTO spends <30% of time on operational engineering decisions
- CTO has external presence (conference, writing, or industry network)

**Failure signal if transition forced without readiness:** CTO moves into Strategist activities before VP Eng is strong enough. Engineering org loses direction. CTO gets pulled back in. Board loses confidence in both CTO and engineering function simultaneously.

---

## Design notes

- Color coding: Purple = Builder, Teal = Multiplier, Blue = Strategist
- Transfer badges: Amber = people delegation, Red-orange = system institutionalization
- Warning items (⚠) in gates are leading indicators — signals transition is approaching, not that it's already ready
- Built with vanilla HTML/CSS, no dependencies, self-contained
