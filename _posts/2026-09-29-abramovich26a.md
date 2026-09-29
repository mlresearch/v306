---
title: 'SPEED-Bench: A Unified and Diverse Benchmark for Speculative Decoding'
openreview: Rl2uQlCoQX
abstract: Speculative Decoding (SD) has emerged as a critical technique for accelerating
  Large Language Model (LLM) inference. Unlike deterministic system optimizations,
  SD performance is inherently data-dependent, meaning that diverse and representative
  workloads are essential for accurately measuring its effectiveness. Existing benchmarks
  suffer from limited task diversity, inadequate support for throughput-oriented evaluation,
  and a reliance on high-level implementations that fail to reflect production environments.
  To address this, we introduce <b>SPEED-Bench</b>, a comprehensive suite designed
  to standardize SD evaluation across diverse semantic domains and realistic serving
  regimes. SPEED-Bench offers a carefully curated <em>Qualitative</em> data split,
  selected by prioritizing semantic diversity across the data samples. Additionally,
  it includes a <em>Throughput</em> data split, allowing speedup evaluation across
  a range of concurrencies, from latency-sensitive low-batch settings to throughput-oriented
  high-load scenarios. By integrating with production engines like vLLM and TensorRT-LLM,
  SPEED-Bench allows practitioners to analyze system behaviors often masked by other
  benchmarks. We highlight this by quantifying how synthetic inputs overestimate real-world
  throughput, identifying batch-size dependent optimal draft lengths and biases in
  low-diversity data, and analyzing the caveats of vocabulary pruning in state-of-the-art
  drafters. We release SPEED-Bench to establish a unified evaluation standard for
  practical comparisons of SD algorithms.
software: https://huggingface.co/datasets/nvidia/SPEED-Bench
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abramovich26a
month: 0
tex_title: "{SPEED}-Bench: A Unified and Diverse Benchmark for Speculative Decoding"
firstpage: 240
lastpage: 267
page: 240-267
order: 240
cycles: false
bibtex_author: Abramovich, Talor and Ashkenazi, Maor and Putterman, Izzy and Chislett,
  Benjamin and Mitra, Tiyasa and Darvish Rouhani, Bita and Zilberstein, Ran and Geifman,
  Yonatan
author:
- given: Talor
  family: Abramovich
- given: Maor
  family: Ashkenazi
- given: Izzy
  family: Putterman
- given: Benjamin
  family: Chislett
- given: Tiyasa
  family: Mitra
- given: Bita
  family: Darvish Rouhani
- given: Ran
  family: Zilberstein
- given: Yonatan
  family: Geifman
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/abramovich26a/abramovich26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
