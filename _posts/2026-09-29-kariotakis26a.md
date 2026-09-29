---
title: 'FairRARI: A Plug and Play Framework for Fairness-Aware PageRank'
openreview: Z2axjFEPH3
abstract: PageRank (PR) is a fundamental algorithm in graph machine learning tasks.
  Owing to the increasing importance of algorithmic fairness, we consider the problem
  of computing PR vectors subject to various group-fairness criteria based on sensitive
  attributes of the vertices. At present, principled algorithms for this problem are
  lacking - some cannot guarantee that a target fairness level is achieved, while
  others do not feature optimality guarantees. In order to overcome these shortcomings,
  we put forth a unified in-processing convex optimization framework, termed FairRARI,
  for tackling different group-fairness criteria in a “plug and play” fashion. Leveraging
  a variational formulation of PR, the framework computes fair PR vectors by solving
  a strongly convex optimization problem with fairness constraints, thereby ensuring
  that a target fairness level is achieved. We further introduce three different fairness
  criteria which can be efficiently tackled using FairRARI to compute fair PR vectors
  with the same asymptotic time-complexity as the original PR algorithm. Extensive
  experiments on real-world datasets showcase that FairRARI outperforms existing methods
  in terms of utility, while achieving the desired fairness levels across multiple
  vertex groups; thereby highlighting its effectiveness.
software: https://github.com/ekariotakis/FairRARI
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kariotakis26a
month: 0
tex_title: "{F}air{RARI}: A Plug and Play Framework for Fairness-Aware {P}age{R}ank"
firstpage: 56075
lastpage: 56110
page: 56075-56110
order: 56075
cycles: false
bibtex_author: Kariotakis, Emmanouil and Konar, Aritra
author:
- given: Emmanouil
  family: Kariotakis
- given: Aritra
  family: Konar
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/kariotakis26a/kariotakis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
