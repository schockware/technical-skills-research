# Research File — Track 3: Axes in the Wild
## Cultural Expectations Area — T2 and T4

**Date started:** June 25, 2026
**Status:** In progress — sections added as evidence accumulates. Each section is independently complete or explicitly flagged as partial.
**Sequencing:** 3.2 and 3.10 run first per priority flag in `00_RESEARCH_PLAN.md` (Axis 2 / Axis 10 boundary is the highest-stakes single finding in the plan).
**Source hierarchy:** peer-reviewed > named institution > named practitioner > content site. Class flagged per citation.

---

## 3.2 — Axis 2 (Institutional Memory) in the Wild

**Axis 2 definition:** The institutional memory of an organization or field fails to keep pace with the growth rate of the domain's complexity. The field keeps discovering the same problems because knowledge of prior discoveries doesn't survive in actionable form.

**Status:** Partially complete. Case A (CHAOS Report) is well-evidenced. Case B (2008 financial crisis) has macro-level evidence (Reinhart & Rogoff) but the structured-finance-as-young-subspecialty angle requires a second pass. Case C (NASA) requires a second pass — rate limits prevented retrieval.

---

### Case A — The CHAOS Report (Standish Group, 1994–present)

**What the evidence says:**

The Standish Group's CHAOS Report (1994) surveyed 365 US companies and 8,380 software applications, producing the most-cited software project failure statistics in the management literature. The headline figures: 16.2% of projects delivered on time and on budget ("successful"), 52.7% were "challenged" (over budget, late, or missing features), and 31.1% were cancelled outright ("impaired/failed"). *Source: Standish Group (1994) — named institution.*

These figures were widely adopted in management literature, project management training, and software engineering curricula. They became the empirical spine of the "software projects fail" claim that Brooks had argued from case study in 1975.

**The methodology critique:**

The CHAOS figures attracted sustained methodological criticism. Two peer-reviewed critiques are the most substantive:

- **Eveleens, J.L. and Verhoef, C. (2010). "The Rise and Fall of the Chaos Report Figures." *IEEE Software*, Vol. 27, No. 1, pp. 30–36. DOI: 10.1109/MS.2009.154.** *Source class: peer-reviewed.* Four-point indictment of the methodology: (1) Standish's definitions are misleading because they measure only estimation accuracy of cost, time, and scope — not whether the project delivered value; (2) the measure is one-sided, producing unrealistic success rates; (3) the metrics pervert good estimation practice (hitting an early estimate is not the same as delivering well); (4) the figures are "meaningless for benchmarking" because they average numbers with unknown bias. Direct quote: "Standish's successful and challenged project results are indeed meaningless for benchmarking." The authors tested 12,187 forecasts from 1,741 real-world projects totaling over €1 billion and found IT forecasts carry political biases the CHAOS figures did not account for.

- **Glass, R.L. (2006). "The Standish Report: Does It Really Describe a Software Crisis?" *Communications of the ACM*, Vol. 49, No. 8. DOI: 10.1145/1145287.1145301.** *Source class: peer-reviewed.* Glass questions whether the CHAOS data supports the "software crisis" framing at all, arguing the definitions inflate the apparent failure rate.

**What this means for Axis 2:**

The CHAOS figures are simultaneously the most-cited evidence of software project failure and methodologically contested. This creates a specific Axis 2 pattern: the field absorbed the *conclusion* ("software projects fail at high rates") without interrogating the *measurement* — the same institutional memory failure the axes predict. The management literature cited CHAOS; it did not widely cite Eveleens & Verhoef's critique. The finding persisted in management vocabulary even after the measurement was challenged.

**What would contradict the Axis 2 reading here:**
- Evidence that Agile methodologies (post-2001) substantially reduced failure rates and that this change was driven by CHAOS data being absorbed and acted on — this would make CHAOS an Axis 2 success story, not a failure. *This sub-question requires a second pass.*

---

### Case B — The 2008 Financial Crisis as Institutional Memory Deficit

**What the evidence says:**

