---
title: Provable Accuracy Collapse in Embedding-Based Representations under Dimensionality
  Mismatch
openreview: ubzXPEfa4R
abstract: 'Embedding-based representations in Euclidean space $\mathbb{R}^d$ are a
  cornerstone of modern machine learning, where a major goal is to use the <em>smallest
  dimension</em> that faithfully captures data relations. In this work, we prove sharp
  dimension–accuracy tradeoffs and identify a fundamental information-theoretic limitation:
  unless the embedding dimension $d$ is chosen close to the ground-truth dimension
  $D$, accuracy undergoes a sudden collapse. Our main result shows that this phenomenon
  arises even in standard contrastive learning settings, where supervision is limited
  to a set of $m$ anchor–positive–negative triplets $(i,j,k)$ encoding distance comparisons
  $\mathrm{dist}(i,j) < \mathrm{dist}(i,k)$. Specifically, given triplets realizable
  by an unknown ground-truth embedding in $D$ dimensions, we prove that there exists
  constant $c < 1$, such that <em>every embedding of dimension at most $cD$ violates
  almost half of the triplets</em>, yielding accuracy as low as a trivial one-dimensional
  solution that ignores the input. We complement our information-theoretic bounds
  with strong computational hardness results: under the Unique Games Conjecture, even
  if the given triplets are nearly realizable in $D=1$ dimension, no polynomial-time
  algorithm—<em>regardless of its dimension</em>—can achieve accuracy above the trivial
  50% baseline.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: arvanitakis26a
month: 0
tex_title: Provable Accuracy Collapse in Embedding-Based Representations under Dimensionality
  Mismatch
firstpage: 3891
lastpage: 3904
page: 3891-3904
order: 3891
cycles: false
bibtex_author: Arvanitakis, Dionysis and Chatziafratis, Vaggos and Luo, Yiyuan
author:
- given: Dionysis
  family: Arvanitakis
- given: Vaggos
  family: Chatziafratis
- given: Yiyuan
  family: Luo
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/arvanitakis26a/arvanitakis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
