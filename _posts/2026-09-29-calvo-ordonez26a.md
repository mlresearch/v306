---
title: Richer Bayesian Last Layers with Subsampled NTK Features
openreview: djASMk0bzO
abstract: Bayesian Last Layers (BLLs) provide a convenient and computationally efficient
  way to estimate uncertainty in neural networks. However, they underestimate epistemic
  uncertainty because they apply a Bayesian treatment only to the final layer, ignoring
  uncertainty induced by earlier layers. We propose a method that improves BLLs by
  leveraging a projection of Neural Tangent Kernel (NTK) features onto the space spanned
  by the last-layer features. This enables posterior inference that accounts for variability
  of the full network while retaining the low computational cost of inference of a
  standard BLL. We show that our method yields posterior variances that are provably
  greater or equal to those of a standard BLL, correcting its tendency to underestimate
  epistemic uncertainty. To further reduce computational cost, we introduce a uniform
  subsampling scheme for estimating the projection matrix and for posterior inference.
  We derive approximation bounds for both types of subsampling. Empirical evaluations
  on UCI regression, contextual bandits, image classification, and out-of-distribution
  detection tasks in image and tabular datasets, demonstrate improved calibration
  and uncertainty estimates compared to standard BLLs and competitive baselines, while
  reducing computational cost.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: calvo-ordonez26a
month: 0
tex_title: Richer {B}ayesian Last Layers with Subsampled {NTK} Features
firstpage: 10939
lastpage: 10961
page: 10939-10961
order: 10939
cycles: false
bibtex_author: Calvo Ordo\~{n}ez, Sergio and Plenk, Jonathan and Bergna, Richard and
  Cartea, Alvaro and Gal, Yarin and Hern\'{a}ndez-Lobato, Jos\'{e} Miguel and Ciosek,
  Kamil
author:
- given: Sergio
  family: Calvo Ordoñez
- given: Jonathan
  family: Plenk
- given: Richard
  family: Bergna
- given: Alvaro
  family: Cartea
- given: Yarin
  family: Gal
- given: José Miguel
  family: Hernández-Lobato
- given: Kamil
  family: Ciosek
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/calvo-ordonez26a/calvo-ordonez26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
