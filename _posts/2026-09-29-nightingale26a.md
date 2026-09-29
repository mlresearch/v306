---
title: Asymmetric Contrastive Objectives for Efficient Phenotypic Screening
openreview: oQSqJfJUvJ
abstract: Phenotypic screening experiments produce many microscope images of cells
  under diverse perturbations, with biologically significant responses often subtle
  or difficult to identify visually. A central challenge is to extract image representations
  that distinguish activity from controls and group phenotypically similar perturbations.
  In this work we propose new adaptations of contrastive loss functions that incorporate
  experimental metadata as learned class vectors, and a geometrically inspired variant,
  called SPC, where class vectors are confined to the unit sphere and updated only
  by attractive terms (allowing more overlap of phenotypically similar classes). The
  approach is tested on two popular benchmarking datasets, BBBC021 and RxRx3-core;
  and we also evaluate performance on uncurated screens of HaCaT cells to gauge effectiveness
  in a realistic use-case scenario. We find we outperform prior methods across the
  three datasets and on a wide array of metrics measuring phenotype grouping, biological
  recall, drug-target interaction and mechanism-of-action inference. We also show
  we maintain this improved performance compared to models over 10x larger in parameter
  count, and that SPC can be used as an effective fine-tuning technique. The method
  is easy to implement and is well suited to settings with limited data or compute
  resources.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nightingale26a
month: 0
tex_title: Asymmetric Contrastive Objectives for Efficient Phenotypic Screening
firstpage: 93191
lastpage: 93211
page: 93191-93211
order: 93191
cycles: false
bibtex_author: Nightingale, Luke and Tuersley, Joseph and Warchal, Scott and Cairoli,
  Andrea and Howes, Jacob and Shand, Cameron and Powell, Andrew J and Green, Darren
  V.S. and Strange, Amy and Howell, Michael
author:
- given: Luke
  family: Nightingale
- given: Joseph
  family: Tuersley
- given: Scott
  family: Warchal
- given: Andrea
  family: Cairoli
- given: Jacob
  family: Howes
- given: Cameron
  family: Shand
- given: Andrew J
  family: Powell
- given: Darren V.S.
  family: Green
- given: Amy
  family: Strange
- given: Michael
  family: Howell
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/nightingale26a/nightingale26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
