# R2: Falsification & Bias Audit

## Where the Authors Overclaimed, Motivated-Reasoned, or Cherry-Picked — and What Would Prove the Thesis Wrong

**Review date:** 2026-06-25
**Series:** CTO Operating Modes — independent adversarial review track (`R1`–`R4`)
**Predecessor:** `R1_ADVERSARY_strongest_counterevidence.md` (attacks the claims from outside; this file audits the authors' own reasoning from inside).
**Reviewer stance:** Independent. This file is deliberately uncharitable about *process*: not "is the conclusion true?" but "did the way this corpus was built bias it toward its conclusion, and would the authors have noticed if it were false?"

> **The two jobs of this file.**
> 1. **Bias audit** — name every place the corpus reasons *toward* its thesis rather than *at* the evidence: overclaim, motivated reasoning, cherry-picking, asymmetric scrutiny, and the subtler tell — *flagging a problem and then proceeding as if flagging fixed it.*
> 2. **Falsification protocol** — state, concretely, what observations would prove the thesis (or each pillar) wrong. A thesis with no stated falsifier is a worldview, not a finding. The corpus has one real falsifier (`GAP-CTO-TRANSITION`) and needs a full battery.
>
> Throughout, I treat each `RISK-` anchor as a hypothesis to be tested, not a credit to be banked. **The question for every flag is: did the mitigation actually change the argument, or did it let the argument continue unchanged with a disclaimer attached?**

---

## Part I — The Bias Audit

### Bias 1 — The corpus was collected to confirm, not to test (the original sin)

This is the meta-bias from which most others descend, and the corpus states it against itself in `07_APPENDIX` review-note #3:

> "the ~35 threads were gathered in a single session oriented around the taxonomy itself — the sample was not assembled to test the taxonomy, so it cannot validate it."

That sentence should appear at the top of every research file, because it conditions all of them. A corpus assembled by asking "what supports Builder/Multiplier/Strategist?" will find support for Builder/Multiplier/Strategist. The danger is not any single citation; it is that the **search itself was the hypothesis wearing a disguise.** Every "independent line of evidence" in `08_DRAFT` §2 (industry splits tracks; industry splits roles; the compendium shows the offload) was retrieved by someone who already believed the conclusion and stopped looking when they found it.

**The tell that the mitigation didn't take:** the corpus flags this for the *asymmetry claim specifically* (`RISK-ASYMMETRY`) and nowhere generalizes it. But confirmation-oriented collection doesn't only bias the "0 Strategist findings" stat — it biases the *selection of which mechanisms to chase.* Why did the corpus chase the competence trap, Dunning-Kruger, and curse-of-expertise (all of which support "expertise interferes with the next mode") and *not* chase, say, the literature on **skill transfer and far-transfer successes**, or on **founder learning curves**, or on **CTOs who deliberately hired around their gaps early**? The absence of any disconfirming-mechanism search is itself the bias. A genuinely tested thesis would have a file titled "evidence the modes are *not* incompatible" — and there isn't one. (`R4` should commission it.)

**Severity: high.** This is the bias a journal referee names first.

### Bias 2 — Asymmetric scrutiny: supporting sources get promoted; threatening sources get "reframed"

Watch what happens to evidence depending on which way it points.

- Evidence *for* the thesis that arrives on weak sources gets **upgraded and load-bearing**: the ~50% reversion stat (a single practitioner's "at least half the time" estimate) is promoted to a headline number, then retroactively buttressed with CEB/Gartner once it's already structural. The no-triple-mode finding (5 blog/podcast cases) is promoted to a corpus headline (`AX-NO-TRIPLE-MODE`).
- Evidence *against* the thesis gets **reframed into support**: the Mathias & Williams "physical vs. psychological disengagement" finding (which shows the offload is *survivable* — keep the meaning, drop the activity) is folded in as defusing the identity-threat objection, rather than being recognized as undercutting the "lethal boundary" framing (see `R1` Claim 4). The CMO's short tenure + weak cross-stage overlap (which threatens the CTO-uniqueness keystone) is logged as "a possible early second instance… worth a flag but not load-bearing" — i.e., quarantined so it can't disturb the keystone.

The pattern is consistent: **a finding's source-class scrutiny is inversely proportional to how much the finding helps the thesis.** A five-case anecdote becomes "survivor-proof"; a peer-reviewed nuance that complicates the story becomes a quarantined flag.

**The cleanest single example:** `16_RESEARCH` calls the no-triple-mode result "the kind survivorship bias *cannot* manufacture" — granting its favorite finding immunity from the exact bias the *same file* spends 60 lines teaching the reader to fear. That is asymmetric scrutiny in one document.

**Severity: high.**

### Bias 3 — "Win-either-way" reasoning (the unfalsifiable engine)

The corpus repeatedly structures its tests so that no outcome could disconfirm. Named instances:

- **The ScienceDirect "win-either-way test"** (`09_RESEARCH`): stated explicitly — "if it knocks a model out, the claim strengthens; if it confirms an existing model, we have a solution. The result does both — and that is the strongest possible outcome." A test designed so that *both* possible results confirm the thesis is not a test. The corpus presents this as a virtue.
- **The no-triple-mode interpretation machine** (`R1` Claim 3): stayed-and-spanned (near-impossible by definition) would refute; every actually-observed outcome (graceful exit, crisis replacement, promotion to CEO) confirms.
- **The three failure signatures** (`R1` Claim 4): failure-to-acquire, burnout, slippage jointly exhaust the outcome space; observing any one "confirms."
- **The asymmetry** (pre-correction): a Builder finding would confirm (Builder mode exists); *no* Builder finding confirms ("Builder mode is structurally invisible to researchers"). The corpus caught this one (`RISK-ASYMMETRY`) — which proves it *can* catch the pattern, and makes the un-caught instances above harder to excuse.

**The diagnostic question the corpus should apply everywhere and applies almost nowhere:** *"What would I expect to see if this were false, and have I looked for it?"* When the answer is "nothing would look different," the claim is not empirical.

**Severity: high — this is the through-line of `R1`'s NARROWS verdicts.**

### Bias 4 — Overclaim through vocabulary inflation

The corpus systematically uses a stronger word than its evidence licenses, then does its arguing in the gap between the word and the warrant.

| Inflated term | Where | What the evidence actually supports |
|---|---|---|
| "survivor-proof" | `16_`, `AX-NO-TRIPLE-MODE` | an absence in a 5-case anecdotal sample |
| "irrational / dominated demand" | `08_DRAFT` §3 | "hard, under-resourced, and under-supported" — see Bias 5 |
| "the keystone… the single most important result" | `09_RESEARCH` | one unmatched 4-row comparison table |
| "this is the rigor" (Mill's method) | `09_RESEARCH` | a comparison with no variables held constant (`R1` Claim 2) |
| "falsifiable consequence / it is testable" | `08_DRAFT` §4 | corroboration by a general org-growth model + unverified attrition data |
| "epistemological isolation" | `15_RESEARCH` | the real but ordinary observation that senior leaders get filtered feedback |

None of these is a lie; each is a *load the word can't carry.* The cumulative effect is a corpus that *reads* as more empirically established than it is — which is precisely the failure mode the citation appendix was built to catch on the *citation* axis but does not catch on the *rhetoric* axis.

**Severity: medium-high.** Mechanical to fix (downgrade the words), but pervasive.

### Bias 5 — "Irrational" is the motivated word, and it smuggles a value judgment

The corpus's central adjective is "irrational," and `08_DRAFT` open-question #3 *admits it isn't sure the word is earned* ("is contradiction-with-own-beliefs the strongest framing… still open"). That honesty is good; the resolution offered (`09_RESEARCH`: "a dominated move… no version is rational") is motivated reasoning.

A "dominated strategy" has a precise game-theoretic meaning: an option worse than another *available* option in every state. The corpus has not shown a dominating alternative exists *for the actual decision-makers.* `R1` Rival A shows the opposite: given that ~74% of startups die before mode-3 matters, hiring one cheap equity-aligned generalist and replacing at the boundary may be the *payoff-maximizing* policy, not a dominated one. If so, the composite is not irrational — it is a rational bet under uncertainty that *feels* tragic to the person holding the equity. "Irrational" imports the CTO's-eye-view value judgment ("this is unfair to me") into a system-level descriptive claim ("no rational actor would design this"). Those are different statements, and the corpus runs them together because the stronger word is rhetorically better.

**Severity: high — it's the thesis's titular claim.** The defensible word is "under-resourced," "structurally unsupported," or "individually costly," not "irrational."

### Bias 6 — Cherry-picked comparators (the keystone's asymmetry trick)

`R1` Claim 2 covered the substance; here is the *bias* mechanism. The keystone compares the CTO at its worst against the other C-roles at their most-stable, by:
- describing the other roles only at the *level* of skill ("manage money," "own the narrative") where they look stable, and never at the *object* of skill (books→capital markets; campaigns→brand) where they rotate;
- granting the CTO the *object*-level reading ("product→people→market") that produces rotation, while denying the comparators the same reading.

It is the same construct read two different ways depending on which role is in the dock. The corpus's own data (CMO tenure/overlap) contains the refutation and the corpus quarantines it. This is textbook cherry-picking: not fabricating evidence, but **applying a generous frame to the favored case and a stingy frame to the rivals.**

**Severity: high — it's load-bearing and self-refuted by the corpus's own pages.**

### Bias 7 — The motte-and-bailey on "legibility, not a cure"

The corpus has a retreat position it deploys when pressed: *"the contribution is legibility, not a cure"* (`15_RESEARCH`, `CTO_RESEARCH_MAP` §4). This is the **motte** — modest, defensible, nearly unattackable ("we just want to give people vocabulary"). But the **bailey** is everything else: "irrational composite," "dominated demand," "the investors who created the problem," "survivor-proof," a quantified compression ratio, a falsifiable prediction, a 2×2 that *predicts which CTOs fail* (`13_RESEARCH`). You cannot claim the strong, quantified, causal bailey throughout and then fall back to "we only offered vocabulary" when a referee presses.

**The test:** if the contribution is *really* just legibility, delete every causal and quantitative claim and see what's left. The corpus would not accept that deletion — which means the bailey is the actual thesis and "legibility" is the fortified fallback. An honest framing picks one: either the modest descriptive contribution (and drop "irrational/dominated/caused/survivor-proof") or the strong structural thesis (and defend it without retreating to "just vocabulary" when attacked).

**Severity: medium-high.** This is the rhetorical structure a sharp reviewer enjoys most.

### Bias 8 — Anchoring on the author's firsthand experience

Tells throughout the corpus indicate the thesis originated in a *specific lived experience* of the failure: `09_RESEARCH` calls slippage "the failure mode you observed firsthand." That origin is not disqualifying — much good theory starts in n=1 — but it introduces a specific bias: **the framework is shaped to explain observed failures and then generalized.** The slippage mode gets three paragraphs and a peer-reviewed mechanism; the *success* paths get a 2×2 cell and a "this is rare." The corpus is more interested in *why the boundary breaks people* than in *who crosses it and how often* — exactly the asymmetry you'd expect if the framework is reverse-engineering the structure that explains observed pain. The missing study (`GAP-CTO-TRANSITION`) is missing in a *direction*: it would tell you the base rate of success, the number least flattering to a failure-first framework.

**Disclosed origin (added 2026-06-25, by the author):** the study began from the author's personal knowledge of **four CTOs who could not make the transition** — and whose **organizations expected them to transition *or step down on their own.*** This is the originating observation. Stated precisely, it is a **failure-only, author-selected sample of n≈4 with observer involvement** — i.e., the live form of `RISK-SURVIVORSHIP`'s mirror (we see four who failed; we do not see the matched cases who faced the same boundary and crossed it). The honest reading:

- **What it legitimately did:** generate the hypothesis. n=4 firsthand cases are a fine *source of a question*. Disclosing them is what lets a reader check they aren't doing more than that.
- **What it must not do:** carry evidential weight. And — this is the mitigation that makes the disclosure safe — **it doesn't.** The load-bearing evidence is *independent of the four cases*: the n≈30,000 IC→EM reversion rate, the IC/management institutional split (verifiable without the framework), the peer-reviewed founder-offload mechanism, and the CRO/VP-Sales fact. None of these were derived from or selected to fit the four. The four motivated the search; the search found evidence that stands without them. *That separation is exactly the test for whether a firsthand-anchored thesis is honest, and the corpus passes it — but only because the separation is stated, not assumed.*
- **The detail that is research signal, not just bias:** "transition *or step down on their own*" is the cultural-expectation pattern `TODO` T2 proposes to study — the organizations put the burden on the *individual* to transform-or-self-eliminate, never examining whether the demand was coherent. That is `§3` misattribution observed in the wild. It is **not evidence** (n=4, selected), but it is the legitimate *originating observation* of T2's demand-side question.

**Severity: medium — now fully declared (origin + sample shape + the independence-of-load-bearing-evidence mitigation). The residual risk is the *shaping* effect on what got researched (failure-first emphasis), which `GAP-CTO-TRANSITION` and the success-case de-escalation (`AX-NO-TRIPLE-MODE`, demoted) partially correct.**

---

## Part II — Did the `RISK-` flags actually mitigate, or just alibi?

The corpus's defenders will point to its anchor system as evidence of rigor. I judged each load-bearing flag by one standard: **after the flag, did the argument change — or did it proceed unchanged with a disclaimer bolted on?**

| Flag | What it admits | Did the argument change? | Verdict |
|---|---|---|---|
| `RISK-ASYMMETRY` | "0 Strategist findings" = arguing from silence | **Yes** — the draft carries a do-not-reuse guard at the claim site (`08_DRAFT` §4) and the asymmetry is downgraded to a gap. | **Genuine mitigation.** The model the others should follow. |
| `RISK-SURVIVORSHIP` | success cases = presence-as-evidence | **Partially.** The 3-layer tagging is real scaffolding — but the headline finding (`AX-NO-TRIPLE-MODE`) is then called "survivor-proof," re-importing the bias the flag exists to block. The flag governs the *cases* and exempts the *finding drawn from them.* | **Alibi at the headline.** Mitigates the parts, not the conclusion. |
| `RISK-INVESTOR-CAUSAL` | causal narrative, not measured | **No (not in prose).** The hedge is registered, but `08_DRAFT` §3.3 still contains the un-hedged causal sentence ("institutionalized by the very party…"). A flag in the appendix does not unwrite the sentence in the body. | **Alibi until the prose is cut.** |
| `RISK-COMPRESSION-RATIO` | ratio treats CTO equity as zero | **Framing yes, substance no.** Restated as "4–6:1 band" — but the deeper category error (comparing a pre-scale job to a post-scale org chart, `R1` Claim 6) is untouched, and the equity-offset contradiction with `AX-EQUITY-PREMIUM` is unaddressed. | **Partial.** Fixed the stated risk, not the real one. |
| `RISK-TEE-DOMAIN` | TEE is an AI-systems paper, misapplied to humans | **Yes** — TEE demoted to analogy; load shifted to verified human-cognition sources (competence trap, Hinds, Gupta). | **Genuine mitigation.** Caught a real error and corrected the substance. |

**The pattern:** the corpus's flags are genuine when the fix is *cheap and local* (swap a citation, add a guard at one claim site) and become alibis when the fix would *cost the headline* (retract "survivor-proof," cut the causal investor sentence, abandon the compression multiple). The anchor system is excellent at catching citation-level errors and **structurally bad at catching thesis-level overclaim**, because the people maintaining it are the people who want the thesis to hold. A flag the author is motivated not to act on becomes a permission slip: "we disclosed it, so we can keep saying it."

**Net:** the `RISK-` system is real rigor on the citation axis and a partial alibi on the rhetoric axis. It should not be cited as evidence the thesis is unbiased; it is evidence the *citations* are careful.

---

## Part III — The Falsification Protocol

A thesis is only a finding if it can lose. The corpus names exactly one falsifier (`GAP-CTO-TRANSITION`). Here is the full battery it should commit to — stated so that a future study could actually return the disconfirming value.

### Falsifiers for the whole thesis

**F1 — The base-rate falsifier (the central one).**
*If* a systematic study of founding CTOs (defined cohort, e.g., all seed-funded technical co-founders in a vintage, tracked to Series C or death) found that a **substantial fraction successfully spanned Builder→Multiplier (or all three) as a continuous tenure** → the "structurally near-impossible / survivor-proof" framing falls, and the thesis reduces to "this transition is hard," which is unremarkable. *The corpus's whole edifice predicts this number is low. It has never been measured.* This is `GAP-CTO-TRANSITION` and it is the single observation that most threatens the thesis.

**F2 — The early-bifurcation falsifier.**
*If* startups that **split CTO/VP-Eng from seed (funding held constant)** showed *no better* technical-leadership survival or company outcomes than composite-CTO startups → the core claim that the composite is the problem (rather than, say, under-resourcing generally) weakens sharply. The corpus asserts bifurcation is "the cleanest structural solution" but has *zero* comparative outcome data (`12_RESEARCH` Solution 3: "No empirical research on outcomes of early bifurcation vs. single CTO"). Until this is run, "bifurcation would help" is faith.

**F3 — The matched-comparator falsifier (kills the keystone).**
*If* a like-for-like study (founding CFO vs. founding CTO vs. founding CMO, all at seed, tracked across the same stage transitions) found **comparable rotation-driven failure/replacement rates** → the scope-vs-kind keystone falls (the CTO is not categorically different, `R1` Claim 2). The corpus's own CMO data already gestures at this; a real study could confirm it.

**F4 — The documentation-artifact falsifier (Rival B).**
*If* CTO failure/replacement rates, measured *behaviorally* (tenure, replacement-at-boundary, post-CTO trajectory), were found **statistically indistinguishable from other C-suite roles once measurement legibility is controlled for** → the thesis is documenting a *visibility* difference, not a *severity* difference. The corpus must lean on behavioral outcomes (à la the sibling thread's discipline) and stop treating "CTO failure is hard to see" as evidence it is worse.

### Falsifiers per pillar

**F5 — Taxonomy (Claim 1).** *If* an independent rater, given CTO career histories and *blinded to the three-mode scheme*, could not reliably segment them into Builder/Multiplier/Strategist phases (low inter-rater agreement) → the modes are imposed, not discovered. A construct-validity study the corpus never ran.

**F6 — Transformation mechanism (Claim 4).** *If* successful CTO transitions were found to proceed **without** the offload-and-acquire structure (e.g., CTOs who kept building *and* led effectively, never offloading) at meaningful rates → the model is not describing the mechanism, just one path.

**F7 — Boundary clustering (Claim 5).** *If* CTO difficulty were found to cluster at moments **decoupled from funding-round stress** as strongly as at the rounds → boundary-clustering is about skill rotation. *If it only clusters at funding rounds* → it's the financial inflection, not the modes (the confound wins). This is a *designable* study and would discriminate the two hypotheses `R1` Claim 5 says are currently conflated.

**F8 — Curse of expertise → CTO failure (the domain axis, `13`/`14`).** The curse-of-expertise *mechanism* is verified in physicians and lab studies. *If* domain-expert CTOs in general-tech companies did **not** fail/underperform at higher rates than generalist CTOs → the elegant cross-domain-interference story (`13_RESEARCH`'s entire bottom-left cell) is a mechanism in search of an effect. The corpus has the mechanism peer-reviewed and the *CTO-level effect entirely unmeasured.*

### The honesty test the corpus should adopt

For every load-bearing claim, the draft should carry a one-line **"this is wrong if:"** clause at the claim site (not in an appendix). The corpus already proved it can do this — the `XR-ASYMMETRY-DRAFT` guard in `08_DRAFT` §4 is exactly that move. Generalize it. A claim that cannot complete the sentence "this is wrong if I observe ___" is not ready to publish as a finding; it publishes as a *framework* (which needs no falsifier, but also may not claim to be measured).

---

## Part IV — What the bias audit does *not* find

Adversarial honesty cuts both ways. The corpus is **not** guilty of:

- **Fabrication.** When citations failed verification (the 2.5yr tenure, the TEE domain-mismatch, the McKinsey/Bain misattribution, the inverted micromanagement stats, the CMO "decade-low"), the corpus *caught them itself* and corrected in-source. That is real intellectual honesty and rare. The citation appendix is a genuine asset.
- **Hiding its weak sources.** The content-site dependence is labeled content-site dependence. The anecdotal cases are labeled anecdotal. Nothing is dressed above its class on the *citation* axis (the rhetoric axis is the problem, Part I).
- **Ignoring the survivorship trap wholesale.** It built an elaborate, genuinely good 3-layer model for it (`16_RESEARCH`). The failure is local (exempting the headline), not categorical.
- **Refusing to kill its darlings.** It declined to ship the self-diagnostic quiz (`EVALUATIONS/16`) on ethical grounds *against its own interest* — a costly, credibility-earning move.

The corpus's problem is not dishonesty. It is **motivated framing by people who are careful about citations and careless about the gap between "consistent with" and "demonstrated"** — and who built a flagging system that polices the first axis far better than the second.

---

## Summary: the bias audit in one table

| # | Bias | Severity | Cheapest honest fix |
|---|---|---|---|
| 1 | Confirmation-oriented collection (no disconfirming search) | High | ✅ **ADDRESSED (2026-06-25):** the disconfirming file is written — `18_RESEARCH_modes_not_incompatible.md`. It found the modes are *distinct but can coexist* (engineer/manager pendulum, positive transfer), retired "incompatible" corpus-wide, and *strengthened* the "under-resourced" framing. |
| 2 | Asymmetric scrutiny (promote allies, reframe threats) | High | Apply the 5-case sample's own skepticism to the finding drawn from it |
| 3 | Win-either-way / unfalsifiable tests | High | Add the F1–F8 falsifiers at claim sites |
| 4 | Vocabulary inflation ("survivor-proof," "falsifiable") | Med-High | Downgrade the words to what the evidence licenses |
| 5 | "Irrational" smuggles a value judgment | High | Replace with "under-resourced / structurally unsupported" |
| 6 | Cherry-picked comparators (keystone asymmetry) | High | Read CFO/CMO at the *object* level too; un-quarantine the CMO data |
| 7 | Motte-and-bailey ("legibility, not a cure") | Med-High | Pick one: modest-descriptive OR strong-structural, not both-on-demand |
| 8 | Founder-experience anchoring (failure-first shaping) | Medium | Resource the base-rate (success) study, not just the failure mechanism |

**The single highest-leverage honesty repair:** state F1 (the base-rate falsifier) as the thesis's central open bet, in the draft body, in the authors' own voice — *"if a systematic cohort study finds founding CTOs span the modes at a meaningful rate, this thesis is wrong, and that study has not been done."* A thesis that names the number that would kill it, and admits the number is unmeasured, converts from advocacy into a genuine, honest, falsifiable claim. That sentence is worth more to the corpus's credibility than any of the supporting citations.

---

*Companion: `R1_ADVERSARY_strongest_counterevidence.md` (the external attack this audits from inside), `R3_STEELMAN_strongest_form.md` (the version that survives both), `R4_OPEN_RESEARCH_agenda.md` (the F1–F8 falsifiers as a forward research program).*
*Independent adversarial review, 2026-06-25.*
