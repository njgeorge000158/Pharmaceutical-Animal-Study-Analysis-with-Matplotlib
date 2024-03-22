![pymaceuticals](https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/8ad2eb50-bc3b-48ce-97c3-0ccfc2d51c17)

----

# Pymaceuticals Animal Study Analysis

----

Over the course of 45 days, this study analyzes the effects of a placebo and nine drug treatment regimens on the tumor development of 248 mice suffering from a commonly occurring form of skin cancer, squamous cell carcinoma (SCC).  From the initial results, the most promising treatments include Ceftamin, Infubinol, Ramicane, and this company’s drug of interest, Capomulin.  The study’s ultimate purpose is to compare the performance of Capomulin against the other drug candidates.

<img width="1108" alt="4_2_1_tumor_volume_by_drug_regimen" src="https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/c0c6add1-413c-4efc-88a4-6fb00e01fee7">

<img width="1105" alt="5_2_1_last_timepoint" src="https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/fa16ba57-61f4-4ccf-97cb-826a4aa84257">

<img width="1105" alt="6_4_1_drug_treatment_regimen_by_data_points_per_mouse" src="https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/b5839887-ce17-49dd-af77-0fdf672aa6f9">

A superficial review yields some interesting observations concerning the efficacy of the top four drugs.  Except for Ramicane with its symmetrical tumor volume distribution, all the treatment regimens have skewed distributions towards the low end indicated by a difference between the median and mean below.  Moreover, Ramicane and Capomulin have the narrowest distributions while Ceftamin’s is the widest, about as wide as the placebo’s, followed by Infubinol.  Generally, the narrower distributions with their lower variances infer consistency in outcomes.  On top of that, Ramicane and Capomulin have the lowest median tumor volumes; Ceftamin and Infubinol have the same median, which is noticeably higher and comparable to the placebo’s value.  What’s more, Capomulin’s mouse weight and tumor volume metrics have a very strong relationship evidenced by a 0.842 linear correlation.

<img width="1106" alt="7_4_1_mouse_weight_distributions_per_treatment" src="https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/da890977-662c-4780-bb14-420e630fe224">

<img width="1106" alt="7_3_11_tumor_volumes_vs_mouse_weights" src="https://github.com/njgeorge000158/Pharmaceutical-Animal-Study-Analysis-with-Matplotlib/assets/137228821/679724d1-bcf5-4e37-afed-261f0687b70f">

Unfortunately, upon closer examination, there are serious anomalies in data collection and quality control.  For instance, Infubinol’s distribution has a single low outlier: inexplicably, one of only two data points from a single mouse in a study where each mouse should have ten.  From this discovery, further investigation reveals that Ramicane and Capomulin have 22-29% more data points than the other treatment regimens except for Propriva where the deviation grows to 55%.  The origin of this discrepancy is data points per mouse: each candidate has about 25 mice for its trial, however, unlike the others who have fewer – in some cases, appreciably fewer – Ramicane’s and Capomulin’s mice overwhelmingly have the maximum number of data points, ten.  If we assume that each trial has 25 mice with ten data points, then the total should be 2,500 not 1,880: hence, the study is missing 620 data points or 24.8% of its expected total.  In addition, the original number of mice was 249, but one mouse had duplicate timepoints with incredulously different tumor volumes.

Is this situation a product of poor administration or a deliberate attempt to manipulate results in favor of certain unmerited treatments?  Ostensibly, Ramicane is the most promising drug with Capomulin a close second, and neither Ceftamin nor Infubinol have any discernable effect on decreasing tumor volume.  In truth, this study should be invalidated due to asymmetrical data collection, suspicious inconsistencies, and insufficient sample spaces.  Therefore, I recommend another study of these treatments where each mouse uniformly provides the same quantity of data points for analysis, the number of mice per trial increases, at least, by an order of magnitude, the weight of each mouse in the study is approximately the same, and clinical trial managers review data closely immediately after collection.  Once information based on a valid and accurate study is forthcoming and available to management, the company can then use drug cost to determine each treatment’s level of effectiveness per dollar spent and examine the impact of varying the dosage of Capomulin, or any other treatment for SCC, based on a subject’s weight.

----

## Copyright

Nicholas J. George © 2023. All Rights Reserved.
