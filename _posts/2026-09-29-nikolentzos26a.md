---
title: 'InvGNN: Learning Invertible Node Representations on Graphs'
openreview: okKDijCwRn
abstract: Over the past decade, Graph Neural Networks (GNNs) have become a standard
  tool for solving machine learning problems on graphs. While many aspects of GNNs
  have been studied in depth, including their efficiency and expressive power, the
  invertibility of these models has remained largely unexplored. Standard aggregation
  functions, such as the mean, max and sum operators, are not invertible, which limits
  their applicability in tasks requiring invertible transformations. In this work,
  we introduce an invertible GNN layer. By stacking multiple such layers, we construct
  fully invertible GNN models, which we refer to as InvGNNs. These models inherit
  the benefits of invertible neural networks, including low memory usage for deep
  architectures, exact likelihood computation, and generative modeling capabilities.
  We demonstrate that InvGNNs can match the expressive power of the 1-dimensional
  Weisfeiler-Leman algorithm, showing that invertibility does not compromise model
  expressiveness. On standard graph classification benchmarks, our model performs
  comparably to other well-established GNNs. Beyond classification, we demonstrate
  the potential of invertible layers through density estimation tasks, including outlier
  detection and node feature generation.
software: https://github.com/giannisnik/invgnn
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nikolentzos26a
month: 0
tex_title: "{I}nv{GNN}: Learning Invertible Node Representations on Graphs"
firstpage: 93262
lastpage: 93282
page: 93262-93282
order: 93262
cycles: false
bibtex_author: Nikolentzos, Giannis and Kelesis, Dimitrios and Nakis, Nikolaos
author:
- given: Giannis
  family: Nikolentzos
- given: Dimitrios
  family: Kelesis
- given: Nikolaos
  family: Nakis
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/nikolentzos26a/nikolentzos26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
