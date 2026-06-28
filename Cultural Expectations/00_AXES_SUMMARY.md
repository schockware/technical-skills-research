# The Axes: A Summary
## Structural Variables Discovered Across the Cultural Expectations Research Thread

**Date:** June 25, 2026
**Purpose:** Quick reference for synthesis work. Each axis is named, defined, and connected to the finding that surfaced it. Workshopped collaboratively before any research pass — these are hypotheses to test, not conclusions.
**Companion:** `CTO/TODO.md` T2 and T4 (the originating questions); `Software Industry/00_AXES_SUMMARY.md` (sibling axis set).

---

## The core question this area is investigating

> *Why does the culture grant the "smart → learn anything" permission for technical roles but withhold it for medicine, law, aviation, and other fields? Where is the line, and what draws it?*

The doctor thought experiment (T4) locates the question: everyone instantly knows the doctor list is absurd — surgery + colonoscopies + taxes + filing insurance + driving an 18-wheeler + launching rockets. That immediacy is the data. The line is real, sharp, and culturally drawn — not capacity-drawn. Each item is individually learnable. The absurdity isn't difficulty or quantity. It's that the culture *refuses permission* to pile incompatible demands on a doctor while granting that permission for engineers and CTOs.

These axes are the candidate mechanisms for *why* the line falls where it does.

---

## Axis 0: Fictional Media Portrayal
**Source:** Lone genius archetype; hacker archetype; technical founder mythology (Jobs, Zuckerberg); science fiction composite hero
**Position:** Axis 0 by design — this is the only axis that operates on children before any institution, credential system, or workplace exists in their life. The other axes explain brake failures in systems. This axis explains the prior belief those systems are staffed by.

**Definition:**
- **Culturally accurate portrayal:** Media depicts specialization, transition difficulty, scope limits, team dependency. The audience develops a model where expertise is bounded, composite demands are unusual, and failure is structurally explicable.
- **Genius-composite portrayal:** Media depicts unlimited competence radiating from a single individual. Specialization is weakness or limitation. Composite mastery is the heroic form. Transition costs are invisible. The audience internalizes the composite as the aspirational norm — before they ever enter a workplace.

**The archetypes and what they install:**
- **The lone genius** (Tony Stark, MacGyver, Q) — one brilliant technical mind, no team, no runway, no transition support, no scope limit. Genius is sufficient for everything. The implication absorbed: a sufficiently intelligent person can do it all.
- **The hacker** — one person, one keyboard, cracks any system in minutes. Domain boundaries don't exist. "Good with computers" covers network security, satellite control, genetic sequencing, and launching rockets. The cognitive architecture differences between these domains are invisible by design.
- **The mad scientist / inventor** — builds rockets, creates life, rewrites physics, runs the organization. The composite is the *point* of the archetype. Specialization would ruin the character.
- **The technical founder** — the Sorkin/Fincher Zuckerberg, the Jobs mythology, the Musk narrative. One visionary who *is* the product, the strategy, the culture, the engineering simultaneously. The Builder/Multiplier/Strategist composite is presented as the *heroic form*, not as an unreasonable demand.

**Why Axis 0 is upstream of every other axis:**
Every other axis operates on a person who is already in a decision-making role — writing a JD, evaluating a CTO, setting board expectations. Axis 0 operates decades earlier. By the time the liability framework (Axis 9), the credential system (Axis 8), the feedback loop (Axis 6), and the halo effect (Axis 7) all come into play, the prior belief is already installed. The other axes fail to install the brake. Axis 0 installs the *opposite* of the brake before the other axes even exist in the person's life.

**What fictional media does to the other axes:**
- **Axis 1 (tangibility):** Fiction makes cognitive complexity *look* tangible and fast. The hacker types furiously and the firewall falls. The genius scribbles and the equation is solved. The invisible is rendered visible and effortless — and the audience internalizes the speed and ease as normal.
- **Axis 7 (halo):** The genius archetype *is* the halo effect normalized. Unlimited competence radiating from a single identity is the aspirational form, not an unreasonable demand. The CEO who expects the CTO to be brilliant engineer *and* great people leader *and* strategic visionary isn't making an unusual demand — they're pattern-matching to the archetype they've seen their whole life.
- **Axis 8 (credential as capability):** In fiction, the credential is never the point — the *person* is. "He's brilliant" is the credential. No scope label, no boundary, pure capability signal. This is the model installed before any real credentialing system is encountered.
- **Axis 6 (feedback loop):** The fictional genius never fails due to structural overload. They fail due to hubris, relationships, or villains. The structural critique is never the narrative. The audience never receives the feedback that the composite is unreasonable — the loop is broken before it's formed.

**The specific damage to the CTO case:**
The people writing CTO JDs grew up watching these archetypes. The expectation that the CTO should be technically brilliant *and* a great people leader *and* a strategic visionary is so deeply installed that it doesn't feel like a demand — it feels like a *description* of what a technical leader is. The impossibility of the composite isn't argued against at the JD stage because it was never questioned at the formation stage.

**Research note:** This axis is the hardest to operationalize but may be the most important to name. The evidence is cultural and longitudinal — what archetypes dominate technical media, across what decades, reaching what audiences. The claim isn't that fiction *causes* the expectation; it's that fiction *normalizes* the composite as the default prior, making all other axes harder to overcome.

---

## Axis 1: Tangibility of Complexity
**Source:** Doctor thought experiment (T4); MMM corpus (Software Industry `02_MMM_fungibility_assumption.md`)

**Definition:**
- **Tangible complexity:** The incompatible demands involve physically distinct artifacts — a scalpel, a keyboard, a CDL, a rocket. The incompatibility is *perceptually obvious*. You don't need to understand the domain to see that the CDL and the scalpel are different things. The cultural brake fires automatically.
- **Intangible complexity:** The incompatible demands all happen on a laptop, in meetings, in documents. Everything looks like "knowledge work." The cognitive architecture required for each mode is radically different, but that difference is invisible to anyone who can't do the work — and the people setting the expectations are overwhelmingly people who can't.

**Why it matters:** The cultural brake fires automatically for tangible incompatibility. For cognitive incompatibility it requires active modeling that most decision-makers lack. This is why the doctor list is *immediately* absurd and the CTO list requires argument.

**The MMM connection:** Brooks' core insight is about complexity that is invisible by nature — not incidentally invisible but *essentially* invisible. Communication overhead, coordination cost, context-rebuilding time are all internal and cognitive. They don't show up until a project is late. The same invisibility that makes Brooks' Law easy to ignore makes the CTO composite easy to demand.

