---
layout: archive
title: "WGS for transmission"
permalink: /WGStrans/
author_profile: true
---

mlTransEpi: Using Sequencing Data to infer transmission dynamics
================================================================

We created an R package that is being developed [`here`](https://github.com/sarahleavitt/nbTransmission). We describe key features of this package here.

Estimation of pairwise transmission probabilities
-------------------------------------------------

Using a machine learning approach, we make use of SNP distances and other meta data (e.g. individual level attibutes, spatial distance between potential infectors and infectees, differences in diagnosis dates, etc.) to estimate pairwise transmission probabilities. The method does not require a strict SNP cut-off and allows for quantification of uncertainty. The method was published in the [`International Journal of Epidemiology`](https://pmc.ncbi.nlm.nih.gov/articles/PMC7394954/pdf/dyaa031.pdf).

Estimation of odds ratios
-------------------------

There is interest in understanding what factors might be most or least associated with transmission of an infectious disease. We describe a method for estimating these odds ratios in a paper published in [`Epidemiology`](https://pubmed.ncbi.nlm.nih.gov/34847084/).
