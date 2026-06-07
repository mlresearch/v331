---
title: Certified Robust Invariant Polytope Training in Neural Controlled ODEs
section: Poster
openreview: vQJlnn9tum
abstract: We propose a framework for training neural network controllers with certified
  robust forward invariant polytopes. First, we parameterize a family of lifted control
  systems in a higher dimensional space, where the original neural controlled system
  evolves on an invariant subspace of each lifted system. We use interval analysis
  and neural network verifiers to further construct a family of lifted embedding systems,
  carefully capturing the knowledge of this invariant subspace. If the vector field
  of any lifted embedding system satisfies a sign constraint at a single point, then
  a certain convex polytope of the original system is robustly forward invariant.
  Treating the neural network controller and the lifted system parameters as variables,
  we propose an algorithm to train controllers with certified forward invariant polytopes
  in the closed-loop control system. Through two examples, we demonstrate how the
  simplicity of the sign constraint allows our approach to scale with system dimension
  to over $50$ states, and outperform state-of-the-art Lyapunov-based sampling approaches
  in runtime.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: harapanahalli26a
month: 0
tex_title: Certified Robust Invariant Polytope Training in Neural Controlled ODEs
firstpage: 982
lastpage: 999
page: 982-999
order: 982
cycles: false
bibtex_author: Harapanahalli, Akash and Coogan, Samuel
author:
- given: Akash
  family: Harapanahalli
- given: Samuel
  family: Coogan
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/harapanahalli26a/harapanahalli26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
