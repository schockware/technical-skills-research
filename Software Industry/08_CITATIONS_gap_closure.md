# 08: Citation Gap Closure
## Verified Primary Sources for the Gaps Flagged in the Review Track (`R1`–`R3`)

**Research date:** June 25, 2026
**Series:** Software Industry — Human Capacity Research Thread
**Purpose:** This file closes the `⬜` verification flags in `R1_ADVERSARY_strongest_counterevidence.md` and `R2_FALSIFICATION_and_bias_audit.md`. Every source here was verified to primary by web search against the actual publication. Status codes follow the CTO corpus convention from `../CTO/07_APPENDIX_citation_review.md`.

> **Note on file references:** the adversarial/steelman pass was renumbered into the `R1`–`R3` review track after this file's research was run. References below now read `R1` (adversary), `R2` (bias audit + falsification), `R3` (steelman), matching the current filenames.

**What this file does NOT do:** Rewrite the claims in the `MMM` series (`01`–`06`). It provides the citations the adversary and steelman files need; the edits to the substantive files are a separate pass.

---

## Gap 1 — DORA / *Accelerate* (flagged in `R1` Claim 1)

**Why it matters:** The adversary identified DORA as "the single most important omission" — if software had no stable craft, a replicated body of practice predicting performance across organizations could not exist. DORA is the evidence that the "no stable craft" claim is overstated.

### Primary citation

**Forsgren, N., Humble, J., & Kim, G. (2018).** *Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations.* IT Revolution Press. ISBN: 9781942788331.

- Founded on 4 years of research, 23,000+ respondents from 2,000+ organizations (start-ups to Fortune 500)
- Shingo Institute Publication Award
- Status: ✅ Verified. Named authors, named publisher, ISBN confirmed.
- Source class: Trade book presenting research findings. NOT peer-reviewed as a book.

### Peer-reviewed support

**Forsgren, N., Chiarini Tremblay, M., Vandermeer, D., & Humble, J. (2017).** "DORA Platform: DevOps Assessment and Benchmarking." *Proceedings of DESRIST 2017*, Karlsruhe, Germany.
- Status: ✅ Verified peer-reviewed conference paper.

**Wiedemann, A., Forsgren, N., Wiesche, M., Gewald, H., & Krcmar, H. (2019).** "The DevOps Phenomenon." *ACM Queue*, 17(2), 40.
- Status: ✅ Verified peer-reviewed journal article.

### Program scope and replication

- DORA State of DevOps annual reports: 2014–2025 (11 continuous years). 2024 report: 39,000+ professionals, global, multi-industry. Publicly accessible at dora.dev.
- Core finding: deployment frequency, lead time for changes, MTTR, and change failure rate are stable predictors of organizational performance. "Speed and stability are not tradeoffs." Top performers excel across all metrics simultaneously.
- Identified practices (trunk-based development, continuous delivery, automated testing) show consistent correlation with performance across diverse organizations.

### Limitations to state when citing

- Raw dataset not publicly released; independent peer replication is incomplete.
- Self-reported survey metrics; potential respondent bias flagged by independent analysts (Spears, 2024).
- Practices require organizational adaptation; DORA itself warns against decontextualized application.
- Causation vs. correlation not fully resolved.

### What this establishes for the thread

DORA does NOT refute the thread's thesis. It refutes the *overstated* version of file 04 ("no stable craft"). The narrowed claim — "the credited, fashionable layer is unstable; the durable foundation exists but is uncredited by evaluation systems" — survives DORA intact. DORA's identified practices (trunk-based development, CI/CD) are **delivery engineering practices**, not the framework/methodology fashion layer (React vs. Vue, microservices vs. monolith, Scrum vs. Shape Up) that the half-life data measures. The two layers are different. The thread can cite DORA as evidence of the durable layer's existence while maintaining that the volatile layer is what promotion and review systems actually credit.

**How to deploy in text:** "That some software practices are stable and transferable is demonstrated by the DORA research program (Forsgren, Humble, & Kim, 2018; State of DevOps annual reports 2014–2025), which has consistently identified delivery engineering practices predictive of organizational performance across 11 years and tens of thousands of respondents. The durable substrate exists. The claim is not that nothing in software is stable — it is that the evaluation machinery (hiring criteria, performance review rubrics, promotion criteria) credits the volatile fashionable layer rather than the durable foundation."

---

## Gap 2 — SPACE Framework (flagged in `R1` Claim 2)

**Why it matters:** The thread slides from "performance is contextual" toward "performance is unmeasurable." SPACE is the field's own answer: naive single metrics fail, but multi-dimensional measurement is possible and necessary.

