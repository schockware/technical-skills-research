# 02: The Fungibility Assumption
## How the Software Industry Operationalized the Belief That Developers Are Interchangeable

**Research date:** June 25, 2026
**Series:** Software Industry — Human Capacity Research Thread
**File:** 02 of series
**Predecessor:** `01_MMM_brooks_original_argument.md`
**Companion files:** `03_MMM_transformation_expectation.md`, `04_MMM_performance_review_compression.md`, `05_MMM_ray_of_hope.md`

---

## The Assumption

Brooks established in 1975 that human cognitive contribution to software is not fungible. People and time are not interchangeable. The man-month is a dangerous fallacy.

The software industry heard this, cited the law, and then spent the next fifty years building management infrastructure, career frameworks, hiring practices, and productivity measurement systems on the opposite assumption.

**The fungibility assumption:** a software developer is a configurable unit of cognitive output. Add more units to increase output. Swap units when they underperform. Measure units against a standard scale. Expect units to reconfigure themselves when the organization needs a different configuration.

This assumption is so deeply embedded in how the industry operates that it is mostly invisible. It is not stated as a belief. It is expressed as standard practice.

This file documents how it got operationalized — the specific mechanisms through which the industry translated the fungibility assumption into everyday management reality.

---

## Mechanism 1: The Man-Month Never Died — It Just Got Renamed

Brooks specifically named the man-month as the dangerous fallacy. The industry response was to rename it.

**Story points and velocity** — introduced by Extreme Programming in the late 1990s and adopted wholesale by Scrum — are the man-month with a new variable name. The logic is identical:

- A team has a velocity: the number of story points it can complete in a sprint
- A sprint backlog has a size: the number of story points of work to be done
- Planning works by dividing backlog size by velocity to get duration

The story point was explicitly designed to *not* map to hours — to avoid the man-month problem by making units relative rather than absolute. This was the correct instinct. But in practice:

- Management converts velocity to headcount planning: if we need to ship X story points in Y sprints, we need Z developers
- Velocity becomes a measure of team capacity that is treated as scalable: add one developer, increase velocity proportionally
- Story points become a productivity measure across developers: who is completing the most points?

Story points, as unit-less relative effort measures, allow participants to focus on the relative size and complexity of tasks rather than predicting exact durations. Team velocity, the rate at which a team completes work, is used to guide iteration planning and determine a feasible set of features for the next development cycle.

The mechanism is sound in theory. In practice it reimports fungibility assumptions through the back door: velocity treats team output as a uniform, scalable resource. Adding a developer is expected to increase velocity. Replacing a developer is expected to maintain velocity after a ramp-up period. The communication overhead that scales as n(n-1)/2 does not appear anywhere in the velocity calculation.

Brooks named this exact problem. The industry built a more sophisticated version of the same fallacy.

---

## Mechanism 2: The 10x Developer — Non-Fungibility Used to Justify Fungibility

The 10x developer concept is the industry's most confused response to the productivity variation evidence.

The original research (Sackman, Erikson & Grant, 1968) found that the best programmers in a specific context solved problems approximately 10x faster than the worst. This was a genuine finding about non-fungibility: developers are not interchangeable units, they vary enormously in performance.

The industry's response was to use this non-fungibility finding to double down on fungibility:

- If 10x developers exist, find them and hire them
- Build your team of 10x developers
- Replace developers who aren't 10x

The assumption underneath: that a 10x developer is a better *version of the same thing* — a more productive unit of the same fungible resource. The possibility that a 10x developer in one context becomes a 1x developer in a different context, or that the 10x performance is inseparable from the specific problem, team, and codebase — this possibility doesn't appear in the hiring practice the myth generates.

What the research actually shows: Professor William Nichols' study observed that 90% of developers fall within modest performance ranges. There was a lack of evidence to support the idea that some developers are naturally more efficient than others.

