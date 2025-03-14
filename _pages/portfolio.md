---
layout: archive
title: "Lab Repositories"
permalink: /portfolio/
author_profile: true
---

Reproductive Number Estimation
==============================

We have recently created a new R package ([`WhiteLabRt`](https://github.com/cmilando/WhiteLabRt)) that improves performance on the methods proposed in [`Zhou et al`](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010434) and [`Li et al`](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009210). This is loaded on to CRAN and uses C and Stan to improve computation time. 

These functions perform the following tasks:

- Estimate spatially localized reproductive numbers that can incorporate mobility data.
- Account for reporting delays in data and nowcast cases to get more up to date estimates.

mlTransEpi: Using Sequencing Data to infer transmission dynamics
================================================================

We created an R package that is being developed [`here`](https://github.com/sarahleavitt/nbTransmission). We describe key features of this package here.

Estimation of pairwise transmission probabilities
-------------------------------------------------

Using a machine learning approach, we make use of SNP distances and other meta data (e.g. individual level attibutes, spatial distance between potential infectors and infectees, differences in diagnosis dates, etc.) to estimate pairwise transmission probabilities. The method does not require a strict SNP cut-off and allows for quantification of uncertainty. The method was published in the [`International Journal of Epidemiology`](https://pmc.ncbi.nlm.nih.gov/articles/PMC7394954/pdf/dyaa031.pdf).

Estimation of odds ratios
-------------------------

There is interest in understanding what factors might be most or least associated with transmission of an infectious disease. We describe a method for estimating these odds ratios in a paper published in [`Epidemiology`](https://pubmed.ncbi.nlm.nih.gov/34847084/).


Statistical inference with data from respondent driven samples
==============================================================

Data collected from respondent driven samples, a method to sample social networks to identify hard to reach populations, is highly correlated and typical statistical methods do not apply. We have developed a bivariate test of association for this data that was published in the [`Journal of the Royal Statistical Society`](https://academic.oup.com/jrsssc/article-abstract/74/2/429/7909014?redirectedFrom=PDF) with code for implementing this method available [`here`](https://github.com/samalatesta/RDSAssociation).

Tuberculosis methods
====================

Below are some of our methods developed to assist in understanding TB epidemiology.

TB-STATIS: Measures of tuberculosis disease severity
----------------------------------------------------

Tuberculosis is the leading cause of death due to infectious disease globally and antibiotic treatment regimens can take months to years to successfully treat the disease. There is growing interest in treatment shortening regimens for individuals with less severe disease. With that in mind, we developed a rigorous statistical approach to estimate TB disease severity using available data at diagnosis and event-based modeling (popular in the study of cognitive decline). Our software is available [`here`](https://github.com/samalatesta/tbSTATISpaper) and the paper is under review.

imputeTBculture: methods to handle missing data in serially collected culture samples
-------------------------------------------------------------------------------------

In clinical trials and cohort studies of TB, it is common to collect culture samples at multiple time points during follow-up. Missing data is common in these studies and there was no well-established approach to handle this missing data. We have published a [`paper`](https://doi.org/10.1186/s12874-022-01782-8) in *BMC Medical Research Methods* describing best practices for this problem and created [`code`](https://github.com/samalatesta/imputeTBculture) for practitioners to use.



