# Draft Thesis: The Skill-Set Divergence Argument

> ## ⚠️ SUPERSEDED AS THE BUILD TARGET (2026-06-25) — read this first
>
> **This file is no longer the document to build the public paper from.** The externally-facing draft is now [`DRAFT_SYNTHESIS.md`](DRAFT_SYNTHESIS.md), built on the independent adversarial review's defensible distillation ([`R3_STEELMAN_strongest_form.md`](R3_STEELMAN_strongest_form.md)). Where this file's phrasing conflicts with `R3`/`DRAFT_SYNTHESIS`, **prefer those.**
>
> **Why it was superseded — the discoveries kept changing our assumptions.** This draft was written during the *incremental* research phase, when each session's conclusion became the next session's premise. That is how the work actually progressed — and it is exactly why this file accreted claims that later research, and then an independent adversarial pass (`R1`/`R2`), narrowed or retired. The most visible casualty is in this file's own working title: **"*Why the CTO Role Is an Irrational Composite*."** The word **"irrational" has been retired** — `R1` showed the role's *design* may be a rational equilibrium under budget constraint (the composite is what the company can afford; the harm lands on the person, not the logic). The defensible claim is **"structurally under-resourced,"** not "irrational." Other claims this file still states in their original strong form — "a mismatch of *kind*, uniquely the CTO," three modes as a *discovered structure* rather than a *useful lens*, the etymology/investor material as load-bearing — were likewise narrowed downstream. See `R3`'s must-not-claim table and `DRAFT_SYNTHESIS` §5 for the full list of retirements.
>
> **What this file still is (why it's kept, not deleted):** the *source of record* for material that survived into the synthesis — the transformation model (§1, now `AX-MW2018`/`AX-VL2023`-grounded), the IC/management divergence (§2), the competence-trap mechanism (`AX-COMPETENCE`), and several anchors still point here. It is the honest artifact of how the thesis was discovered, including the parts that didn't survive contact. **Superseded as the build target ≠ wrong** — it is the earlier, less-narrowed framing, preserved for provenance.

**Working title:** ~~*One Title, Three Skill Sets: Why the CTO Role Is an Irrational Composite*~~ → *(retired — see banner; the defensible framing is "the under-resourced CTO," `DRAFT_SYNTHESIS`)*
**Status:** **Superseded as build target** (2026-06-25). Historical/source-of-record. Prior lead draft of the incremental phase.
**Created:** 2026-06-24
**Relationship to existing corpus:** This is a *reframing*, not a replacement. The original working document (`05_FULLTEXT_working_document.md`) argues from failure/success modes inward to the skills mismatch, and opens with etymology. This document **inverts the order of argument**: it starts from the skill-set divergence as the primary, observable phenomenon (Section 1), treats the irrational composite as the named condition (Section 3, with etymology folded in at §3.1 as the reason the structure went unnamed), and treats failure as the predicted symptom (Section 4). *(Note: the synthesis later kept the §1 inversion and §2 divergence, but retired §3's "irrational composite" naming and demoted §3.1's etymology to a contingent layer — see banner.)*

---

## Why a new entry point

The original research began as a diagnosis of CTO failure and success modes. The taxonomy, etymology, and Greiner alignment were all assembled to *explain the failures*. That makes failure the subject and the skill mismatch a downstream finding.

But the strongest evidence for the whole framework was sitting in the skills compendium the entire time. **We can observe the skill-set divergence directly** — it does not require survival data, etymology, or theories of failure to establish. It is visible in the job description of the role at each stage. Failure then follows as a prediction, not as the premise.

The new argument order:

1. **Observe** — the CTO is asked to be excellent at three skill sets with *different focuses* across the arc of one tenure.
2. **Establish** — these skill sets are not "more of the same skill maturing." They point in different directions: at the product, at people, at the market. The industry's own structures treat them as different *jobs*.
3. **Name the condition** — asking one person to hold all three, sequentially, in the most fragile window of the company, is an **irrational condition**.
4. **Predict** — this irrational condition is what concentrates failure at the boundaries *between* the skill sets, not within them.

The original failure evidence (Greiner, Carta/Crunchbase, the failure-clustering data) becomes **confirmation of a prediction the skills argument makes**, rather than the thing the argument was built backwards from. That is a stronger rhetorical and logical position.

---

## The thesis, stated

> **We are expecting a single CTO to be excellent at skill sets that have completely different focuses over the course of their career — directing their effort at the product, then at people, then at the market.**
>
> **This is an irrational condition. It is what contributes to the failure mode that clusters between significant company stages, rather than within them.**

Two claims, deliberately separated:

- **Claim 1 (the observation):** The skill sets diverge in *focus*, not just in *level*. (Established by inspection — Section 2.)
- **Claim 2 (the consequence):** That divergence is an irrational thing to demand of one person, and the irrationality surfaces as boundary failure. (Argued — Sections 3–4.)

Claim 1 is hard to dispute. Claim 2 is the contribution. Keeping them separate means a skeptic who accepts the observation is already on the hook for most of the argument.

---

## Section 1 — The observation: three focuses, one person

Consider what we ask a startup CTO to be good at, and when.

At pre-seed, the job is the product. The CTO selects the stack, designs the system, writes the load-bearing code, and makes every architectural call directly — speed over perfection, the design living mostly in their own head. Excellence here is measured in shipped product and sound technical judgment under uncertainty.

Eighteen months later, at Series A, the same person is asked to be good at something with no technical content at all. The job is now people: running structured 1:1s, defining a career ladder, installing a hiring process that does not depend on their personal network, and — hardest of all — releasing the technical decisions they were previously praised for making. The skill that defined them in the first job is now the thing they must stop doing for the second job to succeed.

Eighteen months after that, at Series B, the focus moves again — this time outward. The job is the market and the future: the board narrative, the three-to-five-year platform bet, the external relationships and industry presence. Internal management, the entire content of the previous job, is now something the CTO must hand to a VP of Engineering and largely stop doing.

Three jobs. One title. The object of the CTO's skill moves from the product, to people, to the market — and at each move, the excellence that defined the previous mode becomes something they must actively hand off, while the next mode demands a skill they do not yet have. The transition is not a step up a ladder; it is a transformation the CTO undergoes while still carrying the prior job, until they can set it down safely. These are not three depths of a single competence. They are three different competences pointed in three different directions, and the industry knows this: it has split exactly these skills into separate career tracks (individual-contributor versus management) and, at scale, into separate roles (CTO, VP Eng, Staff Engineer). We have formally declared, twice over, that these skills do not belong in one person — and then we demand all three from one person, sequentially, in the most fragile window of the company's life, and call it a single job.

This paper argues that this demand is not difficult but irrational, and that its irrationality is the proximate, predictable cause of the failures that cluster at the seams between the modes — not within them.

The same observation, in tabular form — across a CTO's tenure, the *object of their skill* moves:

| Mode | Stage | Skill is directed **at** | Primary output |
|---|---|---|---|
| Builder | Pre-seed → Seed | **The product** — architecture, code, technical decisions | The product itself |
| Multiplier | Seed→A → Series A | **People** — coaching, delegation, team infrastructure | Team capability |
| Strategist | Series B → B+ | **The market / the future** — vision, board, external bets | Direction |

The point is not that the work gets *harder* or *bigger*. It is that it points *somewhere else*. A Builder who becomes twice as good a Builder has not moved toward Multiplier — they have moved *further from it*. Skill in one focus does not accumulate toward the next; in some respects it actively resists it. The mechanism is documented in human terms: the **competence trap** (organizations and individuals over-exploit an existing competence and under-explore new ones) and **cross-domain overconfidence** (deep expertise in one domain inflates confidence in an adjacent one where the causal rules differ). Each makes the expert *more* likely to misapply their strongest instincts at exactly the boundary where those instincts stop working. <!-- APPENDIX-REF: AX-COMPETENCE — competence trap + Dunning-Kruger cross-domain as the human mechanism for boundary failure. See 07_APPENDIX #20/#21. TEE demoted to analogy (it's an AI-systems paper) — see 07_APPENDIX #10. -->

This is the crux: **the skill sets do not stack like a ladder, and the CTO does not simply pivot away from the old one. Each transition is a transformation — two motions at once.** At every boundary the CTO must:

1. **Offload** the previous mode's responsibilities — cleanly transferring each one out, either to a *person* (delegation) or into a *system* (institutionalized process, tooling, documentation), until they no longer hold it. Successful transformation ends with the old load fully transferred, not partially retained.
2. **Acquire** the next mode's responsibilities — picking up a skill set with little or no overlap with the one being released, and becoming excellent at it on the company's timeline, not their own.

The danger is that these motions run **simultaneously and in tension**. The old responsibilities do not leave on their own; they have to be actively pushed off. Until the offload completes, the CTO is carrying *both* loads at full intensity — the un-transferred old job and the not-yet-mastered new one. The boundary is lethal not because the new job is hard, but because for a window the CTO is doing two jobs that share no skills, and the success condition is to finish transferring the first *before* the weight of both breaks something.

### How the transformation fails

Because the transformation is two motions, it has three distinct failure signatures — not one. They are not severities of the same failure; they have different mechanisms and different tells:

| Failure mode | Mechanism | What it looks like |
|---|---|---|
| **Failure to acquire** | Offloads (or is forced off) the old responsibilities, but never picks up the new skill set in time. | Stuck. The CTO has let go of building but cannot yet lead/strategize — a gap with nothing in it. |
| **Burnout** | Carries both full loads simultaneously and refuses to drop either. Collapses under the doubled weight. | Overwork, then breakdown. Was excellent at everything until they weren't. |
| **Slippage / neglect** | Refuses to offload, cannot keep up with the combined load, so responsibilities silently drop. *No collapse* — things just don't get done. | Procrastination on duties they won't delegate. Work quietly slips. The CTO looks fine; the *output* has holes. |

The third is the easiest to miss and the one most often mistaken for a personality quirk. A CTO who will not delegate and therefore lets tasks slip is not lazy and is not burning out — they are failing the *offload* half of the transformation while looking, day to day, like they are coping.

The offload-and-acquire model is not only observed — it is grounded in peer-reviewed entrepreneurship research. Mathias and Williams (2018), in an inductive field study of 45 founders, describe exactly this structure: founders "face important decisions about which roles to give up, which roles to retain, and which new roles to adopt." Critically, they identify *why* the offload half is hard — roles "represent more than just something entrepreneurs do but also an important part of who they are (role identities)." Releasing a role is an identity loss, not a task hand-off. This is the same identity-threat mechanism the failure literature already attaches to the Builder→Multiplier transition, and it gives the *slippage* failure mode a named cause: the CTO who will not delegate is defending a role-identity, not avoiding work. <!-- APPENDIX-REF: AX-MW2018 — Mathias & Williams (2018), transformation model + identity mechanism. See 07_APPENDIX. -->

This raises the obvious objection: if offloading means surrendering part of one's identity, how does anyone ever do it? The same research answers it, and the answer reshapes what "offload" means. Mathias and Williams find that founders who successfully transition *physically* disengage from a role — they stop doing the work — without *psychologically* disengaging from it. They keep the meaning; they drop the activity. The transformation does not require the CTO to stop caring about building. It requires them to stop building. That is a far smaller identity ask than "stop being a builder," and naming the difference is itself part of the intervention: much of the resistance comes from conflating the two.

The mechanism by which the offload completes is equally concrete. Mathias and Williams call it *role-identity imprinting*: the founder transfers a role by imprinting it onto another person — training and shaping them until the founder can see their own "stamp" in how that person carries the work — and it is seeing that stamp that finally frees the founder to move on. The slippage failure mode is the photographic negative of this: founders who believe "no one can be me," or who cannot see employees as an extension of themselves, never complete the imprint and so never let go. <!-- APPENDIX-REF: AX-MW2018 — physical-vs-psychological disengagement + role-identity imprinting (success/failure paths). See 07_APPENDIX. -->

This tells us what a successful transformation actually *requires* — not just willpower, but conditions in the receiving team. Van Lancker and colleagues (2023), studying founder role evolution during scaling, identify two: the person taking over the role must experience **psychological safety** (they cite Edmondson's construct — the same psychological safety that Project Aristotle independently found to be the top predictor of team effectiveness), and the founder must perceive **value fit** — a belief that the receiver genuinely shares the venture's values. Where value fit is absent, founders pull the role back. Both papers converge on the same condition from opposite directions: the offload sticks only when the founder trusts that the receiver shares what made the role meaningful. <!-- APPENDIX-REF: AX-VL2023 — Van Lancker et al. (2023), offload success conditions (psychological safety + value fit). See 07_APPENDIX. -->

For the CTO this is exactly where the title turns against them. The Builder must imprint technical craft onto a team and trust that team to carry it — but the title tells the company, the board, and the CTO themselves that the craft *is* the CTO. The very signal that is supposed to certify the role works against the value-fit perception the offload depends on: it is hard to believe "they can carry this" about work the org has named after you. The conditions for a successful transformation are well understood; the CTO is the role structurally configured to deny itself those conditions.

---

## Section 2 — Establishing divergence (not just difference)

Three independent lines show these are different skill sets, not stages of one skill. Each can stand alone; together they make the divergence hard to wave away.

### 2a. The industry splits them into separate tracks
The IC vs management track bifurcation exists *because* technical-craft skill and people-leadership skill are recognized as different enough to require different career paths, different evaluation, different promotion criteria. The industry formally declared these incompatible — then asks the seed-stage CTO to hold both at once. It is widely reported that technical skills atrophy after the move into management, as the cognitive and calendar demands of leading displace hands-on practice — the practitioner literature treats this as a defining hazard of the transition. <!-- APPENDIX-REF: AX-ATROPHY — IC/management track divergence + skill atrophy. Qualitative claim well-corroborated; the specific "2–3yr" figure and the "HR Oasis" source were dropped as unverified. See 07_APPENDIX #13/#14. -->

### 2b. The industry splits them into separate roles at scale
At Series B+, the composite is **distributed**: CTO, VP Eng, EMs, Staff/Principal engineers each own a slice. Larson's Staff Engineer archetypes map onto the modes almost exactly. The organization's mature solution is *role differentiation* — which is only necessary if the skills genuinely diverge. *(Source: Larson 2021 — `07_APPENDIX` #15.)*

### 2c. The skills compendium shows the offload directly
The master skills compendium (`02_ARTIFACT`) maps each skill across modes by **transfer type** — `→ people`, `→ system`, `→ both`. This is the offload half of the transformation made concrete: every skill that has to *transfer* at a transition (rather than simply deepen) is a responsibility the CTO must actively push off to complete the change. A skill that just matured would not need to be handed off or institutionalized; it would stay with the person. The `→ people` / `→ system` columns are not metadata — they are the *exit routes* for the old load, and the compendium's own structure assumes every one of them gets used. A CTO who leaves those transfers incomplete is, by the compendium's own logic, mid-transformation with the old load still attached.

**The synthesis:** The industry's own architecture — two tracks, and role distribution at scale — is an admission that these are different jobs. The irrationality is asking one person to be all of them, alone, in the pre-seed-to-Series-A window, before any of the distributing structure exists.

---

## Section 3 — Why this is an *irrational* condition

"Irrational" is a strong word; here is the load it carries. The demand is irrational because it is **internally contradictory with the asker's own beliefs**:

1. **It contradicts the industry's own track design.** We built two career ladders on the premise that craft and people-leadership are different enough to separate — then demand both from one person at the start.
2. **It contradicts the industry's own scaling solution.** We distribute the composite across four-plus roles the moment we can afford to — proving we don't think one person *should* hold it — yet we require exactly that when the company can least absorb the failure.
3. **It is temporally concentrated at the worst moment.** The composite is demanded precisely in the pre-seed → Series A window: when the company is most fragile, the CTO is most alone, the peer gap is widest, and compensation defers the reward to an outcome most companies never reach.

The irrationality is not that the job is hard. Hard is fine. The irrationality is that **we demand a composite we have already, structurally and repeatedly, declared should be decomposed** — and we demand it at the one stage where there is no slack to absorb the cost of getting it wrong.

### 3.1 Why the irrational structure went unnamed: the inherited title

An irrational demand this visible should have been corrected long ago. It wasn't — and the reason is in the title itself. "Chief Technology Officer" was not designed for the job startups use it for. It was coined in the late 1980s at large industrial firms — GE, Allied-Signal, ALCOA — to name an executive sitting *above* an established engineering organization of hundreds: research strategy, platform vision, external scientific relationships. The first academic study of the role (Adler & Ferdows, 1990) found twenty-five such people across a hundred of America's largest industrial companies. The original CTO was, in every case, a Strategist with an organization already running beneath them. *(Citations pending review — `07_APPENDIX` #1, #2.)*

When startups borrowed the title during the dot-com era, they applied it to its structural opposite: a solo technical co-founder writing the first lines of code, with no team at all — a Builder. The three letters stayed the same; the job they named inverted. Crucially, the title carried **no instruction manual**, because it was inherited rather than designed for the startup context. It names a single continuous role and centers "technology" as the differentiating skill — and both of those signals are wrong for every stage except the last.

This is why the irrationality persisted unnamed for thirty-five years: the people living it had no language for it. A title that implies one job cannot warn you that you are being asked to do three. The etymology is not the core argument — the skill divergence in Section 1 is — but it explains the *silence*: an irrational structure inherited under a misleading name is an irrational structure no one was equipped to see.

### 3.2 Scope mismatch versus kind mismatch: why only the CTO is catastrophic

A fair objection arrests the argument here: if the CTO title was inherited from an enterprise context at scale, so was every other C-suite title — CEO, CFO, CMO were all coined for mature functions at large firms. Why single out the CTO?

The answer isolates a single variable. Every Chief Officer title was created *at scale, for the mature mode it currently occupies*: the CFO when companies needed a financial strategist, not a bookkeeper who had to become one; the CMO when they needed a marketing strategist, not a brand designer who had to evolve; the CTO, consistently, for a technology strategist at GE and Allied-Signal. So applying *any* of these titles to a pre-scale startup imports an executive-scale job description into a pre-organizational context. The anomaly, at this level, is not the CTO title — it is applying any C-suite title pre-scale. This condition is *constant* across all the roles; it cannot explain why the CTO specifically breaks.

What differs is one thing. For every other C-suite role, the core skill does not change direction as the company grows — it only scales. The CFO at seed does what the CFO at Series B does: manage money; scope expands, focus holds. The CMO owns the market narrative at every stage; channels and budget scale, direction holds. **Only the CTO's focus rotates** — product, then people, then market — because the IC/management bifurcation that forces this rotation exists in no other discipline (Section 2a).

The conclusion follows cleanly, and it is the sharpest statement of the thesis:

> The migration of C-suite titles to startups was **universally irrational — but only *catastrophically* irrational for the CTO**, because the technical function is the only one where the job changes *direction* rather than merely *scaling*. Every other executive title imported a mismatch of **scope**. The CTO imported a mismatch of **kind**. <!-- APPENDIX-REF: AX-SCOPEKIND — C-suite origin comparison (CEO ~1917 / CFO 1970s [SEC/FASB, est. 1973] / CMO 1993 Coca-Cola / CTO late-80s); scope-vs-kind. CMO-tenure & CFO-1979 specifics corrected — see 07_APPENDIX. -->

A scope mismatch is survivable: it asks for the same skill, sooner and with less support. A kind mismatch asks one person, pre-scale, to span two skill tracks the industry itself formally declared incompatible — sequentially, three times. That is not merely hard; it is a dominated demand, irrational in the precise sense that no version of meeting it is rational.

### 3.3 The misnomer was installed, not merely inherited

The account so far treats the misnomer as passive drift — a title that arrived without an instruction manual. The evidence suggests something more active: the title was *installed, and reinstalled every funding cycle*, by an incentive that has nothing to do with organizational coherence.

The mechanism is investor signaling. Enterprise CTOs at GE, Allied-Signal, and IBM made the title an institutional credibility marker. Venture investors in the 1990s, trained on institutional patterns, read a complete C-suite as reduced risk — and at pre-seed and seed, where there is little traction to evaluate, they bet almost entirely on the team. A "CTO" on the team slide signaled precisely what an investor needed to hear: technical execution risk is covered by a named, senior executive. Startups filled that slot not because the role existed organizationally, but because the slide required filling and the title *worked for fundraising* — in a dot-com moment that rewarded signaling over fundamentals (over 80% of late-1990s internet IPOs were loss-making).

The consequence is the part with teeth:

> A Builder doing an individual-contributor job was given a Strategist title to satisfy an investor pattern-recognition heuristic — then measured against that title's implied expectations at the next round, with no support structure to get there. **The investors who required the signal helped create the structural problem they were trying to avoid.** The irrational composite was institutionalized by the very party whose job is to evaluate execution risk. <!-- APPENDIX-REF: AX-INVESTOR — investor-signaling causal chain; dot-com "management by press release." Causal-narrative, not measured study — see framing caution in 07_APPENDIX. -->

This reframes the misnomer as *maintained*, not just inherited: correcting it would mean removing a credibility signal investors rely on, so the incentive to keep it is structural. It also repositions the investor-facing implications of this framework (Section 5) — investors are not neutral diagnosticians of this failure; historically, they are its co-authors. *(This is a causal narrative assembled from signaling evidence, not a measured causal study; the published form should claim the evidence is consistent with the title functioning as an investor signal, not that investors caused the failure. See `07_APPENDIX`.)* <!-- RISK: RISK-INVESTOR-CAUSAL — publish as "consistent with," not "caused." Paired with AX-INVESTOR. Registered in CONVENTIONS.md. -->

---

## Section 4 — The prediction: failure clusters at the transformations

If the skill sets were a single maturing competence, failure would distribute smoothly with scale — bigger company, proportionally bigger challenge. It does not. Failure **clusters at the boundaries between modes** — the Seed→A and Series B transitions — exactly where the transformation (offload-and-acquire) is demanded. The transformation model makes a sharper prediction than "transitions are hard": because the boundary is where the CTO carries two non-overlapping loads at once, it is precisely there that *all three* failure signatures — failure-to-acquire, burnout, and slippage — should appear, and nowhere else. Within a mode, there is no second load to carry; the conditions for these specific failures do not exist.

This is what the skills-divergence argument *predicts*, and it is what the failure data *shows*:

- Greiner's phase-crisis model independently locates crises at the transitions, not mid-phase. *(`07_APPENDIX` #3.)*
- Carta/Crunchbase attrition data shows two distinct high-attrition transition points. *(`07_APPENDIX` #7 — verify these are real, separate transition points.)*
- The compensation gap (Kruze) is largest at Seed→A — the first transformation. *(`07_APPENDIX` #9.)*

<!-- XREF: XR-ASYMMETRY-DRAFT — guards RISK-ASYMMETRY at this claim site. See 07_APPENDIX review note #3. -->
> **Note (carried from `07_APPENDIX` review):** the "0 Strategist / 2 Builder / 22 Multiplier" research-population asymmetry should **not** be used as confirming evidence here. It is a research gap, not support. If referenced, frame it as "we cannot yet test the third transformation empirically," not as proof. See `07_APPENDIX` review note #3.

The inversion's payoff: failure is no longer the thing we set out to explain. It is the **falsifiable consequence** of an observation we can establish independently. If the skills genuinely diverge in focus, failure *must* concentrate at the transformations — and it does. The three failure signatures give the prediction teeth: a competing "CTOs just need to be better/smarter" model predicts failure scales with difficulty; the transformation model predicts three *specific, distinguishable* failure tells, all located at the boundaries. That is testable.

---

## Section 5 — What this reframing changes downstream

- **Hiring:** Stop hiring "a CTO." Hire for the *current mode* and name the next transformation out loud. A great Builder hire is not a failed Strategist; they are a correct Builder.
- **Evaluation:** Judge the CTO against the focus their stage demands, not against a composite ideal no one satisfies. At a boundary, evaluate *both* motions separately: is the old load being offloaded, and is the new one being acquired? The three failure modes are distinguishable in review if you look for them — a slipping CTO and a burning-out CTO need opposite interventions.
- **Transition support:** The boundary is the dangerous place. Resource the transformation — VP Eng hire, explicit offload plan, named hand-off targets for each responsibility — *before* the company needs it, because the old load does not leave on its own and the new skills don't arrive on their own.
- **Self-knowledge (the practitioner brief):** "Which mode am I actually good at, and am I willing to undergo the next transformation — to give up the work I'm good at and learn work I'm not?" is a more honest question than "am I a good CTO?"

---

## Open questions for this draft

1. ~~Is "rotation" the right metaphor?~~ **Resolved (2026-06-24): no — replaced with "transformation."** Rotation wrongly implied turning *away* from the old focus. The real model is two simultaneous motions — *offload* the old responsibilities (fully, to people or systems) while *acquiring* the new ones — held in tension across the boundary. This also fixed the blend objection: the overlap isn't a flaw in the model, it *is* the model (the dangerous window where both loads are carried at once). Yielded the three-failure taxonomy (failure-to-acquire / burnout / slippage). See §1 crux and §4.
2. ~~Does starting from skills weaken the etymology hook?~~ **Resolved (2026-06-24):** Skills-first. Version A is now the opener (Section 1); etymology moved to §3.1 as the mechanism explaining why the irrational structure went unnamed. Skills-first is more rigorous and needs no citation to land its first punch.
3. **Claim 2's "irrational" — is contradiction-with-own-beliefs the strongest framing,** or is there a cleaner formal sense of irrational (e.g., demanding a dominated strategy)? Worth sharpening. — *Still open.*
4. **How much of the original failure-diagnosis document (`05_FULLTEXT`) survives as a standalone, vs folds into Section 4 as "the prediction, confirmed"?** — *Still open. The full working document's §1 already seeds the skills hook, so the merge path exists; decide whether `08_` supersedes `05_FULLTEXT` or the two publish as separate framings.*

---

*Companion drafts: `00_RESEARCH_CONTEXT.md` (master), `05_FULLTEXT_working_document.md` (failure-first version), `07_APPENDIX` (citation review). This document is the skills-first reframing for evaluation against the original.*