**Reinhart, C.M. and Rogoff, K.S. (2009). *This Time Is Different: Eight Centuries of Financial Folly*. Princeton University Press.** *Source class: book (peer-reviewed authors, academic press).*

Reinhart and Rogoff document financial crises across 66 countries and eight centuries, finding that crises follow "surprisingly consistent frequency, duration, and ferocity" — and that each generation's experts, investors, and policymakers believe the current situation is genuinely different from prior disasters.

Key passages (from publisher description and Carnegie Council lecture transcript, October 30, 2009):
- "Short memories make it all too easy for crises to recur."
- "The seductive 'this-time-is-different syndrome' — the prevalent belief that to us, here and now, old economic laws of motion no longer apply."
- Rogoff (spoken, Carnegie Council): "People forgot about the 1930s." On serial default: "Virtually every country, when they are going through the emerging-market stage, defaults periodically" — yet each instance is treated as a novel event.
- "A dangerous mix of hubris, euphoria and amnesia" drives the pattern.

The relevance to Axis 2: Reinhart & Rogoff provide the macro case that institutional memory of financial crisis does not survive across generations — the crisis pattern is ancient, well-documented, and repeatedly ignored. This is the civilizational-scale version of Axis 2, operating in finance rather than software.

**The LTCM → 2008 chain — documented institutional non-response:**

The LTCM case (1998) provides the specific Axis 2 / Axis 10 evidence for Case B. The findings were written up, circulated at the highest regulatory levels, and then actively legislated away. This is not a memory deficit — this is documented knowing-and-not-acting, which makes it Axis 10 territory as much as Axis 2.

**The documented chain:**

1. **LTCM near-collapse (1998):** LTCM held balance-sheet leverage exceeding 25-to-1 and $1.4 trillion in notional derivatives contracts on $4.8 billion in capital. Federal Reserve intervened because rapid liquidation would have caused "extreme price movements" and potentially halted market function. The systemic risk mechanism was fully visible and named. *Source: GAO/GGD-00-3, October 1999. Named institution.*

2. **The lessons were documented immediately and at the highest level:** The President's Working Group on Financial Markets (signatories: Treasury Secretary Rubin, Fed Chair Greenspan, SEC Chair Levitt, CFTC Chair Born) published *Hedge Funds, Leverage, and the Lessons of Long-Term Capital Management* (April 1999). Eight specific recommendations including enhanced disclosure, improved risk measurement, and stronger counterparty risk management. The report explicitly named the failure: "market discipline broke down" — creditors failed to enforce their own risk management standards. *Source: PWG Report, 1999. Named institution.*

3. **The lessons were then legislatively neutralized:** Congress passed a statutory moratorium on CFTC regulatory action in OTC derivatives in 1998 (immediately after LTCM). The Commodity Futures Modernization Act of 2000 removed all CFTC jurisdiction over OTC derivatives entirely. CFTC Chair Brooksley Born, who had warned about exactly this risk before LTCM and pushed for derivatives oversight after it, testified: "consideration of regulation probably came and went within a few days." *Source: Born interview, PBS Frontline "The Warning," 2009. Named practitioner. Born's account is corroborated by the statutory record.*

4. **The gap persisted with full regulatory awareness:** In May 2006 — two years before the crisis — Fed Chair Bernanke gave a speech acknowledging that post-LTCM challenges remained unresolved: "competition eroding initial margin requirements; complexity making exposure measurement difficult; insufficient stress-testing." His recommendation was still market discipline rather than direct regulation. *Source: Bernanke speech, Federal Reserve Bank of Atlanta conference, May 16, 2006. Named institution.*

5. **The GAO issued a warning weeks before the crisis:** GAO-08-200, *Hedge Funds: Regulators and Market Participants Are Taking Steps to Strengthen Market Discipline, but Continued Attention Is Needed*, was published January 24, 2008 and publicly released February 25, 2008 — weeks before Bear Stearns collapsed in March 2008. The title's "continued attention is needed" language documents the ongoing gap. *Source: GAO-08-200, 2008. Named institution.*

