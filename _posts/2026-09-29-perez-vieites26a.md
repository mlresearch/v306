---
title: Online Bayesian Experimental Design for Partially Observed Dynamical Systems
openreview: 1Rh9assFy5
abstract: Bayesian experimental design (BED) provides a principled framework for optimising
  data collection by choosing experiments that are maximally informative about unknown
  parameters. However, existing methods cannot deal with the joint challenge of (a)
  <em>partially observable dynamical systems</em>, where only noisy and incomplete
  observations are available, and (b) <em>fully online inference</em>, which updates
  posterior distributions and selects designs sequentially in a computationally efficient
  manner. Under partial observability, dynamical systems are naturally modeled as
  state-space models (SSMs), in which latent states mediate the link between parameters
  and data, making the likelihood—and thus information-theoretic objectives like the
  expected information gain (EIG)—intractable. We address these challenges by deriving
  new estimators of the EIG and its gradient that explicitly marginalise latent states,
  enabling scalable stochastic optimisation in nonlinear SSMs. Our approach leverages
  nested particle filters for efficient online state-parameter inference with convergence
  guarantees. Applications to realistic models, such as the susceptible–infectious–recovered
  (SIR) model and a moving source location task, show that our framework successfully
  handles both partial observability and online inference.
software: https://github.com/sarapv/badpods
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: perez-vieites26a
month: 0
tex_title: Online {B}ayesian Experimental Design for Partially Observed Dynamical
  Systems
firstpage: 98257
lastpage: 98280
page: 98257-98280
order: 98257
cycles: false
bibtex_author: Perez-Vieites, Sara and Iqbal, Sahel and S\"{a}rkk\"{a}, Simo and Baumann,
  Dominik
author:
- given: Sara
  family: Perez-Vieites
- given: Sahel
  family: Iqbal
- given: Simo
  family: Särkkä
- given: Dominik
  family: Baumann
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/perez-vieites26a/perez-vieites26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