**Comparison cases:**
| Field | Position |
|---|---|
| Medicine, aviation | Tangible — physical artifacts signal incompatibility |
| Law, accounting, taxes | Intangible but brake applied (see Axes 2, 9) |
| Science (public-facing) | Intangible, brake partially absent (NDT case) |
| Software, CTO | Intangible, brake absent |

---

## Axis 2: Institutional Memory Relative to Complexity Growth Rate
**Source:** Age-of-discipline observation; finance subspecialty case

**Definition:**
- **High institutional memory:** The field is old enough, and grew slowly enough, that its failures have already been attributed, codified, and built into the accountability architecture. The brake is installed because the scar tissue formed. Law, medicine, accounting — centuries of visible failures that forced specialization.
- **Low institutional memory:** The field is young, or acquired a subspecialty faster than the scar tissue could form. The brake hasn't been built yet because the failures haven't been legibly attributed yet.

**Why it matters:** Age is a proxy, not the variable. The variable is the *ratio* between complexity growth rate and institutional memory formation rate. A field can be old (finance) but acquire a subspecialty (structured finance, derivatives) faster than it can institutionalize it — and the brake fails in that subspecialty. Software is a case where this happened to an entire field at once.

**The finance case:** Finance has centuries of institutional memory for banking and accounting. But the quant revolution (1980s–2000s) and structured finance outpaced that memory. The 2008 crisis is the brake-failure event: complexity became imaginatively inaccessible to decision-makers (CDOs, synthetic CDOs, correlation assumptions) in the same way CTO complexity is inaccessible to boards. Old field, young subspecialty, same vulnerability.

**The spaceflight case:** Aerospace inherited the institutional brake from mechanical and aeronautical engineering (centuries old, licensed, PE stamp, visible failure). Challenger and Columbia show the brake can be *degraded* even in mature fields when schedule pressure overrides engineering judgment — and what restores it is visible, attributable failure. Derivative fields inherit the brake; they don't generate it independently.

**Discipline:** Age alone is not the claim. "When complexity outpaces institutional memory, the brake fails regardless of the field's age" — that is the claim. Finance proves it can happen to old fields.

---

## Axis 3: Structurally Obscured vs. Incidentally Invisible Complexity
**Source:** Finance observation (fees, compound interest, fund drag)

**Definition:**
- **Incidentally invisible:** Complexity is hard to make legible because nobody has built the tools yet, or the domain is young, or the expertise gap is genuinely wide. The invisibility is a side effect, not a design.
- **Structurally obscured:** Complexity is kept invisible because the institution *benefits from the obscurity*. Legibility would transfer power from the institution to the individual. The 1.2% annual fee drag, compound interest, CDO correlation assumptions — these are not invisible because they're hard to explain. They're invisible because explaining them would reduce demand or transfer negotiating power.

**Why it matters:** Both produce the same surface effect — the individual can't evaluate the demand placed on them. But the mechanism and the remedy are different. Incidental invisibility can be fixed with better tools and communication. Structural obscuring requires changing institutional incentives.

**The software case:** Software complexity is primarily *incidentally* invisible — nobody has built legibility tools for "what does it take to cross the IC→management boundary," and the expertise gap is real. But there may be a structural obscuring component: the "smart people should learn everything" assumption is convenient for organizations that want to keep headcount costs low. Worth testing whether the obscuring is ever incentivized, not just incidental.

---

## Axis 4: Institutionally Mediated vs. Individually Demanded Competence
**Source:** Financial regulation; fiduciary standards; absence of equivalent in software

**Definition:**
- **Institutionally mediated:** Formal structures exist (regulatory bodies, fiduciary standards, licensing authorities) whose job is to say "this exceeds one person's scope." The individual defers to the institution and is protected from the raw demand. The institution absorbs the complexity-evaluation burden.
- **Individually demanded:** No institutional buffer exists. The demand lands directly on the individual. There is no body whose job is to say "this JD is asking for more than one person can deliver." The CEO, board, or investor makes the demand without any structural check on whether it's reasonable.

**Why it matters:** The fiduciary standard exists *because* there's a liability framework behind it (see Axis 9). The institution mediates the demand because someone is legally on the hook if the mediation fails. Without the liability framework, there's no incentive to build the mediating institution.

**The CTO case:** There is no institutional body that evaluates whether a CTO job description is reasonable. The CEO can't defer to a technical standards authority. The investor can't consult a technical capacity regulator. The demand is written, posted, and enforced without any structural check. The individual absorbs the entire complexity-evaluation burden — and absorbs the blame when they can't meet a demand that was never evaluated for reasonableness.

---

## Axis 5: Internal Brake vs. External Brake
**Source:** NDT / science communication case; software internal culture; 4.7 occupational transitions research (Abbott 1988; Wilensky 1964)

**Definition:**
- **Internal brake:** The professional community polices scope among its own members. Peer review, subfield credentialing, citation structures — specialists challenge each other's authority outside their domain. The virologist corrects the cosmologist. The brake operates within the community.
- **External brake:** The public or institutional audience also respects scope boundaries. You don't ask your dermatologist about your heart. The external demand is bounded by the same scope logic the internal community enforces.

**Why it matters:** A field can have a strong internal brake and a weak external brake — science is the clearest case. Peer review enforces scope rigorously; the public makes undifferentiated demands on "scientists." The NDT critique is the symptom: the scientific community knows he's outside his scope; the audience can't tell. The internal brake and the external brake are independently variable.

**Axis 5 is the preventive brake.** It operates *before* failure — stopping the unreasonable demand before it is made, or correcting the scope claim before it causes harm. This is distinct from Axis 9 (the corrective brake), which operates *after* failure.

> **⚑ REVISED 2026-06-27 (§3.9 evidence).** The earlier formulation held that *"Axis 5 is the output of a process that requires Axis 9 to initiate"* — i.e. Axis 9 fires → Axis 2 forms → Axis 5 strengthens. **Section 3.9 disconfirmed the "requires Axis 9" part.** Brakes install *without* liability: guild/college internal brakes (Royal College of Physicians, 1518) predate tort standard-of-care (~1767) by ~250 years; medical specialty boards (1917+) formed from knowledge growth and competitive market threat (optometry), with malpractice predating them by 50–80 years without causing them. **Axis 5 can fire without Axis 9.**

**The corrected causal model — visible attributable harm is the shared upstream initiator, not Axis 9.** Both brakes are downstream of the *same* trigger:

