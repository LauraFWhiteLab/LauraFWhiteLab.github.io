---
layout: archive
title: "Reproductive Number"
permalink: /Rtestim/
author_profile: true
---

Software
========

WhiteLabRt
----------

We have recently created a new R package ([`WhiteLabRt`](https://github.com/cmilando/WhiteLabRt)) that improves performance on the methods proposed in [`Zhou et al`][1] and [`Li et al`][2]. This is loaded on to CRAN and uses C and Stan to improve computation time. 

These functions perform the following tasks:

- Estimate spatially localized reproductive numbers that can incorporate mobility data.
- Account for reporting delays in data and nowcast cases to get more up to date estimates.

Estimation of Local reproductive numbers
-------------------------

This method is described in [`Li et al`][3] and allows one to estimate \\(R_t\\) accounting for imported cases from other regions. Code for implementing the method is found [`here`](https://github.com/KolaczykResearch/EstimLocalRt).


Helpful tools
=============

We are working on a bookdown to describe all available \\(R_t\\) estimation methods with implementation in R to be useful for practitioners. This is a work in progress [`here`](https://chadmilando.com/RtEstimBook/).

Publications
============

- Zhou Z, Thompson RN, Kolaczyk ED, White LF. Estimation of heterogeneous instantaneous reproduction numbers with application to characterize SARS-CoV-2 transmission in Massachusetts counties. PLoS Comput Biol. 2022 Sep;18(9):e1010434. [link][1]
- Li T, White LF. Bayesian back-calculation and nowcasting for line list data during the COVID-19 pandemic. 2021 Plos Comp Biol, 2021 Jul 12;17(7):e1009210. [link][2]
- Li W, Bulekova K, Gregor B, White LF, Kolaczyk ED. Estimation of local time-varying reproduction numbers in noisy surveillance data. Philos Trans A Math Phys Eng Sci. 2022 Oct 3;380(2233):20210303. doi: 10.1098/rsta.2021.0303. [link][3]




[1]: <https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010434> 
[2]: <https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009210>
[3]: <https://pubmed.ncbi.nlm.nih.gov/35965456/>
