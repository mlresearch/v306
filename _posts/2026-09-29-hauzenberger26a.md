---
title: Effective Distillation to Hybrid xLSTM Architectures
openreview: kj9wufh0EI
abstract: There have been numerous attempts to distill quadratic attention-based large
  language models (LLMs) into sub-quadratic linearized architectures. However, despite
  extensive research, such distilled models often fail to match the performance of
  their teacher LLMs on various downstream tasks. We set out the goal of <em>lossless
  distillation</em>, which we define in terms of tolerance-corrected <em>Win-and-Tie
  rates</em> between student and teacher on sets of tasks. To this end, we introduce
  an effective distillation pipeline for xLSTM-based students. We propose an additional
  merging stage, where individually linearized experts are combined into a single
  model. We show the effectiveness of this pipeline by distilling base and instruction-tuned
  models from the Llama, Qwen, and Olmo families. In many settings, our xLSTM-based
  students recover most of the teacher’s performance, and even exceed it on some downstream
  tasks. Our contributions are an important step towards more energy-efficient and
  cost-effective replacements for transformer-based LLMs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hauzenberger26a
month: 0
tex_title: Effective Distillation to Hybrid x{LSTM} Architectures
firstpage: 40877
lastpage: 40909
page: 40877-40909
order: 40877
cycles: false
bibtex_author: Hauzenberger, Lukas and Schmidinger, Niklas and Schmied, Thomas and
  Hartl, Anamaria-Roberta and Stap, David and Hoedt, Pieter-Jan and B\"{o}ck, Sebastian
  and Klambauer, G\"{u}nter and Hochreiter, Sepp
author:
- given: Lukas
  family: Hauzenberger
- given: Niklas
  family: Schmidinger
- given: Thomas
  family: Schmied
- given: Anamaria-Roberta
  family: Hartl
- given: David
  family: Stap
- given: Pieter-Jan
  family: Hoedt
- given: Sebastian
  family: Böck
- given: Günter
  family: Klambauer
- given: Sepp
  family: Hochreiter
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hauzenberger26a/hauzenberger26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
