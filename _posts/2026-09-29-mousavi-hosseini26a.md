---
title: 'Post-Training with Policy Gradients: Optimality and the Base Model Barrier'
openreview: nnWlTi7A7a
abstract: We study post-training linear autoregressive models with outcome and process
  rewards. Given a context $x$, the model must predict the response $y \in \mathcal{Y}^N$,
  a sequence of length $N$ that satisfies a $\gamma$ margin condition, an extension
  of the standard separability to sequences. We prove that on test samples where the
  base model achieves a non-trivial likelihood $\alpha$, a variant of policy gradient
  (PG) can achieve likelihood $1 - \varepsilon$ with an essentially minimax optimal
  number of reward queries $\tilde{\mathcal{O}}((\alpha^{-1} + \varepsilon^{-1})/\gamma^2)$.
  However, a barrier arises for going beyond the support of the base model. We prove
  that the overall expected error after post-training with outcome rewards is governed
  by a property of the base model called the <em>Likelihood Quantile</em> (LQ), and
  that variants of PG, while minimax optimal, may require a number of reward queries
  exponential in $N$ to go beyond this support, regardless of the pre-training algorithm.
  To overcome this barrier, we study post-training with a process reward model, and
  demonstrate how PG variants in this setting avoid the curse of dimensionality in
  $N$ via dependence on a token-level LQ. Along the way, we prove that under the margin
  condition, SGD with adaptive learning rate (LR) achieves a near optimal test error
  for statistical learning, and PG with adaptive LR achieves a near optimal number
  of mistakes for online learning while being computationally efficient whenever possible,
  both of which may be of independent interest.
software: https://github.com/mousavih/rlvr-base-model-barrier
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mousavi-hosseini26a
month: 0
tex_title: 'Post-Training with Policy Gradients: Optimality and the Base Model Barrier'
firstpage: 90680
lastpage: 90713
page: 90680-90713
order: 90680
cycles: false
bibtex_author: Mousavi-Hosseini, Alireza and Erdogdu, Murat A
author:
- given: Alireza
  family: Mousavi-Hosseini
- given: Murat A
  family: Erdogdu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/mousavi-hosseini26a/mousavi-hosseini26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
