---
title: 'Hyper-ICL: Attention Calibration with Hyperbolic Anchor Distillation for Multimodal
  In-Context Learning'
openreview: rDKFflrjZK
abstract: Multimodal In-Context Learning (ICL) has emerged as a practical inference
  paradigm for Multimodal Large Language Models, where a small set of interleaved
  image-text In-Context Demonstrations (ICDs) conditions the model to solve new tasks.
  Despite its flexibility, multimodal ICL incurs high inference latency and suffers
  from instability due to sensitivity to demonstration formatting, ordering, and content.
  To address these limitations, we propose Hyper-ICL, a lightweight, training-based
  framework for demonstration-free multimodal ICL that reconstructs demonstration
  effects directly without requiring ICDs at inference time. Hyper-ICL learns a parameter-efficient
  low-rank logit-level adapter that calibrates attention distributions to better match
  demonstration-induced attention redistribution. To capture how demonstration influence
  varies across queries, we introduce a query-adaptive modulation mechanism that adaptively
  controls intervention strength at token level across layers and heads based on the
  current query. Finally, we propose a layer-wise hyperbolic anchor distillation loss
  that aligns intermediate student features to a demonstration-conditioned teacher
  via Lorentz geodesic distance. This loss encourages the student to reconstruct the
  demonstration–query relationships induced by ICDs. Extensive experiments across
  six different multimodal benchmarks (including VQAv2, OK-VQA, and COCO Caption)
  demonstrate that Hyper-ICL consistently improves accuracy and stability over vanilla
  ICL and existing state-of-the-art methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: alipour-talemi26a
month: 0
tex_title: 'Hyper-{ICL}: Attention Calibration with Hyperbolic Anchor Distillation
  for Multimodal In-Context Learning'
firstpage: 1981
lastpage: 1994
page: 1981-1994
order: 1981
cycles: false
bibtex_author: Alipour Talemi, Niloufar and Kashiani, Hossein and Afghah, Fatemeh
author:
- given: Niloufar
  family: Alipour Talemi
- given: Hossein
  family: Kashiani
- given: Fatemeh
  family: Afghah
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/alipour-talemi26a/alipour-talemi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
