---
title: Decoupling The "What" and "Where" With Polar Coordinate Positional Embedding
openreview: I3Z9za1EkO
abstract: The attention mechanism in a Transformer architecture matches key to query
  based on both content—the what—and position in a sequence—the where. We present
  an analysis indicating that what and where are entangled in the popular rotary position
  embedding (RoPE). This entanglement can impair performance particularly when decisions
  require independent matches on these two factors. We propose an improvement to RoPE,
  which we call Polar Coordinate Position Embedding or PoPE, that eliminates the what-where
  confound. PoPE is far superior on a diagnostic task requiring indexing solely by
  position or by content. On autoregressive sequence modeling in music, genomic, and
  natural language domains, Transformers using PoPE as the positional encoding scheme
  outperform baselines using RoPE with respect to evaluation loss (perplexity) and
  downstream task performance. On language modeling, these gains persist across model
  scale, from 124M to 774M parameters. Crucially, PoPE shows strong zero-shot length
  extrapolation capabilities compared not only to RoPE but even a method designed
  for extrapolation, YaRN, which requires additional fine tuning and frequency interpolation.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gopalakrishnan26a
month: 0
tex_title: Decoupling The "{W}hat" and "{W}here" With Polar Coordinate Positional
  Embedding
firstpage: 36197
lastpage: 36214
page: 36197-36214
order: 36197
cycles: false
bibtex_author: Gopalakrishnan, Anand and Csord\'{a}s, R\'{o}bert and Schmidhuber,
  J\"{u}rgen and Mozer, Michael Curtis
author:
- given: Anand
  family: Gopalakrishnan
- given: Róbert
  family: Csordás
- given: Jürgen
  family: Schmidhuber
- given: Michael Curtis
  family: Mozer
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/gopalakrishnan26a/gopalakrishnan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
