---
title: 'Flat Minima and Generalization: Insights from Stochastic Convex Optimization'
openreview: u6zp8zZ8Ou
abstract: Understanding the generalization behavior of learning algorithms is a central
  goal of learning theory. A recently emerging explanation is that learning algorithms
  are successful in practice because they converge to flat minima, which have been
  consistently associated with improved generalization performance. In this work,
  we study the link between flat minima and generalization in the canonical setting
  of stochastic convex optimization with a non-negative, $\beta$-smooth objective.
  Our first finding is that, even in this fundamental setting, flat empirical minima
  may incur trivial $\Omega(1)$ population risk while sharp minima generalizes optimally.
  We then demonstrate that this phenomenon extends to sharpness-aware algorithms introduced
  by Foret et al. (2021), namely Sharpness-Aware Gradient Descent (SA-GD) and Sharpness-Aware
  Minimization (SAM). For SA-GD we prove that it successfully converges to a flat
  minimum at a fast rate, but the population risk of the solution can still be as
  large as $\Omega(1)$. For SAM we show that although it minimizes the empirical loss,
  it may converge to a sharp minimum and also incur population risk $\Omega(1)$. Finally,
  we establish population risk upper bounds for both SA-GD and SAM using algorithmic
  stability techniques.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schliserman26a
month: 0
tex_title: 'Flat Minima and Generalization: Insights from Stochastic Convex Optimization'
firstpage: 108218
lastpage: 108245
page: 108218-108245
order: 108218
cycles: false
bibtex_author: Schliserman, Matan and Vansover-Hager, Shira and Koren, Tomer
author:
- given: Matan
  family: Schliserman
- given: Shira
  family: Vansover-Hager
- given: Tomer
  family: Koren
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/schliserman26a/schliserman26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
