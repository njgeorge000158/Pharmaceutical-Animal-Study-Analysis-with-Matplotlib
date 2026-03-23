![pymaceuticals](https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/8ad2eb50-bc3b-48ce-97c3-0ccfc2d51c17)

----

# **Pharmaceutical Study Analysis: Evaluating Drug Efficacy in the Treatment of Squamous Cell Carcinoma**

----

## **Study Overview**

This analysis examines the effects of a placebo and nine drug treatment regimens on tumor development in mice over a 45-day period. The study population consisted of 248 mice diagnosed with squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. Based on preliminary results, four treatments emerged as the most promising candidates: Ceftamin, Infubinol, Ramicane, and Capomulin — the latter being the company's primary drug of interest. A central objective of this analysis is to evaluate Capomulin's performance relative to the other leading candidates.

---

<img width="3248" height="2319" alt="pymaceuticalsFigure42TumorVolumeLastbyDrugRegimenDistribution" src="https://github.com/user-attachments/assets/52d8bcee-134a-40df-82bc-6c12475e7aad" />

## **Efficacy of the Top Four Treatments**

A comparative review of the four leading regimens reveals meaningful differences in both tumor volume distributions and treatment consistency.

Ramicane stands apart with a symmetrical tumor volume distribution — the only candidate among the four to exhibit this property. All other regimens, including Capomulin, Ceftamin, and Infubinol, display distributions skewed toward lower tumor volumes, as evidenced by their mean values falling below their respective medians. Ramicane and Capomulin also share the narrowest distributions and lowest variances among the four, suggesting greater consistency and predictability in treatment outcomes. By contrast, Ceftamin exhibits the widest distribution — comparable in spread to the placebo — followed by Infubinol, indicating far less reliable efficacy.

Median tumor volumes reinforce this hierarchy. Ramicane and Capomulin achieve the lowest median tumor volumes, while Ceftamin and Infubinol share a notably higher median comparable to that of the placebo group — raising serious questions about whether either drug produces any meaningful therapeutic effect. Further supporting Capomulin's promise, mouse weight and tumor volume under this regimen exhibit a strong positive linear correlation of 0.842, suggesting that body weight may be a meaningful factor in treatment response and a useful variable for dosage optimization.

---

<img width="2792" height="2319" alt="pymaceuticalsFigure52LastGreatestTimepointDistribution" src="https://github.com/user-attachments/assets/1a1dd781-de69-4b99-b656-d87d66f5dd93" />

<img width="3266" height="2041" alt="pymaceuticalsFigure64DrugTreatmentRegimenbyDataPointsPerMouse" src="https://github.com/user-attachments/assets/7d15d70e-f25a-4558-a7dd-4f5f65960282" />

<img width="3393" height="2319" alt="pymaceuticalsFigure74MouseWeightDistributionsforEachTreatmentGroup" src="https://github.com/user-attachments/assets/1387558c-b256-41a0-94d4-80cc4b38365e" />

---

## **Data Quality and Integrity Concerns**

Closer examination of the dataset reveals significant anomalies that undermine the study's validity and call its findings into question.

The first irregularity involves Infubinol, whose tumor volume distribution contains a single low outlier traceable to one mouse that contributed only two of the expected ten data points. This isolated case prompted a broader audit of data completeness across all treatment groups, which uncovered a systemic problem. Ramicane and Capomulin have 22–29% more data points than most other regimens, with the disparity reaching 55% in the case of Propriva. The root cause is uneven data collection at the mouse level: while each trial enrolled approximately 25 mice, only Ramicane's and Capomulin's subjects predominantly contributed the full complement of ten data points. Mice in other treatment groups contributed substantially fewer, in some cases far fewer.

The numerical consequences of this imbalance are significant. Assuming a complete study of 25 mice per regimen at ten data points each, the expected total is 2,500 data points. The actual count is 1,880 — leaving the study 620 data points short, or 24.8% below its expected total. Compounding these concerns, the original study population was recorded as 249 mice, but one subject was found to have duplicate timepoints with implausibly divergent tumor volumes. That mouse was removed, reducing the population to 248 — but its presence raises further questions about the rigor of data collection and oversight.

Taken together, these irregularities present a troubling picture. Whether the result of administrative negligence or a deliberate effort to skew results in favor of certain treatments, the asymmetry in data collection systematically advantages Ramicane and Capomulin while disadvantaging the remaining regimens. No meaningful efficacy comparison can be made under these conditions.

---

<img width="5283" height="2484" alt="pymaceuticalsFigure732TumorVolumesvsMouseWeightsPlotswithHighCorrelation" src="https://github.com/user-attachments/assets/112a338d-7e61-45cf-ab2f-5cf32bba7630" />

<img width="6061" height="2895" alt="pymaceuticalsFigure822MouseGenderDistributionRegimensPieCharts" src="https://github.com/user-attachments/assets/0374d351-918d-4626-928e-de5bf50a2af3" />

---
## **Study Validity and Recommendations**

Based on the evidence, this study should be invalidated. The combination of asymmetrical data collection, suspicious inconsistencies, insufficient per-treatment sample sizes, and inadequate quality control renders its findings unreliable. Ostensibly, Ramicane appears to be the most effective treatment, with Capomulin a close second — but these conclusions cannot be accepted with confidence given the integrity issues identified. Ceftamin and Infubinol, meanwhile, show no discernible reduction in tumor volume beyond placebo levels, though even this conclusion is difficult to state definitively given the compromised data.

I recommend that the study be repeated under the following conditions:

- **Uniform data collection:** Each mouse must contribute an equal number of data points throughout the trial, ensuring symmetrical and comparable datasets across all treatment groups.
- **Larger sample sizes:** The number of mice per treatment group should be increased by at least one order of magnitude to provide statistically robust sample spaces.
- **Standardized subject weights:** Mice across all groups should be weight-matched at enrollment to eliminate body weight as a confounding variable and enable cleaner cross-group comparisons.
- **Real-time data oversight:** Clinical trial managers should review data immediately after collection at each timepoint, enabling the prompt identification and resolution of anomalies before they propagate through the dataset.

## **Future Analytical Opportunities**

Once a valid and well-controlled study is available, several promising analytical directions become possible. Cost-effectiveness analysis — evaluating each treatment's therapeutic impact per dollar spent — would allow management to make more informed investment decisions. Additionally, the strong correlation observed between mouse weight and tumor volume under Capomulin suggests that weight-adjusted dosage optimization may be a productive area of investigation, both for Capomulin and for any other SCC treatment moving forward. These analyses, grounded in reliable data, could meaningfully advance the company's drug development strategy.

----

## Copyright

Nicholas J. George © 2023. All Rights Reserved.
