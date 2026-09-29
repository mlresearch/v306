---
title: Learning Normalized Energy Models for Linear Inverse Problems
openreview: PlFJwgaaDK
abstract: 'Generative diffusion models can provide powerful prior probability models
  for inverse problems in imaging, but existing implementations suffer from two key
  limitations: $(i)$ the prior density is represented implicitly, and $(ii)$ they
  rely on likelihood approximations that introduce sampling biases. We address these
  challenges by introducing a new energy-based model trained for denoising with a
  covariance-based regularization term that enforces consistency across different
  measurement conditions. The trained model can compute normalized posterior densities
  for diverse linear inverse problems, without additional retraining or fine tuning.
  In addition to preserving the sampling capabilities of diffusion models, this enables
  previously unavailable capabilities: energy-guided adaptive sampling that adjusts
  schedules on-the-fly, unbiased Metropolis-Hastings correction steps, and blind estimation
  of the degradation operator via Bayes rule. We validate the method on multiple datasets
  (ImageNet, CelebA, AFHQ) and tasks (inpainting, deblurring), demonstrating competitive
  or superior performance to established baselines.'
software: https://github.com/nzilberstein/Anisotropic-energy-Model
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zilberstein26b
month: 0
tex_title: Learning Normalized Energy Models for Linear Inverse Problems
firstpage: 168381
lastpage: 168415
page: 168381-168415
order: 168381
cycles: false
bibtex_author: Zilberstein, Nicolas and Segarra, Santiago and Simoncelli, Eero P and
  Guth, Florentin
author:
- given: Nicolas
  family: Zilberstein
- given: Santiago
  family: Segarra
- given: Eero P
  family: Simoncelli
- given: Florentin
  family: Guth
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/zilberstein26b/zilberstein26b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
