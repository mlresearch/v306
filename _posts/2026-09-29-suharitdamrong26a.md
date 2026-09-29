---
title: 'CoLA: Cross-Modal Low-rank Adaptation for Multimodal Downstream Tasks'
openreview: 8CBWgJY7n9
abstract: Foundation models have revolutionized AI, but adapting them efficiently
  for multimodal tasks, particularly in dual-stream architectures composed of unimodal
  encoders, such as DINO and BERT, remains a significant challenge. Parameter-Efficient
  Fine-Tuning (PEFT) methods like Low-Rank Adaptation (LoRA) enable lightweight adaptation,
  yet they operate in isolation within each modality, limiting their ability in capturing
  cross-modal interactions. In this paper, we take a step in bridging this gap with
  Cross-Modal Low-Rank Adaptation (CoLA), a novel PEFT framework that extends LoRA
  by introducing a dedicated inter-modal adaptation pathway alongside the standard
  intra-modal one. This dual-path design enables CoLA to adapt unimodal foundation
  models to multimodal tasks effectively, without interference between modality-specific
  and cross-modal learning. We evaluate CoLA across a range of vision-language (RefCOCO,
  RefCOCO+, RefCOCOg) and audio-visual (AVE, AVS) benchmarks, where it consistently
  outperforms LORA, achieving a relative gain of around 3% and 2%, respectively, while
  maintaining parameter efficiency. Notably, CoLA enables the first multi-task PEFT
  framework for visual grounding, bridging a key gap in efficient multimodal adaptation.
  Code is available at https://github.com/peterwisu/CoLA
software: https://github.com/peterwisu/CoLA
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: suharitdamrong26a
month: 0
tex_title: "{C}o{LA}: Cross-Modal Low-rank Adaptation for Multimodal Downstream Tasks"
firstpage: 116320
lastpage: 116336
page: 116320-116336
order: 116320
cycles: false
bibtex_author: Suharitdamrong, Wish and Alex, Tony and Awais, Muhammad and Atito,
  Sara
author:
- given: Wish
  family: Suharitdamrong
- given: Tony
  family: Alex
- given: Muhammad
  family: Awais
- given: Sara
  family: Atito
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/suharitdamrong26a/suharitdamrong26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