### Primary citation

**Forsgren, N., Storey, M.-A., Maddila, C., Zimmermann, T., Houck, B., & Butler, J. (2021).** "The SPACE of Developer Productivity." *Communications of the ACM*, 64(6), 46–53. DOI: 10.1145/3453928.

- Also published in *ACM Queue*, 19(1), 20–48 (February 2021).
- Status: ✅ Verified. Full citation confirmed to primary. Peer-reviewed.
- Source class: Peer-reviewed journal article (Communications of the ACM — flagship ACM publication).

### What SPACE actually claims

Five dimensions: Satisfaction and well-being, Performance, Activity, Communication and collaboration, Efficiency and flow.

Core argument: "No single metric can capture the full complexity of software development." Single metrics create perverse incentives and measure the wrong things. Recommendation: measure across at least three dimensions to avoid blind spots and gaming.

Critically: **SPACE does not claim productivity is unmeasurable. It claims naive single-metric approaches fail and that multi-dimensional measurement is both possible and necessary.**

### What this establishes for the thread

The steelman's discipline correction applies here: the thread must not slide from "performance is contextual" (true, per Nichols) to "performance is unmeasurable" (false, per SPACE). The clean statement: performance is real, large, and contextual — which refutes fungibility (you can't swap units freely and maintain output) without implying unmeasurability.

**How to deploy in text:** "The field's own response to naive productivity metrics is not to abandon measurement but to build better measurement (Forsgren et al., 2021 — the SPACE framework). What is refuted is the assumption that a single metric captures developer contribution. What is not refuted is that performance differences are real, measurable, and consequential."

---

## Gap 3 — Jørgensen & Moløkken-Østvold CHAOS Critique (flagged in `R1` Claim 4)

**Why it matters:** The thread cites CHAOS Report success rates (61%/11%/6%) as load-bearing evidence in three files, while separately criticizing Agile methods for lacking empirical support. The CHAOS critique exposes this inconsistency.

### Primary citation

**Jørgensen, M., & Moløkken-Østvold, K. (2006).** "How large are software cost overruns? A review of the 1994 CHAOS report." *Information and Software Technology*, 48(4), 297–301. DOI: 10.1016/j.infsof.2005.07.002.

- Status: ✅ Verified. Journal, volume, issue, pages, and DOI confirmed to primary.
- Source class: Peer-reviewed journal article.

**Supporting:** Eveleens, J.L., & Verhoef, C. (2010). "The Rise and Fall of the Chaos Report Figures." *IEEE Software*, 27(1), 30–36. DOI: 10.1109/MS.2009.154.
- Status: ✅ Verified. IEEE Xplore confirmed.

### Specific criticisms verified

1. **Opaque proprietary methodology:** "The Standish Group's methods are not fully disclosed, and the bits that are disclosed are apparently deeply flawed."
2. **Self-selected failure-biased sample:** Survey method "strongly biased towards failure projects" — confidential surveys asked executives to share failure stories.
3. **Idiosyncratic success definition:** "Insufficient definitions of successful and failed projects." CHAOS classifies useful, shipped, valuable software as "failed" if it exceeded time or budget.
4. **Non-reproducing figures:** Resulting figures are "misleading, one-sided and meaningless" — the 189% average cost overrun figure is "probably much too high."

### Required action for the thread

Demote CHAOS in all three files (01, 02, 13) from load-bearing to illustrative-only. Add footnote at each occurrence: *"The Standish CHAOS Report methodology has been substantially criticized in peer-reviewed literature (Jørgensen & Moløkken-Østvold, 2006; Eveleens & Verhoef, 2010) for opaque methods, self-selected samples, and idiosyncratic success definitions. Cited here as widely-known industry reference; see Rodriguez et al. (2012) for a cleaner large-n analysis."*

---

## Gap 4 — Team Size Data: ISBSG as CHAOS Replacement (flagged in `R1` Claim 4)

**The verification result is more complex than expected.** The "1,000+ projects / 3–5 optimal / 9+ degrades" claim conflates two separate studies. Both exist and are citable, but the specific number ranges come from different sources with different methodological statuses.

### What is verified

**Rodríguez, D., Sicilia, M.-A., García-Barriocanal, E., & Harrison, R. (2012).** "Empirical Findings on Team Size and Productivity in Software Development." *Journal of Systems and Software*, 85(3), 562–570. DOI: 10.1016/j.jss.2011.09.009.