> **Visible attributable harm** → *either* path (often both):
> - **Preventive path (Axis 5):** professional community internalizes a scope limit → internal brake strengthens → audience learns the limit → external brake strengthens. Can run on complexity/knowledge growth or market competition *alone*, with no liability event (guilds, specialty boards).
> - **Corrective path (Axis 9 → Axis 2 → Axis 5):** named failure + attribution forces a liability/oversight event → Axis 2 encodes the lesson → Axis 5 strengthens after the fact.

Axis 9 is *one* route by which Axis 5 strengthens (the after-failure route), not its required initiator. Liability is a downstream instrument — see the Axis 9 §3.9 demotion banner. The deeper variable upstream of *all three* (Axis 5, Axis 9, and the four-tier structure below) is **visible attributable harm**: where harm is invisible or unattributable (software — Axis 1 + Axis 6), *no* path fires, regardless of which instrument is theoretically available.

**The four-tier structure of the brake (evidenced by 4.7 research):**
The brake is not binary — it operates across four tiers, each requiring progressively more attributed failure to install:

| Tier | What it installs | Trigger required |
|---|---|---|
| 1 — Technical standards | Wind-loading codes, boiler codes, design specifications | Any visible failure + complexity argument |
| 2 — Self-governance | Internal professional standards, peer review, codes of ethics (IEEE/ACM, Uncle Bob) | Complexity argument alone — no named failure required |
| 3 — External credential enforcement | PE stamp, CPA, ATP hours, specialty board certification | Named failure with sufficient political will |
| 4 — Liability framework + social contract | License revocation, external oversight (PCAOB), legally actionable scope violation | Named failure + named attribution + social harm visible enough to trigger the negotiation (see Axis 9 — but note §3.9: liability is *one of several co-equal instruments*, not the master variable; this tier is a complement to regulation + insurance, frequently *downstream* of the Tier 2 professional norms above it) |

Software currently has Tier 1 (some technical standards in safety-critical domains) and Tier 2 (internal professional standards, Software Craftsmanship Manifesto, ACM/IEEE code of ethics). The internal brake is running. Tiers 3 and 4 have not fired at scale — the ACM/IEEE professionalization attempt (1993–1999) failed when ACM withdrew, citing software engineering knowledge as "too immature." The NCEES PE exam in Software Engineering was offered 2013–2019 and discontinued due to lack of participation (15 first-time takers in April 2017). The internal brake exists and is insufficient to install the external brake without a named failure event.

**Software's position:** Neither external brake tier is reliably present. The composite CTO is *celebrated* internally — "full-stack," "technical founder," "player-coach" are positive labels, not scope violations. The external audience (CEOs, investors, boards) has even less ability to evaluate scope than the general public evaluating a scientist. Software is the worst-case position on both dimensions of the internal/external split, and has only reached Tier 2 on the four-tier scale.

**The absorption path — a non-failure route to Tier 3/4:** Aviation software (FAA DO-178C), medical device software (FDA IEC 62443), and automotive functional safety (ISO 26262) are acquiring Tier 3 and Tier 4 brake structure through adjacent licensed professions imposing their scope language on software. The formally-originated vocabulary of civil and systems engineering is being applied to software from outside. This is the mechanism Abbott (1988) identified as jurisdictional competition — an existing licensed profession absorbing a domain rather than the domain self-credentialing. It is already happening in safety-critical pockets and may represent the path by which software acquires external brake structure without a software-specific catastrophic failure.

**The science/software cousin relationship:** Science and software share the vulnerability structure — no liability, unlicensed identity, weak external brake, broken feedback loop to the public. But software adds the commercial demand layer: an employer with specific needs, a board with financial incentives, a JD that encodes the impossible composite, and a replacement mechanism when the individual fails. Same vulnerability structure, different demand mechanism, different consequence architecture.

---

## Axis 6: Feedback Loop Integrity
**Source:** NDT case; CTO hiring loop; MMM akrasia framing (T4)

**Definition:**
- **Closed loop:** The people who know the scope limits and the people who decide the scope demands are in the same legibility community, or the knowledge can cross the gap in actionable form. The brake propagates from expertise to decision.
- **Broken loop:** The expertise community and the decision-making community are separated by a legibility gap the knowledge can't cross. The decision-makers aren't ignoring the knowledge — they can't receive it in a form they can act on.

**Why it matters:** The akrasia is *stable* because the loop is broken. The engineers, senior CTOs, and researchers who know the composite is unreasonable cannot make that knowledge legible to the founders and investors writing the JD. The knowledge exists; the transmission mechanism doesn't. This is structurally different from "decision-makers are ignoring the evidence" — the evidence is present but untranslatable.

**The NDT parallel:** The scientific community's critique of NDT's scope overreach cannot reach the audience that needs to hear it, because the audience lacks the expertise to evaluate whose critique is valid. The loop is broken at the legibility gap.

**Implication for the fix:** "Educate the CEOs" is insufficient if the loop is structurally broken. The fix requires making the scope boundary legible *at the decision point* — credential, title split, explicit labeling — not just making the knowledge available somewhere. This is what the CTO corpus argues is missing.

---

## Axis 7: Halo-Bounded vs. Scope-Bounded Authority
**Source:** Authority bias literature (Milgram, Cialdini, Thorndike Halo Effect); NDT case

**Definition:**
- **Scope-bounded authority:** The credential defines what the holder is authoritative *about*. The cardiologist's authority stops at cardiology. The scope limit is part of what the credential communicates.
- **Halo-bounded authority:** Excellence in one visible domain generates assumed excellence in adjacent domains. The brilliant engineer is assumed to be a brilliant manager. The famous cosmologist is assumed to know virology. The credential signals *general* mastery rather than *scoped* mastery.

**Why it matters:** Where authority is scope-bounded, the demand stays within scope. Where authority is halo-bounded, the demand expands to fill whatever the organization needs the title to imply. The CTO's technical excellence halos into assumed managerial excellence, assumed strategic excellence, assumed organizational excellence — none of which follow from the demonstrated competence.

**The research backbone:**
- Milgram's obedience studies: people defer to authority figures even when the demand is clearly wrong. The white coat, the title, the institutional affiliation are enough.
- Thorndike's Halo Effect (1920): excellence in one visible domain creates assumption of excellence in adjacent domains.
- Cialdini on authority as persuasion lever: the *symbols* of authority trigger deference even when the substance is absent. The suit and the camera are enough.

**Interaction with Axis 6:** When you can't evaluate expertise (broken feedback loop), you defer to the authority signal. But the signal (the title) says nothing about scope limits. The deference becomes unbounded precisely where the loop is most broken.

