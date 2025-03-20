---
layout: archive
title: "WGS for transmission"
permalink: /WGStrans/
author_profile: true
---

mlTransEpi: Using Sequencing Data to infer transmission dynamics
================================================================

We created an R package that is being developed [`here`](https://github.com/sarahleavitt/nbTransmission) and is available on CRAN. We describe key features of this package here.

Estimation of pairwise transmission probabilities
-------------------------------------------------

Using a machine learning approach, we make use of SNP distances and other meta data (e.g. individual level attibutes, spatial distance between potential infectors and infectees, differences in diagnosis dates, etc.) to estimate pairwise transmission probabilities. The method does not require a strict SNP cut-off and allows for quantification of uncertainty. The method was published in the [`International Journal of Epidemiology`][1].

Estimation of odds ratios
-------------------------

There is interest in understanding what factors might be most or least associated with transmission of an infectious disease. We describe a method for estimating these odds ratios in a paper published in [`Epidemiology`][2]. We have recently modified this method to allow for multivariable analyses and this is being added to the R package and being prepared for publication.

Estimation of serial intervals
----------

We demonstrate a method to use SNP distances between individuals to derive an estimate of the generation interval. We have published a paper demonstrating how this can be done using tuberculosis data in Massachusetts that was published in the journal [`Biostatistics`][3].

References
====

- Leavitt SV, Lee RS, Sebastiani P, Horsburgh CR, Jenkins HE, White LF. Estimating the relative probability of direct transmission between infectious disease patients. Int J Epidemiol. 2020 Jun 01; 49(3):764-775. 
- Leavitt SV, Jenkins HE, Sebastiani P, Lee RS, Horsburgh Jr., CR, Tibbs AM, White LF. Estimation of the generation interval using pair-wise relative transmission probabilities. Biostatistics. 2022 Jul 18; 23(3):807-824. 
- Leavitt SV, Horsburgh CR, Lee R, Tibbs A, Jenkins HE , White LF. What can genetic relatedness tell us about risk factors for tuberculosis transmission? Epidemiology, 2022 Jan 1;33(1):55-64. 


[1]:<https://pmc.ncbi.nlm.nih.gov/articles/PMC7394954/pdf/dyaa031.pdf>
[2]:<https://pubmed.ncbi.nlm.nih.gov/34847084/>
[3]:<https://pmc.ncbi.nlm.nih.gov/articles/PMC9291635/pdf/kxaa059.pdf>
