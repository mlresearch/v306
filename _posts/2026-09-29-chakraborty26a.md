---
title: Probabilistically-routed Bayesian Additive Spanning Trees for Learning on Constrained
  Domains
openreview: aCZY76ltpg
abstract: Bayesian additive spanning tree (BAST) is an useful tool for interpretable,
  non-parametric regression on complex constrained domains. It improves upon the performance
  of Bayesian additive regression trees (BART) by replacing axis-aligned splits through
  binary tree components by cuts on a spanning tree components, enabling the formation
  of contiguous splits that respect the underlying complex structure. While BAST is
  effective for learning on constrained spaces, it still relies on hard partitions,
  albeit on spanning trees, which limits its ability to represent smoothly varying
  functions on constrained domains. We propose Probabilistically-routed Bayesian additive
  spanning trees (PR-BAST), a principled relaxation that replaces hard cuts on spanning
  tree components with probabilistic routing along spanning tree components. PR-BAST
  represents the regression surface as an additive ensemble of such spanning tree-aligned
  smooth components. Conditional on a fixed spanning tree, each component in PR-BAST
  induces a Gaussian random field with a sparse, tree-structured precision matrix,
  enabling scalable posterior computation via sparse linear algebra. We theoretically
  establish that PR-BAST yields strictly faster posterior contraction rates compared
  to BAST under graph-smooth truth. Experiments on synthetic and real datasets demonstrate
  that PR-BAST consistently improves accuracy over BAST and other baselines, while
  retaining the interpretability of tree-based models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26a
month: 0
tex_title: Probabilistically-routed {B}ayesian Additive Spanning Trees for Learning
  on Constrained Domains
firstpage: 12435
lastpage: 12459
page: 12435-12459
order: 12435
cycles: false
bibtex_author: Chakraborty, Abhisek and Mandal, Abhishek and Chakraborty, Anirban
author:
- given: Abhisek
  family: Chakraborty
- given: Abhishek
  family: Mandal
- given: Anirban
  family: Chakraborty
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/chakraborty26a/chakraborty26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
