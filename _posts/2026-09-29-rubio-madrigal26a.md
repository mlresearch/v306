---
title: Fixed Aggregation Features Can Rival GNNs
openreview: gSZhNPp103
abstract: Graph neural networks (GNNs) are widely believed to excel at node representation
  learning through trainable neighborhood aggregations. We challenge this view by
  introducing Fixed Aggregation Features (FAFs), a training-free approach that transforms
  graph learning tasks into tabular problems. This simple shift enables the use of
  well-established tabular methods, offering strong interpretability and the flexibility
  to deploy diverse classifiers. Across 14 benchmarks, well-tuned multilayer perceptrons
  trained on FAFs rival or outperform state-of-the-art GNNs and graph transformers
  on 12 tasks—often using only mean aggregation. The only exceptions are the Roman
  Empire and Minesweeper datasets, which typically require unusually deep GNNs. To
  explain the theoretical possibility of non-trainable aggregations, we connect our
  findings to Kolmogorov–Arnold representations and discuss when mean aggregation
  can be sufficient. In conclusion, our results call for (i) richer benchmarks benefiting
  from learning diverse neighborhood aggregations, (ii) strong tabular baselines as
  standard, and (iii) employing and advancing tabular models for graph data to gain
  new insights into related tasks.
software: https://github.com/celrm/fixed-aggregation-features
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rubio-madrigal26a
month: 0
tex_title: Fixed Aggregation Features Can Rival {GNN}s
firstpage: 106135
lastpage: 106164
page: 106135-106164
order: 106135
cycles: false
bibtex_author: Rubio-Madrigal, Celia and Burkholz, Rebekka
author:
- given: Celia
  family: Rubio-Madrigal
- given: Rebekka
  family: Burkholz
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rubio-madrigal26a/rubio-madrigal26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
