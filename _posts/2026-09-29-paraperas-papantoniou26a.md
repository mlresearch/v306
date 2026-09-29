---
title: 'STARCaster: Spatio-Temporal AutoRegressive Video Diffusion for Identity- and
  View-Aware Talking Portraits'
openreview: 8wOASkNLzQ
abstract: This paper presents STARCaster, an identity-aware spatio-temporal video
  diffusion model that addresses both speech-driven portrait animation and dynamic
  viewpoint control, given an identity embedding or reference image, within a unified
  framework. Existing 2D speech-to-video diffusion models depend heavily on reference
  guidance, leading to limited motion diversity. At the same time, 3D-aware animation
  typically relies on inversion through pretrained tri-plane generators, which often
  leads to imperfect reconstructions and identity drift. We rethink reference- and
  geometry-based paradigms in two ways. First, we deviate from strict reference conditioning
  at pretraining by introducing softer identity constraints. Second, we address 3D
  awareness implicitly within the 2D video domain by leveraging the inherent multi-view
  nature of video data. STARCaster adopts a compositional approach progressing from
  ID-aware motion modeling, to audio-visual synchronization via lip reading-based
  supervision, and finally to novel view animation through temporal-to-spatial adaptation.
  To overcome the scarcity of 4D audio-visual data, we propose a decoupled learning
  approach in which view consistency and temporal coherence are trained independently.
  Comprehensive evaluations demonstrate that STARCaster generalizes effectively across
  tasks and identities, consistently surpassing prior approaches in different benchmarks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: paraperas-papantoniou26a
month: 0
tex_title: "{STARC}aster: Spatio-Temporal {A}uto{R}egressive Video Diffusion for Identity-
  and View-Aware Talking Portraits"
firstpage: 96516
lastpage: 96534
page: 96516-96534
order: 96516
cycles: false
bibtex_author: Paraperas Papantoniou, Foivos and Galanakis, Stathis and Potamias,
  Rolandos Alexandros and Kainz, Bernhard and Zafeiriou, Stefanos
author:
- given: Foivos
  family: Paraperas Papantoniou
- given: Stathis
  family: Galanakis
- given: Rolandos Alexandros
  family: Potamias
- given: Bernhard
  family: Kainz
- given: Stefanos
  family: Zafeiriou
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/paraperas-papantoniou26a/paraperas-papantoniou26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
