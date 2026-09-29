---
title: How Should Transformers Encode Numeric Values in Electronic Health Records?
openreview: YzlscRoNUj
abstract: How do we encode numeric values in transformer-based sequence processing,
  particularly in electronic health record (EHR) data? We systematically compare discrete,
  continuous, and hybrid value encoding strategies using synthetic arithmetic tasks
  embedded within real-world EHR data, as well as real-world clinical prediction tasks.
  Our study reveals trade-offs between numeric precision, optimisation stability,
  and architectural flexibility. We find that approaches that explicitly model value-concept
  interactions perform best on precision-sensitive arithmetic tasks when architectural
  constraints permit. Hybrid token-based approaches that retain numeric values but
  apply binning prior to projection provide a more robust and broadly applicable alternative,
  with the optimal number of bins following a simple empirically derived power-law
  in dataset size. Across tasks, models consistently exhibit reliable “good enough”
  numeric computation rather than exact arithmetic, while clinical gains from incorporating
  laboratory values are task-dependent. This suggests that robustness and deployability
  often outweigh maximal numeric precision in practice, motivating hybrid token-based
  approaches as a practical default.
software: https://github.com/Montgomeryyyy/BONSAI_values/tree/main
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: montgomery26a
month: 0
tex_title: How Should Transformers Encode Numeric Values in Electronic Health Records?
firstpage: 90118
lastpage: 90133
page: 90118-90133
order: 90118
cycles: false
bibtex_author: Montgomery, Maria Elkj{\ae}r and Igel, Christian and Odgaard, Mikkel
  Fruelund and Sillesen, Martin and Nielsen, Mads
author:
- given: Maria Elkjær
  family: Montgomery
- given: Christian
  family: Igel
- given: Mikkel Fruelund
  family: Odgaard
- given: Martin
  family: Sillesen
- given: Mads
  family: Nielsen
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/montgomery26a/montgomery26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
