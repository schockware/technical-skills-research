# HTML Artifacts — Full Text Rendering
## team-skills-compendium.html + cto-transition-brief.html

---

# ARTIFACT A: Team Skills Compendium
## team-skills-compendium.html

*A three-layer document mapping skills required at each CTO operating mode, how they distribute across roles as the CTO transitions, and what the team must collectively demonstrate before a mode transition is viable.*

**Transfer types:**
- `→ people` — skill delegates to a person when CTO transitions
- `→ system` — skill bakes into process, tooling, or documentation
- `→ both` — partially delegates, partially institutionalized

---

## Layer 1 — Skills Compendium

*Master list of all skills required across all modes, who owns them at each stage, and how they transfer when the CTO moves up. Skills do not disappear — they redistribute.*

### Domain: Technical Architecture
*How the system is designed, built, and evolved*

| Skill | Builder owns | Multiplier owns | Strategist owns | Transfer |
|---|---|---|---|---|
| Stack selection | CTO makes all calls directly. Speed over perfection. | CTO sets guardrails. Tech leads own decisions within them. | VP Eng owns. CTO approves only major platform bets. | → people |
| System architecture | CTO is the architect. Design lives in their head. | CTO documents decisions (ADRs). Begins mentoring architects. | Staff/Principal Engineers own. CTO reviews strategic bets only. | → both |
| Technical debt management | CTO tracks informally. Accepts debt to ship. | CTO installs debt registry and prioritization process. | VP Eng owns quarterly debt review. Process runs without CTO. | → system |
| Build/infrastructure | CTO sets up. May be the only person who knows it. | CTO documents and hands off. DevOps hire or rotation. | Platform/DevOps team owns. CTO directs investment level only. | → both |
| Security posture | CTO makes basic decisions. Often deferred. | CTO installs security review process and ownership model. | Dedicated security function. CTO owns regulatory/board narrative. | → both |

### Domain: People & Team
*How talent is found, developed, and retained*

| Skill | Builder owns | Multiplier owns | Strategist owns | Transfer |
|---|---|---|---|---|
| Hiring judgment | CTO interviews and decides all technical hires. Network-driven. | CTO builds hiring process. EMs own sourcing. CTO closes seniors. | VP Eng owns pipeline. CTO attracts via brand and thought leadership. | → both |
| 1:1s and feedback | CTO does informal check-ins. No structured 1:1s yet. | CTO runs structured 1:1s. Installs feedback culture. Models it. | EMs own 1:1s. CTO does skip-levels quarterly. Process runs itself. | → people |
| Career development | Informal. CTO gives ad hoc guidance. No ladder yet. | CTO installs career ladder. Owns first promo decisions. | Career framework runs without CTO. EMs/Directors own growth conversations. | → system |
| Performance management | CTO handles directly. No formal process. | CTO installs review cadence. Owns difficult conversations initially. | EMs own performance cycles. VP Eng handles escalations. CTO rarely involved. | → both |
| Culture definition | CTO is the culture. Implicit, not explicit. | CTO makes culture explicit — writes principles, models behaviors. | Culture is institutionalized. New hires absorb it without CTO present. | → system |
| Psychological safety | Determined by CTO's personal style. Often accidental. | CTO actively builds — blameless postmortems, feedback channels, safe dissent. | Embedded in team norms. Survives CTO absence. Measured regularly. | → system |

### Domain: Process & Delivery
*How work gets planned, executed, and measured*

