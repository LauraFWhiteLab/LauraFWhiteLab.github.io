---
layout: archive
title: "TB projects"
permalink: /TBproj/
author_profile: true
---

We work in many TB related research projects. This describes some of our modeling and methods work in this area. More information on our work using whole genome sequencing to understand transmission can be found on this [`page`](https://laurafwhitelab.github.io/WGStrans/).

TB-STATIS: Measures of tuberculosis disease severity
===========

Tuberculosis is the leading cause of death due to infectious disease globally and antibiotic treatment regimens can take months to years to successfully treat the disease. There is growing interest in treatment shortening regimens for individuals with less severe disease. With that in mind, we developed a rigorous statistical approach to estimate TB disease severity using available data at diagnosis and event-based modeling (popular in the study of cognitive decline). Our software is available [`here`](https://github.com/samalatesta/tbSTATISpaper) and the paper is under review.

Inferential methods with data from Respondent Driven Sampling (RDS)
===========

RDS is a popular method for sampling hard to reach populations. We have implemented this approach in South Africa in a study to understand TB and HIV among people who smoke illicit drugs [(PWSD)][3].

While there are several methods to estimate prevalence from RDS surveys, there are limited methods to perform statistical tests. We have developed a test to do basic two group comparisons and the R package to run this method can be found [`here`](https://github.com/samalatesta/RDSAssociation). This work has been published in [`The Journal of the Royal Statistical Society, Series A`][4].

imputeTBculture: methods to handle missing data in serially collected culture samples
===========

In clinical trials and cohort studies of TB, it is common to collect culture samples at multiple time points during follow-up. Missing data is common in these studies and there was no well-established approach to handle this missing data. We have published a [`paper`][1] in *BMC Medical Research Methods* describing best practices for this problem and created [`code`](https://github.com/samalatesta/imputeTBculture) for practitioners to use.

Backcalculation methods for estimating TB incidence
=========

We have developed a Bayesian implementation of backcalculation methods for estimating TB incidence, using information obtained from TB prevalence surveys. This work is under review. 

Contribution of reinfection to the annual rate of infection (ARI)
=========

We developed a model to determine the impact of reinfection on measured annual rates of infection (ARI) and found that when there is heterogeneity in infection risk, which is recognized to be most realistic, measured ARI is underestimated. The code for our model is found [`here`](https://github.com/forsbee/ReMoTe/tree/main) and the paper which has been published in Clinical Infectious diseases, can be found [`here`][2].

Data driven targets for reducing TB burden
==========

We developed a model that uses data from countries with two prevalence surveys to determine the amount of prevalent TB disease that needs to be treated in order to meaningfully decrease TB disease burden. The method also estimates the duration of infectiousness for individuals who eventually receive treatment. The code for this model can be found [`here`](https://github.com/forsbee/TB-duration-estimation). This paper has recently been accepted to the International Journal of Tuberculosis and Lung Disease.

References
======

- Carney T, Rooney JA, Niemand N, Myers B, Theron D, Wood R, White LW, Meade C, Chegou NN, Ragan E, Walzl G, Horsburgh CR, Warren RM, Jacobson KR. Transmission Of Tuberculosis Among illicit drug use Linkages (TOTAL):  a cross-sectional observational study protocol using respondent driven sampling, PlosOne, 2022 Feb 15;17(2):e0262440 [`link`][3]
- Malatesta S, Jacobson KR, Carney T, Kolaczyk ED, Gile KJ, White LF. Inferring bivariate association with continuous data from a respondent-driven sample. Journal of the Royal Statistical Society Series C: Applied Statistics. 2024:qlae061.[`link`][4]
- Malatesta S, Weir IR, Weber SE, Bouton TC, Carney T, Theron D, Myers B, Horsburgh CR, Warren RW, Jacobson KR, White LF. Methods for Handling Missing Data in Serially Sampled Sputum Specimens for Mycobacterial Culture Conversion Calculation. BMC Med Res Methodol. 2022 Nov 19;22(1):297. [`link'][1]
- Horsburgh CR, Jo Y, Nichols B, Jenkins HE, Russell CA, White LF. Contribution of reinfection to annual rate of tuberculosis infection (ARI) and incidence of TB disease. Clin Infect Dis. 2023 Feb 8;76(3):e965-e972. doi: 10.1093/cid/ciac451. [`link`][2]
- Horsburgh CR, Jenkins HE, Martinez L, White LF. Data-driven targets for reducing the global tuberculosis burden. 2025 Int J Tuberc Lung Dis., accepted for publication.



[1]:<https://doi.org/10.1186/s12874-022-01782-8>
[2]:<https://pubmed.ncbi.nlm.nih.gov/35666515/>
[3]:<https://pubmed.ncbi.nlm.nih.gov/35167586/>
[4]:<https://academic.oup.com/jrsssc/article-abstract/74/2/429/7909014?redirectedFrom=fulltext&login=false>
