---
layout: default
title: Home
nav_order: 1
description: ""
# last_modified_date: 2021-07-12
---

<!-- UIkit CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/uikit@3.6.22/dist/css/uikit.min.css" />

# cancertrials.io

**ABOUT**
cancertirals.io contains imputed individual participant data (IPD) from previously published oncology research clinical trials (RCTs). The site also contains various types of analysis performed on these data. Data and analysis can be downloaded or viewed interactively using R-Shiny. 
  
  
**Public domain license** 
All data are are available under a permissive CC BY4.0 license; software is released under an MIT License. 
  
  
**Individual participant data**
IPD in oncology trials is the time (relative to the start of the trial) at which events such as progression, death and censoring occur for individual (anonymous) trial participants. This is the most useful form of survival data for meta-analysis and retrospective investigation of trial outcomes [1,2]. 
  
  
**Data imputation**
The Kaplan Meir estimators [3] for survival universally published as part of Phase 3 clinical trial reports are plotted using IPD but the underlying values are rarely published. The International Committee of Medical Journal Editors (ICMJE) has stated release of IPD from clinical trials is an ethical necessity but compliance remains poor: less than 1% of papers published in the last three actually comply [4]. To overcome this problem we have developed methods we have developed image processing methods to impute IPD values from published plots of the Kaplan-Meier estimator [5–7]. Our approach is consistent with the Institute of Medicine’s reports on best practices for sharing data from published clinical trials, including crediting the sources of the data and sharing all code used in the analyses [8]. However, primary data with associated demographic information would be superior to imputed data; we welcome data contributions from individuals with access to the primary data. Contact us at CancerIPD [at] gmail.com.
  
  
**DATA SETS**
  
**CT1.v1** 
Imputed IPD from ~150 trial publications in breast, colorectal, lung, and prostate cancer, which in aggregate comprise ~220,000 overall survival OS) or event-free survival events (e.g. progression free survival, PFS). 

Citation: “Cancer patient survival can be accurately parameterized, revealing time-dependent therapeutic effects and doubling the precision of small trials” by Deborah Plana, Geoffrey Fell, Brian M. Alexander, Adam C. Palmer, Peter K. Sorger. bioRxiv 2021.05.14.442837; doi: https://doi.org/10.1101/2021.05.14.442837.

<b>PARTICIPANTS<b/>
  
<u>Harvard MIT Program in Regulatory Sciences.</u>
  
* [Deborah Plana](https://connects.catalyst.harvard.edu/Profiles/display/Person/159270)
* [Peter Sorger](https://connects.catalyst.harvard.edu/Profiles/display/Person/6970)
  
<u>Dana-Farber Cancer Institute</u>
  
* [Geoffrey Fell](https://ds.dfci.harvard.edu/our-people/geoffrey-fell-ms/)
* [Brian Alexander](https://www.dfhcc.harvard.edu/insider/member-detail/member/brian-alexander-md-mph/)
* [Lorenzo Trippa](https://www.hsph.harvard.edu/lorenzo-trippa/)


<u>Palmer Laboratory at University of North Carolina at Chapel Hill</u>
  
* [Adam Palmer](https://www.med.unc.edu/pharm/directory/adam-palmer-phd/)
* [Haeun (Hannah) Hwangbo](https://www.linkedin.com/in/haeun-hannah-hwangbo-b0a17515a/) 


<b>CITATIONS<b/>

1.	Stewart, L. A. & Tierney, J. F. To IPD or not to IPD?: Advantages and Disadvantages of Systematic Reviews Using Individual Patient Data. Eval Health Prof 25, 76–97 (2002).
2.	Riley, R. D., Lambert, P. C. & Abo-Zaid, G. Meta-analysis of individual participant data: rationale, conduct, and reporting. BMJ 340, c221 (2010).
3.	Kaplan, E. L. & Meier, P. Nonparametric Estimation from Incomplete Observations. 53, (1958).
4.	Danchev, V., Min, Y., Borghi, J., Baiocchi, M. & Ioannidis, J. P. A. Evaluation of Data Sharing After Implementation of the International Committee of Medical Journal Editors Data Sharing Statement Requirement. JAMA Netw Open 4, e2033972 (2021).
5.	Alexander, B. M., Schoenfeld, J. D. & Trippa, L. Hazards of Hazard Ratios - Deviations from Model Assumptions in Immunotherapy. N. Engl. J. Med. 378, 1158–1159 (2018).
6.	Guyot, P., Ades, A., Ouwens, M. J. & Welton, N. J. Enhanced secondary analysis of survival data: reconstructing the data from published Kaplan-Meier survival curves. BMC Med Res Methodol 12, 9 (2012).
7.	Rahman, R. et al. Deviation from the Proportional Hazards Assumption in Randomized Phase 3 Clinical Trials in Oncology: Prevalence, Associated Factors, and Implications. Clin Cancer Res 25, 6339–6345 (2019).
8.	Committee on Strategies for Responsible Sharing of Clinical Trial Data, Board on Health Sciences Policy, & Institute of Medicine. Discussion Framework for Clinical Trial Data Sharing: Guiding Principles, Elements, and Activities. (National Academies Press (US), 2014).

<b>FUNDING<b/>
  
This project was supported by NIH grant U54-CA225088 to Peter Sorger. Deborah Plana is supported by NIGMS training grants T32-GM007753 and F30-CA260780.
