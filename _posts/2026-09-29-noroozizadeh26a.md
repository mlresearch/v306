---
title: Deep sequence models tend to memorize geometrically; it is unclear why
openreview: CT2tSmahVQ
abstract: 'Deep sequence models are said to store atomic facts predominantly in the
  form of <em>associative</em> memory: a brute-force lookup of co-occurring entities.
  We identify a dramatically different form of storage of atomic facts that we term
  as <em>geometric</em> memory. Here, the model has synthesized embeddings encoding
  novel <em>global</em> relationships between all entities, including ones that do
  not co-occur in training. Such storage is powerful: for instance, we show how it
  transforms a hard reasoning task involving an $\ell$-fold composition into an easy-to-learn
  $1$-step navigation task. From this phenomenon, we extract fundamental aspects of
  neural embedding geometries that are hard to explain. We argue that the rise of
  such a geometry, as against a lookup of local associations, cannot be straightforwardly
  attributed to typical supervisory, architectural, or optimizational pressures. Counterintuitively,
  a geometry is learned even when it is more complex than the brute-force lookup.
  Then, by analyzing a connection to Node2Vec, we demonstrate how the geometry stems
  from a spectral bias that—in contrast to prevailing theories—indeed arises naturally
  despite the lack of various pressures. This analysis also points out to practitioners
  a visible headroom to make Transformer memory more strongly geometric. We hope the
  geometric view of parametric memory encourages revisiting the default intuitions
  that guide researchers in areas like knowledge acquisition, capacity, discovery,
  and unlearning.'
software: https://github.com/shahriarnz14/Geometric_Memory
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: noroozizadeh26a
month: 0
tex_title: Deep sequence models tend to memorize geometrically; it is unclear why
firstpage: 93801
lastpage: 93862
page: 93801-93862
order: 93801
cycles: false
bibtex_author: Noroozizadeh, Shahriar and Nagarajan, Vaishnavh and Rosenfeld, Elan
  and Kumar, Sanjiv
author:
- given: Shahriar
  family: Noroozizadeh
- given: Vaishnavh
  family: Nagarajan
- given: Elan
  family: Rosenfeld
- given: Sanjiv
  family: Kumar
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/noroozizadeh26a/noroozizadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
