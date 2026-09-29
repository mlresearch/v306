---
title: 'One Intervention per Component is Enough: Towards Identifiability in Linear
  Stochastic Dynamics from Steady State'
openreview: g07aDcWYJ9
abstract: 'We study the problem of recovering the parameters of a multivariate Ornstein–Uhlenbeck
  (OU) process from steady-state observational and interventional data. In many applications,
  such as large-scale gene perturbation experiments, only stationary “snapshot” measurements
  are available, making standard stochastic differential equation estimation methods
  that rely on time-series trajectories inapplicable. We first establish an identifiability
  result: one intervention per strongly connected component (SCC) of the drift graph
  suffices to recover all OU process parameters generically up to a global scaling
  factor. This holds provided that the SCC condensation graph is connected with a
  single root and certain spectral nondegeneracy assumptions hold. We propose a recursive
  learning algorithm that orders SCCs topologically and, for each component, isolates
  its marginal dynamics and solves a linear system derived from the steady-state moment
  equations, leveraging parameters recovered for upstream components. Building on
  this theoretical foundation, we propose a regularized least-squares estimator that
  jointly minimizes residuals of the steady-state mean and covariance equations across
  observational and interventional data. Experiments on synthetic and real datasets
  demonstrate the effectiveness of our method in recovering parameters and predicting
  unseen interventions.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: salehkaleybar26a
month: 0
tex_title: 'One Intervention per Component is Enough: Towards Identifiability in Linear
  Stochastic Dynamics from Steady State'
firstpage: 107313
lastpage: 107342
page: 107313-107342
order: 107313
cycles: false
bibtex_author: Salehkaleybar, Saber
author:
- given: Saber
  family: Salehkaleybar
date: 2026-09-29
address:
container-title: Proceedings of the 43rd International Conference on Machine Learning
volume: '306'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 9
  - 29
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/salehkaleybar26a/salehkaleybar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
