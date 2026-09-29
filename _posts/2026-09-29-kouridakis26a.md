---
title: Linear Regression with Unknown Truncation Beyond Gaussian Features
openreview: DsV89lJ58l
abstract: 'In truncated linear regression, samples $(x,y)$ are shown only when the
  outcome $y$ falls inside a certain survival set $S^\star$ and the goal is to estimate
  the unknown $d$-dimensional regressor $w^\star$. This problem has a long history
  of study in Statistics and Machine Learning going back to the works of (Galton,
  1897; Tobin, 1958) and more recently in, e.g., (Daskalakis et al., 2019; 2021; Lee
  et al., 2023; 2024). Despite this long history, however, most prior works are limited
  to the special case where $S^\star$ is precisely known. The more practically relevant
  case, where $S^\star$ is unknown and must be learned from data, remains open: indeed,
  here the only available algorithms require strong assumptions on the distribution
  of the feature vectors (e.g., Gaussianity) and, even then, have a $d^{\mathrm{poly}
  (1/\varepsilon)}$ run time for achieving $\varepsilon$ accuracy. In this work, we
  give the first algorithm for truncated linear regression with unknown survival set
  that runs in $\mathrm{poly} (d/\varepsilon)$ time, by only requiring that the feature
  vectors are sub-Gaussian. Our algorithm relies on a novel subroutine for efficiently
  learning unions of a bounded number of intervals using access to positive examples
  (without any negative examples) under a certain smoothness condition. This learning
  guarantee adds to the line of works on positive-only PAC learning and may be of
  independent interest.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kouridakis26a
month: 0
tex_title: Linear Regression with Unknown Truncation Beyond {G}aussian Features
firstpage: 60603
lastpage: 60660
page: 60603-60660
order: 60603
cycles: false
bibtex_author: Kouridakis, Alexandros and Mehrotra, Anay and Kalavasis, Alkis and
  Caramanis, Constantine
author:
- given: Alexandros
  family: Kouridakis
- given: Anay
  family: Mehrotra
- given: Alkis
  family: Kalavasis
- given: Constantine
  family: Caramanis
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/kouridakis26a/kouridakis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