**The CTO internal trap:** The title creates an internal obligation in the CTO themselves — the halo generates a self-expectation to live up to it across all domains. This is part of what makes the identity trap effective: the CTO absorbs the unreasonable demand not just because the board applies it but because the title applies it to themselves.

---

## Axis 8: Credential as Capability Signal vs. Credential as Scope Label
**Source:** "Titles don't matter" observation; JD archaeology; cargo cult replication

**Definition:**
- **Credential as scope label:** The credential tells you what the holder does *and* what they don't do. The CPA credential defines scope. The MD + specialty certification defines scope. The credential is a boundary, not just a badge.
- **Credential as capability signal:** The title is treated as proof of general capability independent of demonstrated scope. The CTO title signals "technical everything" without specifying what technical everything includes or excludes.

**Why it matters — distinct from Axis 7:** The halo effect (Axis 7) generalizes from *demonstrated* competence. The credential-capability conflation doesn't even need demonstrated competence — the title alone does the work. You can hold the CTO title without having demonstrated Builder, Multiplier, or Strategist capability, and the title still signals all three.

**The JD as artifact:** CTO job descriptions are written by copying previous CTO job descriptions, which trace back to some original composite that may have fit one specific company at one specific moment. The title persists; the capability requirements it was originally matched to may have shifted entirely. The credential carries the capability assumption forward through time without revalidation.

**The "titles don't matter" observation:** This cuts both ways. The title inflates expectations beyond actual capability. And the title masks the absence of capability from the outside — signaling "technical leadership is covered" long past the point where the reality has diverged. Both directions produce the same outcome: the title substitutes for ongoing evaluation of whether the capability match is real.

**Credentials become scope labels when:** licensure defines scope (Axis 9 liability framework enforces it), the professional community polices scope violations (Axis 5 internal brake), and failure is individually attributable (Axis 9 again). Remove all three and credentials drift toward capability signals.

---

## Axis 9: Culpability, Liability, and the Social Contract
**Source:** Comparison across medicine, law, accounting, aviation, engineering (PE stamp); 4.7 occupational transitions research (SOX/PCAOB, Air Commerce Act, Tay Bridge inquiry, Abbott 1988)

> **⚑ REVISED 2026-06-27 — section 3.9 researched; Axis 9 DEMOTED from "master variable." See `03_RESEARCH_axes_in_the_wild.md` §3.9.** Liability is **not** the master enforcement variable. Multi-domain evidence: medical malpractice predated specialty boards by 50–80 yrs without causing them; guild/college self-regulation predated tort standard-of-care by ~250 yrs and tort law *defers* to professional norms (Bolam); aviation's flagship safety brake (ASRS) runs on *immunity*, not liability; GARA *removed* a liability burden; the EU is installing software brakes via *regulatory mandate* (CRA), not liability. Law-and-economics consensus (Kolstad-Ulen-Johnson 1990; Faure 2014): liability is unreliable *alone* and is a **complement** to ex-ante regulation + insurance — none individually sufficient. **Liability is one of several co-equal instruments, frequently downstream of professional norms and enacted through insurance.** Candidate replacement master variable: **visible attributable harm** (the common antecedent of *all* brake types; connects to 4.7's named-failure finding). The mechanism described below still holds for *how* liability bounds demand when present — what's revised is its *primacy*.

**Definition:**
- **Liability-bounded demand:** Formal liability structures make the *demand itself* evaluable. A hospital cannot instruct a nurse to perform surgery and then blame the nurse for the outcome — the liability framework makes the demand unreasonable in a legally actionable way. The liability bounds the demand, not just the response.
- **Liability-free demand:** The demand is placed without legal structure. If the individual fails to meet it, the individual is replaced. The demand itself is never on trial. No named person, named credential, or named decision point bears legal accountability for having made an unreasonable demand.

**Axis 9 is the corrective brake — and the highest tier of external governance.** Where Axis 5 is the preventive brake (stopping unreasonable demand before it is made), Axis 9 operates *after* failure. It is not merely "external oversight with legal teeth" — it is the formal social contract between a profession and society: *we will police ourselves within this domain, and if we fail, you have legally actionable recourse.* The social contract has two sides: society grants the profession exclusive jurisdiction over a domain (only licensed physicians may practice medicine); the profession accepts accountability for failures within that domain (malpractice, license revocation, criminal liability). Remove either side and the contract breaks — which is exactly what Enron demonstrated (profession stopped self-policing) and what triggered SOX (society renegotiated the contract by imposing external oversight through PCAOB).

**The social contract requires a named failure to negotiate.** The 4.7 research evidence is consistent across cases: liability frameworks and external oversight bodies appear specifically in response to named failures with named attribution. Not complexity growth alone:
- PE stamp / boiler codes → named failures (Tay Bridge, Grover Shoe Factory, St. Francis Dam)
- Air Commerce Act downstream standards → named failures (United 173 → CRM; Colgan 3407 → ATP rule)
- SOX / PCAOB → named firms (Enron, WorldCom; auditor Arthur Andersen)
- Medical specialty boards → slow-diffusion complexity path (30–50 years after germ theory), then accelerated by military incentive structure (WWII)

The social contract negotiation requires that society has been harmed visibly enough, and attribution has landed clearly enough, that the political will exists to write the contract. Complexity growth alone produces self-governance (Axis 5, Tier 2). It does not produce the social contract.

**Why it matters — three simultaneous functions:**
1. **Bounds the demand:** You cannot ask a doctor to perform surgery outside their licensed scope because *they* bear liability if something goes wrong. Personal, financial, career-ending consequences enforce the scope boundary more reliably than any cultural norm.
2. **Makes failure individually attributable:** When a bridge engineer stamps a drawing and the bridge fails, accountability lands on a named person at a named decision point. The scar tissue (Axis 2) forms *because* the liability framework forces failure to be attributed rather than organizationally absorbed.
3. **Grants jurisdiction in exchange for accountability:** The social contract is what gives the profession its exclusive claim to a domain. Medicine's monopoly on diagnosis and prescription is legitimate *because* medicine accepted the accountability structure. Without the accountability side, the jurisdiction claim is just a guild protecting its territory — which is why software's informal claim to "only engineers should evaluate engineers" carries no institutional weight.

**The CTO case:** When a CTO burns out a team, ships a brittle architecture, or fails the Builder→Multiplier transition — no liability. Neither does the CEO who wrote the impossible JD. Neither does the investor who structured the incentives. The cost is real but lands nowhere specific enough to generate institutional change. The demand is invisible (Axis 1), unlicensed (Axis 8), unmediated (Axis 4), and **unliable**. More precisely: software has the autonomy half of the social contract (no external body tells engineers how to engineer) without the accountability half (no liability, no external oversight, no legally actionable scope violation). It is a jurisdiction without a social contract.

