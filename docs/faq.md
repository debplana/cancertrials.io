---
layout: default
title: FAQ
nav_order: 80
---

# Frequently Asked Questions

## Data set
### Q: What is individual participant data (IPD)?
A: IPD are the timing of events for individual patients enrolled in a clinical trial. Event types most often include censoring or death for cancer clinical trials, but can also include surrogate events such as disease progression, biochemical or clinical treatment failure, and local-regional recurrence of disease. 

### Q: How does the data imputation procedure work, and how do you check the quality of the resulting data? 
A: The data extraction and imputation procedures followed the methods outline in the following two studies:
* Guyot, P., Ades, A., Ouwens, M.J., and Welton, N.J. (2012). Enhanced secondary analysis of survival data: reconstructing the data from published Kaplan-Meier survival curves.   BMC Med Res Methodol 12, 9.
* Rahman, R., Fell, G., Ventz, S., Arfé, A., Vanderbeek, A.M., Trippa, L., and Alexander, B.M. (2019). Deviation from the Proportional Hazards Assumption in Randomized Phase 3     clinical Trials in Oncology: Prevalence, Associated Factors, and Implications. Clin Cancer Res 25, 6339–6345.
The quality of the data imputation was confirmed quantitatively by calculating the Hazard Ratio using this imputed data and compared to the corresponding trial’s reported Hazard Ratio and qualitatively by overlaying the KM curve generated from the imputed data on top of the published curve. 
Trials with a Hazard Ratio difference greater than 0.1 or perceptible visual differences, were removed from the final data set and not analyzed further. 


### Q: How many studies are included in the current data set? 
A: The data set consists of ~150 unique published phase III clinical trials in breast, colorectal, lung, and prostate cancer in metastatic and non-metastatic setting from 2014-2016. The resulting curated data set consists of 262 IPD .csv files, each with data from a unique image from the published trial results. In aggregate, these data comprise ~ 220,000 overall survival or event-free survival events (e.g. progression free survival, PFS).

## Analysis
### Q: Is this study a systematic review or meta-analysis? 
A: No. A systematic review is a formal study design to gather data, based on prespecified eligibility criteria, to answer a specific question. A meta-analysis is a subtype of systematic review that integrates the results of previous research studies to make conclusions relevant to that disease and treatment area, such as to provide a pooled estimate of a treatment’s effect.  

Our work performed exploratory analysis on cancer survival data broadly across many types of oncology clinical trials and treatment modalities. We do not intend to make specific conclusions about a single treatment or therapy. None of our analysis is intended to influence treatment decisions.

