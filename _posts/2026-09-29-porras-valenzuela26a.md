---
title: A Constrained Optimization Perspective of Unrolled Transformers
openreview: aYe8j2jOmK
abstract: We introduce a constrained optimization framework for training transformers
  that behave like optimization descent algorithms. Specifically, we enforce layerwise
  descent constraints on the objective function and replace standard empirical risk
  minimization (ERM) with a primal-dual training scheme. This approach yields models
  whose intermediate representations decrease the loss monotonically in expectation
  across layers. We apply our method to both unrolled transformer architectures and
  conventional pretrained transformers on tasks of video denoising and text classification.
  Across these settings, we observe that constrained transformers achieve stronger
  robustness to perturbations and maintain higher out-of-distribution generalization,
  while preserving competitive in-distribution performance.
software: https://github.com/jotaporras/constrained-unrolled-transformers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: porras-valenzuela26a
month: 0
tex_title: A Constrained Optimization Perspective of Unrolled Transformers
firstpage: 99198
lastpage: 99230
page: 99198-99230
order: 99198
cycles: false
bibtex_author: Porras-Valenzuela, Javier and Hadou, Samar and Ribeiro, Alejandro
author:
- given: Javier
  family: Porras-Valenzuela
- given: Samar
  family: Hadou
- given: Alejandro
  family: Ribeiro
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/porras-valenzuela26a/porras-valenzuela26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
