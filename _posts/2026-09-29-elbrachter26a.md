---
title: 'MAD: Manifold Attracted Diffusion'
openreview: CL6Byu4aIA
abstract: Score-based diffusion models are a highly effective method for generating
  samples from a distribution of images. We consider scenarios where the training
  data comes from a noisy version of the target distribution, and present an efficiently
  implementable modification of the inference procedure to generate noiseless samples.
  Our approach is motivated by the manifold hypothesis, according to which meaningful
  data is concentrated around some low-dimensional manifold of a high-dimensional
  ambient space. The central idea is that noise manifests as low magnitude variation
  in off-manifold directions in contrast to the relevant variation of the desired
  distribution which is mostly confined to on-manifold directions. We introduce the
  notion of an extended score and show that, in a simplified setting, it can be used
  to reduce small variations to zero, while leaving large variations mostly unchanged.
  We describe how its approximation can be computed efficiently from an approximation
  to the standard score and demonstrate its efficacy on toy problems, synthetic data,
  and real data.
software: https://github.com/delbraechter/MAD
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: elbrachter26a
month: 0
tex_title: "{MAD}: Manifold Attracted Diffusion"
firstpage: 27822
lastpage: 27843
page: 27822-27843
order: 27822
cycles: false
bibtex_author: Elbr\"{a}chter, Dennis and Alberti, Giovanni S and Santacesaria, Matteo
author:
- given: Dennis
  family: Elbrächter
- given: Giovanni S
  family: Alberti
- given: Matteo
  family: Santacesaria
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/elbrachter26a/elbrachter26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
