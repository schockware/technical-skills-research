# Audience Derivation Prompts — 5 Chats, One Per Actor (dev-ladder tier)

**Purpose:** Five separate chats, each producing an audience-specific version of the public draft from the *same* rigorous spine. Hand one prompt per chat. Each derived draft is a **projection** of `Software Developer/DRAFT_SYNTHESIS.md` (softening downward, losslessly) — **not a new argument.**

This is the dev-ladder (career-ladder) sibling of `CTO/AUDIENCE_DERIVATION_PROMPTS.md`. Same machine, one altitude wider: the flagship's actors orbit *one role* (CTOs, founders, investors, recruiters, academics); this tier's actors orbit *the whole ladder* (the engineers on it, the EMs who just crossed the loud rung, the founders/CEOs who run the ladder, the academics who could test it, the recruiters who write its reqs). **There is no investor/board actor at this tier** — that demand-signal story is CTO-specific; the five below are the dev-ladder set.

**Hard rule for all five (state it in every chat):** the rigorous spine `DRAFT_SYNTHESIS.md` is the **single source of truth**. A derived draft may *re-weight, re-voice, and drop* — it may **never add a claim not in the spine, nor restore a claim the spine's §6 concessions or `R3`'s do-not-build-on table retired.** If a derived draft needs a claim the spine doesn't license, that's a finding to bring *back* to the spine (and through `R1`–`R3`), not to assert in the derivation.

**The four narrowings the spine was reconciled to — every derived draft inherits these and may not walk any of them back:**
1. **Not "rotation at every rung"** → one corroborated seam (IC→management) + a recurring pattern above it (Senior→Staff via Larson). The lower rungs are craft-deepening shading into rotation. *(`R1` Claim A.)*
2. **The reversion number proves boundary-difficulty, not software-distinctiveness** — it's a cross-industry rate; it does **not** "close the measurement-artifact null." Distinctiveness lives in the cushion comparison (§3), never in the number. *(`R1` Claim B.)*
3. **The Senior→Staff plateau is a hypothesis, not a measured population** — never "the purest case" or "larger than reversion." The measured harm is the visible reversion. *(`R1` Claim D.)*
4. **"distinct skill sets with no on-the-job runway," never "incompatible"; imposter syndrome is corroborating-not-load-bearing and *not* "accurate self-assessment"; the *credited* layer decays while the durable foundation compounds (no "prior expertise is a liability").** *(`R1` Claim H; corpus-wide retirement.)*

**Shared inputs (every chat reads these first):**
- `Software Developer/DRAFT_SYNTHESIS.md` — the spine (§0–§6) + the **Audience Map** (each actor's row is that draft's brief)
- `Software Developer/R3_STEELMAN_strongest_form.md` — the do-not-build-on table + the one-paragraph version (prefer `R3` wording for any externally-facing line)
- `Software Developer/08_RESEARCH_axes_integration.md` — the five axes (the causal mechanism, in their already-narrowed form)
- `../CTO/07_APPENDIX_citation_review.md` — verification log; keep the `AX-`/`RISK-` anchor discipline (`AX-REVERSION`, `AX-MW2018`, `AX-VL2023`, `AX-LARSON`, `AX-COMPETENCE`, `AX-CURSE`)

**Shared output spec:** `Software Developer/derived/DRAFT_SYNTHESIS_<actor>.md` (create the `derived/` folder). Commit when done. Keep the audience-map row for that actor at the top as the brief. Carry a one-line provenance stamp: `derived from DRAFT_SYNTHESIS.md @ c240d35` (update the hash if the spine moves before you run).

**Behavioral-vs-sentiment discipline (all five):** lead with the n≈30,000 reversion rate and Larson/ISBSG field data; let the 52.7% imposter and burnout figures *corroborate*, never carry. The ⬜-unverified figures (imposter %, knowledge half-lifes, Peter-Principle ABM, Intuit 82%) are illustrative — flag, don't lean.

---

## CHAT 1 — Engineers (the people on the ladder)

