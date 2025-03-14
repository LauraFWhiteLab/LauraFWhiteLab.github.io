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