| Skill | Builder owns | Multiplier owns | Strategist owns | Transfer |
|---|---|---|---|---|
| Sprint/delivery process | Ad hoc. CTO decides what ships and when. | CTO installs Agile/Scrum. Coaches EMs to run it. Steps back. | EMs own sprints. CTO reviews quarterly roadmap alignment only. | → both |
| Engineering metrics | CTO tracks velocity intuitively. No formal metrics. | CTO installs DORA metrics or equivalent. Creates dashboards. | Metrics run automatically. CTO uses them for board narrative, not daily ops. | → system |
| Incident response | CTO is primary responder. On-call by default. | CTO installs on-call rotation and runbooks. Removes themselves. | On-call program runs without CTO. CTO is notified for P0 only. | → both |
| Documentation standards | Minimal. Knowledge lives in CTO's head — key-person risk. | CTO mandates and seeds documentation. ADRs, runbooks, onboarding docs. | Documentation culture self-sustains. New hires document without prompting. | → system |
| Technical roadmap | CTO holds roadmap. Product and tech interchangeable. | CTO separates tech roadmap from product. Installs quarterly planning. | VP Eng owns execution roadmap. CTO owns 2-year technology vision. | → people |

### Domain: Strategy & Business
*How technology connects to business outcomes and external stakeholders*

| Skill | Builder owns | Multiplier owns | Strategist owns | Transfer |
|---|---|---|---|---|
| Board communication | Not yet required. | CTO begins attending board meetings. Learns to translate tech for business audience. | CTO owns board technology narrative. Drives technology agenda items. | → people |
| Investor relations | CTO supports CEO in technical due diligence. | CTO presents tech strategy independently. Explains architecture to non-technical investors. | CTO leads technical diligence. Builds investor confidence in platform. | → people |
| Make vs. buy decisions | CTO decides based on technical preference. | CTO introduces business-case framework. Involves finance and product. | VP Eng brings recommendations. CTO approves strategic vendor relationships. | → both |
| Technology vision | CTO has implicit vision. Rarely articulated beyond next sprint. | CTO articulates 12-month tech vision. Aligns with CEO on product direction. | CTO owns 3–5 year platform vision. Shapes company's technical identity externally. | → people |
| Emerging technology radar | CTO tracks what's relevant to current build. | CTO introduces structured technology radar process. Involves senior engineers. | CTO owns external scanning. Thought leadership. Conference presence. Industry relationships. | → people |

---

## Layer 2 — Role-Based Rubric

*What each role in the engineering org must cover at each mode. As the CTO transitions up, the roles below absorb what the CTO was doing.*

### CTO-Builder Mode · Pre-seed through Seed

| CTO | VP Eng / Head of Eng | Engineering Manager | Tech Lead / Staff Eng |
|---|---|---|---|
| **Owns everything technical:** Architecture and stack, all hiring decisions, delivery and on-call, product-tech integration, direct IC contribution | *Role does not yet exist. CTO fills this function.* | *Role does not yet exist at most seed companies. CTO fills informally.* | **If present — Senior Engineer:** Executes within CTO's architecture, owns specific system components, informal mentoring of juniors, code review and quality bar |

### CTO-Multiplier Mode · Seed→A through Series A

| CTO | VP Eng / Head of Eng | Engineering Manager | Tech Lead / Staff Eng |
|---|---|---|---|
| **People infrastructure:** Installs feedback culture, defines career ladder, owns org design decisions, coaches EMs into their roles, delegates technical decisions, sets development standards | **Emerging role — delivery focus:** Owns sprint planning and execution, manages engineering headcount, technical debt prioritization, cross-team coordination, hiring pipeline management | **Team health and delivery:** Runs structured 1:1s, owns team performance, sprint execution, first line of engineer support, removes team blockers | **Technical authority:** Architecture decisions for domain, code review standards, technical onboarding, engineering best practices, mentors mid-level engineers |

### CTO-Strategist Mode · Series B through B+

| CTO | VP Eng / Head of Eng | Engineering Manager | Tech Lead / Staff Eng |
|---|---|---|---|
| **External and strategic:** Board technology narrative, 3–5 year platform vision, technical M&A diligence, industry presence, talent brand and attraction, executive peer relationships | **Owns engineering organization:** Hiring and org structure, engineering culture and values, delivery velocity and quality, budget and headcount, EM performance and growth, roadmap execution | **Team execution layer:** All people management for their team, sprint health and delivery, career development conversations, escalation management, cross-functional coordination | **Technical depth and breadth:** Principal: cross-org architecture; Staff: domain technical ownership; emerging technology evaluation; technical standards and review; mentors engineers at all levels |

