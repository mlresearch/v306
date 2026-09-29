---
title: On the Theoretical Limitations of Embedding-based Link Prediction
openreview: MB5Qejqmtw
abstract: Neural networks often map low-dimensional embeddings to high-dimensional
  output spaces. Usually, the output layer is linear, which can create a <em>rank
  bottleneck</em> that limits the functions a model can represent. Such bottlenecks
  are ubiquitous in link prediction models, such as knowledge graph embeddings (KGEs),
  as the output space of entities can be orders of magnitude larger than the embedding
  dimension. We investigate how rank bottlenecks limit model expressivity for fitting
  the training data. While previous work focused on sufficient bounds on the embedding
  dimension required for specific KGEs, we show necessary bounds for <em>all</em>
  KGEs with a linear output layer, which grow with graph size and connectivity. We
  also consider a non-linear output layer using mixtures to break the bottleneck without
  significant parameter overhead. Empirically, we show that models using this non-linear
  layer improve in ranking performance and probabilistic fit for large and dense datasets
  at a low parameter cost, as predicted by our theory. Our work reveals how linear
  output layers limit KGEs and motivates non-linear alternatives for scaling to large
  and dense graphs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: badreddine26a
month: 0
tex_title: On the Theoretical Limitations of Embedding-based Link Prediction
firstpage: 4866
lastpage: 4893
page: 4866-4893
order: 4866
cycles: false
bibtex_author: Badreddine, Samy and Van Krieken, Emile and Serafini, Luciano
author:
- given: Samy
  family: Badreddine
- given: Emile
  family: Van Krieken
- given: Luciano
  family: Serafini
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/badreddine26a/badreddine26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
