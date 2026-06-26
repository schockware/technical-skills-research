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

---

## 4.9 — The Gendered Reclassification of Programming (1950s–1960s)

**Argument being tested:** Programming was initially classified as clerical work performed predominantly by women. In the 1950s–1960s it was reclassified as engineering through three specific mechanisms: aptitude testing that selected for an existing male profile; a professionalization narrative requiring credentials women were excluded from; and the masculinization of hacker identity. This reclassification installed the fungibility assumption and the composite demand simultaneously, replacing a specialist female workforce with a generalist male template.

**Axes implicated:** 2 (institutional memory — the prior female specialist workforce was overwritten), 5 (internal brake — the professional community that emerged from reclassification celebrated the composite), 8 (credential as capability signal — the reclassification made "programmer" a general capability signal rather than a scoped specialist credential), 10 (measurement paradox — the aptitude tests' invalid predictive power was documented by the late 1960s and ignored).

**Status:** Complete first pass. Key sources retrieved. One significant counter-argument identified (Misa) that requires integration.

---

### Finding 1 — Ensmenger (2010), *The Computer Boys Take Over*

**Source:** MIT Press monograph. Class: monograph (named academic press). Secondary discussion: Digital Humanities Quarterly review (peer-reviewed), Martin Fowler / Thoughtworks blog (named practitioner/secondary).

**The reclassification argument.** Ensmenger traces programming's evolution from feminized clerical labor in the 1940s–1950s through its reinvention as a "black art" and then as rationalized academic computer science and "software engineering" in the 1960s. Central thesis: "Programming was not born male, but rather had to be made masculine." The 1968 NATO Software Engineering Conference is identified as the institutional pivot where programming was reoriented toward scientific and masculine engineering norms, erasing the prior feminized labor history.

**The aptitude testing mechanism.** By 1962, ~80% of businesses used some form of aptitude test for programmer hiring; ~50% used the IBM Programmer Aptitude Test (PAT) specifically. By 1967, the PAT was administered to more than 700,000 individuals annually — functioning as "the gateway into the programming occupation." The PAT was developed by J.L. Hughes and W.J. McNamara, introduced 1955. Three sections: number sequence completion, geometric/figure paired comparisons, arithmetic reasoning (~seventh-grade level). Firsthand accounts describe it as resembling "the math part of an IQ test."

**The Cannon-Perry profile — the key mechanism.** SDC (Systems Development Corporation) psychologists William M. Cannon and Dallas K. Perry used the Strong Vocational Interest Bank (SVIB) to develop a "vocational interest scale for programmers," published 1966. SDC's institutional weight: in 1956 it employed ~700 programmers (nearly three-fifths of all programmers worldwide) and had trained 7,000 more by the early 1960s. The SVIB profile produced resembled engineering and chemistry vocational profiles. The one distinctively divergent characteristic: "They don't like people." This profile was generated from a population already predominantly male.

**The self-fulfilling mechanism (directly quoted in secondary sources):** "The primary selection mechanism used by the industry selected for antisocial, mathematically inclined males, and therefore antisocial, mathematically inclined males were overrepresented in the programmer population; this in turn reinforced the popular perception that programmers ought to be male, antisocial and mathematically inclined." — Ensmenger, as cited by DHQ review and Thoughtworks blog.

**On test validity.** Ensmenger: the PAT "seems to have no proof that the scores actually correspond with real-world programming performance." Most employers never checked. The few that did could not establish a relationship. Evidence of test failure was available by the late 1960s. The industry continued using the test regardless. *This is Axis 10 in miniature: measurement existed, was ignored, practice continued.*

**The Cosmopolitan test.** Cosmopolitan ran an aptitude test for "computer girls" in the same era (Lois Mandel, "The Computer Girls," 1967). Ensmenger notes the questions were "slanted toward an antisocial, mathematically inclined male" — the inclusive publicity artifact was shaped by the same masculine profile it nominally invited women into.

**Source citations:**
- Ensmenger, N. (2010). *The Computer Boys Take Over*. MIT Press.
- DHQ review: https://dhq.digitalhumanities.org/vol/7/2/000160/000160.html (peer-reviewed)
- Making Programming Masculine chapter PDF: https://homes.luddy.indiana.edu/nensmeng/files/Ensmenger2010-MPM.pdf
- Thoughtworks blog: https://www.thoughtworks.com/insights/blog/born-it-how-image-software-developers-came-about (named practitioner/secondary)
- Martin Fowler blog: https://martinfowler.com/articles/born-for-it.html (named practitioner/secondary)

---

### Finding 2 — Light (1999), "When Computers Were Women"

**Source:** Technology and Culture, Vol. 40, No. 3, July 1999, pp. 455–483. Johns Hopkins University Press / Society for the History of Technology. Class: peer-reviewed.

**The ENIAC programmers.** Six women selected from ~200 human computers to program ENIAC: Kathleen McNulty (Antonelli), Jean Jennings (Bartik), Betty Snyder Holberton, Marlyn Wescoff (Meltzer), Frances Bilas (Spence), Ruth Lichterman (Teitelbaum). Their work involved: understanding ENIAC's physical architecture, devising input methods, controlling sequential operations, extracting results — without pre-existing manuals. Light describes this as fundamentally creative technical work requiring problem-solving, not data entry.

**How they were credited.** Not credited. The 1946 ENIAC press release excluded them. Secondary sources report they were "literally cut out of a picture used in the press and later advertisements, showing a man working on the computer in the foreground." Press coverage focused on male engineers Eckert, Mauchly, and Goldstine. Light's characterization: their work "setting up and debugging the ENIAC was intangible, and to all who observed the machine running full speed, invisible." *Axis 1 (tangibility) in a named historical instance.*

**Light's core argument.** Programming sat between scientific and clerical labor: it required advanced training but was categorized as clerical. The hierarchy structured around male "hardware" engineers and female "software" operators shaped both press attention and institutional credit. This classification "affected how their contributions were remembered, compensated, and valued institutionally."

**Scope limitation — important.** Light's article documents an exceptional wartime case, not the numerical composition of the broader postwar programming workforce. The Misa counter-argument (below) targets this distinction directly.

**Source citations:**
- Light, J.S. (1999). When computers were women. *Technology and Culture*, 40(3), 455–483.
- PDF: https://rybn.org/human_computers/articles/when_computers_were_women.pdf
- PDF (alt): https://cs.brown.edu/courses/cs1951i/lightWhenComputersWereWomen.pdf

---

### Finding 3 — Abbate (2012), *Recoding Gender*

**Source:** MIT Press monograph. Class: named academic press. Secondary reviews: LSE Review of Books (secondary).

**Central thesis.** "The same work—programming—was classified as clerical when performed by women but reclassified as engineering once men dominated the field." Women's declining representation resulted from deliberate institutional choices, not innate aptitude differences.

**Three reclassification mechanisms (consistent with Ensmenger, different archival base including British computing):**
1. Hiring tests biased toward certain personality profiles
2. Shifts in university recruitment and credentialing
3. Professionalization strategies repositioning programming as high-status technical work

**Abbate's counter-intuitive finding on aptitude tests.** Tests initially opened doors for women by bypassing credential requirements women were excluded from. "On both sides of the Atlantic, hiring practices that prioritized aptitude tests over formal degrees opened doors for women who remained largely excluded from higher education during the 1950s and 1960s." The exclusion came through the *personality profiling* layer (Cannon-Perry type assessments) added on top of aptitude testing — a subsequent step, not built into the PAT from 1955. This complicates a simple narrative: the PAT was not purely exclusionary at inception; it became exclusionary through the personality overlay.

**On what was lost.** Women-led firms (Elsie Shutt, Stephanie Shirley) "innovated in distributed work, flexible staffing, and project management" — practices the LSE reviewer describes as "counternarratives to conventional innovation theories." The masculinization excluded not just people but organizational practices.

**On labor shortage rhetoric.** "The labor shortage really referred to a specific, privileged category of workers—male programmers with traditional technical qualifications and no childcare obligations." The shortage was constructed, not empirical.

**Source citations:**
- Abbate, J. (2012). *Recoding Gender*. MIT Press.
- LSE Review: https://blogs.lse.ac.uk/lsereviewofbooks/2013/02/13/book-review-recoding-gender-by-janet-abbate/

---

### Finding 4 — The 1968 NATO Software Engineering Conference and Gender

**Source:** Secondary descriptions of proceedings (bazaarmodel.net, isthisit.nz, Wikipedia). Primary PDF inaccessible. Class: secondary.

**Attendees.** ~50 experts. Named male participants include Dijkstra, Hoare, Perlis, Naur, Wirth, Bauer (chairman), McIlroy, Gries, Randell. Women named in proceedings: Miss Doris Angemeyer, Miss Enid Austin, Miss Petra Dandler, Mrs. Dagmar Hanisch, Miss Erika Stief — performing typing and office duties. No women identified as technical participants, working group members, or speakers in any source reviewed.

**Acknowledgment of prior female workforce.** None. Available secondary descriptions contain no discussion of workforce composition, demographics, or gender. The conference framed itself against a "software crisis" without acknowledging the workforce that had previously built software. *This is Axis 2 in operation: the institutional memory of the prior specialist female workforce was not transmitted to the founding conference of "software engineering."*

**On the term "software engineering."** Chosen deliberately — "expressed a need rather than a reality" (proceedings, via bazaarmodel.net). Aspirational/provocative framing positioning programming as analogous to established engineering disciplines. This is the vocabulary reclassification: the word "engineering" imported scope and masculinity assumptions from civil and electrical engineering without importing the liability, credentialing, or specialization structures.

**Confidence note.** Full proceedings not readable via tools. Participant list not fully confirmed from primary sources. Secondary sources provide consistent picture but primary verification pending.

---

### Finding 5 — The IBM Programmer Aptitude Test (PAT)

**Source:** Alt.folklore.computers Usenet archive (firsthand accounts), Ensmenger-citing secondary sources. IBM documentation (Hughes & McNamara 1969 manual) not retrieved. Class: firsthand accounts (Usenet) + secondary.

**Structure and introduction.** Introduced 1955 by J.L. Hughes and W.J. McNamara. Three sections: number sequences, figure analogies, arithmetic word problems (~seventh-grade level). Resembled "the math part of an IQ test" (firsthand). Revised version documented 1969.

**Scale.** By 1962: ~80% of businesses used some aptitude test for programmer hiring; ~50% used the PAT. By 1967: 700,000 administrations annually.

**Documented invalidity.** No evidence PAT scores correlated with actual programming performance. Employers who investigated could not establish a relationship. Ensmenger: "There seems to be no proof that the scores in the IBM PAT actually correspond with real-world programming performance." Evidence of failure available by late 1960s; industry continued regardless. *Axis 10 in miniature.*

**Gender filter mechanism.** The PAT itself did not explicitly exclude women. The gender filter operated through: (a) cultural coding of the measured traits as masculine; (b) the Cannon-Perry SVIB personality overlay (published 1966) which normalized "don't like people" as the defining programmer characteristic, generated from an already-male population; (c) the institutional inertia that treated the combined profile as a natural description of programmer aptitude rather than a circular self-fulfilling measurement. No IBM documentation from 1955 explicitly correlates PAT design to male demographics — the gender exclusion was emergent, not designed.

---

### The Misa Counter-Argument — Integrated via Access Restriction Loop

**Source:** Thomas Misa, cited in "Computer programming was never a women's occupation at its inception" (Computing and Society Substack). Class: secondary citing named academic historian.

**The challenge.** Misa uses SHARE attendance archives (1950s programmer community) and Bureau of Labor Statistics data (tracking began 1970s) to argue: women were a small and *growing* minority in programming from the 1950s through the early 1980s, not a dominant workforce that was then displaced. On Misa's reading, the ENIAC case (Light) was exceptional rather than representative, and Ensmenger's framing of programming's origins as "feminized clerical labor" requires empirical qualification.

**The resolution — Misa's data is post-loop.** The Access Restriction Loop (documented in `common_vs_normal_definition_doc.md`, Hidden Labor Variant) explains why Misa's data is not a refutation of Ensmenger but a measurement artifact of the loop itself:

```
Women perform specialized programming work (ENIAC, Bletchley Park, 1940s–early 1950s) →
Work reclassified as clerical; credit flows to institution / male engineers →
IBM PAT introduced 1955; selects for already-male profile →
Cannon-Perry profile published 1966; normalizes "antisocial mathematical male" as programmer definition →
BLS begins tracking occupation in 1970s — after reclassification machinery has run for 15–20 years →
SHARE archives (mid-1950s onward) show women as growing minority →
"Women weren't dominant" becomes the historical baseline
```

Misa is counting heads after the restriction was already in place and calling that the starting condition. The BLS data and SHARE archives are *outputs* of the reclassification machinery, not independent baselines. The ENIAC six are the pre-loop data point — specialized work performed before the vocabulary and testing apparatus of "software engineering" existed to reclassify it.

**The consensus point.** Misa, Ensmenger, and Abbate all agree on the 1984 inflection: women's participation peaked around 38% of the computing workforce in the mid-1980s and then declined. The disagreement is about starting conditions — but the starting conditions are precisely what the loop erases from the record.

**What survives Misa.** The Cannon-Perry circular profiling. The NATO 1968 gender erasure. The credential reclassification mechanism. The documented test invalidity and continued use (Axis 10 instance). None of these depend on women having been numerically dominant. The argument doesn't require dominance — it requires that specialized work was performed, classified as clerical, and that the reclassification machinery installed the fungibility assumption in its place.

**The thread this connects to — title as compression artifact.** This is the same mechanism operating on "CTO" and "software developer" today. The title survives the reclassification; the actual work, skill set, and expectation don't travel with it. "Programmer" in 1955 dropped the scope of the ENIAC work. "Software engineer" in 1968 imported engineering's authority without its liability or specialization. "CTO" today signals "technical everything" without specifying what technical everything includes or excludes. In each case: the word is the compression artifact; the scope is what got dropped. The Access Restriction Loop is not just a historical finding about women in computing — it is the engine by which titles accumulate meaning they no longer carry and shed meaning they once had. The reclassification is the mechanism; the title is the residue.

**Framework reference:** `common_vs_normal_definition_doc.md` — Hidden Labor Variant of the Access Restriction Loop. The ENIAC six appear as a named example in that document (line 97–98). The 4.9 research confirms and extends that case with the institutional machinery (PAT, Cannon-Perry, NATO 1968) that ran the loop at field scale.

---

### Axis Implications

- **Axis 2:** The institutional memory of the prior specialist female workforce (ENIAC, Bletchley Park, Shutt, Shirley's organizational innovations) was not transmitted to the founding conference of "software engineering." The reclassification is a documented instance of Axis 2 operating at a field's founding moment — not gradual forgetting but institutional erasure at origin.
- **Axis 8:** "Programmer" became a capability signal (mathematical aptitude, antisocial profile) rather than a scope label. The Cannon-Perry profile defined what a programmer *is* without defining what a programmer *does* or *doesn't do*. The composite demand followed from this: if the credential signals general cognitive capability, the demand expands to fill what the organization needs from a generalist.
- **Axis 10:** The PAT's documented predictive invalidity was known by the late 1960s. The industry continued using it regardless. One of the earliest documented instances of Axis 10 in software — measurement existed, failure was known, practice was unchanged.
- **Axis 11:** The vocabulary shift from "computer operator" / "programmer" to "software engineer" imported the scope and authority assumptions of formally originated language (engineering) without importing the liability, credentialing, or specialization structures. A wild-originated field borrowed a formally-originated word and used it as a capability signal rather than a scope label.

---

### Source List

- Ensmenger, N. (2010). *The Computer Boys Take Over*. MIT Press.
- Light, J.S. (1999). When computers were women. *Technology and Culture*, 40(3), 455–483. DOI pending.
- Abbate, J. (2012). *Recoding Gender*. MIT Press.
- DHQ review of Ensmenger: https://dhq.digitalhumanities.org/vol/7/2/000160/000160.html
- Ensmenger chapter PDF: https://homes.luddy.indiana.edu/nensmeng/files/Ensmenger2010-MPM.pdf
- Light PDF: https://cs.brown.edu/courses/cs1951i/lightWhenComputersWereWomen.pdf
- LSE review of Abbate: https://blogs.lse.ac.uk/lsereviewofbooks/2013/02/13/book-review-recoding-gender-by-janet-abbate/
- Thoughtworks blog (Ensmenger secondary): https://www.thoughtworks.com/insights/blog/born-it-how-image-software-developers-came-about
- Martin Fowler blog: https://martinfowler.com/articles/born-for-it.html
- Computing and Society Substack (Misa counter): https://computingandsociety.substack.com/p/computer-programming-was-never-a
- Confluence NYU (secondary): https://confluence.gallatin.nyu.edu/sections/research/how-computing-became-masculine-in-the-cold-war
- JSTOR Daily (secondary): https://daily.jstor.org/how-computer-science-became-a-boys-club/
- History.com (secondary): https://www.history.com/articles/coding-used-to-be-a-womans-job-so-it-was-paid-less-and-undervalued
- Silicon Republic / Cosmopolitan 1967: https://www.siliconrepublic.com/people/women-in-technology-the-computer-girls-cosmopolitan
- NATO 1968 (bazaarmodel): https://bazaarmodel.net/Onderwerpen/Software-Crisis-Nato/
- NATO 1968 (isthisit.nz): https://isthisit.nz/posts/2022/1968-nato-software-engineering-conference/
- IBM PAT (Usenet): https://groups.google.com/g/alt.folklore.computers/c/BBgKR1KXbrM

---

*Research file opened June 25, 2026. Sections 3.2 (partial) and 3.10 (pending) are the first entries. Additional Track 3 sections will be added as research proceeds, in priority order from `00_RESEARCH_PRIORITY.md`.*
*Built on: `00_AXES_SUMMARY.md` (Axes 2 and 10); `00_RESEARCH_PLAN.md` sections 3.2 and 3.10; `00_RESEARCH_PRIORITY.md` priority flag for 3.10.*
