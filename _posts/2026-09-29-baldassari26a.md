---
title: Dimension-Free Multimodal Sampling via Preconditioned Annealed Langevin Dynamics
openreview: 3wMM5NEFvr
abstract: 'Designing sampling algorithms for multimodal targets that remain stable
  under refinement of the finite-dimensional approximation of an underlying function-space
  problem is a central challenge. Annealed Langevin dynamics (ALD) is a natural alternative
  to classical Langevin in this context, since it is often observed to improve exploration
  across modes. Yet a gap remains between its empirical success and existing theory:
  under which conditions can ALD be guaranteed to remain stable across dimensions?
  In this paper, we bridge this gap by providing a uniform-in-dimension analysis of
  continuous-time ALD for Gaussian-mixture targets. Along an explicit annealing path
  obtained by gradually removing Gaussian smoothing from the target, we identify spectral
  conditions linking the smoothing covariance to the component covariances under which
  ALD achieves a prescribed accuracy in Kullback-Leibler divergence within a dimension-uniform
  time horizon. We then establish stability in a perturbative regime with imperfect
  initialization and approximate scores. Under a misspecified-mixture score model,
  we show that preconditioning ALD with an operator whose spectrum decays sufficiently
  fast prevents error terms from accumulating across coordinates and thereby preserves
  dimension-uniform control.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: baldassari26a
month: 0
tex_title: Dimension-Free Multimodal Sampling via Preconditioned Annealed {L}angevin
  Dynamics
firstpage: 5811
lastpage: 5848
page: 5811-5848
order: 5811
cycles: false
bibtex_author: Baldassari, Lorenzo and Garnier, Josselin and Solna, Knut and De Hoop,
  Maarten V.
author:
- given: Lorenzo
  family: Baldassari
- given: Josselin
  family: Garnier
- given: Knut
  family: Solna
- given: Maarten V.
  family: De Hoop
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/baldassari26a/baldassari26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
