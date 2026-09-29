---
title: MODEL SOUPS NEED ONLY ONE INGREDIENT
openreview: wuWRCajFj8
abstract: Fine-tuning large pre-trained models on a target distribution often improves
  in-distribution (ID) accuracy, but at the cost of out-of-distribution (OOD) robustness
  as representations specialize to the fine-tuning data. Weight-space ensembling methods,
  such as Model Soups, mitigate this effect by averaging multiple checkpoints, but
  they are computationally prohibitive, requiring the training and storage of dozens
  of fine-tuned models. In this paper, we introduce MonoSoup, a simple, data-free,
  hyperparameter-free, post-hoc method that achieves a strong ID–OOD balance using
  <em>only a single</em> checkpoint. Our method applies Singular Value Decomposition
  (SVD) to each layer’s update and decomposes it into high-energy directions that
  capture task-specific adaptation and low-energy directions that introduce noise
  but may still encode residual signals useful for robustness. MonoSoup then uses
  entropy-based effective rank to automatically re-weigh these components with layer-wise
  coefficients that account for the spectral and geometric structure of the model.
  Experiments on CLIP models fine-tuned on ImageNet and evaluated under natural distribution
  shifts, as well as on Qwen language models tested on mathematical reasoning and
  multiple-choice benchmarks, show that this plug-and-play approach is a practical
  and effective alternative to multi-checkpoint methods, retaining much of their benefits
  without their computational overhead.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abdollahpoorrostam26a
month: 0
tex_title: "{MODEL} {SOUPS} {NEED} {ONLY} {ONE} {INGREDIENT}"
firstpage: 101
lastpage: 124
page: 101-124
order: 101
cycles: false
bibtex_author: Abdollahpoorrostam, Alireza and Dimitriadis, Nikolaos and Hazimeh,
  Adam and Frossard, Pascal
author:
- given: Alireza
  family: Abdollahpoorrostam
- given: Nikolaos
  family: Dimitriadis
- given: Adam
  family: Hazimeh
- given: Pascal
  family: Frossard
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/abdollahpoorrostam26a/abdollahpoorrostam26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