**The science parallel — and divergence:** Science shares the no-liability vulnerability. A scientist publishes a flawed paper; if it fails to replicate, the paper is retracted but no credential is at risk, no financial consequence, no legal exposure. The accountability is reputational and communal, not structural and individual. However: science has the replication crisis as a *weak liability analog* — high-profile failed replications are career-damaging in a way that a software project failure typically isn't. Weak, slow, inconsistent — but present. Software has no equivalent even at that level.

**Interaction with other axes:** Axis 9 is the enforcement mechanism that, if present, would force the others to resolve — and is the mechanism by which the preventive brake (Axis 5) gets installed across generations. Axis 2 (institutional memory) — liability frameworks are *how* scar tissue gets formally encoded; attributed failure is what the memory forms around. Axis 4 (institutionally mediated competence) — the fiduciary standard exists *because* there's a liability framework behind it; the institution mediates because someone is legally on the hook if mediation fails. Axis 5 (internal/external brake) — Axis 9 is what builds Axis 5 Tiers 3 and 4; the social contract is the mechanism that installs the external credential and liability brake. Axis 6 (feedback loop) — liability closes the loop by force; you can't ignore the failure signal when it arrives as a lawsuit or license revocation. Axis 8 (credential as scope label) — credentials become scope labels precisely because the liability framework makes scope matter; without Axis 9, credentials remain capability signals.

---

## Axis 10: The Measurement Paradox
**Source:** Taylor (1911), Hawthorne Studies (1924–1932), Drucker (1954), Brooks (1975), CHAOS Report (1994–present), CEB/Gartner reversion data (2000s–present)
**Position:** The capstone axis — the one that makes all other axes collectively damning rather than individually unfortunate.

**Definition:**
- **Measurement without revision:** The composite demand on cognitive workers has been continuously measured for over a century. The measurements consistently find the same thing — the demand exceeds capacity, failure is structurally predicted, the individual absorbs the attribution. And the demand is reproduced unchanged in every generation regardless.
- **Measurement with revision:** Findings change practice. The scar tissue forms. The institutional brake is installed. The demand adjusts to what the evidence shows is achievable.

**Why this is distinct from Axis 2 (institutional memory deficit):**
Axis 2 describes fields where the memory *doesn't exist yet* — the failures haven't been attributed or codified. Axis 10 describes something more disturbing: the memory *exists*, is cited, is taught in MBA programs, is canonical in management literature — and the demand is reproduced anyway. This is not a memory deficit. This is the akrasia claim in its strongest and most general form.

**The measurement timeline — one continuous tradition:**
- **Taylor (1911)** — *The Principles of Scientific Management* — first systematic measurement of worker output vs. organizational expectation. Found that workers were being asked to produce more than the work structure supported. Response: redesign the work structure. The composite demand on *specialists* was revised. The composite demand on *generalist managers* was left untouched and amplified.
- **Hawthorne Studies (1924–1932)** — first empirical study of knowledge workers in organizational settings. Found that productivity was affected by social and psychological factors, not just task design. Named the human variable. Did *not* find that cognitive tasks were non-fungible — the fungibility assumption survived intact. The measurement found the human; it didn't find the capacity ceiling.
- **Drucker (1954)** — *The Practice of Management* — named the knowledge worker as a distinct category requiring different management than the factory worker. Explicitly argued that knowledge work cannot be Taylorized. Widely cited. Management practice continued to Taylorize knowledge work regardless.
- **Brooks (1975)** — *The Mythical Man-Month* — named the fungibility fallacy directly, in the domain where it was most damaging. Became canonical. The industry built story points, velocity tracking, and headcount-as-capability-proxy in the decades that followed.
- **CHAOS Report (1994–present)** — thirty years of consistent data showing large software projects fail at 6–11% success rates. Published annually. The industry response: continue building large software projects.
- **CEB/Gartner IC→EM reversion (2000s–present)** — n≈30,000, showing ~50% of IC→EM transitions fail. The industry response: continue promoting the best ICs into management without transition support.

**The thesis this axis generates:**
> *The composite demand on smart people is not a software invention. Software is the latest and most compressed instance of a pattern that has been applied to educated cognitive workers since organizations existed — and we have been measuring the failure of that pattern the entire time without recognizing what we were measuring.*

**The pre-software origin — the bureaucrat as prototype:**
Before software engineers existed, organizations had a population of *generalist bureaucrats* — educated administrators who moved across departments, synthesized information, managed projects, and were explicitly valued for *not* specializing. The Weberian ideal bureaucrat (Weber, 1922) is defined by *office*, not by person: a sufficiently educated person fills any bureaucratic role because the role is defined by process, not craft. This is the theoretical foundation for "a smart person can do any administrative task."

When software engineers arrived, they stepped into a cultural slot that was already defined — the smart generalist in the organization. The specialization that programming actually required was invisible against that template. The composite demand wasn't invented for engineers; it was *inherited* from the bureaucrat and applied without examining whether the transfer was valid.

The licensed professions — medicine, law, accounting — are the fields that successfully *argued their way out* of the generalist-bureaucrat template through credentialing, liability, and hard-won institutional memory. The doctor isn't protected because doctors are special. The doctor is protected because the medical profession successfully established that its complexity exceeds the generalist template. Engineers never made that argument successfully. They remained inside the bureaucrat template — and software engineers inherited the most compressed and least-cushioned version of it.

**The Lean Six Sigma note:**
Lean (Toyota Production System, 1950s–1970s) actually *challenges* the fungibility assumption at the operational level — cross-training, kaizen, contextual knowledge as quality mechanism. When exported to the West as Lean Six Sigma, it was re-Taylorized: the statistical tools were adopted, the contextual-knowledge insight was lost. The measurement framework survived; the finding that context is non-fungible did not. This is Axis 10 in miniature: the measurement found the right thing, and the organization extracted the wrong lesson.

**Why this is the akrasia claim at civilizational scale — with a temporal boundary:**
Every generation of management science rediscovers that the composite demand exceeds capacity. Names it differently. Builds tools around the edges. And then the next generation inherits the composite demand intact and starts measuring again.

