---
title: Towards Understanding Steering Strength
openreview: A52LNgpGKy
abstract: 'A popular approach to post-training control of large language models (LLMs)
  is the steering of intermediate latent representations. Namely, identify a well-chosen
  direction depending on the task at hand and perturbs representations along this
  direction at inference time. While many propositions exist to pick this direction,
  considerably less is understood about how to choose the magnitude of the move, whereas
  its importance is clear: too little and the intended behavior does not emerge, too
  much and the model’s performance degrades beyond repair. In this work, we propose
  the first theoretical analysis of steering strength. We characterize its effect
  on next token probability, presence of a concept, and cross-entropy, deriving precise
  qualitative laws governing these quantities. Our analysis reveals surprising behaviors,
  including non-monotonic effects of steering strength. We validate our theoretical
  predictions empirically on eleven language models, ranging from a small GPT architecture
  to modern models.'
software: https://github.com/MagamedT/steering
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: taimeskhanov26a
month: 0
tex_title: Towards Understanding Steering Strength
firstpage: 118084
lastpage: 118133
page: 118084-118133
order: 118084
cycles: false
bibtex_author: Taimeskhanov, Magamed and Vaiter, Samuel and Garreau, Damien
author:
- given: Magamed
  family: Taimeskhanov
- given: Samuel
  family: Vaiter
- given: Damien
  family: Garreau
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/taimeskhanov26a/taimeskhanov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
