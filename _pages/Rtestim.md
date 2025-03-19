---
layout: archive
title: "Reproductive Number"
permalink: /Rtestim/
author_profile: true
---

Software
========

We have recently created a new R package ([`WhiteLabRt`](https://github.com/cmilando/WhiteLabRt)) that improves performance on the methods proposed in [`Zhou et al`][1] and [`Li et al`](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009210). This is loaded on to CRAN and uses C and Stan to improve computation time. 

These functions perform the following tasks:

- Estimate spatially localized reproductive numbers that can incorporate mobility data.
- Account for reporting delays in data and nowcast cases to get more up to date estimates.


Publications
============
-[Zhou Z, Thompson RN, Kolaczyk ED, White LF. Estimation of heterogeneous instantaneous reproduction numbers with application to characterize SARS-CoV-2 transmission in Massachusetts counties. PLoS Comput Biol. 2022 Sep;18(9):e1010434.][1]


[1]: <https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010434> 