**The pre/post-internet distinction matters here.** Research into the citation trail (section 3.10 of `03_RESEARCH_axes_in_the_wild.md`) found that the cross-generational chain is broken at every node: NATO 1968 didn't cite prior failure literature, Brooks didn't cite NATO, CHAOS didn't cite Brooks. Each generation independently rediscovered the same empirical problem. Pre-internet, this is structurally expected — the NATO conference was closed, Brooks wrote from direct IBM experience, CHAOS was a private industry report. Knowledge couldn't travel fast enough to form a citation chain even if the intent was there. Cross-generational forgetting (Axis 2) was the structural default; transmission was the exception.

Post-internet, the excuse evaporates. MMM is free online. The CHAOS data is cited in PMP certification curricula. The IC→EM reversion literature is on every tech blog. The finding is findable in minutes — and yet JDs still demand the composite, headcount plans still treat engineers as fungible, CTOs are still hired for all three modes simultaneously. The post-internet case is no longer Axis 2. It is Axis 10.

**The revised claim:** Axis 2 and Axis 10 operate simultaneously at different scales and different historical periods:
- **Cross-generational, pre-internet (~pre-2000):** Axis 2. Each generation lost the finding entirely and rediscovered it from scratch. Structural amnesia — the wheel gets reinvented every 20–30 years because transmission was genuinely hard.
- **Cross-generational, post-internet (~post-2000):** Axis 2 becomes Axis 6. The knowledge is universally accessible but still can't cross the legibility gap from the technical community to the decision-making community. One Google search away; still unreachable.
- **Intra-generational (any era):** Axis 10. Once a finding is canonical within a generation — once MMM is cited, once CHAOS is in the curriculum — the field proceeds as if it isn't. The knowing-and-acting-against happens within the generation, not across it.

Together they are impenetrable: the wheel gets reinvented across generations (Axis 2), and when the new generation finds it, they put it on a shelf and keep walking (Axis 10). The first prevents institutional learning from accumulating. The second prevents the learning that does accumulate from changing practice. The CTO is the current generation's most compressed and visible instance of a failure mode that Taylor was already measuring in 1911 — and that the internet made inexcusable to keep losing.

---

## Axis 11: Language Formalization Origin
**Source:** Observation that professions with standardized language (medicine, law, military) make scope boundaries legible; software and bureaucracy lack this; science sits in between.

**Definition:**
- **Formally originated language:** The discipline's vocabulary emerged from within a credentialing or professional institution. The institution created the words *in order to define scope*. "Cardiologist" means the same thing in Boston and Bangkok because the word and the scope boundary were created simultaneously by the same body. The language carries scope information automatically — outsiders can perceive domain boundaries even without understanding either domain.
- **Academically originated language:** The discipline's vocabulary emerged from universities with shared methodology and notation. Scope is partially encoded — an astrophysicist and a geologist share scientific method and structure, so they can follow each other's reasoning even across domain gaps. But without a single credentialing body, specialization vocabulary isn't standardized across disciplines. Scope is legible within the class; not always across it.
- **Wild-originated language:** The discipline's vocabulary emerged from distributed, uncoordinated practice communities — companies, subcultures, geographic clusters — with no controlling institution. Terms mean different things in different organizations. "Architect," "senior engineer," "lead" are not scope labels; they are local conventions. The language grew faster than any institution could standardize it, and no institution had the authority to try. Language carries capability signal only — no scope information, no boundary.
- **Process-originated language:** The vocabulary was built to describe a procedure, not a discipline. "Clerk" means "person who executes this step in this process." The scope is defined by the workflow, not by any body of knowledge. When the workflow changes or crosses organizational boundaries, the language doesn't transfer — it was never attached to knowledge in the first place. Scope expands automatically when the process expands, regardless of whether the person's capacity expands.

**The four categories and what their language carries:**

| Origin | Examples | Language carries |
|---|---|---|
| Formally originated | Medicine, Law, Military | Scope + boundary + accountability |
| Academically originated | Science | Method + structure, partial scope |
| Wild-originated | Software | Capability signal only, no scope |
| Process-originated | Bureaucracy | Procedure step, no knowledge, no scope |

**Why it matters — the brake failure mechanism:**
Formally originated language makes scope boundaries legible *automatically*. "Cardiologist" tells you what this person does and what they don't do. The cultural brake fires because the vocabulary contains the boundary. Wild-originated language carries no boundary — "senior software engineer" tells you roughly what this person can do but nothing about what they won't be expected to do. The brake can't fire because the word doesn't contain the concept of a limit. Process-originated language creates a different composite demand mechanism: not "you're smart, learn anything" but "the procedure now includes this step, so you do it" — scope creep through workflow expansion rather than through capability assumption.

**Why software's language origin matters specifically:**
Software terminology emerged from practice communities with no controlling institution. The same title means different things across companies, generations, and subcultures. A "CTO" at a five-person startup, a public company, and a defense contractor are doing categorically different jobs — but the title signals the same thing to outsiders: "technical everything." The JD copies the previous JD; the title propagates the composite assumption forward; and no standardizing body exists to say the composite has drifted past what one person can hold.

**The bureaucracy divergence:**
Bureaucratic language didn't originate wild — it originated inside organizations to describe processes. But because the processes weren't grounded in a body of knowledge, the language never developed scope-carrying capacity. A "clerk" in a Maine DMV intake office and a "clerk" processing California mail are executing different processes under the same title. When the process expands (digitization, new regulatory requirements, cross-departmental coordination), scope expands automatically — not because the person can do more, but because the process now says they do more. The composite demand arrives through workflow, not capability assumption, but the outcome is the same: unreasonable demand without acknowledgment that the demand is composite.

**Interaction with existing axes:**
- **Axis 1 (tangibility):** Wild-originated language makes cognitive scope boundaries invisible the same way cognitive complexity is invisible — there's no perceptual signal that "senior engineer" and "CTO" are different jobs the way a scalpel and a keyboard are different tools.
- **Axis 6 (feedback loop):** Formally originated language is the transmission mechanism the feedback loop needs. If the language doesn't carry scope information, the loop has nothing to transmit. You can't tell a founder "the CTO scope is unreasonable" in a vocabulary that doesn't contain the concept of CTO scope limits.
- **Axis 8 (credential as scope label):** Credentials become scope labels when formally originated language backs them. Without formally originated language, credentials remain capability signals regardless of intent — the word "certified" means nothing if the scope behind the certification isn't encoded in the title itself.
- **Axis 9 (liability):** Liability frameworks can only function when the language is specific enough to attach accountability to a named scope. "The cardiologist performed a procedure outside their licensed scope" is a legible legal claim. "The senior engineer was asked to do too much" is not — the vocabulary doesn't contain the boundary the claim would need.