- Dataset: 951 high-quality instances preprocessed from 4,105 ISBSG Release 10 projects (the full ISBSG R10 contains 11,000+ projects from 32 countries).
- Verified finding: **teams of 9 or more exhibit significantly lower productivity.**
- Status: ✅ Verified peer-reviewed. Named journal, DOI confirmed.
- Source class: Peer-reviewed journal article.
- **Important correction:** The study analyzed 951 instances, not "1,000+ projects." The "1,000+" figure in the thread was a slight overstatement of the preprocessing result.

**The "3–5 optimal, up to 7 comparable" specific numbers:**

**Putnam, D. (1997).** "Team Size Can Be the Key to a Successful Software Project." QSM (Quantitative Software Management). Available at qsm.com.

- Dataset: 491 completed software projects from QSM Database (medium-sized systems).
- Verified finding: "A 3-7 person team has the best performance (3-5 would be the best, but 5-7 people is a very close second)."
- Status: ✅ Verified finding. ⚠️ Source class: Industry analysis / practitioner article. NOT peer-reviewed.

### What this means for citation practice

The "9+ degrades" finding has peer-reviewed support (Rodríguez et al., 2012 via ISBSG). The "3–5 optimal" specific range comes from Putnam (1997), which is industry analysis. Both can be cited with appropriate source-class labeling.

**Also note:** A 2022 ICSE study (Gote et al., "Big Data = Big Insights? Operationalising Brooks' Law in a Massive GitHub Data Set," ICSE 2022) analyzing 201 GitHub projects and 30,000+ developers found that conclusions about team size vary significantly depending on how productivity is measured and data cleaned. This means any specific optimal-size claim should be stated with appropriate confidence calibration.

### ISBSG dataset credibility assessment

- 11,000+ projects, 32 countries, standardized collection, quality-rated.
- More transparent and credible than CHAOS (proprietary, opaque).
- Limitations: heterogeneity across organizations, missing data (Rodríguez filtered 77% of records to get high-quality subset), voluntary self-reporting.
- Peer-respected: multiple independent researchers have published analyses using it.
- **Verdict:** Cleaner than CHAOS, not bulletproof. Appropriate as a more credible alternative with acknowledged limitations.

---

## Gap 5 — Physician Burnout Rates (flagged in `R1` Claim 3 / `R2` Bias 5)

**Why it matters:** The thread's cross-industry comparison presents medicine as a craft-deepening idyll. The adversary flags that physician burnout may be comparable to or worse than software's figures, undermining the asymmetric comparison.

### Verified data

**AMA Physician Burnout Survey (2025):** 41.9% of physicians report at least one burnout symptom. n=19,000 physicians across 106 health systems. Down from 48.2% in 2023.

**Medscape Physician Burnout Report (2025):** 62% reporting burnout symptoms.

**Range by specialty:** 23.3% (infectious diseases) to 49.8% (emergency medicine).

- Status: ✅ Verified. Named organizations, publicly available reports.
- Source class: Named organization surveys (AMA, Medscape). Not peer-reviewed but named and large-n.

### The administrative burden finding

Physicians spend ~49.2% of workday on EHRs and administrative tasks vs. 27% on face-to-face patient care. 46% of physicians identified reducing administrative burden as the most effective burnout intervention. Administrative interactions associated with 44.8–51% burnout; patient interactions with 26.4–34.5%.

This is directly relevant to the thread: physician burnout is substantially driven by rotation away from craft (clinical work) toward administrative burden — the same structural dynamic the thread documents in software. Medicine has the rotation problem too. The physician who became Department Chair stopped practicing. The attending buried in EHR documentation is experiencing the same craft-abandonment the thread attributes to software.

**What is NOT found:** Specific data on burnout reversion rates for physicians who moved to administrative roles vs. those who remained clinical. This remains an open gap.

---

## Gap 6 — Imposter Syndrome Base Rates Across Fields (flagged in `R1` Claim 5)

**Why it matters:** The thread cites 52.7% imposter syndrome prevalence in software engineers and frames it as "an organizational diagnostic" caused by structural mismatch. The adversary correctly notes that imposter phenomenon is elevated across all high-achievement fields. If medicine and law show comparable or higher rates, the 52.7% figure cannot be cited as evidence of software-specific structural problems.

### Verified data

**Software engineers (52.7%):**
Guenes et al. (2024). "Impostor Phenomenon in Software Engineers." ICSE 2024. n=624 software engineers, 26 countries. Clance Impostor Phenomenon Scale. DOI: 10.1145/3639475.3640114.
- Status: ✅ Verified. Peer-reviewed conference paper.

