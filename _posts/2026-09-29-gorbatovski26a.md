---
title: The Differences Between Direct Alignment Algorithms are a Blur
openreview: tCXxWWBjxQ
abstract: Direct Alignment Algorithms (DAAs) simplify LLM alignment by directly optimizing
  policies, bypassing reward modeling and RL. While DAAs differ in their use of SFT
  (one-stage vs. two-stage) and the scalar score they optimize (likelihood vs. odds
  ratios), the key performance drivers remain underexplored. We present a systematic
  comparison and analyze a previously overlooked axis - the ranking objective (pairwise
  vs. pointwise). To isolate this factor, we propose a unified training framework
  across DAAs by (i) converting one-stage methods (ORPO, ASFT) into a two-stage pipeline
  with an explicit SFT phase and (ii) introducing a $\beta$ parameter that places
  all methods in the same hyperparameter space and improves the quality of odds-ratio
  DAAs (ORPO, ASFT). Under this setup, the ranking objective emerges as the primary
  determinant of alignment quality, whereas the particular scalar score (policy–reference
  ratio vs. odds ratio) is secondary. We corroborate this on instruction-following
  tasks and further confirm it on math-reasoning benchmarks across model scales. Evidence
  suggests that this stems from how these objectives interact with prompt-specific
  biases, supported both by strictly controlled experiments and by observations on
  real data. Our findings underscore the need for nuanced evaluations in DAA research
  to avoid oversimplified claims of superiority.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gorbatovski26a
month: 0
tex_title: The Differences Between Direct Alignment Algorithms are a Blur
firstpage: 36215
lastpage: 36246
page: 36215-36246
order: 36215
cycles: false
bibtex_author: Gorbatovski, Alexey and Shaposhnikov, Boris and Sinii, Viacheslav and
  Malakhov, Alexey and Gavrilov, Daniil
author:
- given: Alexey
  family: Gorbatovski
- given: Boris
  family: Shaposhnikov
- given: Viacheslav
  family: Sinii
- given: Alexey
  family: Malakhov
- given: Daniil
  family: Gavrilov
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/gorbatovski26a/gorbatovski26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
