---
title: Efficient Hallucination Detection for LLMs Using Uncertainty-Aware Attention
  Heads
openreview: nddfPlfS09
abstract: 'While large language models (LLMs) have become highly capable, they remain
  prone to factual inaccuracies, commonly referred to as "hallucinations." Uncertainty
  quantification (UQ) offers a promising way to mitigate this issue, but most existing
  methods are computationally intensive and/or require supervision. In this work,
  we propose Recurrent Attention-based Uncertainty Quantification (RAUQ), an unsupervised
  and efficient framework for identifying hallucinations. The method leverages an
  observation about transformer attention behavior: when incorrect information is
  generated, certain "uncertainty-aware" attention heads tend to reduce their focus
  on preceding tokens. RAUQ automatically detects these attention heads and combines
  their activation patterns with token-level confidence measures in a recurrent scheme,
  producing a sequence-level uncertainty estimate in just a single forward pass. Through
  experiments on twelve datasets spanning question answering, summarization, and translation
  across nine different LLMs, we show that RAUQ consistently outperforms state-of-the-art
  UQ baselines. Importantly, it incurs minimal overhead, requiring less than 1% additional
  computation. Since it requires neither labeled data nor extensive parameter tuning,
  RAUQ serves as a lightweight, plug-and-play solution for real-time hallucination
  detection in white-box LLMs.'
software: https://github.com/mbzuai-nlp/rauq-hallucination-detection
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vazhentsev26a
month: 0
tex_title: Efficient Hallucination Detection for {LLM}s Using Uncertainty-Aware Attention
  Heads
firstpage: 123596
lastpage: 123627
page: 123596-123627
order: 123596
cycles: false
bibtex_author: Vazhentsev, Artem and Rvanova, Lyudmila and Kuzmin, Gleb and Fadeeva,
  Ekaterina and Lazichny, Ivan and Panchenko, Alexander and Panov, Maxim and Sachan,
  Mrinmaya and Nakov, Preslav and Baldwin, Timothy and Shelmanov, Artem
author:
- given: Artem
  family: Vazhentsev
- given: Lyudmila
  family: Rvanova
- given: Gleb
  family: Kuzmin
- given: Ekaterina
  family: Fadeeva
- given: Ivan
  family: Lazichny
- given: Alexander
  family: Panchenko
- given: Maxim
  family: Panov
- given: Mrinmaya
  family: Sachan
- given: Preslav
  family: Nakov
- given: Timothy
  family: Baldwin
- given: Artem
  family: Shelmanov
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/vazhentsev26a/vazhentsev26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
