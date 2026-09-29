---
title: Multicalibration Yields Better Matchings
openreview: G1bzbJtcHD
abstract: Consider the problem of finding the best matching in a weighted graph where
  we only have access to predictions of the actual stochastic weights, based on an
  underlying context. If the predictor is the Bayes optimal one, then computing the
  best matching based on the predicted weights is optimal. However, in practice, this
  perfect information scenario is not realistic. Given an imperfect predictor, a suboptimal
  decision rule may compensate for the induced error and thus outperform the standard
  optimal rule. In this paper, we propose multicalibration as a way to address this
  problem. This fairness notion requires a predictor to be unbiased on each element
  of a family of protected sets of contexts. Given a class of matching algorithms
  $\mathcal C$ and any predictor $\gamma$ of the edge-weights, we show how to construct
  a specific multicalibrated predictor $\hat \gamma$, with the following property.
  Picking the best matching based on the output of $\hat \gamma$ is competitive with
  the best decision rule in $\mathcal C$ applied onto the original predictor $\gamma$.
  We complement this result by providing sample complexity bounds, and by performing
  numerical experiments.
software: https://github.com/facebookresearch/multicalibration_for_matching
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: colini-baldeschi26a
month: 0
tex_title: Multicalibration Yields Better Matchings
firstpage: 21230
lastpage: 21240
page: 21230-21240
order: 21230
cycles: false
bibtex_author: Colini Baldeschi, Riccardo and Gregorio, Simone Di and Fioravanti,
  Simone and Fusco, Federico and Guy, Ido and Haimovich, Daniel and Leonardi, Stefano
  and Linder, Fridolin and Perini, Lorenzo and Russo, Matteo and Sirin, Cem and Tax,
  Niek
author:
- given: Riccardo
  family: Colini Baldeschi
- given: Simone Di
  family: Gregorio
- given: Simone
  family: Fioravanti
- given: Federico
  family: Fusco
- given: Ido
  family: Guy
- given: Daniel
  family: Haimovich
- given: Stefano
  family: Leonardi
- given: Fridolin
  family: Linder
- given: Lorenzo
  family: Perini
- given: Matteo
  family: Russo
- given: Cem
  family: Sirin
- given: Niek
  family: Tax
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/colini-baldeschi26a/colini-baldeschi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
