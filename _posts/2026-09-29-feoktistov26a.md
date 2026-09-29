---
title: 'Softsign: Smooth Sign in Your Optimizer For Better Parameter Heterogeneity
  Handling'
openreview: n47bK7WM3U
abstract: 'Sign-based and LMO-inspired optimizers have recently attracted substantial
  attention in deep learning due to their strong performance and low memory footprint.
  However, their fixed-magnitude updates can hurt terminal convergence: they decouple
  update mechanisms from gradient magnitudes and fail to account for parameter heterogeneity,
  often leading to oscillation rather than convergence. We propose SoftSignum, a smooth
  relaxation of sign-based optimization that replaces the hard sign map with a temperature-controlled
  soft-sign transformation, enabling a parameter-wise transition from sign-like updates
  to magnitude-sensitive SGD-like steps. We complement it with an adaptive quantile-based
  temperature schedule and extend the same principle to matrix-valued optimizers,
  obtaining SoftMuon. We also develop a generalized geometry-relaxation framework
  based on strongly convex regularizers and Fenchel conjugates, proving convergence
  in stochastic non-convex setting. Experiments on diverse deep learning tasks, including
  LLM pretraining, show that SoftSignum and SoftMuon consistently improve over their
  hard sign-based counterparts and standard AdamW.'
software: https://github.com/brain-lab-research/softsign
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: feoktistov26a
month: 0
tex_title: 'Softsign: Smooth Sign in Your Optimizer For Better Parameter Heterogeneity
  Handling'
firstpage: 30720
lastpage: 30746
page: 30720-30746
order: 30720
cycles: false
bibtex_author: Feoktistov, Dmitrii and Belinsky, Timofey and Veprikov, Andrey and
  Zainullin, Amir and Beznosikov, Aleksandr
author:
- given: Dmitrii
  family: Feoktistov
- given: Timofey
  family: Belinsky
- given: Andrey
  family: Veprikov
- given: Amir
  family: Zainullin
- given: Aleksandr
  family: Beznosikov
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/feoktistov26a/feoktistov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
