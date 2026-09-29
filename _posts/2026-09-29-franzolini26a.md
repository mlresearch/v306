---
title: Complexity Bounds for Dirichlet Process Slice Samplers
openreview: c2neBfCuoz
abstract: Slice sampling is a standard Monte Carlo technique for Dirichlet process
  (DP)-based models, widely used in posterior simulation. However, formal assessments
  of the scalability of posterior slice samplers have remained largely unexplored,
  primarily because the computational cost of a slice-sampling iteration is random
  and potentially unbounded. In this work, we obtain high-probability bounds on the
  computational complexity of DP slice samplers. Our main results show that, uniformly
  across posterior cluster-growth regimes, the overhead induced by slice variables,
  relatively to the number of clusters supported by the posterior, is $O_{\mathbb
  P}(\log n)$. As a consequence, even in worst-case configurations, superlinear blow-ups
  in per-iteration computational cost occur with vanishing probability. Our analysis
  applies broadly to DP–based models without any likelihood-specific assumptions,
  still providing complexity guarantees for posterior sampling on arbitrary datasets.
  These results establish a theoretical foundation for assessing the practical scalability
  of slice sampling in DP-based models.
software: https://github.com/beatricefranzolini/DPalg
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: franzolini26a
month: 0
tex_title: Complexity Bounds for {D}irichlet Process Slice Samplers
firstpage: 31553
lastpage: 31574
page: 31553-31574
order: 31553
cycles: false
bibtex_author: Franzolini, Beatrice and Gaffi, Francesco
author:
- given: Beatrice
  family: Franzolini
- given: Francesco
  family: Gaffi
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/franzolini26a/franzolini26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
