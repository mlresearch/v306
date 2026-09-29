---
title: A Sketch-and-Project Analysis of Subsampled Natural Gradient Algorithms
openreview: 2iDtIht7W4
abstract: Subsampled natural gradient descent (SNG) has been used to enable high-precision
  scientific machine learning, but standard analyses based on stochastic preconditioning
  fail to provide insight into realistic small-sample settings. We overcome this limitation
  by instead analyzing SNG as a sketch-and-project method. Motivated by this lens,
  we discard the usual theoretical proxy which decouples gradients and preconditioners
  using two independent mini-batches, and we replace it with a new proxy based on
  squared volume sampling. Under this new proxy the expectation of the SNG direction
  becomes equal to a preconditioned gradient descent step even in the presence of
  coupling, leading to (i) global convergence guarantees when using a single mini-batch
  of any size, and (ii) an explicit characterization of the convergence rate in terms
  of quantities related to the sketch-and-project structure. These findings in turn
  yield new insights into small-sample settings, for example by suggesting that the
  advantage of SNG over SGD is that it can more effectively exploit spectral decay
  in the model Jacobian. We also extend these ideas to explain a popular structured
  momentum scheme for SNG, known as SPRING, by showing that it arises naturally from
  accelerated sketch-and-project methods.
software: https://github.com/ggoldsh/sketch-and-project-natural-gradient
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: goldshlager26a
month: 0
tex_title: A Sketch-and-Project Analysis of Subsampled Natural Gradient Algorithms
firstpage: 35740
lastpage: 35765
page: 35740-35765
order: 35740
cycles: false
bibtex_author: Goldshlager, Gil and Hu, Jiang and Lin, Lin
author:
- given: Gil
  family: Goldshlager
- given: Jiang
  family: Hu
- given: Lin
  family: Lin
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/goldshlager26a/goldshlager26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
