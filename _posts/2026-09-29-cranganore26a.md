---
title: 'ANTiC: Adaptive Neural Temporal In Situ Compressor'
openreview: dIhYhrVTCO
abstract: The persistent storage requirements for high-resolution, spatiotemporally
  evolving fields governed by large-scale and high-dimensional partial differential
  equations (PDEs) have reached the petabyte-to-exabyte scale. Transient simulations
  modeling Navier-Stokes equations, magnetohydrodynamics, plasma physics, or binary
  black hole mergers generate data volumes that are prohibitive for modern high-performance
  computing (HPC) infrastructures. To address this bottleneck, we introduce ANTIC
  (Adaptive Neural Temporal in situ Compressor), an end-to-end in situ compression
  pipeline. ANTIC consists of an adaptive temporal selector tailored to high-dimensional
  physics that identifies and filters informative snapshots at simulation time, combined
  with a spatial neural compression module based on continual fine-tuning that learns
  residual updates between adjacent snapshots using neural fields. By operating in
  a single streaming pass, ANTIC enables a combined compression of temporal and spatial
  components and effectively alleviates the need for explicit on-disk storage of entire
  time-evolved trajectories. Experimental results demonstrate that ANTIC achieves
  storage reductions of approximately $\sim 400\times$ for 2D Kolmogorov flow simulations
  and $\sim 7000\times$ for large-scale physics simulations such as binary black hole
  mergers.
software: https://github.com/AndreiB137/ANTIC
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cranganore26a
month: 0
tex_title: "{ANT}i{C}: Adaptive Neural Temporal In Situ Compressor"
firstpage: 21650
lastpage: 21680
page: 21650-21680
order: 21650
cycles: false
bibtex_author: Cranganore, Sandeep Suresh and Bodnar, Andrei and Galletti, Gianluca
  and Paischer, Fabian and Brandstetter, Johannes
author:
- given: Sandeep Suresh
  family: Cranganore
- given: Andrei
  family: Bodnar
- given: Gianluca
  family: Galletti
- given: Fabian
  family: Paischer
- given: Johannes
  family: Brandstetter
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/cranganore26a/cranganore26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