> You are writing an audience-specific version of a completed research paper, **for the people the paper is about: working software engineers — ICs at every level from Mid through Senior and Staff, and anyone staring at the manager jump.** It is a *projection* of an existing rigorous spine — you re-voice and re-weight it, you never add claims.
>
> **Read first:** `Software Developer/DRAFT_SYNTHESIS.md` (the spine — §0–§6 and the Audience Map; your row is "Engineers (IC)"), `Software Developer/R3_STEELMAN_strongest_form.md` (the do-not-build-on table).
>
> **The payload (what this audience needs):** the **non-pejorative reframe** — this tier's version of relief-from-misattribution. The single thing an engineer should walk away with: *"the next rung is a different job, not a deeper you — and 'not ready for the next level' is the structure talking, not a verdict on you."* Lead with §4 (misattribution) and §2's reversion reframe (*half revert even when trained — it's an identity switch, not a skills gap*); §1 supplies the "the object of the work rotates: code → team → org" framing. The §5 line for them: *it's not just ordinary growth — growth is getting deeper at your craft; this is being asked to do a different craft, with no runway.*
>
> **Register:** plain, direct, second-person where it helps. Vivid but not motivational-poster. This is the version that gets *shared* in Slack and on Mastodon — it has to feel true to someone living it. The honest, specific note that lands here: the Senior→Staff plateau is real for *some* people, but you (the spine, §4a / `R1` Claim D) carry it as a possibility, **not** as "most plateaued Seniors failed" — many chose the craft, and that's a legitimate, good outcome now that IC tracks exist.
>
> **Drop / soften:** the falsifiers (§6b) — drop them; keep only the honest *tone* ("we're describing a pattern, not predicting your future"). The MW2018/VL2023-are-founders boundary (§2b) stays *true* but can be stated once, lightly.
>
> **Never:** tell them how to "win" the transition (no recipe — that's the survivor trap, `RISK-SURVIVORSHIP`; the success factors are mostly org conditions they don't control, per `07_RESEARCH`'s anti-recipe). The deliverable is *legibility and relief from misattribution*, not a playbook. Don't tell them to revert, or not to — reversion isn't failure (the pendulum is healthy), it's just counted as one.
>
> **Length:** tight — 800–1500 words. An engineer reads this on a Sunday and feels *seen and re-oriented*, not lectured.
>
> Output to `Software Developer/derived/DRAFT_SYNTHESIS_engineers.md`.

---

## CHAT 2 — Engineering Managers

> You are writing an audience-specific version of a completed research paper, **for engineering managers and managers-of-managers — the people who already crossed the loud rotation and now shepherd reports across it.** It is a *projection* of an existing rigorous spine — re-voice and re-weight, never add claims.
>
> **Read first:** `Software Developer/DRAFT_SYNTHESIS.md` (spine + Audience Map; your row is "Engineering managers"), `Software Developer/R3_STEELMAN_strongest_form.md`, `Software Developer/07_RESEARCH_success_exceptions.md` (the org-conditions / anti-recipe finding — this is the EM's actionable core).
>
> **The payload:** *you crossed the loud rotation (IC→EM); Staff is the quiet one your reports are hitting unnamed — and your job is to provide the cushions before the boundary, not to coach the person through a structural gap.* Two moves land hard here: (1) §2c/`07_RESEARCH` — durable transitions cluster on **org conditions you can actually supply** (psychological safety in the receiving team, value-fit, active manager-of-managers investment, a real imprint target), not on the report trying harder; (2) §4 — "your reports' reversion risk is structural, not weakness," so stop writing "not ready" on people the structure under-resourced. Personal reframe to offer gently: *your own reversion risk back then was structural too.*
>
> **Register:** peer-to-peer, practical, low-ego. An EM wants "what do I *do* on Monday." Give them the diagnostic sentence ("we're asking this person to do a different job and we named no transition for it") and the concrete cushions it unlocks — without turning it into a management-listicle.
>
> **Drop / soften:** most falsifiers → keep **F3** (do the three cushions actually improve survival?) as *your experiment to run* — you're positioned to test it on your own team. Academic boundaries stay true, stated lightly.
>
> **Never:** hand them a "how to guarantee your report makes Staff" recipe (`RISK-SURVIVORSHIP` — the anti-recipe is the finding: the conditions are necessary-not-sufficient and partly outside anyone's control). And don't imply good management *eliminates* the ~50% — the rate holds even with support; the honest promise is "you can change the conditions and the *sentence*," not the throughput limit.
>
> **Length:** 1000–1800 words. Practical, slightly more structured than the engineer version.
>
> Output to `Software Developer/derived/DRAFT_SYNTHESIS_engineering_managers.md`.

---

## CHAT 3 — Founders / CEOs

> You are writing an audience-specific version of a completed research paper, **for founders and CEOs who run the career ladder their company offers — who promote, level, and sometimes lose their best engineers to it.** It is a *projection* of an existing rigorous spine — re-voice and re-weight, never add claims.
>
> **Read first:** `Software Developer/DRAFT_SYNTHESIS.md` (spine + Audience Map; your row is "Founders / CEOs"), `Software Developer/R3_STEELMAN_strongest_form.md`.
>
> **The payload:** *the ladder rotates your people at the load-bearing rung — name it, and resource the rotation before the rung, because serial replacement never converges (§4b).* The actor-level move: instead of "promote the best IC and hope," provide **one cushion early — the cheapest is honest labeling** ("this is a different job, here's the runway"), then a respected IC track so staying technical is a real outcome, then a scaffolded transition. §5's accidental-concession lands hard: *"we can't afford to scaffold every transition" already concedes the transition needs scaffolding — so plan for it instead of being surprised when half revert.* The revealed-preference line is *theirs*: you already differentiate the ladder the moment you can afford to (Staff/Principal tracks, the EM/Staff split) — that's you admitting the cushions are needed.
>
> **Register:** operator-to-operator, decision-oriented. A CEO wants "what do I *do* with this." Give the diagnostic sentence ("we demanded an identity rotation here and resourced no transition for it") and the concrete moves it unlocks. Keep it about retention and not-burning-your-best-people, not HR-process.
>
> **Drop / soften:** falsifiers → a light "here's where this could be wrong" footnote, not a section (lean on concessions **3, 5, 7** to keep it honest — other professions aren't idylls, the large-company correction is real, "every rung" is a pattern not a cliff). Academic boundaries stated lightly.
>
> **Never:** claim the ladder is "irrational" (§5 / `R3`: "under-cushioned," not "irrational") — to a CEO that reads as "your company is badly run"; the honest claim is "this is under-resourced and you can resource it." And don't imply they should stop promoting people or pre-emptively manage people out — that's the broken loop one level up.
>
> **Length:** 1000–1800 words. Practical, decision-framed.
>
> Output to `Software Developer/derived/DRAFT_SYNTHESIS_founders_ceos.md`.

---

## CHAT 4 — Academic / Researcher

> You are writing an audience-specific version of a completed research paper, **for an academic / researcher audience** — the people who could actually run the studies that would confirm or break the thesis. It is a *projection* of an existing rigorous spine. For this audience, the projection is *closest to the spine* — you may keep nearly all of it; your job is emphasis and research-agenda framing, not simplification.
>
> **Read first:** `Software Developer/DRAFT_SYNTHESIS.md` (spine + Audience Map; your row is "Academics / researchers"), `Software Developer/R3_STEELMAN_strongest_form.md`, `Software Developer/R4_OPEN_RESEARCH_agenda.md` (the open studies, answerable-vs-unstudiable split), `Software Developer/R2_FALSIFICATION_and_bias_audit.md` (the falsification protocol + bias audit).
>
> **The payload:** *the falsifiers are the deliverable.* §6b's F1/F2/F3/F5 are study designs — and **F5 (the construct-validity test: can blinded raters even segment careers into "deepening" vs "rotation" rungs?) is the one to run first**, because it's cheap and if the construct fails there the expensive cohort studies (F1/F2) measure an artifact. Lead with what is *established* vs. what is *framework*: established = the IC/management institutional track split (§1, needs no framework) and the n≈30,000 behavioral reversion anchor (§2, read as **boundary-difficulty, not distinctiveness** — be scrupulous about this; the cross-industry rate is the corpus's own self-correction, `R1` Claim B); framework = "rotation at every rung" (one seam + a lens), the MW2018/VL2023 mechanism (peer-reviewed *in founders*, the engineer-severity is the extension, `R1` Claim C), and the plateau population (a structural *hypothesis*, unmeasured, `R1` Claim D). The honest framing: **strong component grounding, an open distinctiveness question, and a central unrun construct test** — present it as that, with the experiments specified.
>
> **Register:** rigorous, citation-precise, concedes openly. This audience *rewards* the concessions and falsifiers — foreground them, including the two new ones the review added (concession 8: the behavioral data does *not* close the measurement-artifact null; concession 9: the plateau is a hypothesis). State the borrowed-rigor provenance honestly: this area ran on the Software Industry R-track until it was promoted to its own (`R1`–`R4`), and the `[inherited]`/`[re-derived]`/`[never-reviewed]` tags are part of the audit trail.
>
> **Drop:** almost nothing. This is the version that keeps §6 in full and *expands* the research agenda (pull from `R4`). Drop only the practitioner-vivid framings that don't carry evidential weight.
>
> **Never:** overclaim the framework as a finding (the cardinal sin for this audience). Every "framework vs. finding" and "boundary-difficulty vs distinctiveness" line in the spine stays. Do not present the reversion number as closing the null — that retraction is the area's signature correction; reproducing the overclaim is a regression.
>
> **Length:** can run longer — 1800–3000 words. This is the citable version.
>
> Output to `Software Developer/derived/DRAFT_SYNTHESIS_academic.md`.

---

## CHAT 5 — Recruiters / Talent

> You are writing an audience-specific version of a completed research paper, **for the people who write and place the job descriptions: recruiters, talent teams, leveling-rubric and job-board taxonomy owners.** They are the actors who *operationalize* the rotation into the JD ("Senior Engineer — hands-on AND a technical leader who multiplies the team"). It is a *projection* of an existing rigorous spine — re-voice and re-weight, never add claims.
>
> **Read first:** `Software Developer/DRAFT_SYNTHESIS.md` (spine + Audience Map; your row is "Recruiters / talent"), `Software Developer/R3_STEELMAN_strongest_form.md`, `Software Developer/04_RESEARCH_senior_to_staff.md` (Larson's four archetypes — the operational distinction this audience can actually use).
>
> **The payload:** *the JD that demands "senior = does the work AND leads the org" writes the composite — and it's the first link in the misattribution loop.* The practical move: "hands-on AND strategic/multiplying" demands both sides of a rotation half the field can't cross once (§2's reversion at IC→EM; the Staff illegibility at Senior→Staff); writing the composite req selects for people who'll then be blamed for not being superhuman (§4). The Larson hook is *operational gold* for this audience: "Staff Engineer" is **four different jobs** (Tech Lead, Architect, Solver, Right Hand) — so a req that says "Staff Engineer" without specifying *which archetype the org needs* is unsearchable and sets up a mis-hire. The §5 line: the "rockstar full-stack lead who also sets direction" req is **a budget compromise dressed as a requirement.** §6 concession 7 reassures them: you're not being told to stop writing senior/Staff reqs — to stop writing the *undifferentiated composite* one.
>
> **Register:** practical, taxonomy-aware, concrete. This audience thinks in titles, levels, and search filters. Give them the *distinction* (which Larson archetype / which side of the rotation the req is actually for) as something operational — what to actually put in the req, and what to stop putting in.
>
> **Drop:** the falsifiers, most of the academic boundaries. Keep it short and usable.
>
> **Never:** turn it into a "how to source a unicorn engineer who can do it all" guide (the opposite of the message). The message is *stop specifying the unicorn; specify the archetype.* No recipe for finding someone who can cross every rung at once (`RISK-SURVIVORSHIP`). And don't claim the skills are "incompatible" — the req problem is *no runway and no archetype*, not that the skills can't coexist.
>
> **Length:** short — 600–1200 words. Closer to a practitioner brief than an essay.
>
> Output to `Software Developer/derived/DRAFT_SYNTHESIS_recruiters.md`.

---

## After all five

Each derived draft should be auditable against the spine the same way the increments were: a derived claim that isn't traceable to a spine section (or that restores a retired claim) is a defect. A quick post-pass: grep each derived draft for the do-not-build-on left-column phrases — **"rotation at every rung", "incompatible", "closes the null", "purest case", "larger than reversion", "accurate self-assessment", "prior expertise is a liability", "irrational"** — any hit that isn't a *denial* is a regression to fix. (This is the same discipline the spine's reconciliation already enforced on itself; the derived drafts must not re-introduce what the spine retracted.)

When done, the area mirrors the CTO layout: one rigorous spine + five audience projections under `derived/`, plus this prompt file as the derivation key. Consider adding a `Software Developer/AUDIENCE_DERIVATION_AUDIT.md` afterward (as the CTO area has) to record the consistency pass.

*Derived from `DRAFT_SYNTHESIS.md` (spine §0–§6 complete, reconciled to `R1`–`R3`). One actor per chat; consistency enforced by the shared spine + do-not-build-on discipline. Dev-ladder sibling of `../CTO/AUDIENCE_DERIVATION_PROMPTS.md`. Research conducted June 2026.*
