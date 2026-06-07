---
title: Data-driven Acceleration of MPC with Guarantees
section: Poster
openreview: ssARcZYQli
abstract: Model Predictive Control (MPC) is a powerful framework for optimal control
  but can be too slow for low-latency applications. We present a data-driven framework
  to accelerate MPC by replacing online optimization with a nonparametric policy constructed
  from offline MPC solutions. Our policy is greedy with respect to a constructed upper
  bound on the optimal cost-to-go, and can be implemented as a nonparametric lookup
  rule that is orders of magnitude faster than solving MPC online. Our analysis shows
  that under sufficient coverage condition of the offline data, the policy is recursively
  feasible and admits provable, bounded optimality gap. These conditions establish
  an explicit trade-off between the amount of data collected and the tightness of
  the bounds. New solutions can be incorporated straightforwardly without the need
  for retraining, enabling continual improvement. Our experiments show that this policy
  is between 100 and 1000 times faster than standard MPC, with only a modest hit to
  optimality, showing  potential for real-time control tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: castellano26a
month: 0
tex_title: Data-driven Acceleration of MPC with Guarantees
firstpage: 1339
lastpage: 1362
page: 1339-1362
order: 1339
cycles: false
bibtex_author: Castellano, Agustin and SHIJIE, PAN and Mallada, Enrique
author:
- given: Agustin
  family: Castellano
- given: PAN
  family: SHIJIE
- given: Enrique
  family: Mallada
date: 2026-06-07
address:
container-title: Proceedings of The 8th Annual Learning for Dynamics and Control Conference
volume: '331'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 6
  - 7
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/castellano26a/castellano26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
