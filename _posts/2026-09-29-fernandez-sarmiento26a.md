---
title: 'Dropout Universality: Scaling Laws and Optimal Scheduling at the Edge-of-Chaos'
openreview: FoDU47u2jk
abstract: 'We develop a mean-field theory of dropout as a perturbation of critical
  signal propagation at the edge of chaos, and show that it predicts a simple, no-cost
  change to standard practice: front-loaded dropout schedules cut test loss by 18–35%
  over constant dropout in MLPs and Vision Transformers at fixed budget. The theoretical
  mechanism is that dropout shifts the perfect-alignment fixed point, making the depth
  scale for information propagation finite even at critical initialization. We derive
  critical and crossover scaling laws for correlation decay and establish that smooth
  activations and kinked, ReLU-like activations constitute distinct universality classes,
  with different critical exponents and a universal two-parameter scaling collapse
  in detuning and dropout strength. The distinction traces to the analytic structure
  of the correlation map: smooth activations admit a Taylor expansion near perfect
  alignment, while kinked activations develop a branch point with universal non-analyticity.
  As a corollary, the framework yields saturated dropout profiles under fixed budget;
  a regularization-reach argument then selects front-loaded schedules, with accuracy
  gains as a consistent secondary effect. We also discuss how the same Gaussian-kernel
  structure extends the theory beyond MLPs toward CNNs and residual architectures.'
software: https://github.com/luklacasito/dropout-universality-experiments/tree/ce1baa41915ba1601186c604e91fecf9f13b83fe
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fernandez-sarmiento26a
month: 0
tex_title: 'Dropout Universality: Scaling Laws and Optimal Scheduling at the Edge-of-Chaos'
firstpage: 30825
lastpage: 30860
page: 30825-30860
order: 30825
cycles: false
bibtex_author: Fernandez-Sarmiento, Lucas
author:
- given: Lucas
  family: Fernandez-Sarmiento
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/fernandez-sarmiento26a/fernandez-sarmiento26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
