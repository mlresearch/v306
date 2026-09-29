---
title: 'DP-KFC: Data-Free Preconditioning for Privacy-Preserving Deep Learning'
openreview: Z6HxJqAzbp
abstract: 'Differentially private optimization suffers from a fundamental geometric
  mismatch: deep networks have highly anisotropic loss landscapes, yet DP-SGD injects
  isotropic noise. Second-order preconditioning can resolve this, but estimating curvature
  typically requires private data (consuming privacy budget) or public data (introducing
  distribution shift). We show that the Fisher Information Matrix decouples into <em>architectural
  sensitivity</em>, recoverable via synthetic noise, and <em>input correlations</em>,
  approximable from modality-specific frequency statistics. We propose DP-KFC, which
  constructs KFAC preconditioners by probing networks with structured synthetic noise,
  requiring neither private nor public data. Empirically, DP-KFC consistently outperforms
  DP-SGD and adaptive baselines across diverse modalities in strong privacy regimes
  ($\varepsilon \leq 3$). DP-KFC matches private-data preconditioners while public-data
  variants degrade by up to $4.8$ %, showing that curvature can be estimated without
  consuming privacy budget or introducing distribution shift. This enables privacy-preserving
  learning in specialized domains (e.g., medical applications) where regulatory constraints
  make data scarce.'
software: https://github.com/molinamarcvdb/DP-KFC
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-den-bosch26a
month: 0
tex_title: "{DP}-{KFC}: Data-Free Preconditioning for Privacy-Preserving Deep Learning"
firstpage: 123383
lastpage: 123415
page: 123383-123415
order: 123383
cycles: false
bibtex_author: Van Den Bosch, Marc Molina and Taiello, Riccardo and Aillet, Albert
  Sund and Protani, Andrea and Gonzalez Ballester, Miguel Angel and Serio, Luigi
author:
- given: Marc Molina
  family: Van Den Bosch
- given: Riccardo
  family: Taiello
- given: Albert Sund
  family: Aillet
- given: Andrea
  family: Protani
- given: Miguel Angel
  family: Gonzalez Ballester
- given: Luigi
  family: Serio
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/van-den-bosch26a/van-den-bosch26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
