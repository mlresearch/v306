---
title: 'U-Cast: A Surprisingly Simple and Efficient Frontier Probabilistic AI Weather
  Forecaster'
openreview: XF0wkyEbuM
abstract: 'AI-based weather forecasting now rivals traditional physics-based ensembles,
  but state-of-the-art (SOTA) models rely on specialized architectures and massive
  computational budgets, creating a high barrier to entry. We demonstrate that such
  complexity is unnecessary for frontier performance. We introduce U-Cast, a probabilistic
  forecaster built on a standard U-Net backbone trained with a simple recipe: deterministic
  pre-training on Mean Absolute Error followed by short probabilistic fine-tuning
  on the Continuous Ranked Probability Score (CRPS) using Monte Carlo Dropout for
  stochasticity. As a result, our model matches or exceeds the probabilistic skill
  of GenCast and IFS ENS at $1.5^\circ$ resolution while reducing training compute
  by over $10\times$ compared to leading CRPS-based models and inference latency by
  over $10\times$ compared to diffusion-based models. U-Cast trains in under 12 H200
  GPU-days and generates a 15-day ensemble forecast in 3 seconds. These results suggest
  that scalable, general-purpose architectures paired with efficient training curricula
  can match complex domain-specific designs at a fraction of the cost, opening the
  training of frontier probabilistic weather models to the broader community.'
software: https://github.com/Rose-STL-Lab/u-cast
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ruhling-cachay26a
month: 0
tex_title: 'U-Cast: A Surprisingly Simple and Efficient Frontier Probabilistic {AI}
  Weather Forecaster'
firstpage: 106213
lastpage: 106234
page: 106213-106234
order: 106213
cycles: false
bibtex_author: R\"{u}hling Cachay, Salva and Watson-Parris, Duncan and Yu, Rose
author:
- given: Salva
  family: Rühling Cachay
- given: Duncan
  family: Watson-Parris
- given: Rose
  family: Yu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ruhling-cachay26a/ruhling-cachay26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