**Research note:** This axis predicts that the historical professions (medicine, law, accounting, engineering) all developed formally originated language *as part of* the same occupational transition documented in 4.7 — the credential, the liability framework, and the standardized vocabulary arrived together because each required the others. Test: did any profession acquire liability frameworks before it standardized its vocabulary? If not, language formalization may be a necessary precondition for brake installation, not merely a correlate.

---

## The Compound: How the Axes Interact for Software/CTO

These axes don't operate independently. For the CTO case, they stack — and they stack in causal order:

0. The decision-maker arrives with the **genius-composite as their prior** — installed by decades of fictional media before any institution shaped them (Axis 0)
1. Complexity is **cognitively invisible** to decision-makers (Axis 1)
2. The field is **too young** to have accumulated the scar tissue that would install the brake — and the institutional memory it did have was *actively suppressed* by the 1950s–1960s reclassification that overwrote specialized women's knowledge with the generalist-bureaucrat template (Axis 2, section 4.9)
3. The invisibility may be **partially incentivized** by organizations that benefit from the composite (Axis 3)
4. **No institutional body** exists to say the demand is unreasonable (Axis 4)
5. The professional community has only reached **Tier 2 self-governance** — internal standards exist (IEEE/ACM, Software Craftsmanship Manifesto) but the community *celebrates* the composite rather than policing it; external credential enforcement (Tier 3) and the social contract / liability framework (Tier 4) have not fired (Axis 5)
6. The knowledge that the demand is unreasonable **cannot cross** the legibility gap to decision-makers — and the social cost of admitting the gap is high enough that the room performs comprehension rather than surfacing it (Axis 6)
7. The title **halos** technical excellence into assumed managerial and strategic excellence (Axis 7)
8. The credential **signals general capability** rather than bounded scope (Axis 8)
9. **No social contract exists** between software and society — software holds the autonomy side of the professional contract (no external body evaluates engineering decisions) without the accountability side (no liability, no licensed scope, no legally actionable demand). The corrective brake has never fired because no named software failure has been large enough, visible enough, and individually attributable enough to force the negotiation (Axis 9)
10. The failure of the composite demand has been **continuously measured for over a century** — and the demand is reproduced unchanged in every generation regardless (Axis 10)
11. The **vocabulary used to describe the role carries no scope information** — wild-originated language cannot transmit the boundary even when the boundary is known; "CTO" signals "technical everything" with no word for what it excludes (Axis 11)

**The sequential relationship between Axes 5 and 9 is the structural core of why the system is stable:**
Axis 9 (corrective brake / social contract) is what builds Axis 5 (preventive brake) across generations. The causal chain in every profession that successfully specialized: named failure → named attribution → liability event (Axis 9 fires) → institutional memory encodes the lesson (Axis 2) → internal community internalizes the scope limit (Axis 5 Tier 2 → Tier 3) → external audience learns to respect the scope limit (Axis 5 Tier 4). Software has no named failure large enough to start this chain. The internal brake is running at Tier 2; it cannot self-install to Tier 3 or 4 without either a triggering failure event or absorption by an adjacent licensed profession (the absorption path already happening in safety-critical domains).

Each axis alone would be a problem. Together they form a system that reproduces the unreasonable demand reliably, invisibly, and without any structural mechanism for correction. Axis 10 is what makes the system *indicting* rather than merely unfortunate: this is not a young field making understandable mistakes. This is a pattern with a hundred years of measurement behind it, still running.

**The ambient condition: authority / consequence misalignment**

The axes stack the way they do because of an underlying structural condition that none of them individually names: **the person who holds decision authority and the person who bears the consequence of that decision are systematically different people.**

The CEO writes the impossible JD — no consequence. The investor structures the incentives — no consequence. The board approves the composite hire — no consequence. The CTO absorbs the demand, fails the transition, burns out the team — consequence lands here. The engineer implements what management directs — consequence lands here when the product fails or the fraud surfaces. The women who built the ENIAC were classified as clerical — consequence of that classification landed on them, not on the institution that made it.

No single actor in this system is malicious. Every actor is executing their role inside a structure where authority and consequence are co-located at different levels of the hierarchy. This is the Arendt observation at organizational scale: not evil, but thoughtless in the precise sense — the decision-maker is insulated from the outcome of their decision by the structure itself.

This condition is not an axis — it is the *ambient state* that allows the axes to stack without self-correcting. When Axes 4, 5, and 9 are simultaneously absent (no mediating institution, no external brake, no social contract), authority accumulates at the decision point with no structural check, and consequence accumulates at the bottom with no structural relief. The axes describe the specific mechanisms; the authority/consequence misalignment is the condition those mechanisms operate inside.

**Why it recurs across the corpus:** Semmelweis's physicians had institutional authority over medical practice and bore no consequence for patient mortality. Software engineers had no authority over waterfall adoption and bore the consequence of its failure. VW engineers had no authority over the defeat device directive and bore partial consequence for its fraud. The women of early computing had no authority over their own reclassification and bore the consequence of being written out of the field's founding narrative. Same condition, different domains, different eras.

**Why it matters for the research:** The authority/consequence misalignment is what makes the system *self-reproducing*. The people with the power to change the demand never experience the cost of the demand. The people who experience the cost have no power to change the demand. This is not correctable by education, persuasion, or cultural change alone — it requires structural realignment of authority and consequence, which is precisely what Axis 9 (social contract) and Axis 5 Tier 4 (liability framework) accomplish when they fire.

*Flagged as a potential meta-axis or structural condition pending further research. Connects directly to sections 1.1 (Milgram / Arendt), 5.1 (authority bias), 4.9 (gendered reclassification), and 4.7 (occupational transitions). The Milgram / Arendt research in those sections addresses compliance from the bottom of the hierarchy; this condition addresses the structural insulation at the top. Both are required for the full picture.*

**The akrasia framing (T4):** The Mythical Man-Month is simultaneously accepted and acted against. The field agrees Brooks was right and then staffs, scales, and writes JDs as if he were wrong. Knowing-and-acting-against is irrational by the field's own lights. The axes explain *why the akrasia is stable*: the knowledge exists (MMM is cited, Aristotle is cited, the reversion rate is real) but cannot reach the decision point in actionable form (Axis 6), is not enforced by any liability structure (Axis 9), and is actively obscured by the halo on the credential (Axes 7, 8) — and has been reproduced across institutional generations without revision (Axis 10). The irrationality isn't random — it's structurally reproduced across a century of evidence.

---

## Science and Software as Cousins

