---
title: Improving EV Aggregate Flexibility with End-to-End Learning
section: Poster
openreview: 3c1lNehUlf
abstract: As the adoption of electric vehicles (EVs) rises, meeting their charging
  demand efficiently while continuing to ensure reliable power grid operation has
  become increasingly challenging. One promising avenue for more efficient integration
  of EV charging demands is leveraging their flexibility. To facilitate this, aggregators—entities
  that pool energy resources into a single market participant—must combine the constraints
  encoding each EV’s charging flexibility into an aggregate flexibility set. Computing
  this set exactly is computationally intractable, motivating the development of methods
  to approximate this set. However, current methods for approximating this aggregate
  flexibility set are either unreliable—in that they may contain infeasible power
  schedules which could lead to grid instability—or they are overly conservative,
  and may neglect regions of the true aggregate set which are important for optimizing
  grid-relevant costs. Motivated by these limitations, we develop a novel approach
  for learning inner approximations of aggregate flexibility sets using Input-Convex
  Neural Networks (ICNNs). In particular, we propose to train approximate flexibility
  sets parametrized by ICNNs to minimize a decision cost, while incorporating a feasibility
  projection at each step of training to ensure the reliability of the learned set.
  We experimentally validate our methodology on the problem of learning aggregate
  flexibility sets for a peak power minimization task with real-world load data, showing
  that our approach enables better performance than decision-agnostic methods while
  guaranteeing reliability.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thanvantri26a
month: 0
tex_title: Improving EV Aggregate Flexibility with End-to-End Learning
firstpage: 624
lastpage: 639
page: 624-639
order: 624
cycles: false
bibtex_author: Thanvantri, Apoorva and Yeh, Christopher and Christianson, Nicolas
  and Wierman, Adam
author:
- given: Apoorva
  family: Thanvantri
- given: Christopher
  family: Yeh
- given: Nicolas
  family: Christianson
- given: Adam
  family: Wierman
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/thanvantri26a/thanvantri26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
