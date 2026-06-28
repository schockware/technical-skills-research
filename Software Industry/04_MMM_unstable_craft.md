# 04: The Unstable Craft
## What Makes Software Uniquely Different — And Why Every Other Problem Compounds From It

**Research date:** June 25, 2026
**Series:** Software Industry — Human Capacity Research Thread
**File:** 04 of series
**Predecessors:** `01` through `03` in this series
**The question this file answers:** Why is software specifically worse than other professions that also have career rotation problems?

---

## The Thesis Stated Plainly

> **⚠️ Keystone restated (2026-06-27, per `R1`).** The original keystone — "software has no stable craft to master" — was **overstated** and in tension with the corpus's own anti-fungibility win: a durable layer (algorithms, data structures, systems thinking, architecture, debugging judgment) *does* compound. The defensible claim, carried throughout this file: **the *credited* skill layer — the fashionable frameworks, tools, and methodologies the field actually measures and rewards — is unstable; the durable layer is real but largely *uncredited*.** Read every "no stable craft" / "the craft is unstable" phrasing below in that narrowed sense (credited layer), not as "nothing in software persists."

In stable-craft professions, you gain identity by mastering something that persists.

The surgeon masters anatomy, physiology, and technique. These are stable. Ten years of practice produces genuine mastery of something real and durable. The craft identity — "I am a surgeon" — is anchored to accumulated expertise in a domain that does not fundamentally change between 2015 and 2025. The surgeon who retires in 2030 is practicing the same discipline they entered in 1990, deepened by thirty years of accumulated experience.

**In software, the *credited* craft — the fashionable frameworks, tools, and methodologies the field measures and rewards — is unstable, so the act of continuous learning is forced onto practitioners; the durable layer beneath it (algorithms, systems thinking, architecture, judgment) is real and compounds, but the field largely does not credit it.**

The framework you mastered is deprecated. The architecture pattern you internalized is now considered harmful. The language you built your identity around has lost market share. The methodology that defined how you work has been replaced by its successor, which will be replaced by its successor's successor. And critically, there is no consensus on what good software development even *is* — not at the methodological level, not at the theoretical level, not at the practice level.

This is not a temporary condition. It is structural. It is what software is.

And it means that every other problem the software industry has built into its career structure — the fungibility assumption, the identity rotation, the Red Baron effect, the deceptive labeling — is operating on an unstable foundation that makes each of them worse than it would be in any other field.

---

## The Evidence: Software's *Credited* Craft Layer Is Unstable (the Durable Layer Is Real but Uncredited)

### The Methodological Instability

The software industry cannot agree on how to build software.

Empirical research on Agile methodologies found that only four of ten methods studied present any empirical support for their claims. The lack of empirical evidence results in practitioners not having reliable evidence on the real usability and the effectiveness of the different agile methods. Therefore the practitioners cannot determine whether the existing methods really make sense or not — wondering if the methods describe proven wisdom or if they are merely appealing development stories.

This is not a research gap that will be closed. Waterfall, Agile, DevOps, Lean, XP, Scrum, SAFe, Shape Up — these methodologies are not converging toward a single validated best practice. They represent genuinely different models of what software development is and how it should be organized. The debate between them is not empirical — it is philosophical.

No one methodology fits all projects. The conclusion reached repeatedly, across multiple comparative analyses, is that context determines which approach works — not evidence about which approach is superior in general.

In medicine, there is evidence-based practice. The Cochrane Collaboration exists to aggregate randomized controlled trials. When a treatment works, it becomes standard of care. The craft deepens as the evidence base accumulates.

In software, the equivalent initiative — evidence-based software engineering — explicitly acknowledges that there exists no generally accepted theory in software engineering. Some laws, hypotheses and conjectures exist, but yet no generally accepted theory.

**The craft has no stable theoretical foundation to stand on.**

### The Consensus Problem

A peer-reviewed study of the software engineering research community — Consensus in Software Engineering: A Cognitive Mapping Study — found that the academic community of practice suffers from poor consensus. Researchers are divided into several camps where each camp exhibits some internal consensus, but significant disagreements separate the camps and many researchers are not in any camp at all.

The Jacobson observation, cited in multiple empirical software engineering papers, names this directly: software engineering is gravely hampered by:

1. The prevalence of fads more typical of the fashion industry than of an engineering discipline
2. The lack of a sound, widely accepted theoretical basis
3. The huge number of methods and method variants, with differences little understood and artificially magnified
4. The lack of credible experimental evaluation and validation
5. The split between industry practice and academic research

This is the research community describing its own field. Point 1 — the prevalence of fads — is the practitioner experience of point 2, the lack of a theoretical basis. When there is no stable theory, fashion fills the vacuum.