And the original 1968 finding has significant methodological limitations: The sample size was small, with only 12 programmers participating. The tasks were relatively simple and may not reflect the complexity of modern software development. The study focused on individual performance rather than team dynamics, which are increasingly important in today's collaborative development environments.

The deeper problem: A developer's performance can vary greatly depending on the project, team dynamics, and organizational culture. What might make someone a "10x developer" in one context could be less impactful in another. A developer with deep expertise in a specific technology stack might appear to be a 10x developer when working within that stack, but could struggle when faced with unfamiliar challenges.

This is the Brooks essential complexity argument applied to individuals: performance is not a property of the person in isolation. It is a property of the person *in relation to* a specific problem, codebase, team, and organizational context. Performance is not portable. The 10x developer myth treats it as portable — as a property of the unit rather than the context.

The industry used a non-fungibility finding to justify hiring practices built on fungibility assumptions. The result: relentless searching for mythological 10x units, combined with the same headcount-based planning that treats all units as interchangeable once hired.

---

## Mechanism 3: "Resources" — The Language That Made Fungibility Official

The most revealing evidence for the fungibility assumption is linguistic.

Software developers are routinely referred to as "resources" in management contexts:

- "We need three more resources on this project"
- "Resource allocation" as a term for assigning developers to work
- "Resource planning" as a term for headcount forecasting
- "Resoure utilization" as a measure of how much of a developer's capacity is being consumed

The word "resource" is not neutral. It is a category claim. Resources are:
- Interchangeable within a type (one unit of RAM is equivalent to another)
- Scalable (adding more resources increases capacity proportionally)
- Deployable (resources can be moved between tasks without loss)
- Consumable (resources are used up and must be replenished)

None of these properties accurately describe a software developer. A developer assigned to a new codebase requires months of ramp-up. A developer moved between projects takes their contextual knowledge with them and must rebuild it elsewhere. Developers are not interchangeable within a seniority band — domain expertise, relationship context, and system knowledge are not properties of the "resource type," they are properties of the specific person in a specific context.

Research on the consequences of unhappiness and happiness among software developers found that the highest impact of both happiness and unhappiness is experienced on development productivity and quality as expressed by cognitive performance, including creativity and flow, and process-related performance. Several instances of job-related adverse effects of unhappiness were found: work withdrawal, stress, anxiety, burnout, and depression.

The "resource" framing removes the human from the model. Resources don't have unhappiness consequences. Resources don't have identity investments in their work. Resources don't experience the meaning loss that Mathias & Williams documented when asked to give up role identities. Resources are reconfigured.

The language did not cause the fungibility assumption. But it crystallized it, made it transmissible, and gave organizations a vocabulary for treating human cognitive work as a material input rather than a contextual, relational, and identity-embedded process.

---

## Mechanism 4: Team Size as the Primary Scaling Lever

When a software project needs to go faster, the default organizational response is to add people.

This is Brooks' Law scenario played out in thousands of organizations, thousands of times, across fifty years of empirical confirmation that it doesn't work — and the industry keeps doing it.

The 2015 CHAOS Report analyzed thousands of projects and found that small projects achieved a 61% success rate, while large projects succeeded only 11% of the time and grand projects just 6%, with failure rates rising to 30% and 43%, respectively, for the latter categories. This pattern holds across reports from 1994 onward, attributing poorer outcomes in larger efforts to coordination challenges and resource inefficiencies.

A 2012 empirical analysis of over 1,000 projects from the International Software Benchmarking Standards Group (ISBSG) repository identified 3 to 5 members as the optimal team size for peak productivity, with comparable performance up to 7 members; however, teams of 9 or more exhibited significantly lower productivity, marked by exponential increases in effort and schedule overruns.

The research is consistent, replicated, and covers decades. The optimal team size for software productivity is small — 3 to 7 people. Beyond that, coordination overhead consumes the productivity gains from additional headcount.

The industry's response: build larger teams, add coordination overhead in the form of project management, agile ceremonies, and tooling, and then wonder why the project is late.

