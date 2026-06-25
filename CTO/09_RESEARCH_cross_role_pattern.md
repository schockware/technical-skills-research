# Research: The Cross-Role Pattern — Is the CTO Composite a General Failure Mode?

**Status:** First-pass research captured; analysis in progress
**Created:** 2026-06-24
**Purpose:** Test whether the skill-set transformation problem (`08_DRAFT`) is unique to the CTO or an instance of a general structural pattern across C-level founding roles.
**Sources:** `Prompt Evaluations/check-for-other-c-level-issues.txt` (skills comparison) and `check-the-etymology-of-other-c-levels.txt` (origin comparison) — both web-searched first passes.

---

## Why this matters to the thesis

The original draft (`08_DRAFT`) argues the CTO composite is *irrational*. A natural objection: "if it's so irrational, why does only the CTO have it?" The answer reframes — and strengthens — the claim:

> The transformation problem is **not unique to the CTO**. It appears in every founding C-level role where the skill set diverges across stages. What is unique to the CTO is that **every mitigation other roles enjoy is absent**. The CTO is not the only instance of the pattern — it is the *unmitigated* instance.

This converts "the CTO is special" (weak, special-pleading) into "the CTO is the worst case of a documented general pattern" (strong, and the comparison itself is the evidence). It also sharpens *how* it is irrational (open question #3): the irrationality is **structural and recurring**, and we can see exactly which structural supports, when removed, make it lethal.

---

## The keystone finding: scope mismatch vs. kind mismatch

*This is the etymological complement to the skills comparison below, and may be the single most important result in the corpus. It isolates the one variable that makes the CTO catastrophic rather than merely strained.*

### C-suite title origins (verified first pass — citations pending)

| Title | Coined | Created for | At what scale | Core skill across stages |
|---|---|---|---|---|
| **CEO** | ~1917 | Answering "who is in charge?" — leadership | Formalization of modern corp structure | Leadership — *same job, larger* |
| **CFO** | 1970s–80s | Financial strategist (response to 1970s SEC/FASB regulatory changes [FASB est. 1973], inflation, shareholder complexity) | Large corporations under earnings pressure | Financial stewardship — *same domain, higher stakes* |
| **CMO** | 1993 (Coca-Cola) | Marketing strategist | Large enterprise, marketing dept already beneath them | Market narrative — *same direction, more channels/budget* |
| **CTO** | late 1980s (GE, Allied-Signal, ALCOA) | Technology strategist | Hundreds of engineers already running beneath them | **Rotates: product → people → market** |

### The comparative-method argument (this is the rigor)

The finding has the structure of **Mill's method of difference** — hold everything constant except one variable and see what the outcome tracks.

**Shared condition (constant across ALL C-suite titles):**
> Every Chief Officer title was created *at scale, for the mature mode it currently occupies.* The CFO was created when companies needed a financial strategist — not a bookkeeper who had to become one. The CMO, when they needed a marketing strategist — not a brand designer who had to evolve. The CTO is *consistent* with this: created at GE/Allied-Signal for a Strategist function.
>
> Therefore: applying *any* C-suite title to a pre-scale startup is irrational. Every one of them imports an executive-scale job description into a pre-organizational context. **The anomaly is not the CTO title — it is applying any C-suite title to a pre-scale startup.** This is the shared condition; it does not discriminate between roles.

**The one variable that differs (the IC/management bifurcation):**
> ⚠️ **SUPERSEDED (2026-06-25) — see `R3_STEELMAN` must-not-claim table + `DRAFT_SYNTHESIS` §1.** The claim below ("only the CTO's focus rotates; CFO/CMO don't") is **retracted**: it is the "mismatch of *kind*, uniquely the CTO" overclaim that `R1` Claim 2 demolished. **Verified 2026-06-25:** the CRO genuinely rotates too — VP-Sales→CRO is "fundamentally different from a typical promotion," execution→revenue-system, and sales leaders *fail* the transition the same way CTOs do (`AX-CRO-SPLIT`). The defensible claim is **not** "only the CTO rotates" but "the CTO is the *most severe* case of a rotation the whole C-suite shares — uniquely sharpened by the formal IC/management split, which the others lack." The original (wrong) text is preserved below for the record:
>
> ~~For every other C-suite role, the core skill *does not rotate.* The CFO at seed does what the CFO at Series B does: manage money — scope expands, focus holds. The CMO owns the market narrative at every stage — channels scale, direction holds. **Only the CTO's focus rotates** — product → people → market — because the IC/management bifurcation exists in no other discipline.~~ *(The IC/management-bifurcation point survives; the "only the CTO rotates" claim does not.)*

**The conclusion (outcome tracks the variable, not the shared condition):**
> The C-suite title migration to startups was **universally irrational — but only *catastrophically* irrational for the CTO**, because the technical function is the only one where the job genuinely changes *direction* rather than merely *scaling*.
>
> **Every other executive title imported a mismatch of *scope*. The CTO imported a mismatch of *kind*.**

### Why this is the keystone

1. **It pre-empts the strongest objection to the whole thesis.** "If startup C-suite titles are all borrowed-at-scale, why single out the CTO?" Answer: every other role borrowed a *scope* mismatch (survivable — same skill, more of it); the CTO borrowed a *kind* mismatch (a different skill entirely, three times). The comparison *is* the proof, and it's clean because the shared condition controls for the obvious confound.

2. **It isolates the IC/management bifurcation as the true cause.** The skills comparison (below) showed the CTO has 0/5 mitigations. This etymological cut goes further: it identifies *which single structural fact* (the bifurcation) converts a universal scope-mismatch into a unique kind-mismatch. One variable, not five — much harder to argue with.

3. ⚠️ ⟦**RETIRED — see README callout + `R3` must-not-claim + `18_RESEARCH`.**⟧ ~~It sharpens "irrational" (open question #3) to a precise formal sense. Not "irrational = hard." Irrational = the industry imported a job description across a context boundary it doesn't survive, and for the CTO specifically across a skill-kind boundary the industry itself had already declared uncrossable (the two tracks). That is a dominated move: there is no version of "one person, pre-scale, spanning two formally-incompatible skill tracks sequentially" that is rational.~~ **This entire formal-irrationality / dominated-move / uncrossable-tracks construction is retired:** R1 showed the role design may be a *rational* budget bet (not dominated); `18_RESEARCH` shows the tracks are *not* incompatible/uncrossable (the pendulum crosses them routinely). The defensible residue: the two tracks are *distinct work the industry split into separate ladders*, and the founding CTO spans them *with no runway* — **under-resourced, not irrational.**

4. **Bonus signal — the CMO is starting to show it too.** The CMO has the shortest tenure among C-suite functional roles — **~4.2 years (Spencer Stuart, 2023), below the ~4.6-year functional-leader average.** (An earlier draft claimed "~40 months, lowest in a decade"; Spencer Stuart's actual figure is 4.2yr and *not* a decade low — corrected 2026-06-24, see `07_APPENDIX`.) Marketing has the weakest cross-stage skill overlap *after* engineering — a possible early second instance of kind-mismatch, worth a flag but not load-bearing.

### The single sentence for the thesis

> **The C-suite title migration to startups was universally irrational — but only catastrophically so for the CTO, because every other title imported a mismatch of *scope*, while the CTO imported a mismatch of *kind*.**

*This belongs in `08_DRAFT` — likely as the close of §3.1 (the etymology/inheritance section), where it converts "the title was inherited wrong" into "the title was inherited wrong in the one way that doesn't survive." It resolves the latent objection that §3.1 otherwise leaves open.*

### Citations to verify (route to `07_APPENDIX`)

| Claim | Attributed to | Status |
|---|---|---|
| CEO title ~1917, corporate-structure formalization | (unsourced in first pass) | ⬜ Verify date/origin |
| CFO crystallized 1970s–80s; ~~1979 accounting-rule trigger~~ → 1970s SEC/FASB changes (FASB est. 1973) | LinkedIn, Sage Journals | ⚠️ Corrected — "1979" softened to "1970s regulatory changes"; decade + mechanism hold |
| CMO introduced 1993 by Coca-Cola | AMA, Wikipedia | ⬜ Verify the Coca-Cola "first" claim |
| ~~CMO avg tenure 40 months (2020), lowest in decade~~ → **4.2yr (Spencer Stuart 2023), not a decade low** | Spencer Stuart 2023 | ✅ Corrected 2026-06-24 |
| CTO late-1980s GE/Allied-Signal/ALCOA origin | (already in corpus, `07_APPENDIX` #1, #2) | ⬜ Already flagged |

---

## The transformation fingerprint (scoring rubric)

From `08_DRAFT`, a role exhibits the composite-transformation problem if it has all three:

1. **Focus divergence** — the *object* of skill changes across stages (product → people → market), not just the level.
2. **Offload-and-acquire** — each transition requires fully transferring the old responsibilities (to people/systems) *while* acquiring a non-overlapping new skill set.
3. **Boundary-clustered failure** — the three failure signatures (failure-to-acquire / burnout / slippage) appear *at the transitions*, not within stages.

And then, separately, the **mitigation axes** — the supports that determine whether the problem is survivable:

- **M1 — Support infrastructure:** Does a coaching/playbook/literature ecosystem exist for this transition?
- **M2 — Title split:** Has the industry split the title to acknowledge the incompatibility (so one person isn't asked to span it)?
- **M3 — Skill transferability:** Do the Builder-stage skills transfer *into* the next stage, softening the offload-and-acquire tension?
- **M4 — Title points right:** Does the title name the durable differentiating skill, or a skill that stops mattering?
- **M5 — Visible failure:** Is failure measurable/fast (so it gets caught and attributed structurally), or diffuse/slow (so it gets blamed on the individual)?

---

## The causal mechanism: who installed the misnomer, and why

*Source: `Prompt Evaluations/check-for-CTO-title-misappropriation-as-investor-tactic.txt` (web-searched first pass). This is the companion to the keystone: the keystone explains why the inherited title doesn't survive (kind-mismatch); this explains the **active force that installed it** in the first place. The framework previously treated the dot-com migration as passive drift ("the title carried no instruction manual"). This finding shows the migration was not accidental — it was **signaling**, and it was demanded by the party whose job is to price execution risk.*

### The causal chain (each link separately evidenced)

1. **Enterprise CTOs were a known institutional signal.** GE, Allied-Signal, IBM had CTOs atop established technical organizations. The title carried institutional credibility.
2. **1990s VCs looked for institutional signals in startup teams** — C-suite completeness among them. Trained on institutional investment patterns, they read a filled C-suite as reduced risk.
3. **At pre-seed/seed there is little else to evaluate.** With no traction, investors bet "almost entirely on people" — the team slide is the deciding artifact (investors spend ~30% more time on the first few pages; the team slide is where). ~90% of early-stage investors signal a preference for a technical co-founder; the CTO title specifically communicates "technical execution risk is covered by a named senior executive."
4. **Startups filled the slot to satisfy the pattern.** The CTO title went onto the team slide not because the role existed organizationally, but because the pitch-deck slot required filling and the title *worked for fundraising*.
5. **The dot-com moment amplified signal over substance.** "Management by press release" / "blitzmarketing" — >80% of late-1990s internet IPOs were loss-making. Signaling mattered more than fundamentals; borrowed credibility substituted for earned.
6. **The expectation then bit at the next round.** The person given a Strategist title was doing a Builder (IC) job — and was subsequently measured against the title's implied Strategist expectations at the next funding round, with no support structure to get there.

### The brutal implication (the part that gives the thesis teeth)

> The CTO title was arguably **more about the pitch deck than about the organization** — a fundraising instrument first, an organizational-design decision second. A Builder doing an IC job was given a Strategist title to satisfy an investor pattern-recognition heuristic, then expected to *become the thing the title implied*, unsupported, over the company's growth.
>
> **The investors who required the signal helped create the structural problem they were trying to avoid.** By demanding a "CTO" rather than a "technical co-founder," they imported a title carrying incompatible expectations — and then evaluated the person against those expectations. *The irrational composite was institutionalized by the very party whose job is to evaluate execution risk.*

### Why this matters to the thesis

1. **It upgrades the cause from passive to active.** §3.1 currently says the misnomer persisted because it was inherited and unnamed. This adds: it was not merely inherited, it was *actively installed and re-installed every funding cycle* by an incentive (signaling) that has nothing to do with organizational coherence. The misnomer is *maintained*, not just *inherited*.

2. **It connects to the keystone cleanly.** Keystone: every C-suite title is a scale-mismatch when migrated pre-scale, but only the CTO is a *kind*-mismatch. This finding answers *why the migration happened at all* — investor signaling — and explains why it was never corrected: correcting it would mean removing a credibility signal investors rely on. The incentive to keep the misnomer is structural.

3. **It re-frames the investor-case section of the original document.** `05_FULLTEXT` §8.5 pitches the taxonomy as a *diligence tool for investors*. This finding adds a sharper edge: investors are not neutral diagnosticians of the problem — they are (historically) its **co-authors**. The diligence framing becomes "here is how to stop installing the failure you then penalize."

4. **It is falsifiable and bounded.** The claim is about *origin and maintenance incentive*, not that every CTO title today is fake. The honest scope: the title became a fundraising instrument; that origin shaped the expectations mismatch. Keep it there — don't overclaim that all CTO titles are investor theater.

### Caution flag (rigor)

This is a **causal-narrative** built from signaling evidence, not a measured causal study. Each link is independently plausible and sourced, but the *chain* is an inference. Before it enters the citable draft: (a) verify each link's source (all currently content/industry sites — Cobloom, WTT, Deckary, Seedscope, CFA Institute), and (b) frame in the paper as "the evidence is consistent with the title functioning as an investor signal," not "investors caused the failure." The strong version is a great *argument*; the defensible version is what gets published. See `07_APPENDIX`.

### Citations to verify (route to `07_APPENDIX`)

| Claim | Attributed to | Status |
|---|---|---|
| Investors ask "who is your technical leader?"; prefer experienced CTO on board | Cobloom | ⬜ Verify |
| ~90% of early-stage investors prefer a technical cofounder | WTT-solutions | ⬜ Verify — load-bearing for link 3 |
| Team slide is deciding factor at pre-seed/seed; ~30% more time on first pages | Deckary, Seedscope | ⬜ Verify |
| "Management by press release"/"blitzmarketing"; >80% of late-90s internet IPOs loss-making | CFA Institute | ⬜ Most credible source here — verify and cite directly |

---

## Role comparison

### Fingerprint match (does the pattern exist?)

| Role | 1. Focus divergence | 2. Offload-and-acquire | 3. Boundary failure | Pattern present? |
|---|---|---|---|---|
| **Founding CTO** | Product → People → Market | Yes — widest skill gap of any function | Yes | **Yes (sharpest)** |
| **Founding CEO** | Visionary doer → Org leader → Institutional CEO | Yes | Yes ("founder mode" vs "manager mode") | Yes |
| **Founding CRO / Head of Sales** | Closer → Process-builder → Revenue strategist | Yes — maps almost exactly | Yes | Yes |
| **Founding CPO** | Product intuition → Roadmap/alignment → Market positioning | Partial — skills overlap more | Yes, but softer | Yes (least violent) |

### Mitigation scorecard (why does the pattern hurt more or less?)

| Role | M1 Support | M2 Title split | M3 Transferability | M4 Title points right | M5 Visible failure | Net |
|---|---|---|---|---|---|---|
| **Founding CTO** | ❌ Almost none | ❌ Never split | ❌ Tech craft → people = widest gap | ❌ "Technology" centers the skill that stops differentiating | ❌ Diffuse, slow, blamed on individual | **Worst case — 0/5 mitigations** |
| **Founding CEO** | ✅ Huge (coaching industry, YC, First Round) | ➖ N/A (apex role) | ➖ Mixed | ✅ "Chief Executive" implies leadership from day one | ➖ Mixed | Well-buffered |
| **Founding CRO** | ➖ Some | ✅ **VP Sales (builder) → CRO (strategist)** | ➖ Mixed | ➖ Neutral | ✅ Revenue stalls = fast, measurable | Title-split mitigated |
| **Founding CPO** | ➖ Some | ➖ Ambiguous | ✅ Customer instinct transfers into coaching PMs | ➖ Neutral | ➖ Mixed | Skill-transfer mitigated |

---

## The three mitigations, stated as the argument

Each comparison role survives the same transformation problem because it has at least one mitigation the CTO lacks:

1. **CEO → support infrastructure (M1).** Same Builder→Multiplier→Strategist arc ("founder mode vs manager mode" is exactly this debate). But when the CEO struggles, there are 10,000 frameworks waiting. When the CTO struggles, there is almost nothing. The problem is identical; the scaffolding is not.

2. **CRO → title split (M2).** The sales rotation maps almost exactly (Closer → playbook-builder → revenue strategist). The industry *partially solved it by splitting the title*: VP of Sales carries the Builder/Multiplier load, CRO is the Strategist. The split happened because the composite was too obviously irrational to leave unnamed. **The CTO title never got that split** — which is the single cleanest piece of external evidence that the composite is recognized-as-irrational *everywhere the industry was willing to act on it*.

3. **CPO → skill transferability (M3).** The CPO's Builder skills (product intuition, customer discovery) transfer into the Multiplier role: *you can coach PMs using the same customer instincts that made you a great PM. You cannot coach engineers by writing better code yourself.* And PM was never split into IC/management tracks the way engineering was. The offload-and-acquire tension is real but lower-amplitude.

---

## Why the CTO is the sharpest case (the differentiator)

Three structural factors, none of which the mitigations above can reach:

1. **The IC/management bifurcation is unique to engineering.** No other function built *separate, formally-laddered career tracks* that make engineers choose between craft and management. Sales has no IC track. Marketing doesn't. PM is ambiguous. Only engineering said, structurally, "these skills diverge — choose." *Then we ask the CTO to hold both.* (This is the M3=❌ in its strongest form.) ⟦was "declared its two skill tracks incompatible"; the split proves *divergence requiring choice*, not incompatibility — `18_RESEARCH`⟧

2. **The title was inherited pointing the wrong direction (M4).** "CEO" implies leadership from day one. "CTO" implies *technology* — centering exactly the skill that stops being the differentiator after the Builder stage. (Analogy from the source: as if "CRO" had been borrowed from an enterprise "Chief Closing Officer" and applied to people who needed to build organizations.)

3. **The failure is invisible by design (M5).** When a sales leader stays in Closer mode too long, revenue stalls — measurable, visible, fast. When a CTO stays in Builder mode too long, team quality declines slowly, debt accumulates, top engineers leave quietly. The signal is diffuse and delayed — so it gets attributed to the *individual*, not the structure.

---

## What this does for the thesis

- **Strengthens, not dilutes, the CTO claim.** The CTO is not "an example" of the problem — it is the **worst case**: the one role where the pattern is present at full amplitude *and* all five mitigations are absent or inverted. That is precisely why it deserves a dedicated framework.
- **Answers open question #3 (`08_DRAFT`).** "How is it irrational?" gains a sharper, comparative answer: the irrationality is a *general structural failure mode* that the industry mitigates everywhere it can — and the CTO is the case where it mitigated nothing. The recurrence is the proof; the CTO is the proof-by-extremity.
- **Suggests a new section for the draft.** A "Section 6 — The CTO as worst case of a general pattern" that runs the mitigation scorecard. The CRO title-split is the strongest single exhibit and should be foregrounded.

---

## Citations to verify (route to `07_APPENDIX`)

These came from a web-search first pass and are currently attributed to content sites, not primary research. Before any of this enters the citable draft, verify:

| Claim | Attributed to | Status |
|---|---|---|
| Founder vs CEO skill-set distinction ("visionary/frugal" vs "scale-relevant") | "Saasceo" (content site) | ⬜ Verify / find primary |
| "VP of Sales is a builder, CRO is a strategist" | "Charliesolorzano" (blog) | ⬜ Verify — this is load-bearing for M2 |
| Hiring late-stage CRO before ready = common failure | "Talentfoot" (recruiting site) | ⬜ Verify |
| Founder role transitions — "giving up some roles, taking on others" | ScienceDirect | ⬜ Most credible source here — locate exact paper, likely usable as primary for the transformation model itself |

> **Note:** the ScienceDirect founder-role-transition finding may be citable support for the **core transformation model** in `08_DRAFT` §1 (offload-and-acquire), not just this comparison. Worth chasing down — it could upgrade the model from "observed" to "literature-grounded." **→ CHASED DOWN — see verdict below.**

---

## VERDICT: ScienceDirect source identified and assessed (2026-06-24)

**The paper:** Mathias, B.D. & Williams, D.W. (2018). "Giving up the hats? Entrepreneurs' role transitions and venture growth." *Journal of Business Venturing*, 33(3), 261–277. Elsevier. Peer-reviewed, inductive field study. *(This is a real, citable, peer-reviewed source — a tier above the content-site citations in the table above. Verify final page/issue against the journal before publishing.)*

**Full abstract (verified via RePEc):**
> "At the start of a venture, most entrepreneurs wear many hats. However, entrepreneurs often cannot remain involved in every aspect of the venture process, and so they face important decisions about which roles to give up, which roles to retain, and which new roles to adopt. For many, this process is particularly difficult as roles represent more than just something entrepreneurs do but also an important part of who they are (role identities)."

### The win-either-way test, resolved

We framed this as: *if it knocks a model out, the "CTO role is broken" claim strengthens; if it confirms an existing model, we have a potential solution.* **The result does both — and that is the strongest possible outcome.**

**1. It LITERATURE-GROUNDS the transformation model (confirms — gives a solution path).**
The paper's "give up / retain / adopt" structure is the offload-and-acquire model, independently arrived at in peer-reviewed entrepreneurship research. The transformation framing in `08_DRAFT` §1 is no longer just observed — it has academic grounding. The paper even names the mechanism the draft was missing a citation for. **This upgrades `08_DRAFT` §1 from "observed" to "literature-grounded."**

**2. It IDENTIFIES THE FAILURE MECHANISM as identity — the same identity-threat mechanism already in the corpus (confirms the failure side too).**
<!-- RISK: RISK-TEE-DOMAIN — TEE (Mars 2026) is an AI-systems paper; do NOT cite it as the human failure mechanism. Use competence trap + Dunning-Kruger + role-identity attachment (Mathias & Williams 2018) instead. See 07_APPENDIX #10. -->
The paper's central difficulty: roles are "an important part of who they are (role identities)" — giving them up is an identity loss, not just a task hand-off. This is *exactly* the identity-threat mechanism the original working document already cites for the Builder→Multiplier failure (`05_FULLTEXT` §10.2; classification table Cluster 5). Two independent literatures converge on identity as the thing that blocks the offload. **The "slippage / neglect" failure mode (the CTO who won't delegate) now has a named academic mechanism: role-identity attachment.** *(Note: earlier drafts attributed this failure to "Transitive Expert Error." TEE is a paper about AI systems, not human psychology — it has been demoted to at most a borrowed analogy; the load-bearing human mechanisms are the competence trap, cross-domain overconfidence, and role-identity attachment. See `07_APPENDIX` #10.)*

**3. It DOES NOT solve it for the CTO — which is where the "CTO is broken / worst case" claim survives intact and sharpens.**
The Mathias & Williams success mechanisms (perceiving oneself as someone who "gives up hats," discovering new role identities, role-identity imprinting) describe how *some founders* successfully narrow their role set. But three things make this a CTO-specific gap:
- The study is of **founders/entrepreneurs generally (the CEO-analog)** — the buffered case (M1). It does not study the CTO, where the IC/management bifurcation (M3=❌) makes the "adopt a new role identity" step a jump across a boundary the industry itself split into separate ladders. ⟦was "a track the industry declared incompatible"; softened — `18_RESEARCH`⟧
- The success mechanisms are **identity reframes**, not structural supports. They require the founder to *find new meaning* in the new role. The CTO's new role (Multiplier) asks them to stop doing the exact thing — technical craft — that the title still tells everyone is their identity (M4=❌). The title actively fights the identity reframe the solution depends on.
- The paper offers the mechanism but, per the abstract, **does not specify failure predictors or success-vs-failure contrasts** — the empirical gap the CTO framework is positioned to fill remains open.

### Net effect on the thesis

- **`08_DRAFT` §1** can now cite Mathias & Williams (2018) as peer-reviewed grounding for the offload-and-acquire (transformation) model. Highest-value upgrade from this search.
- **The "slippage" failure mode** (the won't-delegate CTO) is now double-anchored: role-identity attachment (Mathias & Williams 2018) + identity threat (already in corpus). This is the failure mode you observed firsthand — it now has theory under it.
- **The "potential solution"** is real but *conditional*: the founder literature says successful transition runs through **identity reframe** (finding new meaning in the new role). The CTO framework's contribution sharpens to: *the CTO is the role where the title itself blocks the identity reframe that the solution requires.* That is a more precise statement of "broken" than we had before.
- **The CEO buffering claim (M1) gets harder evidence:** the founder-transition literature exists and is studied — for the CEO-analog. Its near-absence for the CTO is the M1=❌ made concrete.

**Action:** add Mathias & Williams (2018) to `07_APPENDIX` as a verified, high-quality citation (the first peer-reviewed source for the transformation model itself). Flag the companion paper ("Preparing for scaling: A study on founder role evolution," S0883902623000290) and Mathias et al. "From founder to CEO: an entrepreneur's roadmap" as next reads — they may carry the success-predictor detail the 2018 abstract withholds.

---

## UPDATE (2026-06-24): both papers read in full — verified, and the picture upgraded

Both ScienceDirect papers were purchased and read in full. `AX-MW2018` and the new `AX-VL2023` are now ✅ verified (see `07_APPENDIX` for the detailed entries). Two things changed beyond simple verification:

**1. Mathias & Williams (2018) gave us more than the abstract did.**
- N = **45 entrepreneurs**, inductive field study. The give-up / retain / adopt model is verbatim (= offload-and-acquire).
- **Physical vs. psychological disengagement:** successful founders *physically* stop enacting a role identity but **keep the meaning** — they don't have to psychologically withdraw. This *answers the identity-threat objection* head-on: the ask is "stop doing it," not "stop caring about it."
- **"Role identity imprinting" is the named success mechanism:** founders offload by imprinting the role onto an employee (training them to value the work); seeing their "stamp" is what frees them to move on. The won't-delegate slippage mode ("no one can be me," "can't see employees as an extension of self") is its peer-reviewed failure path.

**2. The companion paper (Van Lancker et al., 2023 — note: 2023, not 2024) supplies the offload SUCCESS CONDITIONS.**
- Founders offload via "joiners" taking over roles. The offload sticks when two conditions hold: **psychological safety** (joiner feels safe to take the role — cites **Edmondson 1999**, the same construct already in our corpus via Project Aristotle) and **value fit** (founder trusts the joiner shares the venture's values). Low value fit → founder pulls the role back.
- This converges with MW2018's imprinting: **both peer-reviewed JBV studies say the offload succeeds when the founder trusts the receiver shares their values.**

**Net effect on the thesis — the win-either-way test resolves *constructively*:**
The framework now has a peer-reviewed answer to "what does a successful transformation require?" — not just identity reframe, but **a receiving team with psychological safety and value fit, into which the founder can imprint the role.** This connects the transformation model (§1) directly to the team-readiness gates already in the compendium (`02`/`06`) and to the solution taxonomy (`12` Solutions 3 & 5). And it sharpens the CTO-specific "broken" claim: the CTO must imprint Builder-mode craft onto a team — but the title tells everyone the craft *is* the CTO, working against the value-fit perception the offload depends on.

**Follow-on actions:**
- `08_DRAFT` §1: cite both papers; add the physical-vs-psychological disengagement point (defuses the identity-threat objection).
- New solutions section: the psych-safety + value-fit conditions are the *constructive* counterpart to the failure analysis.
- Still unread: Mathias et al. "From founder to CEO: an entrepreneur's roadmap" (Business Horizons) — lower priority now that the success conditions are sourced.

---

*Companion to `08_DRAFT_skills_divergence_thesis.md` (the framework this tests) and `07_APPENDIX` (citation review). Source research: `Prompt Evaluations/check-for-other-c-level-issues.txt`.*