The developer who mastered microservices in 2015 finds them questioned in 2023. The developer who built their identity around NoSQL in 2012 finds relational databases rehabilitated in 2018. The developer who internalized REST in 2010 finds GraphQL displacing it in 2017. The developer who learned Agile in 2005 finds it either triumphant or discredited depending on who they talk to.

None of these represent the field converging on truth. They represent the field cycling through fashions in the absence of a stable theoretical foundation.

### The "Is It Even Engineering?" Problem

The debate about whether software development is a craft, an engineering discipline, or something else entirely has not been resolved in fifty years and shows no signs of resolution.

From the ACM's own analysis: Software engineering is not engineering in the sense of a discipline with a distinctive body of knowledge that must be learned. The body of knowledge engineers are supposed to learn differs in important ways from software engineering's body of knowledge.

The ACM Council, in 1999, opposed licensing software engineers on the grounds that licensing is premature — implying the field does not yet have a stable enough body of knowledge to define what a licensed practitioner should know.

Compare this to medicine, law, and traditional engineering: all have licensure, all have accredited bodies of knowledge, all have defined what a practitioner must demonstrate competence in to be allowed to practice. The licensure is not just quality control — it is an institutional definition of what the craft *is*.

Software has no such definition. The field cannot agree on whether it is engineering, craft, science, art, or some combination. It cannot agree on what a competent practitioner should know because it cannot agree on what competence means in a domain whose tools, languages, frameworks, and methodologies change faster than any accreditation body can track.

---

## The Red Baron Effect on an Unstable Craft

The Red Baron effect — promoting the best practitioner to lead other practitioners — is irrational in any field because craft excellence and the ability to develop others in the craft are different skills.

In software, it is *additionally* irrational because the craft the Red Baron mastered is not stable. The senior engineer who is promoted to engineering manager because of their mastery of distributed systems architecture in 2020 may find that the architecture patterns they mastered are being questioned by 2024. Their technical authority — the thing that justified the promotion — has a shorter half-life than the transition they are being asked to make.

The stable-craft version of the Red Baron problem: you promote the master surgeon to Chief of Surgery. They were promoted for skills that remain valid and relevant. Their technical authority is durable.

The unstable-craft version: you promote the master engineer to Engineering Manager. They were promoted for skills that may be deprecated before they complete the management transition. Their technical authority is decaying while they are being asked to rebuild their identity around developing others.

This is not a metaphor. It is measurable. The software engineering skills half-life is 2.5-5 years. The IC→EM transition takes 1-2 years with support, assuming success — and fails ~50% of the time. These timescales overlap. The engineer's technical craft is becoming obsolete at the same rate as they are attempting to abandon it.

The Red Baron effect in a stable-craft domain: you lose the best practitioner to management, but their craft authority remains as the basis for their management credibility.

The Red Baron effect in software: you lose the best practitioner to management, and then you lose their craft authority to obsolescence anyway, leaving you with neither a practitioner nor a manager with durable technical credibility.

---

## The Fungible Knowledge Problem

The fungibility assumption holds that a leader can diffuse knowledge to their team — that expertise flows from senior to junior through the management hierarchy.

In stable-craft professions, this is approximately true. The Chief of Surgery's clinical knowledge is deep, durable, and genuinely transferable through teaching, supervision, and mentorship. The knowledge that made them the Chief is the knowledge their residents need to develop. The hierarchy serves a real epistemic function.

In software, the knowledge diffusion assumption fails in three compounding ways:

**1. The knowledge is tacit and contextual.** Brooks established this in No Silver Bullet: software complexity is essential, not accidental. The complexity cannot be abstracted away without abstracting away the essence. The senior engineer's knowledge of why the system was built the way it was built — the architectural decisions, the constraints that shaped them, the tradeoffs that were made — cannot be fully articulated. It lives in the person. It is not diffusable through a management hierarchy.

**2. The knowledge is decaying.** By the time the knowledge reaches junior developers through the hierarchy, it may already be obsolete. The manager's expertise in the framework they mastered three years ago is being transmitted to engineers who will use a different framework. The knowledge diffusion hierarchy is transmitting information with an expiration date.

**3. There is no consensus on what knowledge to diffuse.** The manager who learned Agile from one school of practice is managing engineers trained in a different school of practice. The senior engineer who built their identity around one set of architectural patterns is mentoring junior engineers who have been taught that those patterns are anti-patterns. The hierarchy cannot diffuse knowledge coherently when the knowledge base itself is contested.

**The irrational assumption stated precisely:**

*A fungible leader diffuses fungible knowledge across fungible units.*

Every word is wrong for software:
- The leader is not fungible — their contextual knowledge is specific, non-portable, and decaying
- The knowledge is not fungible — it is tacit, contextual, contested, and has a half-life
- The units are not fungible — Project Aristotle proved that team performance is relational, not compositional

