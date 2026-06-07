---
title: A Unified Framework for Locality in Scalable MARL
section: Poster
openreview: N9wt1NqyJs
abstract: Scalable methods for networked multi-agent reinforcement learning let each
  agent plan using only a small neighborhood of the agent graph. This works only when
  the system is value-local, meaning a perturbation at one agent affects the long-run
  value at another agent weakly when the two are far apart. In the average-reward
  setting, the standard way to certify locality is the Dobrushin row-sum bound on
  a single matrix $C^\pi$ that captures how each agent’s next state depends on each
  other agent’s current state. To make this matrix easy to work with, prior work bounds
  it by a supremum over joint actions. The resulting bound is independent of the policy,
  but it is loose whenever the policy never picks the worst-case action. We split
  $C^\pi$ into pieces that separately track environment sensitivity and policy sensitivity,
  $C^\pi \preceq E^{\mathrm s}+E^{\mathrm a}\Pi(\pi)$, where $E^{\mathrm s}$ measures
  how the next state moves with the current state, $E^{\mathrm a}$ measures how it
  moves with the current action, and $\Pi(\pi)$ measures how reactive the policy is
  to changes in state. The spectral radius of $H^\pi := E^{\mathrm s}+E^{\mathrm a}\Pi(\pi)$
  then controls the decay of the average-reward Poisson solution, and the spectral
  certificate $\rho(H^\pi)<1$ is strictly weaker than the row-sum condition $\|H^\pi\|_\infty<1$
  on the same matrix and applies in regimes where policy-independent action-supremum
  bounds used in prior Dobrushin-style work cannot. For temperature-$\tau$ softmax
  policies we get $\Pi(\pi)\le L/(2\tau)$, so the softmax temperature directly controls
  locality. We use this decay result to give a deterministic oracle guarantee for
  a block-coordinate KL-proximal policy-improvement template whose truncation bias
  decays exponentially in the message-passing radius $\kappa$.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26b
month: 0
tex_title: A Unified Framework for Locality in Scalable MARL
firstpage: 367
lastpage: 396
page: 367-396
order: 367
cycles: false
bibtex_author: Chakraborty, Sourav and Rege, Amit Kiran and Monteleoni, Claire and
  Chen, Lijun
author:
- given: Sourav
  family: Chakraborty
- given: Amit Kiran
  family: Rege
- given: Claire
  family: Monteleoni
- given: Lijun
  family: Chen
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/chakraborty26b/chakraborty26b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
