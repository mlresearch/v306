---
title: 'Path-conditioned training: a principled way to rescale ReLU neural networks'
openreview: tZwqlXUc6t
abstract: Despite recent algorithmic advances, we still lack principled ways to leverage
  the well-documented rescaling symmetries in ReLU neural network parameters. While
  two properly rescaled weights implement the same function, the training dynamics
  can be dramatically different. To offer a fresh perspective on exploiting this phenomenon,
  we build on the recent path-lifting framework, which provides a compact factorization
  of ReLU networks. We introduce a geometrically motivated criterion to rescale neural
  network parameters which minimization leads to a conditioning strategy that aligns
  a kernel in the path-lifting space with a chosen reference. We derive an efficient
  algorithm to perform this alignment. In the context of random network initialization,
  we analyze how the architecture and the initialization scale jointly impact the
  output of the proposed method. Numerical experiments illustrate its potential to
  speed up training.
software: https://github.com/Artim436/pathcond
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lebeurrier26a
month: 0
tex_title: 'Path-conditioned training: a principled way to rescale {R}e{LU} neural
  networks'
firstpage: 63172
lastpage: 63205
page: 63172-63205
order: 63172
cycles: false
bibtex_author: Lebeurrier, Arthur and Vayer, Titouan and Gribonval, R\'{e}mi
author:
- given: Arthur
  family: Lebeurrier
- given: Titouan
  family: Vayer
- given: Rémi
  family: Gribonval
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/lebeurrier26a/lebeurrier26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
