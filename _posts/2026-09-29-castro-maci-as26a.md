---
title: Conditional Diffusion Sampling
openreview: lZxQyCh5H7
abstract: 'Sampling from unnormalized multimodal distributions with limited density
  evaluations remains a fundamental challenge in machine learning and natural sciences.
  Successful approaches construct a bridge between a tractable reference and the target
  distribution. Parallel Tempering (PT) serves as the gold standard, while recent
  diffusion-based approaches offer a continuous alternative at the cost of neural
  training. In this work, we introduce Conditional Diffusion Sampling (CDS), a framework
  that combines these two paradigms. To this end, we derive Conditional Interpolants,
  a class of stochastic processes whose transport dynamics are governed by an exact,
  closed-form stochastic differential equation (SDE), requiring no neural approximation.
  Although these dynamics require sampling from a non-trivial initialization distribution,
  we show both theoretically and empirically that the cost of this initialization
  diminishes for sufficiently short diffusion times. CDS leverages this by a two-stage
  procedure: (1) PT is used to efficiently sample the initial distribution, and then
  (2) samples are transported via the transport SDE. This combination couples the
  robust global exploration of PT with efficient local transport. Experiments suggest
  that CDS has the potential to achieve a superior trade-off between sample quality
  and density evaluation cost compared to state-of-the-art samplers.'
software: https://github.com/Franblueee/conditional_diffusion_sampling
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: castro-maci-as26a
month: 0
tex_title: Conditional Diffusion Sampling
firstpage: 12046
lastpage: 12078
page: 12046-12078
order: 12046
cycles: false
bibtex_author: Castro-Mac\'{\i}as, Francisco M and Morales-Alvarez, Pablo and Syed,
  Saifuddin and Hern\'{a}ndez-Lobato, Daniel and Molina, Rafael and Hern\'{a}ndez-Lobato,
  Jos\'{e} Miguel
author:
- given: Francisco M
  family: Castro-Macı́as
- given: Pablo
  family: Morales-Alvarez
- given: Saifuddin
  family: Syed
- given: Daniel
  family: Hernández-Lobato
- given: Rafael
  family: Molina
- given: José Miguel
  family: Hernández-Lobato
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/castro-maci-as26a/castro-maci-as26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