And the information flow assumption is additionally wrong: the hierarchy does not transmit knowledge bidirectionally. The HiPPO effect means that signal flowing upward is filtered by authority dynamics. The essential complexity means that knowledge flowing downward degrades in translation. The hierarchy is not an information system. It is a power structure that management theory misread as an information system.

---

## The Licensure Gap and Its Consequences

Stable-craft professions anchor identity externally through licensure. The surgeon is licensed. The license does not disappear when they become Chief of Surgery. The craft identity is institutionally maintained independent of organizational role.

Software has no licensure. The software engineer's identity is entirely organizationally constructed. It exists as long as the organization validates it by giving them engineering work to do.

This has a specific consequence for the identity rotation problem. When a surgeon becomes Chief of Surgery, they are still, legally and institutionally, a surgeon. The identity is externally anchored. They can step back into clinical work. The craft identity has an institutional home that the organizational role change cannot take away.

When a software engineer becomes Engineering Manager, there is nothing external that says they are still an engineer. The identity exists only in what they do. Management stops them from doing engineering. The identity has no institutional anchor to hold onto during the transition.

This is why the "reverting to IC under pressure" failure mode is so prevalent — and so rational from the practitioner's perspective. The engineer who reverts to writing code during the IC→EM transition is not failing. They are reaching for the only identity anchor they have. There is no license to hold onto. There is no institutional definition of "software engineer" that persists through the role change. The only way to maintain the identity is to keep doing the work.

The ~50% reversion rate is not a failure rate. It is the rate at which people rationally refuse to surrender an unanchored identity with nothing stable to hold in its place.

---

## The Performance Review as Symptom

Your observation — "this domain takes 3 years to even learn, and you want me to compress it into bullet points" — is now fully explained by the convergence of all four problems:

**The craft is invisible** (Brooks' essential complexity — the knowledge that took three years to build cannot be visualized or represented)

**The craft is unstable** (the framework-specific expertise resists standardized evaluation because what counts as excellent has no stable definition)

**The craft is tacit** (the knowledge cannot be fully articulated because it lives in the practitioner's judgment and contextual understanding)

**The craft has no institutional definition** (there is no licensure body to say what a competent software engineer knows, so the performance review system has to invent a proxy)

The manager asking for bullet points is not malicious or incompetent. They are applying an evaluation framework — designed for stable, visible, licensable crafts — to a domain where none of those conditions hold. The bullet points are what the fungibility assumption looks like when it collides with essential complexity. The compression destroys the essence because the essence *is* the complexity — which is exactly what Brooks said in 1986.

---

## What This Means for the Full Argument

The "what makes software different" question now has a precise answer:

**Software is the only major field that:**

1. Required identity rotation at every career rung (not just at the top)
2. Labeled the rotation as natural deepening (Category C deception)
3. Did so without a stable craft foundation that the identity could be anchored to
4. Did so without licensure to maintain the craft identity through organizational role changes
5. Did so with a knowledge half-life short enough that the craft being rotated away from is simultaneously becoming obsolete
6. Did so with no consensus on what the craft even is — meaning there was never a stable "excellent software engineer" identity to build or give up

Every other field with a rotation problem has at least one stabilizing factor:
- Consulting: the rotation is honestly labeled
- Academia: the craft (research) has a stable theoretical foundation, even if administration is deceptively labeled
- Military: separate institutional pipelines with honest labeling

Software has none of these stabilizers. The rotation is deceptively labeled. The *credited* craft is unstable (the durable layer exists but is uncredited). The identity is unanchored to anything the field rewards. The credited knowledge is decaying. And the management hierarchy is built on the assumption that all of these things are false.

**The "smart people should learn everything" assumption is not just irrational in software. It is the assumption that allows the industry to avoid confronting the fact that it built a career structure on top of a craft that was never stable enough to support it.**

---

## The Implication for the CTO

The CTO composite problem — Builder, Multiplier, Strategist — now has one more layer of irrationality added to it.

The Builder mode is built on technical craft. But in software, the technical craft has no stable foundation. The CTO-Builder is not just being asked to give up a craft identity for a leadership identity. They are being asked to give up a craft identity that was itself always provisional — built on frameworks that will be deprecated, architectures that will be reconsidered, methodologies that will be replaced.

The irrational composite is not just asking one person to hold three distinct skill sets at once, with no runway between them. It is asking one person to hold three distinct skill sets *in a field that cannot agree on what the first skill set even is*. *("Incompatible" retired corpus-wide → "distinct, demanded simultaneously, no runway"; the skills coexist over a career — see [`../CTO/18_RESEARCH_modes_not_incompatible.md`](../CTO/18_RESEARCH_modes_not_incompatible.md).)*

---

*Next in series: `05_MMM_ray_of_hope.md` — where the corrections are happening and what they reveal about what should have been built from the start*
*Framework developed in collaboration with Claude Sonnet 4.6 (Anthropic). Research conducted June 2026.*
