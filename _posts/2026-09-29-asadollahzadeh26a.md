---
title: 'TRACER: Persistent Regularization for Robust Multimodal Finetuning'
openreview: XOYXLQRlj8
abstract: 'Mainstream strategies for finetuning pretrained multimodal models often
  degrade out-of-distribution (OOD) robustness, a phenomenon known as catastrophic
  forgetting. In this paper, we develop a theoretical framework for multimodal contrastive
  finetuning, yielding closed-form solutions and a geometric decomposition for these
  strategies. This framework shows that self-distillation is more effective than other
  regularization approaches to retain the knowledge of the pretrained model. Our analysis
  reveals a largely overlooked limitation: standard Exponential Moving Average (EMA)
  teachers, widely used in robust finetuning, suffer from collapse. To solve this,
  we prove that a Weighted Moving Average (WMA) teacher maintains a persistent regularizing
  force over finite horizons and yields bias-free convergence in the task subspace
  while preserving orthogonal knowledge. These insights motivate <b>TRACER</b> (<b>T</b>rajectory-<b>R</b>obust
  <b>A</b>nchoring for <b>C</b>ontrastive <b>E</b>ncoder <b>R</b>egularization), which
  combines contrastive learning with WMA-guided multi-perspective distillation. Extensive
  experiments on CLIP finetuning demonstrate consistent OOD accuracy and calibration
  gains across three backbone architectures, and comprehensive ablations confirm that
  TRACER is both principled and robust to hyperparameter choices. Code is available
  at https://github.com/HesamAsad/TRACER.'
software: https://github.com/HesamAsad/TRACER
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: asadollahzadeh26a
month: 0
tex_title: "{TRACER}: Persistent Regularization for Robust Multimodal Finetuning"
firstpage: 3993
lastpage: 4034
page: 3993-4034
order: 3993
cycles: false
bibtex_author: Asadollahzadeh, Hesam and Liu, Feng and Leckie, Christopher and Erfani,
  Sarah Monazam
author:
- given: Hesam
  family: Asadollahzadeh
- given: Feng
  family: Liu
- given: Christopher
  family: Leckie
- given: Sarah Monazam
  family: Erfani
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/asadollahzadeh26a/asadollahzadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
