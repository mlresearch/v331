---
title: Learned Incremental Nonlinear Dynamic Inversion for Quadrotors with and without
  Slung Payloads
section: Poster
openreview: o8NJwCKhVn
abstract: The increasing complexity of multirotor applications demands flight controllers
  that can accurately account for all forces acting on the vehicle. Conventional controllers
  model most aerodynamic and dynamic effects but often neglect higher-order forces,
  as their accurate estimation is computationally expensive. Incremental Nonlinear
  Dynamic Inversion (INDI) offers an alternative by estimating residual forces from
  differences in sensor measurements; however, its reliance on specialized and often
  noisy sensors limits its applicability. Recent work has demonstrated that residual
  forces can be predicted using learning-based methods. In this paper, we show that
  a neural network can generate smooth approximations of INDI outputs without requiring
  additional sensor inputs. We further propose a hybrid approach that integrates learning-based
  predictions with INDI and demonstrate both methods for multirotors and multirotors
  carrying slung payloads. Experimental results on trajectory tracking errors demonstrate
  that the specialized sensor measurements required by INDI can be eliminated by replacing
  the residual computation with a neural network.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cobo-briesewitz26a
month: 0
tex_title: Learned Incremental Nonlinear Dynamic Inversion for Quadrotors with and
  without Slung Payloads
firstpage: 1260
lastpage: 1274
page: 1260-1274
order: 1260
cycles: false
bibtex_author: Cobo-Briesewitz, Eckart and Wahba, Khaled and H\"onig, Wolfgang
author:
- given: Eckart
  family: Cobo-Briesewitz
- given: Khaled
  family: Wahba
- given: Wolfgang
  family: Hönig
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/cobo-briesewitz26a/cobo-briesewitz26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
