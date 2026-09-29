---
title: Privately Fine-Tuned LLMs Preserve Temporal Dynamics in Tabular Data
openreview: hZJAUJ5l9t
abstract: Research on differentially private synthetic tabular data has largely focused
  on independent and identically distributed rows where each record corresponds to
  a unique individual. This perspective neglects the temporal complexity in longitudinal
  datasets, such as electronic health records, where a user contributes an entire
  (sub) table of sequential events. While practitioners might attempt to model such
  data by flattening user histories into high-dimensional vectors for use with standard
  marginal-based mechanisms, we demonstrate that this strategy is insufficient. Flattening
  fails to preserve temporal coherence even when it maintains valid marginal distributions.
  We introduce PATH, a novel generative framework that treats the full table as the
  unit of synthesis and leverages the autoregressive capabilities of privately fine-tuned
  large language models. Extensive evaluations show that PATH effectively captures
  long-range dependencies that traditional methods miss. Empirically, our method reduces
  the distributional distance to real trajectories by over 60% and reduces state transition
  errors by nearly 50% compared to leading marginal mechanisms while achieving similar
  marginal fidelity.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rosenblatt26a
month: 0
tex_title: Privately Fine-Tuned {LLM}s Preserve Temporal Dynamics in Tabular Data
firstpage: 105673
lastpage: 105717
page: 105673-105717
order: 105673
cycles: false
bibtex_author: Rosenblatt, Lucas and Liu, Peihan and Mckenna, Ryan and Ponomareva,
  Natalia
author:
- given: Lucas
  family: Rosenblatt
- given: Peihan
  family: Liu
- given: Ryan
  family: Mckenna
- given: Natalia
  family: Ponomareva
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rosenblatt26a/rosenblatt26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
