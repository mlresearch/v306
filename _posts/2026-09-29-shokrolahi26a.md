---
title: 'Responsible Text-to-Image Diffusion: Interpretable and Linearly Controllable
  Semantics for Fair and Safe Generation'
openreview: W9ltOfYnhY
abstract: 'Text-to-image (T2I) diffusion models (DMs) have achieved remarkable generative
  quality but still exhibit risk of producing biased and inappropriate images. A promising
  line of prior work aims to mitigate this issue by learning interpretable, linearly
  controllable concepts from semantic spaces, such as the U-Net bottleneck; however,
  these methods rely entirely on U-Net architectures and cannot be generalized to
  modern ViT-based DMs, including FLUX and PixArt. In this work, we present an architecture-agnostic
  framework for discovering interpretable and linearly controllable semantic attributes
  across any T2I DM backbone. Theoretically, we show that multi-modal attention heads
  in ViT-based DMs exhibit a linear semantic structure: injected concept vectors combine
  linearly at the attention level and induce near-linear effects at the model output,
  satisfying homogeneity and additivity. These theoretical results are aligned with
  and supported by empirical experiments. Building on this insight, we introduce a
  method that learns external concept vectors, which are added to the multi-modal
  attention heads for ViT-based DMs or to the bottleneck layer for U-Net-based DMs,
  while keeping pretrained models frozen. Experiments across SDXL, SD3.5, PixArt,
  and FLUX demonstrate that these concept vectors provide interpretability, linearity,
  and significantly improved fairness while preserving visual fidelity. The code and
  demo are available at https://github.com/Moslem-Sh21/responsible-t2i-diffusion.'
software: https://github.com/Moslem-Sh21/responsible-t2i-diffusion
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shokrolahi26a
month: 0
tex_title: 'Responsible Text-to-Image Diffusion: Interpretable and Linearly Controllable
  Semantics for Fair and Safe Generation'
firstpage: 112713
lastpage: 112741
page: 112713-112741
order: 112713
cycles: false
bibtex_author: Shokrolahi, Sayedmoslem and Kang, Jae-Mo and Kim, Il-Min
author:
- given: Sayedmoslem
  family: Shokrolahi
- given: Jae-Mo
  family: Kang
- given: Il-Min
  family: Kim
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/shokrolahi26a/shokrolahi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
