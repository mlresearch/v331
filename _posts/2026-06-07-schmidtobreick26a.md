---
title: Warm-starting active-set solvers using graph neural networks
section: Poster
openreview: EWb9XMamzM
abstract: Quadratic programming (QP) solvers are widely used in real-time control
  and optimization, but their computational cost often limits applicability in time-critical
  settings. To resolve this, we propose a learning-to-optimize approach using graph
  neural networks (GNNs) to predict active constraints in the dual active-set solver
  DAQP. Our method exploits the structural properties of QPs by representing them
  as bipartite graphs and learns to approximate the optimal active set for effectively
  warm-starting the solver. Across varying problem sizes, the GNN consistently reduces
  the number of solver iterations compared to cold-starting, while performance is
  comparable to a multilayer perceptron baseline. In contrast to the baseline, our
  GNN-based approach trained on varying problem sizes generalizes to unseen dimensions,
  demonstrating flexibility and scalability. These results highlight the potential
  of structure-aware learning to accelerate optimization in real-time applications
  such as model predictive control.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schmidtobreick26a
month: 0
tex_title: Warm-starting active-set solvers using graph neural networks
firstpage: 662
lastpage: 677
page: 662-677
order: 662
cycles: false
bibtex_author: Schmidtobreick, Ella J. and Arnstr\"om, Daniel and H\"ausner, Paul
  and Sj\"olund, Jens
author:
- given: Ella J.
  family: Schmidtobreick
- given: Daniel
  family: Arnström
- given: Paul
  family: Häusner
- given: Jens
  family: Sjölund
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/schmidtobreick26a/schmidtobreick26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
