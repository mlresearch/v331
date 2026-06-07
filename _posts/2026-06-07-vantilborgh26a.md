---
title: Efficient State and Parameter Estimation of Nonlinear State-Space Models through
  Probabilistic Optimal Control
section: Poster
openreview: QNIRvfzsSq
abstract: This work presents a novel representation of the smoothing distribution
  - the posterior state distribution of a discrete-time dynamical system - through
  its connection to probabilistic optimal control. The key idea is to represent the
  posterior as the closed-loop behavior of a synthetic control system governed by
  an optimal stochastic policy. This formulation enables forward simulation of equally
  weighted trajectories that capture the statistics of the posterior without the need
  for backward sampling or importance weighting. We derive a practical algorithm based
  on probabilistic dynamic programming to compute this policy efficiently, with linear
  computational complexity in the number of particles. Furthermore, the uniform particle
  weighting significantly simplifies and accelerates the Expectation–Maximization
  algorithm, providing substantial benefits for system identification of nonlinear
  dynamical systems with latent states. The proposed method offers a simple, stable,
  and scalable alternative to traditional particle smoothers and demonstrates accurate
  parameter estimation and model learning at significantly reduced computational cost.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vantilborgh26a
month: 0
tex_title: Efficient State and Parameter Estimation of Nonlinear State-Space Models
  through Probabilistic Optimal Control
firstpage: 1306
lastpage: 1321
page: 1306-1321
order: 1306
cycles: false
bibtex_author: Vantilborgh, Victor and Filabadi, Mohammad Mahmoudi and Lefebvre, Tom
  and Crevecoeur, Guillaume
author:
- given: Victor
  family: Vantilborgh
- given: Mohammad Mahmoudi
  family: Filabadi
- given: Tom
  family: Lefebvre
- given: Guillaume
  family: Crevecoeur
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/vantilborgh26a/vantilborgh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
