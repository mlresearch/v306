---
title: Active Learning with Low-Rank Structure for Data Selection
openreview: i2SGjD0kIj
abstract: In the data selection problem, the objective is to choose a small, representative
  subset of data that can be used to efficiently train a machine learning model. Sener
  and Savarese [ICLR 2018] showed that, given an embedding representation of the data
  and suitable geometric assumptions, heuristics based on $k$-center clustering can
  be used to perform data selection. This perspective was further explored by Axiotis
  et. al. [ICML 2024], who proposed a data selection approach based on $k$-means clustering
  and sensitivity sampling. However, these methods rely on the assumption that the
  dataset exhibits intrinsic geometric structure that can be effectively captured
  by clustering, whereas many modern datasets instead possess global algebraic structure
  that is better exploited by low-rank approximation or principal component analysis.
  In this paper, we introduce a new data selection framework based on low-rank approximation
  and residual-based sampling, formulated through the lens of row subset selection
  and loss-preserving coreset construction. Given an embedding representation of the
  data satisfying mild regularity conditions, which can be interpreted as algebraic
  or angular notions of Lipschitz continuity, we show that it is possible to select
  a weighted subset of $\tilde{O}\left(k + \frac{1}{\varepsilon^2}\right)$ data points
  whose average loss approximates the average loss over the full dataset within a
  $(1+\varepsilon)$ relative error, up to an additive $\varepsilon \Phi_k$ term, where
  $\Phi_k$ denotes the optimal rank-$k$ approximation cost of the embedding matrix.
  We complement these theoretical guarantees with empirical evaluations, demonstrating
  that on a range of real-world datasets, our data selection approach achieves improved
  performance over prior strategies based on uniform sampling or clustering-based
  sensitivity sampling.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-addad26a
month: 0
tex_title: Active Learning with Low-Rank Structure for Data Selection
firstpage: 21154
lastpage: 21175
page: 21154-21175
order: 21154
cycles: false
bibtex_author: Cohen-Addad, Vincent and Kunapuli, Sasidhar and Mirrokni, Vahab and
  Nikdan, Mahdi and Woodruff, David and Zhou, Samson
author:
- given: Vincent
  family: Cohen-Addad
- given: Sasidhar
  family: Kunapuli
- given: Vahab
  family: Mirrokni
- given: Mahdi
  family: Nikdan
- given: David
  family: Woodruff
- given: Samson
  family: Zhou
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/cohen-addad26a/cohen-addad26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
