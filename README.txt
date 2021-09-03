## Cancer Survivorship Analysis
### A Longitudinal Quality of Life Analysis of Cancer Survivors

This repository contains the materials used the capstone project for MSDS - Winter 2020

# Abstract
--------------
	Survival rates of cancer have improved drastically over the years, but many of its effects continue to influence the lives of survivors well past their diagnosis. Fred Hutchinson Cancer Center has monitored these effects through an extensive surveying and diagnosis collection system called SIMS. In this project, we reviewed and analysed the SIMS dataset, which includes self-reported quality of life metrics and clinical information on hundreds of cancer survivors. We explored the dataset using traditional inference techniques to find patterns in responses between baseline and follow up surveys. We also employed regression analysis to further explore individual correlations between features in the survey data. Random forest models were used to see if predictions of quality of life indicators could be accurately made given the rest of the survey data. 

	In the longitudinal analysis, we find that patients are largely walking away from their treatment educated about their plans and personal health, and are not experiencing notable detriments to their perceived quality of life between the baseline and follow up surveys. Many well-established correlations were confirmed in regression analysis, but we also found that some domains of predictor variables consistently failed to correlate with quality of life indicators. Predictions using random forest models were proven accurate, but the models also relied heavily on small sets of intuitively correlated variables. The significant amount of work that has gone into creating the data pipeline, data mappings, and reproducible analyses will be useful tools in generating more key insights from the SIMS data. That said, there are findings presented that yield valuable information about the survivorship program. 


# Data
The data rests on Fred Hutch servers and cannot be shared in this repository due to health data privacy laws. All notebooks in this repository need to be hosted on the servers to run.

# Repository Structure
- Notebooks
	- Exploration
		- Exploration.ipynb
		- Clinical_processing.py
		- ExplorationDemographics.ipynb
	- Linear Analysis
		- LinearModelAnalysis.ipynb
		- Lin_regs.csv
		- Chi_sq.csv
		- ppmc.csv
	- Random Forest Analysis
		- RandomForestAnalysisSample.ipynb
	- Longitudinal Analysis
		- FullSetAnalysis.ipynb
		- PartialAnalysis.ipynb
		- survey_key.py
		- survey_processing.py
		- survey_responses.py
		- SleepAndPainChanges.ipynb
		- AvgPainDeltas.png
		- HoursAndRefreshingness.png
		- GenHealthDiff.jpg

data
- Baseline.csv
- Baseline_ALL.csv
- Clinical.csv
- Followup.csv
- followup_ALL.csv
- notes_for_PRO_features.txt