---

## Layer 3 — Mode Transition Maturity Gates

*What the team must collectively demonstrate before a mode transition is viable. These are not CTO performance reviews — they are organizational readiness checks. A CTO-Builder cannot become a CTO-Multiplier until the team has the structure to receive what the CTO is handing off.*

### Gate 1: Builder → Multiplier
*Typically ~10–20 engineers · Post-PMF*

**Technical readiness:**
- ✓ Architecture documented — not just in CTO's head
- ✓ CI/CD pipeline exists and is understood by team
- ✓ At least one engineer can explain system architecture independently
- ✓ On-call rotation possible without CTO always on it
- ✓ Technical debt is catalogued, not just experienced

**People readiness:**
- ✓ At least one senior engineer capable of technical leadership
- ✓ Hiring process documented — not purely CTO-network-dependent
- ✓ Engineers can complete work without daily CTO input
- ✓ First EM hire made or imminent
- ⚠ No single engineer is a key-person risk other than CTO

**Process readiness:**
- ✓ Sprint cadence exists in some form
- ✓ Code review process established
- ✓ Basic onboarding documentation exists
- ⚠ CTO has started saying "let X decide" in technical discussions
- ⚠ At least one process runs without CTO involvement

> **Failure signal if transition forced without readiness:** The CTO delegates authority before the team has capability to receive it. Engineers escalate everything back up. CTO returns to Builder mode under pressure. The transition fails and leaves a trust deficit in its wake.

---

### Gate 2: Multiplier → Strategist
*Typically ~50–100 engineers · Series B readiness*

**Leadership readiness:**
- ✓ VP Engineering or Head of Engineering in place and effective
- ✓ EMs running 1:1s, performance reviews without CTO prompting
- ✓ Career ladder in use — promotions happen without CTO as sole decision-maker
- ✓ At least one EM could step up into VP Eng role temporarily
- ✓ Engineering culture survives CTO absence of 2+ weeks

**Process readiness:**
- ✓ DORA metrics or equivalent tracked and improving
- ✓ Incident response runs without CTO involvement for P1/P2
- ✓ Technical roadmap exists independently of product roadmap
- ✓ Quarterly planning process runs consistently
- ⚠ Board can receive engineering update from VP Eng if needed

**Strategic readiness:**
- ✓ CTO has presented to board at least once independently
- ✓ CTO can articulate 2-year technology vision to non-technical audience
- ✓ At least one strategic vendor or platform relationship owned by CTO
- ⚠ CTO spends <30% of time on operational engineering decisions
- ⚠ CTO has external presence — conference, writing, or industry network

> **Failure signal if transition forced without readiness:** CTO moves into Strategist activities before the VP Eng function is strong enough to absorb daily operations. Engineering org loses direction. CTO gets pulled back in. Board loses confidence in both CTO and the engineering function simultaneously.

---
---

# ARTIFACT B: The Founder CTO at the Wall
## cto-transition-brief.html

*Research brief for a seed-stage CTO facing displacement. Combines research findings with practical guidance. Note: produced before the taxonomy was locked — uses "Executive" where the taxonomy now uses "Strategist." Practitioner document, not citable as primary framework.*

---

## The Core Argument: The Impossible Role

No other C-suite position is asked to be fundamentally different people at each stage of company growth. The CFO manages money at seed and still manages money at Series B. The CMO drives brand at Series A and still drives brand at Series C. The CTO, uniquely, is expected to transform their entire identity — from solo engineer, to team lead, to org designer, to strategic executive — often without anyone in the room who's done it before.

