---
title: Safe Planning in Interactive Environments via Iterative Policy Updates and
  Adversarially Robust Conformal Prediction
section: Poster
openreview: VBPp1hPkro
abstract: Safe planning of an autonomous agent in interactive environments – such
  as the control of a self-driving vehicle among pedestrians and human-controlled
  vehicles – poses a major challenge as the behavior of the environment is unknown
  and reactive to the behavior of the autonomous agent. This coupling gives rise to
  interaction-driven distribution shifts where the autonomous agent’s control policy
  may change the environment’s behavior, thereby invalidating safety guarantees in
  existing work. Indeed, recent works have used conformal prediction (CP) to generate
  distribution-free safety guarantees using observed data of the environment. However,
  CP’s assumption on data exchangeability is violated in interactive settings due
  to a circular dependency where a control policy update changes the environment’s
  behavior, and vice versa. To address this gap, we propose an iterative framework
  that robustly maintains safety guarantees across policy updates by  quantifying
  the potential impact of a planned policy update on the environment’s behavior. We
  realize this via adversarially robust CP where we perform a regular CP step  in
  each episode using observed data under the current policy, but then transfer safety
  guarantees across policy updates by analytically adjusting the CP result to account
  for distribution shifts. This adjustment is performed based on a policy-to-trajectory
  sensitivity analysis, resulting in a safe, episodic open-loop planner. We further
  conduct a contraction analysis of the system providing conditions under which both
  the CP results and the policy updates are guaranteed to converge. We empirically
  demonstrate these safety and convergence guarantees on a two-dimensional car-pedestrian
  and a high-dimensional quadcopter case study. To the best of our knowledge, these
  are the first results that provide valid safety guarantees in such interactive settings.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mirzaeedodangeh26a
month: 0
tex_title: Safe Planning in Interactive Environments via Iterative Policy Updates
  and Adversarially Robust Conformal Prediction
firstpage: 678
lastpage: 704
page: 678-704
order: 678
cycles: false
bibtex_author: Mirzaeedodangeh, Omid and Shekhtman, Eliot Seo and Matni, Nikolai and
  Lindemann, Lars
author:
- given: Omid
  family: Mirzaeedodangeh
- given: Eliot Seo
  family: Shekhtman
- given: Nikolai
  family: Matni
- given: Lars
  family: Lindemann
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
pdf: https://raw.githubusercontent.com/mlresearch/v331/main/assets/mirzaeedodangeh26a/mirzaeedodangeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
