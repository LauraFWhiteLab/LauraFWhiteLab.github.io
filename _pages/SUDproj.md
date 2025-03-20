---
layout: archive
title: "Substance use disorders"
permalink: /SUDproj/
author_profile: true
---

Building on our initial effort to undestand the prevalence of Opioid Use Disorder using capture recapture methods in a highly cited paper in the [`American Journal of Public Health`][1], we have worked to improve methods for prevalence estimation in this hard to reach population. We use **multiple systems data methods** to estimate prevalence in an attempt to understand the size of the population not captured by any data sources.

Software/Code
=============

- We have done a careful technical comparison of two popular methods to estimate prevalence with multiple data systems: Multiplier based methods and Capture recapture methods. Code is found [`here`](https://github.com/jianing-jenny-wang/Compare-MBM-versus-CRM). The paper describing this has been published [`here`][2].
- We have developed a method to estimate *spatially granular estimates of prevalence* using multiple data systems. Code is available [`here`](https://github.com/jianing-jenny-wang/SCRC-SAE-HealthAdminData).
- We have modified these methods to estimate prevalence among subgroups. Code is available [`here`](https://github.com/jianing-jenny-wang/BHMFA-Subgroup-HealthAdminData).


Comparison of multiple systems prevalence estimation methods
-------

We have done a careful analytic and simulation-based comparison of the two most common methods to estimate the size of a hidden population: Multipler based methods and Capture Recapture methods. We show the conditions under which these methods are equivalent, and importantly, when they are not equivalent. The paper is published in Statistical Methods in Medical Research and can he found [`here`][2]. Code for this project is available [`here`](https://github.com/jianing-jenny-wang/Compare-MBM-versus-CRM).

Spatially granular prevalence estimates
---------------------------------------

We have developed an approach inspired by capture recapture methods to perform small area estimation of prevalence. This fully bayesian approach can estimate prevalence in the presence of sparse data by leveraging spatial correlation between areas. Code for this method is found [`here`](https://github.com/jianing-jenny-wang/SCRC-SAE-HealthAdminData) and the paper describing this is under review.

Subgroup prevalence estimates
-------------

Estimating our spatially granular estimation framework, we have developed an approach to estimate the prevalence among subgroups. A notable feature of this method is that it allows one to estimate the sampling probability for each sub group. In large administrative datasets, we often assumed that everyone is equally likely to be sampled, but our results reveal striking differences in representation of different groups, indicating differential access to healthcare and government services. The code for this is under development [`here`](https://github.com/jianing-jenny-wang/BHMFA-Subgroup-HealthAdminData). This manuscript is in progress.

References
==========

- Barocas JA, White LF, Wang J, Bernson D, Land T, Walley AY, LaRochelle MR, Morgan JR, Samet JH, Linas BP. Prevalence of opioid use disorder in Massachusetts, annual estimates from 2011 through 2015. Am J Public Health. 2018 Dec;108(12):1675-1681. [`link`][1]
- Wang JN, Kline D, White LF. On the Estimation of Population Size - A Comparison of Capture-Recapture and Multiplier-Benchmark Methods. Stat Methods Med Res. 2024 Oct; 33(10):1818-1835. [`link`][2]



[1]: <https://pubmed.ncbi.nlm.nih.gov/30359112/>
[2]: <https://pubmed.ncbi.nlm.nih.gov/39350602/>
