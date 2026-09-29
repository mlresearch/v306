---
title: Protein Language Model Embeddings Improve Generalization of Implicit Transfer
  Operators
openreview: gRzdGEtn3T
abstract: Molecular dynamics (MD) is a central computational tool in physics, chemistry,
  and biology, enabling quantitative prediction of experimental observables as expectations
  over high-dimensional molecular distributions such as Boltzmann distributions and
  transition densities. However, conventional MD is fundamentally limited by the high
  computational cost required to generate independent samples. Generative molecular
  dynamics (GenMD) has recently emerged as an alternative, learning surrogates of
  molecular distributions either from data or through interaction with energy models.
  While these methods enable efficient sampling, their transferability across molecular
  systems is often limited. In this work, we show that incorporating auxiliary sources
  of information can improve the data efficiency and generalization of transferable
  implicit transfer operators (TITO) for molecular dynamics. We find that coarse-grained
  TITO models are substantially more data-efficient than Boltzmann Emulators, and
  that incorporating protein language model (pLM) embeddings further improves out-of-distribution
  generalization. Our approach, PLaTITO, achieves state-of-the-art performance on
  equilibrium sampling benchmarks for out-of-distribution protein systems, including
  fast-folding proteins. We further study the impact of additional conditioning signals
  such as structural embeddings, temperature, and large-language-model-derived embeddings
  on model performance.
software: https://github.com/PanosAntoniadis/platito
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: antoniadis26a
month: 0
tex_title: Protein Language Model Embeddings Improve Generalization of Implicit Transfer
  Operators
firstpage: 2987
lastpage: 3015
page: 2987-3015
order: 2987
cycles: false
bibtex_author: Antoniadis, Panagiotis and Pavesi, Beatrice and Olsson, Simon and Winther,
  Ole
author:
- given: Panagiotis
  family: Antoniadis
- given: Beatrice
  family: Pavesi
- given: Simon
  family: Olsson
- given: Ole
  family: Winther
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/antoniadis26a/antoniadis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