**Healthcare providers (62%):**
Salari et al. (2025). "Global prevalence of imposter syndrome in health service providers: a systematic review and meta-analysis." *BMC Psychology*. Meta-analysis of 30 studies, n=11,483.
- 95% CI: 52.6–70.6%
- General surgery specialists: 66.6% significant-to-intense symptoms
- Lifetime prevalence across healthcare: ~70% at least once in career
- Status: ✅ Verified. Peer-reviewed meta-analysis.

**Legal profession:**
Multiple surveys and practitioner studies (Bradley & Heales, 2021 cited in legal MCLE materials).
- Junior lawyers: ~83%
- All lawyers: 50–74%
- Status: ⚠️ Medium confidence. Named studies but not all verified to primary peer-reviewed publication.

### The definitive finding

**Healthcare at 62% exceeds software at 52.7%. Law at 50–83% overlaps or exceeds software.** Software's 52.7% is not an outlier. It is consistent with base rates across high-achievement professional fields.

No research found that distinguishes imposter syndrome caused by career-structure mismatch specifically from imposter syndrome caused by achievement-pressure generally. The causal mechanism is not empirically established for any field.

### What this requires of the thread

The 52.7% figure cannot be cited as evidence that software's structural problems cause elevated imposter rates. The correct framing (from `R3_STEELMAN`):

**Retire:** "52.7% is an organizational diagnostic — evidence that practitioners are accurately perceiving a structural mismatch."

**Adopt:** "52.7% imposter syndrome prevalence in software engineers (Guenes et al., 2024) is consistent with base rates in comparable high-achievement fields — healthcare at 62% (Salari et al., 2025 meta-analysis), law at 50–83%. The figure does not prove software-specific structural causation. What it establishes is that the individual-pathology response (coaching, mindset work) is being applied at majority prevalence. The structural hypothesis — that the mismatch between what practitioners are trained for and what they are asked to do explains a material share of this burden — deserves testing at that scale, even if causation is not yet established."

---

## Summary: What Is Closed, What Remains Open

### Closed (citations now verified)

| Gap | Source | Status |
|---|---|---|
| DORA / *Accelerate* | Forsgren et al. (2018); DORA annual reports 2014–2025; Wiedemann et al. (2019) ACM Queue | ✅ |
| SPACE framework | Forsgren et al. (2021), *Comm. ACM* 64(6), DOI 10.1145/3453928 | ✅ |
| CHAOS critique | Jørgensen & Moløkken-Østvold (2006), *IST* 48(4), DOI 10.1016/j.infsof.2005.07.002 | ✅ |
| CHAOS critique (supporting) | Eveleens & Verhoef (2010), *IEEE Software* 27(1), DOI 10.1109/MS.2009.154 | ✅ |
| Team size / 9+ degrades | Rodríguez et al. (2012), *JSS* 85(3), DOI 10.1016/j.jss.2011.09.009 | ✅ peer-reviewed |
| Team size / 3–5 optimal | Putnam (1997), QSM — industry analysis, 491 projects | ✅ exists ⚠️ not peer-reviewed |
| Physician burnout | AMA 2025 (41.9%); Medscape 2025 (62%) | ✅ named org surveys |
| Imposter syndrome — software | Guenes et al. (2024), ICSE, DOI 10.1145/3639475.3640114 | ✅ |
| Imposter syndrome — healthcare | Salari et al. (2025), *BMC Psychology*, meta-analysis n=11,483, 62% | ✅ |
| Imposter syndrome — law | Bradley & Heales (2021); Gibson Dunn MCLE 2025 | ⚠️ medium confidence |

### Still open (cannot be closed by available literature)

| Gap | Reason |
|---|---|
| Staff Engineer promotion rates | Not published by companies; no industry survey found |
| Does IC dual-track reduce the ~50% reversion rate? | Would require internal HR data from Google/Meta; not public |
| Do Staff rubrics reduce the plateau rate? | Same — internal data, not public |
| Principal PM track adoption rate outside large tech | No industry survey found at this specificity |
| Physician burnout in administrative-role vs. clinical-role subgroups | Data found on causes but not on career-transition reversion rates |
| Falsification tests (split CTO/VP-Eng from seed, matched high-achievement non-rotation fields) | Natural experiments not yet run or published |

The falsification tests remain named-open as the steelman prescribes — they are what would disconfirm the thesis, and they are stated as such rather than waved away.

---

*Citations verified by web search against primary sources, June 25, 2026.*
*Framework developed in collaboration with Claude Sonnet 4.6 and Claude Opus 4.8 (Anthropic). Research conducted June 2026.*
