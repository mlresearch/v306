---
title: "$α$-PFN: Fast Entropy Search via In-Context Learning"
openreview: 7Oonij8oLU
abstract: Information-theoretic acquisition functions such as Entropy Search (ES)
  offer a principled exploration–exploitation framework for Bayesian optimization
  (BO). However, their practical implementation relies on complicated and slow approximations,
  i.e., a Monte Carlo estimation of the information gain. This complexity can introduce
  numerical errors and requires specialized, hand-crafted implementations. We propose
  a two-stage amortization strategy that learns to approximate entropy search-based
  acquisition functions using Prior-data Fitted Networks (PFNs) in a single forward
  pass. A first PFN is trained to be conditioned on information about the optima;
  second, the $\alpha$-PFN is trained to predict the expected information gain by
  training on information gains measured with the first PFN. The $\alpha$-PFN offers
  a flexible learned approximation, which replaces the complex heuristic approximations
  with a single forward pass per candidate, enabling rapid and extensible acquisition
  evaluation. Empirically, our approach is competitive with state-of-the-art entropy
  search implementations on synthetic and real-world benchmarks, while accelerating
  the different entropy search variants across all our experiments, with speed ups
  over 50x.
software: https://github.com/automl/AlphaPFN
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rakotoarison26a
month: 0
tex_title: "$α$-{PFN}: Fast Entropy Search via In-Context Learning"
firstpage: 103387
lastpage: 103406
page: 103387-103406
order: 103387
cycles: false
bibtex_author: Rakotoarison, Herilalaina and Adriaensen, Steven and Viering, Tom Julian
  and Hvarfner, Carl and M\"{u}ller, Samuel and Hutter, Frank and Bakshy, Eytan
author:
- given: Herilalaina
  family: Rakotoarison
- given: Steven
  family: Adriaensen
- given: Tom Julian
  family: Viering
- given: Carl
  family: Hvarfner
- given: Samuel
  family: Müller
- given: Frank
  family: Hutter
- given: Eytan
  family: Bakshy
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rakotoarison26a/rakotoarison26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