The fungibility assumption is what makes this response feel reasonable. If developers are interchangeable units of cognitive output, adding units should increase output. The fact that it doesn't — that the communication overhead that scales as n(n-1)/2 consumes the added capacity — is invisible to a model that treats people as resources.

---

## Mechanism 5: Headcount as the Proxy for Engineering Capability

At the organizational level, the fungibility assumption manifests as headcount-based capability assessment.

- "How big is your engineering team?" as a proxy for technical capability
- Funding rounds sized partly on headcount growth targets
- Engineering org charts measured by span of control
- Engineering leaders evaluated partly on team size
- Acquisitions valued partly on "acqui-hire" headcount

The assumption: more engineers = more capability. Doubling the engineering team doubles the engineering capacity.

Brooks' communication overhead formula directly refutes this. A team of 10 has 45 communication paths. A team of 20 has 190. Doubling the headcount multiplies the coordination complexity by more than four. The capacity gain is consumed by the overhead.

But headcount is visible and measurable. Communication overhead is invisible until it becomes crisis. And in a funding environment where demonstrating growth is a requirement for the next round, headcount growth is legible in a way that team quality, contextual knowledge depth, and communication efficiency are not.

The fungibility assumption and the startup funding model are mutually reinforcing. Investors ask for headcount growth as evidence of scaling. Companies hire to demonstrate that growth. The coordination overhead accumulates invisibly until the project starts slipping — at which point the response is to add more people.

Brooks described this in 1975. The industry built a funding model that structurally incentivizes the behavior he described as a dangerous fallacy.

---

## What the Fungibility Assumption Costs

The costs are distributed across three levels:

**At the project level:** late projects, cost overruns, quality failures. The CHAOS Report data is consistent across 30 years. Large projects fail at 6% success rates. The coordination overhead that Brooks described is the primary mechanism.

**At the team level:** developers experience work withdrawal, stress, anxiety, burnout, and depression when treated as resources rather than as knowledge workers whose contextual expertise is embedded in specific systems, teams, and organizational relationships. Being moved between projects, having their domain knowledge treated as portable and replaceable, being measured against productivity metrics that abstract away the complexity they are actually managing — these experiences have documented psychological consequences.

**At the individual level:** imposter syndrome at 52.7% prevalence (from the developer career research thread) is partly a consequence of the fungibility assumption. If developers are interchangeable units, then a developer who can't perform as a unit in a new context — new codebase, new team, new domain — is experiencing a personal failure rather than a predictable consequence of the non-portability of contextual knowledge. The fungibility model has no room for the reality that expertise is contextual. The individual is left to interpret their own contextual struggle as inadequacy.

---

## The Connection to the Transformation Expectation

The fungibility assumption at the team and project level — developers as interchangeable, scalable units — generates the transformation expectation at the career level.

If a developer is a configurable unit, then reconfiguring that unit for a new role is just another form of resource allocation. Senior developer needs to become a manager? Configure the unit for management. Principal engineer needs to become a VP Engineering? Configure the unit for executive function. Founding CTO needs to hold Builder, Multiplier, and Strategist capabilities simultaneously? Configure the unit for all three.

The fungibility assumption makes the transformation expectation feel like a management problem rather than a human capacity problem. The reason it keeps failing — the ~50% IC→EM reversion rate, the 8–15 year full path to VP Engineering, the 2.5-year average CTO tenure — is not visible through the fungibility lens. Through that lens, the failures are unit failures: this developer couldn't be reconfigured. Find a better unit.

Brooks named the fallacy in the scheduling context. The transformation expectation is the same fallacy applied to human development. The next file traces how one became the other.

---

*Next in series: `03_MMM_transformation_expectation.md` — how fungibility at the project level generates irrational transformation expectations at the career level*
*Framework developed in collaboration with Claude Sonnet 4.6 (Anthropic). Research conducted June 2026.*
