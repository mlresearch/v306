---
title: 'SMART: Scalable Mesh-free Aerodynamic Simulations from Raw Geometries using
  a Transformer-based Surrogate Model'
openreview: 2dzU8sTOO3
abstract: Machine learning–based surrogate models have emerged as more efficient alternatives
  to numerical solvers for physical simulations over complex geometries, such as car
  bodies. Many existing models incorporate the simulation mesh as an additional input,
  thereby reducing prediction errors. However, generating a simulation mesh for new
  geometries is computationally costly. In contrast, mesh-free methods, which do not
  rely on the simulation mesh, typically incur higher errors. Motivated by these considerations,
  we introduce SMART, a neural surrogate model that predicts physical quantities at
  arbitrary query locations using only a point-cloud representation of the geometry,
  without requiring access to the simulation mesh. The geometry and simulation parameters
  are encoded into a shared latent space that captures both structural and parametric
  characteristics of the physical field. A physics decoder then attends to the encoder’s
  intermediate latent representations to map spatial queries to physical quantities.
  Through this cross-layer interaction, the model jointly updates latent geometric
  features and the evolving physical field. Extensive experiments show that SMART
  is competitive with and often outperforms existing methods that rely on the simulation
  mesh as input, demonstrating its capabilities for industry-level simulations.
software: https://github.com/jhagnberger/smart
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hagnberger26a
month: 0
tex_title: "{SMART}: Scalable Mesh-free Aerodynamic Simulations from Raw Geometries
  using a Transformer-based Surrogate Model"
firstpage: 39376
lastpage: 39420
page: 39376-39420
order: 39376
cycles: false
bibtex_author: Hagnberger, Jan and Niepert, Mathias
author:
- given: Jan
  family: Hagnberger
- given: Mathias
  family: Niepert
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hagnberger26a/hagnberger26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
