---
title: Meta Flow Maps enable scalable reward alignment
openreview: K5gV8Yptne
abstract: Controlling generative models—whether via inference-time steering or fine-tuning—is
  expensive. Control relies on estimating the value function—typically necessitating
  costly trajectory simulations. To eliminate this bottleneck, we introduce <em>Meta
  Flow Maps (MFMs)</em>, stochastic extensions of consistency models and flow maps.
  MFMs are trained to perform <b>one-step posterior sampling</b>, generating arbitrarily
  many i.i.d. draws of clean data $x_1$ from any noisy state $x_t$. Crucially, these
  samples are differentiable in the conditioning state $x_t$, unlocking efficient
  estimation of the value function gradient. We leverage this capability to enable
  both <b>inference-time steering</b> without inner rollouts, and unbiased, off-policy
  <b>fine-tuning</b> to general rewards. Among our fine-tuning and steering experiments
  on ImageNet, we highlight that our single-particle steered-MFM sampler outperforms
  a Best-of-1000 baseline across multiple rewards at a fraction of the compute.
software: https://github.com/adh1s/mfm
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: potaptchik26b
month: 0
tex_title: Meta Flow Maps enable scalable reward alignment
firstpage: 99255
lastpage: 99295
page: 99255-99295
order: 99255
cycles: false
bibtex_author: Potaptchik, Peter and Saravanan, Adhi and Mammadov, Abbas and Prat,
  Alvaro and Albergo, Michael Samuel and Teh, Yee Whye
author:
- given: Peter
  family: Potaptchik
- given: Adhi
  family: Saravanan
- given: Abbas
  family: Mammadov
- given: Alvaro
  family: Prat
- given: Michael Samuel
  family: Albergo
- given: Yee Whye
  family: Teh
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/potaptchik26b/potaptchik26b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
