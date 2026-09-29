---
title: Adaptive Memory Retention in Dynamic Graphs
openreview: x7NGYPNlgs
abstract: Modeling graphs demands a careful balance between long-range propagation
  of information across nodes and the controlled dissipation of noisy or redundant
  signals to ensure stable learning and generalization. This challenge is exacerbated
  in dynamic graphs, where structural and temporal information interact, leading to
  uncontrolled information accumulation and amplifying noise, thereby affecting generalization.
  We introduce LAMP, a dynamic graph model for snapshot-based dynamic graphs that
  incorporates adaptive, learned dissipation within a principled dynamical systems
  framework. Our architecture combines impulsive neural ODEs with an antisymmetric
  parameterization to model conservative information flow, alongside data-driven dissipative
  dynamics that regulate information retention over space and time. This formulation
  yields stable yet expressive representations and enables effective long-range dependency
  modeling while avoiding pathological information buildup. We provide a theoretical
  analysis establishing stability guarantees and characterizing the representational
  power. Extensive experiments on synthetic and real-world benchmarks demonstrate
  state-of-the-art performance, particularly on tasks requiring extended-range dependency
  modeling.
software: https://github.com/FabriDeCastelli/LAMP
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: de-castelli26a
month: 0
tex_title: Adaptive Memory Retention in Dynamic Graphs
firstpage: 23292
lastpage: 23315
page: 23292-23315
order: 23292
cycles: false
bibtex_author: De Castelli, Fabrizio and Gravina, Alessio and Eliasof, Moshe and Sch\"{o}nlieb,
  Carola-Bibiane and Bacciu, Davide
author:
- given: Fabrizio
  family: De Castelli
- given: Alessio
  family: Gravina
- given: Moshe
  family: Eliasof
- given: Carola-Bibiane
  family: Schönlieb
- given: Davide
  family: Bacciu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/de-castelli26a/de-castelli26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
