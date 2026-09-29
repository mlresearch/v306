---
title: 'Diamond Maps: Efficient Reward Alignment via Stochastic Flow Maps'
openreview: tAtpSwjsCB
abstract: Flow and diffusion models produce high-quality samples, but adapting them
  to user preferences or constraints post-training remains costly and brittle, a challenge
  commonly called reward alignment. We argue that efficient reward alignment should
  be a property of the generative model itself, not an afterthought, and redesign
  the model for adaptability. We propose Diamond Maps, a stochastic flow-map model
  that enables efficient and accurate alignment to arbitrary rewards at inference
  time. Diamond Maps amortize many simulation steps into a single-step sampler, like
  flow maps, while preserving the stochasticity required for optimal reward adaptation.
  This design makes search, Sequential Monte Carlo, and guidance scalable by enabling
  efficient and consistent estimation of the value function. Our experiments show
  that Diamond Maps can be learned efficiently via distillation from GLASS Flows,
  achieve stronger reward-alignment performance, and scale better than existing alignment
  methods. Overall, our results point toward a practical route to generative models
  that can be rapidly adapted to arbitrary preferences and constraints at inference
  time.
software: https://github.com/PeterHolderrieth/diamond_maps
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: holderrieth26a
month: 0
tex_title: 'Diamond Maps: Efficient Reward Alignment via Stochastic Flow Maps'
firstpage: 43401
lastpage: 43435
page: 43401-43435
order: 43401
cycles: false
bibtex_author: Holderrieth, Peter and Chen, Douglas and Eyring, Luca and Shah, Ishin
  and Anantharaman, Giri and He, Yutong and Akata, Zeynep and Jaakkola, Tommi and
  Boffi, Nicholas Matthew and Simchowitz, Max
author:
- given: Peter
  family: Holderrieth
- given: Douglas
  family: Chen
- given: Luca
  family: Eyring
- given: Ishin
  family: Shah
- given: Giri
  family: Anantharaman
- given: Yutong
  family: He
- given: Zeynep
  family: Akata
- given: Tommi
  family: Jaakkola
- given: Nicholas Matthew
  family: Boffi
- given: Max
  family: Simchowitz
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/holderrieth26a/holderrieth26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
