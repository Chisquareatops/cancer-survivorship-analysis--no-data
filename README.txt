## Cancer Survivorship Analysis
### A Longitudinal Quality of Life Analysis of Cancer Survivors

This repository contains selected materials from the above project. 
It contains none of the original data due to privacy.
It contains only code authored by Hallie Ertman.

In the original project, PPMC and chi square values were captured to describe the correlation between various outcomes and predictors. This repo contains substitute PPMC and chi square values. They do not express the actual correlations between the variables in the original dataset. This was done for more complete anonymization. This repo does not contain any original data, any altered, shifted, or entirely generated substitute for the original data, or any description of the complete original dataset.

# Original Abstract
--------------
	Survival rates of cancer have improved drastically over the years, but many of its effects continue to influence the lives of survivors well past their diagnosis. Fred Hutchinson Cancer Center has monitored these effects through an extensive surveying and diagnosis collection system called SIMS. In this project, we reviewed and analysed the SIMS dataset, which includes self-reported quality of life metrics and clinical information on hundreds of cancer survivors. We explored the dataset using traditional inference techniques to find patterns in responses between baseline and follow up surveys. We also employed regression analysis to further explore individual correlations between features in the survey data. Random forest models were used to see if predictions of quality of life indicators could be accurately made given the rest of the survey data. 

	In the longitudinal analysis, we find that patients are largely walking away from their treatment educated about their plans and personal health, and are not experiencing notable detriments to their perceived quality of life between the baseline and follow up surveys. Many well-established correlations were confirmed in regression analysis, but we also found that some domains of predictor variables consistently failed to correlate with quality of life indicators. Predictions using random forest models were proven accurate, but the models also relied heavily on small sets of intuitively correlated variables. The significant amount of work that has gone into creating the data pipeline, data mappings, and reproducible analyses will be useful tools in generating more key insights from the SIMS data. That said, there are findings presented that yield valuable information about the survivorship program. 


# Original Statement on Data
The data rests on Fred Hutch servers and cannot be shared in this repository due to health data privacy laws.

# Repository Structure - This Repo
- LinearModelAnalysis.ipynb
- Lin_regs.csv
- Chi_sq.csv
- ppmc.csv

