---
title: Optimal Top-$k$ Identification from Pairwise Comparisons
openreview: xnrxwwAKz5
abstract: 'We study the active learning problem of fixed-confidence top-$k$ identification
  from noisy pairwise comparisons. In this problem, an algorithm sequentially chooses
  pairs of items to compare, observes the outcomes, and stops when it can return the
  set of top-$k$ items with error probability at most $\delta$. The objective is to
  design such a <em>$\delta$-correct</em> procedure that minimizes the expected number
  of comparisons (the sample complexity). This problem falls within the broader literature
  on fixed-confidence pure exploration in bandit models, where a common target is
  asymptotic optimality: the algorithm’s expected sample complexity matches the information
  theoretic lower bound as $\delta \to 0$. Asymptotically optimal procedures have
  been developed for a range of fixed-confidence pure-exploration problems, however
  to the best of our knowledge, for top-$1$, or more generally top-$k$ identification
  from pairwise comparisons under latent utility models an asymptotically optimal
  algorithm has not been established. In this setting, we develop such an algorithm.
  We characterize the structure of the lower bound and formulate it as a saddle-point
  problem. This structure enables a computationally efficient primal–dual procedure
  that learns the asymptotically optimal comparison allocation online. We then construct
  an adaptive comparison-allocation algorithm that tracks the allocation learned by
  the primal–dual procedure and prove it is asymptotically optimal.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: goldberger26a
month: 0
tex_title: Optimal Top-$k$ Identification from Pairwise Comparisons
firstpage: 35572
lastpage: 35599
page: 35572-35599
order: 35572
cycles: false
bibtex_author: Goldberger, Motti and Rudi, Nils
author:
- given: Motti
  family: Goldberger
- given: Nils
  family: Rudi
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/goldberger26a/goldberger26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
