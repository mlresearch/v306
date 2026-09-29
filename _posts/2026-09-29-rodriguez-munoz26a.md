---
title: 'Ambient Dataloops: Generative Models for Dataset Refinement'
openreview: Li5ki5Dopo
abstract: We propose Ambient Dataloops, an iterative framework for refining datasets
  that makes it easier for diffusion models to learn the underlying data distribution.
  Modern datasets contain samples of highly varying quality, and training directly
  on such heterogeneous data often yields suboptimal models. We propose a dataset-model
  co-evolution process; at each iteration of our method, the dataset becomes progressively
  higher quality, and the model improves accordingly. To avoid destructive self-consuming
  loops, at each generation, we treat the synthetically improved samples as noisy,
  but at a slightly lower noisy level than the previous iteration, and we use Ambient
  Diffusion techniques for learning under corruption. Empirically, Ambient Dataloops
  achieve state-of-the-art performance in unconditional and text-conditional image
  generation and de novo protein design. We further provide a theoretical justification
  for the proposed framework that captures the benefits of the data looping procedure.
software: https://github.com/adrianrm99/ambient_dataloops
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rodriguez-munoz26a
month: 0
tex_title: 'Ambient Dataloops: Generative Models for Dataset Refinement'
firstpage: 105535
lastpage: 105563
page: 105535-105563
order: 105535
cycles: false
bibtex_author: Rodriguez-Munoz, Adrian and Daspit, William and Klivans, Adam and Torralba,
  Antonio and Daskalakis, Constantinos Costis and Daras, Giannis
author:
- given: Adrian
  family: Rodriguez-Munoz
- given: William
  family: Daspit
- given: Adam
  family: Klivans
- given: Antonio
  family: Torralba
- given: Constantinos Costis
  family: Daskalakis
- given: Giannis
  family: Daras
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rodriguez-munoz26a/rodriguez-munoz26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
