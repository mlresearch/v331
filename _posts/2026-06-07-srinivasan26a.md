---
title: 'Safety Beyond the Training Data: Robust Out-of-Distribution MPC via Conformalized
  System Level Synthesis'
section: Poster
openreview: o4fb5rSinP
abstract: We present a novel framework for robust out-of-distribution planning and
  control using conformal prediction (CP) and system level synthesis (SLS). Our method
  addresses the challenge of ensuring safety and robustness when using learned dynamics
  models beyond the training data distribution. We first derive high-confidence bounds
  on model errors using weighted conformal prediction with a learned, state-control-dependent
  covariance model. These bounds are then integrated into an SLS-based robust nonlinear
  model predictive control (RMPC) formulation, which performs constraint tightening
  over the prediction horizon via volume-optimized forward reachable sets. We provide
  theoretical guarantees on coverage and robustness under distributional drift, and
  analyze the impact of data density and trajectory tube size on prediction coverage.
  Empirically, we demonstrate our approach on nonlinear systems of increasing complexity,
  including a 4D car and a {12D} quadcopter, showing improved safety and reliability
  compared to fixed-bound and non-robust baselines, especially outside of the collected
  data distribution.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srinivasan26a
month: 0
tex_title: 'Safety Beyond the Training Data: Robust Out-of-Distribution MPC via Conformalized
  System Level Synthesis'
firstpage: 412
lastpage: 439
page: 412-439
order: 412
cycles: false
bibtex_author: Srinivasan, Anutam and Leeman, Antoine and Chou, Glen
author:
- given: Anutam
  family: Srinivasan
- given: Antoine
  family: Leeman
- given: Glen
  family: Chou
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/srinivasan26a/srinivasan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
