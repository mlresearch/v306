---
title: 'PluRel: Synthetic Data unlocks Scaling Laws for Relational Foundation Models'
openreview: rM9r9qyRSA
abstract: 'Relational Foundation Models (RFMs) facilitate data-driven decision-making
  by learning from complex multi-table databases. However, the diverse relational
  databases needed to train such models are rarely public due to privacy constraints.
  While there are methods to generate synthetic tabular data of arbitrary size, incorporating
  schema structure and primary–foreign key connectivity for multi-table generation
  remains challenging. Here we introduce PluRel, a framework to synthesize multi-tabular
  relational databases from scratch. In a step-by-step fashion, PluRel models (1)
  schemas with directed graphs, (2) inter-table primary-foreign key connectivity with
  bipartite graphs, and, (3) feature distributions in tables via conditional causal
  mechanisms. The design space across these stages supports the synthesis of a wide
  range of diverse databases, while being computationally lightweight. Using PluRel,
  we observe for the first time that (1) RFM pretraining loss exhibits power-law scaling
  with the number of synthetic databases and total pretraining tokens, (2) scaling
  the number of synthetic databases improves generalization to real databases, and
  (3) synthetic pretraining yields strong base models for continued pretraining on
  real databases. Overall, our framework and results position synthetic data scaling
  as a promising paradigm for RFMs. Webpage: https://star-project.stanford.edu/plurel'
software: https://github.com/stanford-star/plurel
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kothapalli26a
month: 0
tex_title: "{P}lu{R}el: Synthetic Data unlocks Scaling Laws for Relational Foundation
  Models"
firstpage: 60430
lastpage: 60446
page: 60430-60446
order: 60430
cycles: false
bibtex_author: Kothapalli, Vignesh and Ranjan, Rishabh and Hudovernik, Valter and
  Dwivedi, Vijay Prakash and Hoffart, Johannes and Guestrin, Carlos and Leskovec,
  Jure
author:
- given: Vignesh
  family: Kothapalli
- given: Rishabh
  family: Ranjan
- given: Valter
  family: Hudovernik
- given: Vijay Prakash
  family: Dwivedi
- given: Johannes
  family: Hoffart
- given: Carlos
  family: Guestrin
- given: Jure
  family: Leskovec
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/kothapalli26a/kothapalli26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