Science and software share the *vulnerability structure* across most axes:
- No personal liability for being wrong (Axis 9 — weak or absent)
- Unlicensed identity; credential is a capability signal not a scope label (Axis 8)
- Strong internal brake, weak external brake (Axis 5)
- Feedback loop broken between expertise community and public (Axis 6)
- Complexity incidentally invisible to the public (Axis 1)

**Where they diverge — and why it matters:**
- Science has a *weak liability analog* in the replication crisis (career-damaging, not legally binding)
- Science has no commercial demand structure placing the impossible composite demand on a specific person in a specific seat — the unreasonable demand in science is diffuse (public consumption) not contractual (employer JD + board enforcement)
- Science has a clearer internal hierarchy of credibility — a virologist challenging a cosmologist on virology wins within the community; software has no equivalent body whose job it is to say "this CTO demand is unreasonable"

**The NDT case as parallel:** The audience can't evaluate whether a cosmologist knows immunology, so they defer to "scientist" as the signal — same broken feedback loop (Axis 6), same halo-bounded authority (Axis 7), same credential-as-capability-signal (Axis 8) that produces the impossible CTO JD. Same structural failure, different demand mechanism, different consequence architecture.

---

## Open Research Questions (To Be Filled)

These axes are hypotheses. Each needs evidence before it becomes a finding:

0. **Axis 0 — What archetypes dominate technical media, and across what decades?** The genius-composite claim needs a cultural inventory: which archetypes, which media, which eras, which audiences. The causal claim (fiction installs the prior) is hard to prove; the normalization claim (fiction makes the composite feel like the default description) is more tractable. Literature on media effects on occupational expectations may exist — worth searching before asserting.

1. **Axis 1 — Is the invisibility empirically testable?** Can we find studies on how non-technical decision-makers model software complexity vs. physical-domain complexity? The cognitive invisibility claim should be grounded, not just asserted.

2. **Axis 2 — What is software's institutional memory deficit, measured?** The CHAOS Report data (30 years of consistent large-project failure) is the closest thing to a measured failure rate. Does the field's response to it — or non-response — document the memory deficit?

3. **Axis 6 — The broken feedback loop.** Is there evidence that technical community knowledge about composite-role failure doesn't reach hiring decision-makers? JD archaeology (what JDs say vs. what the technical community says) would be direct evidence.

4. **Axis 9 — Liability as the master variable? — TESTED, ANSWER: NO.** *(Resolved 2026-06-27, §3.9.)* The test ran and **disconfirmed** the master-variable claim. Brakes routinely install *before* or *without* liability (guilds ~250 yrs early; medical specialty boards 50–80 yrs after malpractice but driven by knowledge/market threat, not it; aviation's ASRS via immunity; EU software brakes via regulatory mandate). Liability is *one of several co-equal complements* (with regulation + insurance), often downstream of professional norms. The candidate that inherits the "master variable" role is **visible attributable harm** — the common antecedent of all brake types (connects to the named-failure finding in 4.7). Worth a dedicated future test of harm-visibility as the master variable.

5. **The akrasia evidence gap (T4).** The akrasia claim requires (a) the field genuinely accepts MMM/non-fungibility — citable, canonical — and (b) the field genuinely acts against it. Half (b) needs the JD, the headcount plan, and the composite CTO hire as documented artifacts of the acting-against. Both halves must be evidenced before the claim is load-bearing.

6. **Historical occupational transitions — the tipping moment.** Medicine, law, accounting, engineering, and aviation all successfully separated the composite demand into specializations. The trigger in every case was the same: complexity became *visibly and individually attributable through failure* before the credential and liability structures followed. Can we document the specific tipping moment for each? The Tay Bridge (engineering, 1879), germ theory (medicine, 1860s–1880s), Enron (accounting, 2001), the Air Commerce Act (aviation, 1926) are candidates. These are the comparison baseline for what it would take software to make the same transition — and they directly evidence Axes 1, 2, 9, and 10 simultaneously. See `00_RESEARCH_PLAN.md` Track 4, section 4.7.

7. **Composite demand concentrates on high contributors — but NOT via Price's Law.** *(Updated 2026-06-27 — section 4.8 researched; hypothesis revised.)* The original prior leaned on Price's Law (√N produces half the output). **Research disconfirmed the √N form** — refuted even in its home domain of scientific authorship (Nicholls 1988: 7 of 48 datasets fit), untested for organizational contribution, and reaching general discourse mainly via Jordan Peterson's popularization, not the bibliometric literature. The defensible underlying concept is **cumulative advantage** (Price 1976 unified Pareto/Lotka/Zipf under it), not Price's Law. The personal observation — organizations *add* composite demand to high contributors rather than protect them — **survives and is upgraded**: the documented mechanism is **citizenship pressure / Compulsory Citizenship Behavior** (Bolino 2010; Vigoda-Gadot 2006; CCB↔burnout ρ=0.71), where discretionary contribution becomes felt obligation under pressure from powerful others (the Milgram/authority interaction, internalized). The damage is driven by **involuntariness, not volume** — highest contributors show *less* fatigue (inverted-U, Xu 2021); those who feel they "have no choice" deplete (De Clercq 2021). See `04_RESEARCH_pre_software_history.md` §4.8.

8. **The gendered reclassification — when was the fungibility assumption installed, and by whom?** Programming was specialized work performed by selected women before the reclassification of the 1950s–1960s masculinized and generalized it. The aptitude tests that drove that reclassification were circular (measuring a constructed male profile, filtering for it, then using the filtered population to define the profile). The fungibility assumption arrived with the reclassification, not organically. Can we document precisely what was known about programming's specificity before the reclassification — and what was suppressed when the generalist template replaced it? Ensmenger (2010), Abbate (2012), and Light (1999) are the primary research targets. Directly evidences Axes 2, 5, 8, and 10. See `00_RESEARCH_PLAN.md` Track 4, section 4.9.

---

*Workshopped collaboratively June 25, 2026. These are hypotheses before the research pass — the research pass tests them, it does not confirm them.*
*Axes: 0 (fictional media) → 1 (tangibility) → 2 (institutional memory) → 3 (structural obscuring) → 4 (institutional mediation) → 5 (internal/external brake) → 6 (feedback loop) → 7 (halo authority) → 8 (credential-capability) → 9 (liability) → 10 (measurement paradox) → 11 (language formalization origin).*
*Connection map: `CTO/TODO.md` T2 (expectation audit) and T4 (cultural permission structure); `Software Industry/00_AXES_SUMMARY.md` (sibling); `CROSS_REFERENCES.md` (three-area index); `00_RESEARCH_PLAN.md` (five tracks, research targets, spillage map).*
