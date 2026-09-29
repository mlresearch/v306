---
title: Adversarially Robust Approximate Furthest Neighbor
openreview: E0wwKfaTE0
abstract: We work in the adaptive query model, where one is given a point set $P \subset
  \mathbb{R}^d$ and seeks to construct a data structure that can answer correctly
  and efficiently a sequence of adaptive queries. In this model, an adversary observes
  the answers returned by the data structure to previous queries $q_1, \ldots, q_{i-1}$
  and, based on this information, chooses the next query point $q_i$. This setting
  captures strong forms of adaptivity that naturally arise in modern machine learning
  pipelines, and rules out many classical randomized techniques that assume oblivious
  queries. Our focus is the problem of furthest neighbor search in this adaptive setting,
  a fundamental problem in several learning tasks, including diversity maximization,
  outlier and anomaly detection, adversarial example generation, and more. We present
  the first adversarially robust data structure for $c$-approximate furthest neighbor
  queries that achieves query time $\tilde{O}( \min( d n^{1/c^2}, n^{2/c^2} + d))$.
  This matches the $n$ dependency in the query time of the seminal result by Indyk
  [SODA’03] for $c$-approximate furthest neighbor in the oblivious setting, and improves
  upon the $\tilde{O}(n + d)$ query time achieved via the adaptive distance estimation
  framework of Cherapanamjeri and Nelson [NeurIPS’20] for a wide range of natural
  parameters. To complement this result, we present an adversarial attack against
  oblivious approximate furthest neighbor algorithms. Specifically, we show that the
  data structure from the algorithm by Indyk fails to maintain its guarantees against
  adaptive queries.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: banihashem26b
month: 0
tex_title: Adversarially Robust Approximate Furthest Neighbor
firstpage: 6281
lastpage: 6297
page: 6281-6297
order: 6281
cycles: false
bibtex_author: Banihashem, Kiarash and Giliberti, Jeff and Gokhale, Prashant and Goudarzi,
  Samira and Hajiaghayi, Mohammadtaghi and Liu, Yuhao and Monemizadeh, Morteza and
  Silwal, Sandeep
author:
- given: Kiarash
  family: Banihashem
- given: Jeff
  family: Giliberti
- given: Prashant
  family: Gokhale
- given: Samira
  family: Goudarzi
- given: Mohammadtaghi
  family: Hajiaghayi
- given: Yuhao
  family: Liu
- given: Morteza
  family: Monemizadeh
- given: Sandeep
  family: Silwal
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/banihashem26b/banihashem26b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
