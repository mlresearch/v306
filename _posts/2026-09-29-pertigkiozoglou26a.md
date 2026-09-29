---
title: 'Recurrent Equivariant Constraint Modulation: Learning Per-Layer Symmetry Relaxation
  from Data'
openreview: STeISpzNSd
abstract: Equivariant neural networks exploit underlying task symmetries to improve
  generalization, but strict equivariance constraints can induce more complex optimization
  dynamics that can hinder learning. Prior work addresses these limitations by relaxing
  strict equivariance during training, but typically relies on prespecified, explicit,
  or implicit target levels of relaxation for each network layer, which are task-dependent
  and costly to tune. We propose Recurrent Equivariant Constraint Modulation (RECM),
  a layer-wise constraint modulation mechanism that learns appropriate relaxation
  levels solely from the training signal and the symmetry properties of each layer’s
  input-target distribution, without requiring any prior knowledge about the task-dependent
  target relaxation level. We demonstrate that under the proposed RECM update, the
  relaxation level of each layer provably converges to a value upper-bounded by its
  symmetry gap, namely the degree to which its input-target distribution deviates
  from exact symmetry. Consequently, layers processing symmetric distributions recover
  full equivariance, while those with approximate symmetries retain sufficient flexibility
  to learn non-symmetric solutions when warranted by the data. Empirically, RECM outperforms
  prior methods across diverse exact and approximate equivariant tasks, including
  the challenging molecular conformer generation on the GEOM-Drugs dataset.
software: https://github.com/StefanosPert/Recurrent_Constraint_Modulation
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pertigkiozoglou26a
month: 0
tex_title: 'Recurrent Equivariant Constraint Modulation: Learning Per-Layer Symmetry
  Relaxation from Data'
firstpage: 98322
lastpage: 98341
page: 98322-98341
order: 98322
cycles: false
bibtex_author: Pertigkiozoglou, Stefanos and Petrache, Mircea and Trivedi, Shubhendu
  and Daniilidis, Kostas
author:
- given: Stefanos
  family: Pertigkiozoglou
- given: Mircea
  family: Petrache
- given: Shubhendu
  family: Trivedi
- given: Kostas
  family: Daniilidis
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/pertigkiozoglou26a/pertigkiozoglou26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
