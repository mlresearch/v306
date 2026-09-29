---
title: Provably Learning Attention with Queries
openreview: gC04O9t1WJ
abstract: We study the problem of learning Transformer-based sequence models with
  black-box access to their outputs. In this setting, a learner may adaptively query
  the oracle with any sequence of vectors and observe the output of the target function.
  We begin with studying the learnability of the simplest formulation, that is, learning
  a single-head attention-based regressor with queries. We show that for a model with
  width $d$, there is an elementary algorithm to learn the parameters of single-head
  attention with $O(d^2)$ queries. Further, we show that if there exists an algorithm
  to learn ReLU feedforward networks (FFNs), then the single-head algorithm can be
  easily adapted to learn one-layer Transformers with single-head attention. Next,
  we show that, in the common regime where the head dimension $r \ll d$, single-head
  attention-based models can be learned with $O(rd)$ queries via compressed sensing
  arguments. We also study robustness to noisy oracle access, proving that under mild
  norm and margin conditions, the parameters can be estimated to $\varepsilon$ accuracy
  with a polynomial number of queries even when outputs are only provided up to additive
  tolerance. Finally, we consider the learnability of multi-head attention and show
  that they are not identifiable from queries, and hence, learnability in the same
  sense is not feasible without additional assumptions. We discuss potential approaches
  to learn multi-head attention-based models under certain structural assumptions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattamishra26a
month: 0
tex_title: Provably Learning Attention with Queries
firstpage: 7980
lastpage: 7998
page: 7980-7998
order: 7980
cycles: false
bibtex_author: Bhattamishra, Satwik and Shah, Kulin and Hahn, Michael and Kanade,
  Varun
author:
- given: Satwik
  family: Bhattamishra
- given: Kulin
  family: Shah
- given: Michael
  family: Hahn
- given: Varun
  family: Kanade
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/bhattamishra26a/bhattamishra26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
