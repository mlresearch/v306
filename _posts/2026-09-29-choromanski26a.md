---
title: Computationally-efficient Graph Modeling with Refined Graph Random Features
openreview: NvJPE1oiKd
abstract: We propose <em>refined GRFs</em> (GRFs++), a new class of <em>Graph Random
  Features</em> (GRFs) for efficient and accurate computations involving kernels defined
  on the nodes of a graph. GRFs++ resolve some of the long-standing limitations of
  regular GRFs, including difficulty modeling relationships between more distant nodes.
  They reduce dependence on sampling long graph random walks via a novel <em>walk-stitching</em>
  technique, concatenating several shorter walks without breaking unbiasedness. By
  applying these techniques, GRFs++ inherit the approximation quality provided by
  longer walks but with greater efficiency, trading sequential inefficient sampling
  of a long walk for parallel computation of short walks and matrix-matrix multiplication.
  Furthermore, GRFs++ extend the simplistic GRFs walk termination mechanism (Bernoulli
  schemes with fixed halting probabilities) to a broader class of strategies, applying
  general distributions on the walks’ lengths. This improves approximation accuracy
  of graph kernels, without incurring extra computational cost. We provide empirical
  evaluations to showcase our claims and complement our results with theoretical analysis.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: choromanski26a
month: 0
tex_title: Computationally-efficient Graph Modeling with Refined Graph Random Features
firstpage: 20494
lastpage: 20516
page: 20494-20516
order: 20494
cycles: false
bibtex_author: Choromanski, Krzysztof Marcin and Dubey, Kumar Avinava and Sehanobish,
  Arijit and Reid, Isaac
author:
- given: Krzysztof Marcin
  family: Choromanski
- given: Kumar Avinava
  family: Dubey
- given: Arijit
  family: Sehanobish
- given: Isaac
  family: Reid
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/choromanski26a/choromanski26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