6. **Named retrospective confirmation:** Henry Kaufman (Lehman Brothers Director), quoted in PBS Frontline (2009): "The Long-Term Capital Management event was relatively quickly forgotten." Paul Lee (Columbia Law School, CLS Blue Sky Blog, 2018): "Some observers might suggest that in 1998 we let a good crisis go to waste by not enacting any reforms." *Source: named practitioners.*

**What this means for Axis 2 vs. Axis 10:**

The LTCM → 2008 chain is a mixed finding. The macro knowledge existed and was documented (Reinhart & Rogoff's eight centuries; the PWG report naming the exact mechanisms). The legislation actively removed the regulatory tools that could have acted on that knowledge. This is closer to Axis 10 (knowing-and-not-acting) than pure Axis 2 (memory deficit) — but with a specific political economy mechanism: the knowledge was suppressed by deliberate legislative action, not forgotten organically. The distinction matters for the framework: the financial crisis case may be less "the field forgot" and more "the field was prevented from remembering by the people who profited from the forgetting."

**The Axis 10 sharpening — this is not forgetting:**

A second research pass on the same LTCM material adds a crucial refinement. The LTCM case is not best described as institutional forgetting (Axis 2). The Brooksley Born record shows the mechanism more precisely:

- Born warned Congress about OTC derivatives systemic risk in 1997 — *before* LTCM.
- LTCM confirmed her warning exactly. She named it immediately: "I thought that LTCM was exactly what I had been worried about."
- Larry Summers reportedly told Born her proposed regulations would "cause the worst financial crisis since the end of World War II" — framing the *warning* as the threat, not the unregulated derivatives.
- Congress passed the CFMA (2000) removing all regulatory authority, despite the PWG's own report documenting the risk.
- Paul Lee (Columbia Law, 2018) names this directly: "In 1998 we let a good crisis go to waste by not enacting any reforms." The title of the Cambridge working paper on the same subject: *"Lessons Not Learnt."*

This is not Axis 2. The knowledge was present, named, and acted upon — negatively. The regulatory apparatus moved to *prevent* the institutional response the knowledge called for. This is Axis 10 with a political economy mechanism: the knowledge was actively suppressed by the people who profited from the condition it diagnosed.

Brooksley Born (2012, HuffPost): "We must learn from these experiences, and we don't seem to be doing it yet." Same pattern, still running, fourteen years after LTCM.

*Source: Jorion, P. (2000), "Risk Management Lessons from Long-Term Capital Management," European Financial Management, Vol. 6, No. 3, pp. 277–300. Peer-reviewed. PWG Report (1999). GAO/GGD-00-3 (1999). PBS Frontline "The Warning" (2009) — Born interview, named practitioner. CLS Blue Sky Blog, Lee (2018), law school commentary.*

**Adversarial note — what this does NOT yet establish:**
- The S&L crisis (1980s) as a predecessor data point — whether S&L lessons were available to structured finance practitioners is not yet confirmed.
- Whether the specific structured-finance practitioners (CDO desks, MBS originators) had access to and awareness of the LTCM lessons, or whether the knowledge gap was siloed — regulators knew, trading desks didn't. This distinction matters: if trading desks were genuinely unaware, that sub-population is Axis 2 even while regulators were operating in Axis 10.

*The S&L → LTCM → 2008 lineage requires one additional pass to confirm whether the earlier crisis's lessons were transmitted or lost at the practitioner level.*

---

### Case C — NASA Challenger (1986) and Columbia (2003)

**Status: Requires second pass.** Rate limits prevented retrieval during the first pass. The Rogers Commission (1986) and CAIB Report (2003) are the primary sources. Research questions:
- What was the specific mechanism by which the Challenger O-ring risk was known, documented, and ignored — what broke the institutional brake?
- Did the Columbia investigation find that Challenger's lessons had been institutionally absorbed or had degraded?
- Does CAIB explicitly name organizational memory failure as a causal factor?

---

## 3.10 — Axis 10 (Measurement Paradox) in the Wild

**Axis 10 definition:** The field *knows* about its failure patterns — has documented, cited, and canonized that knowledge — and proceeds as if it doesn't. Distinct from Axis 2: Axis 2 = knowledge was never retained; Axis 10 = knowledge was retained, cited, and ignored. The Axis 2 / Axis 10 boundary lives or dies on whether the citation trail is continuous.

**Status:** Requires a dedicated second pass. The 3.10 agent was rate-limited before returning content. The citation-trail question (Brooks → NATO → CHAOS → reversion literature — unbroken or broken?) is the highest-stakes single finding in the plan.

**What is already known from training and prior corpus work (not yet confirmed by primary source search):**

- The 1968 NATO Software Engineering Conference was explicitly convened to address a "software crisis" that participants named as ongoing. The conference proceedings should be the primary source for whether prior failure documentation was cited as the basis.
- Brooks (1975) cites specific IBM OS/360 failures from his direct experience — but whether he cites a *prior literature* of software failure documentation (pre-1975) is the open question.
- The CHAOS Report (1994) was positioned as new empirical data, not as a continuation of the NATO-conference tradition. Whether it cites Brooks as a predecessor is unconfirmed.

**The critical distinction this section must resolve:**

| Pattern | What it means | Axis it supports |
|---|---|---|
| Each generation cites the prior, knows the finding, proceeds anyway | Knowing-and-acting-against | Axis 10 (akrasia) |
| Each generation rediscovers independently, minimal citation of prior | Independent rediscovery | Axis 2 (memory deficit) |
| Mixed — some citation, some rediscovery, broken at specific points | Partial transmission | Requires axis refinement |

If the trail is broken — if CHAOS does not cite Brooks, or if the reversion literature does not cite CHAOS — the Axis 10 "civilizational akrasia" capstone weakens to Axis 2 operating across institutional generations. That is not a failure of the framework; it is a finding that requires updating the capstone language.

**Research completed June 26, 2026. Single-threaded pass on three nodes.**

### Finding: The citation trail is broken at every node — this is Axis 2, not Axis 10

The three documents that constitute the supposed "continuous tradition" — NATO 1968, Brooks 1975, CHAOS 1994 — do not form a citation chain. Each originated from the same empirical phenomenon (large-system software failures of the 1960s) through independent practitioner experience, not through documented scholarly transmission.

**Node 1 — NATO 1968 (Naur & Randell, eds.)**
The 1968 conference does not cite prior software failure literature. The term "software crisis" appears only once in the proceedings, in an editorial note: *"There was a considerable amount of debate on what some members chose to call the 'software crisis' or 'software gap.'"* The tentative phrasing confirms the term was being coined at Garmisch, not inherited. The conference was organized in response to problems the participants had experienced directly (OS/360, SABRE, Multics) — not in response to a prior published literature. No pre-1968 failure taxonomy or failure-rate literature is cited. *Source: Multiple secondary sources on the proceedings, including Randell's own retrospective account. Named practitioner.*

**Node 2 — Brooks, *The Mythical Man-Month* (1975)**
No secondary source confirms that Brooks cited the NATO 1968 or 1969 proceedings. His acknowledged intellectual sources are Harlan Mills (1971), Niklaus Wirth (1971), and Sackman et al. (1968) — all post-NATO, none of them the conference proceedings. The intellectual relationship between NATO 1968 and Brooks 1975 appears to be parallel convergence on the same empirical problems (OS/360-era failures), not a documented citation link. Brooks was managing OS/360 from 1961–1965 — before the NATO conference — so his experience predates and is independent of Garmisch. *Source: Secondary analyses of Brooks's sources, including the Potts 50th-anniversary retrospective. Secondary.*

**Node 3 — CHAOS Report (Standish Group, 1994)**
The CHAOS Report contains no bibliography or reference list. It cites no prior academic work. It does not cite Brooks or the NATO conferences. The only named prior work is a 1986 Alfred Spector paper on bridge-building as a software analogy — framing, not citation. The report positions itself as original empirical work addressing an industry-wide documentation gap: *"When a bridge falls down, it is investigated and a report is written on the cause of the failure. This is not so in the computer industry where failures are covered up, ignored, and/or rationalized."* This framing is not continuous with Brooks — it treats the problem as newly visible, not as a documented tradition being updated. *Source: Slideshare transcription of full report text; Eveleens & Verhoef (2010) note the report's methodological opacity. Secondary / peer-reviewed.*

---

### What this means for Axis 2 vs. Axis 10

**The Axis 10 (civilizational akrasia) capstone does not hold in its strong form.**

Each generation did not know about the prior generation's findings and proceed anyway. Each generation independently rediscovered the same empirical problem — large software projects fail at high rates, adding people makes them later, the composite demand exceeds capacity — through direct practitioner experience, without a continuous citation chain linking the discoveries.

This is **Axis 2 (institutional memory deficit) operating across institutional generations**, not Axis 10 (knowing-and-ignoring). The field didn't have the knowledge and suppress it. The field kept losing the knowledge entirely, then rediscovering it from scratch.

**What this does to the framework:**

- The Axis 2 / Axis 10 distinction holds — but the evidence places the software failure measurement tradition in Axis 2, not Axis 10.
- The Axis 10 case (knowing-and-ignoring) is better evidenced by the **financial crisis chain** (LTCM → CFMA 2000 → 2008) documented in 3.2 Case B, where the knowledge was explicitly named, legislated against, and the same crisis recurred.
- The "civilizational akrasia" framing for software should be revised: the software field's failure is **civilizational amnesia** — repeated independent rediscovery with no accumulated scar tissue — which is Axis 2 at the largest scale, not Axis 10.
- Axis 10 still applies within software for cases where the finding *is* known and cited (Brooks is widely cited in management education; Agile explicitly cites MMM; the CHAOS Report is cited in PM certification curricula) — but practice doesn't change. That is the intra-generational Axis 10 case. The cross-generational chain is Axis 2.

**The Semmelweis parallel (flagged in 4.7):** The same Axis 2 / Axis 10 boundary test applies. Semmelweis had the data. The medical establishment didn't cite it and continue — it rejected and forgot it. Germ theory arrived as an independent discovery, not as a continuation of his work. That is Axis 2. The post-germ-theory establishment citing Semmelweis retrospectively is not the same as transmitting his knowledge in real time.

---

**Synthesis instruction for future drafting:** Replace "civilizational akrasia" with "civilizational amnesia" when describing the cross-generational software failure pattern. Reserve "akrasia" for the intra-generational case (Brooks is cited in MBA curricula; practice doesn't change). The distinction is now evidenced, not asserted.

*Source discipline: NATO 1968 and Brooks 1975 findings are from secondary sources — primary PDFs were inaccessible. CHAOS 1994 finding (no bibliography) is from a Slideshare transcription of the full text. Confidence: high on the CHAOS finding; medium on the NATO and Brooks findings pending primary source access.*

---

## Pending Second Pass — Priority Order

1. **3.10 citation trail** — run as dedicated single-threaded search. Brooks citing prior failures; NATO conference citing prior failures; CHAOS citing Brooks; reversion literature citing CHAOS. Confirm or break the chain at each node.
2. **3.2 Case C (NASA)** — Rogers Commission + CAIB on organizational memory.
3. **3.2 Case B structured finance** — LTCM lessons available to 2007–2008 practitioners? S&L crisis crossing into structured finance context?
4. **3.2 Agile-as-response sub-question** — did CHAOS data drive Agile adoption in a way that would make Case A a partial Axis 2 success?

---

*Research file opened June 25, 2026. Sections 3.2 (partial) and 3.10 (pending) are the first entries. Additional Track 3 sections will be added as research proceeds, in priority order from `00_RESEARCH_PRIORITY.md`.*
*Built on: `00_AXES_SUMMARY.md` (Axes 2 and 10); `00_RESEARCH_PLAN.md` sections 3.2 and 3.10; `00_RESEARCH_PRIORITY.md` priority flag for 3.10.*