> *"The CTO has been given the impossible task of being the most things during their tenure, in the role most structurally deprived of the peer support needed to make those transitions — and is typically the most under-compensated for it on a risk-adjusted basis."*

This is not a character flaw. It is a design flaw — in how startups build their leadership layer, and in how the industry talks about what a "good CTO" looks like at each stage.

---

## Role Evolution: Four Different Jobs, One Title

| Stage | Mode | Description |
|---|---|---|
| Pre-seed | **The Builder** | Solo or near-solo engineer. Selects the tech stack, ships the MVP, makes every technical call. Identity is entirely in the code. |
| Seed → A ⚠ | **The Transition — Where Most Failures Occur** | Must shift from maker to manager, from execution to delegation, and from technical authority to strategic partner — all simultaneously, under fundraising pressure, often without a model for what success looks like. |
| Series A–B | **The Org Builder** | Builds the engineering culture, installs process, delegates technical decisions. Role splits: VP of Engineering often appears. CTO must lead up, not just down. |
| Series B+ | **The Executive** | Predominantly strategic. Aligns technology vision with business and investor expectations. Technical depth is no longer the job — judgment and communication are. |

---

## Failure Mode Analysis: The Control Collapse Pattern

The most common Seed → Series A failure isn't incompetence. It's a rational response to an impossible situation that produces irrational outcomes. Under pressure, technically-minded founders tighten their grip — doing more of what made them successful early, precisely when the company needs them to do less of it.

> *"At first, founders compensate through intensity. They push harder. They extend their work hours. They micromanage more closely. This approach temporarily masks the problem but amplifies the long-term risk."*

**Five-stage failure sequence:**

1. **The grip tightens** — Scaling pressure triggers anxiety. The CTO responds by trying to control more — every technical decision, every project management detail. It feels like responsibility. It functions like a bottleneck.

2. **Strategic decisions stall** — Absorbed in operations, the CTO delays or avoids the architectural and organizational decisions that only they can make. Technical debt compounds. Team structure stays undefined too long.

3. **Team burns out** — Engineers lose autonomy. Every decision requires approval. Flow is broken by status requests. Top performers — who have options — leave first, taking institutional knowledge with them.

4. **CTO self-relegates** — Without peers who can challenge the pattern or models for what comes next, the CTO shrinks into the lane they're expert in. They become a very senior IC — still technically brilliant, but no longer the executive the company needs.

5. **Replacement becomes inevitable — but delayed** — The board and CEO often recognize the failure mode late, because the CTO is still technically valuable and hard to replace. The company loses 12–24 months of strategic momentum in the gap between when the failure starts and when it's addressed.

Research on micromanagement confirms the structural costs: employees under micromanagement report 74% more stress, produce 50% less output, and are 2.6x more likely to be actively job-hunting.

---

## The Structural Problem: Isolated at the Top

What makes the CTO's transition uniquely hard isn't the transition itself. It's the absence of any structure to support it. Every other C-suite role has external scaffolding: CFOs have a professional discipline with clear career stages. CMOs have a well-worn path from director to VP to CMO. The CTO — especially the founding CTO — has none of this.

> *"CTOs are often the most senior technical authority in their organization, yet expected to make decisions in fast-changing, ambiguous environments — frequently without a true peer internally. While founders, CEOs, and boards may rely on CTOs for clarity, CTOs themselves rarely have a safe forum to pressure-test decisions or share uncertainty."*

The CEO can't model the transition — they don't have the technical context. The engineering team can't either — they revere the CTO's technical depth. The board typically waits until the failure is visible enough to force action. Nobody in the room has both the standing and the knowledge to say: "this is what the next version of your role needs to look like."

---

## Compensation Data (Kruze Consulting, 250+ US VC-backed startups)

| Stage | Founding CTO (avg) | Hired CTO (avg) | Gap |
|---|---|---|---|
| Seed | $133,000 | $190,000 | −$57K |
| Series A | $177,000 | $293,000 | −$116K |
| Series B | $218,000 | ~$300,000+ | −$80K+ |

