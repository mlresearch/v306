---
title: 'Unlearning Isn’t Forgetting: Revealing Hidden Leakage in Class Unlearning
  Evaluations'
openreview: v2mY3gjdnP
abstract: 'In this paper, we reveal a significant shortcoming in class unlearning
  evaluations: overlooking the underlying class geometry can cause information leakage
  about the forgotten class. We further propose a simple unlearning strategy to mitigate
  this issue. We introduce Class Membership Inference Attack (CMIA) that uses the
  probabilities the model assigns to neighboring classes to detect unlearned samples.
  We find that existing unlearning methods are vulnerable to CMIA across multiple
  datasets. We then propose a new fine-tuning objective that mitigates this privacy
  leakage by approximating, for forget-class inputs, the distribution over the remaining
  classes that a retrained-from-scratch model would produce. To construct this approximation,
  we estimate inter-class similarity and tilt the target model’s distribution accordingly.
  The resulting Tilted REWeighting (TREW) distribution serves as the desired distribution
  during fine-tuning. We also show that across multiple benchmarks, TREW matches or
  surpasses existing unlearning methods on prior unlearning metrics. More specifically,
  on CIFAR-10, it reduces the gap with retrained models by $19%$ and $46%$ for U-LiRA
  and CMIA scores, accordingly, compared to the SOTA method for each category.'
software: https://github.com/CrowdDynamicsLab/ICML_TREW
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ebrahimpour-boroojeny26a
month: 0
tex_title: 'Unlearning Isn’t Forgetting: Revealing Hidden Leakage in Class Unlearning
  Evaluations'
firstpage: 27569
lastpage: 27593
page: 27569-27593
order: 27569
cycles: false
bibtex_author: Ebrahimpour-Boroojeny, Ali and Wang, Yian and Sundaram, Hari
author:
- given: Ali
  family: Ebrahimpour-Boroojeny
- given: Yian
  family: Wang
- given: Hari
  family: Sundaram
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ebrahimpour-boroojeny26a/ebrahimpour-boroojeny26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