The equity offset assumes a liquidity event that, statistically, most startups don't reach. The compensation gap signals something important: the market knows the founding CTO role is harder. It just prices that difficulty as a reason to pay less (equity upside), rather than more (recognition of scope).

---

## Self-Reflection Framework: Five Questions

*Not performance review questions — designed to surface the pattern and build language for what happened.*

1. **When did I last make a decision I was uncomfortable making?**
CTOs in control collapse tend to avoid decisions that require acting as an executive — org structure, strategic pivots, difficult people decisions. If the answer is "a while ago," the bottleneck may be inside the role.

2. **Did the team need my approval for things they were more qualified to decide than I was?**
Micromanagement often comes from a mismatch between where authority sits and where knowledge sits.

3. **Who, inside the company, could have told me I was in the wrong mode — and would I have listened?**
Most CTOs in this pattern are getting signals they're dismissing. Identifying who was sending them — and what happened to those signals — is worth reconstructing.

4. **At what point did I shift from building the company to protecting what I'd built?**
Protectiveness of the codebase, the team culture, or the technical vision is often the start of the control collapse pattern.

5. **What did the next version of the CTO role actually require — and did I want to do that job?**
Sometimes the failure isn't an inability to transition — it's an honest mismatch between what the role needed and what the person wants to spend their time on. That's not failure. That's useful information.

---

## Interview Narrative Guidance

**Q: Why did you leave / what happened at your last company?**

*What to avoid:* Vague answers ("it was time for a change"), blame displacement ("the CEO and I had different visions"), or over-explanation that sounds like litigation.

*What works:* "I was a founding CTO through seed stage — I built the team, the architecture, the culture. When we hit the Series A inflection, I stayed in the operating mode that had made us successful early, longer than I should have. I was managing execution when I needed to be setting direction. I understand that pattern now better than I did then, and I've thought hard about what the transition actually requires."

---

**Q: Tell me about a time you made a mistake as a leader.**

*What works:* "I held decision authority too long as the team grew. I thought I was being thorough. The actual effect was that good engineers were waiting for me to approve things they were more qualified to decide than I was. We lost two strong people in six months. I've since built a mental model for when to delegate authority versus ownership — they're different things."

---

**Q: How do you see the CTO role at our stage?**

*What works:* "At your stage, the job is architectural in two senses — technical architecture and organizational architecture. The CTO isn't the best engineer in the room anymore, they're the person who makes sure the right engineers are making the right calls. My job is to build systems that don't need me in every decision loop. I've learned to measure my effectiveness by how well things run when I'm not in the room."

> **The asset, not the liability:** A CTO who went through this at seed stage and came out with genuine self-awareness is more valuable to a Series A company than one who hasn't been tested. The question interviewers are actually asking is: does this person know what they don't know yet? The honest answer, backed by specific language, is the most credible thing in the room.

---

## What to Look for in the Next Role

| Signal | What it means |
|---|---|
| ✓ **Look for:** A CEO who has run a scaled engineering team before | The peer gap is real, but a CEO with technical management experience can model the transition and challenge you when you're in the wrong mode. |
| ✓ **Look for:** An explicit VP of Engineering hire in the plan | Companies that understand the CTO role will have already thought about how to split the execution and strategy layers. |
| ✓ **Look for:** A board with at least one technical operator | A board that can recognize CTO transition patterns — and support rather than just evaluate them — changes the support structure fundamentally. |
| ✗ **Avoid:** Companies that want a "full-stack CTO" indefinitely | If the role description asks you to both write architecture and attend board meetings with no plan to split the function as the team grows, the conditions for the same failure are already in place. |

---

*Research compiled June 2026. Practitioner document — see CTO_Operating_Modes_Working_Document for the citable research artifact.*  
*Framework developed in collaboration with Claude Sonnet 4.6 (Anthropic).*
