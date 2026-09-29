---
title: 'Leak@$k$: Unlearning Does Not Make LLMs Forget Under Probabilistic Decoding'
openreview: sREOiWynXf
abstract: Unlearning in large language models (LLMs) is critical for regulatory compliance
  and for building ethical generative AI systems that avoid producing private, toxic,
  illegal, or copyrighted content. Despite rapid progress, in this work, we show that
  <em>almost all</em> existing unlearning methods fail to achieve true forgetting
  in practice. Specifically, while evaluations of these ‘unlearned’ models under deterministic
  (greedy) decoding often suggest successful knowledge removal using standard benchmarks,
  we show that sensitive information reliably resurfaces when models are sampled with
  standard probabilistic decoding. To rigorously capture this vulnerability, we introduce
  leak@$k$, a new meta-evaluation metric that quantifies the likelihood of forgotten
  knowledge reappearing when generating $k$ samples from the model under realistic
  decoding strategies. Using three widely adopted benchmarks, TOFU, MUSE, and WMDP,
  we conduct the first large-scale, systematic study of unlearning reliability using
  leak@$k$ metric. Our findings demonstrate that knowledge leakage persists across
  methods and tasks, underscoring that current state-of-the-art (SOTA) unlearning
  techniques provide only limited forgetting. We propose an algorithm, termed Robust
  Unlearning under LEak@$k$ metric (RULE) to address this concern. We demonstrate
  that RULE provides an unlearned model for TOFU benchmark with no information leakage
  for a large number of generation samples. On the MUSE benchmark, RULE outperforms
  SOTA unlearning methods under the leak@$k$ metric across most sampling budgets $k$.
  Codes are available at https://github.com/OptimAI-Lab/Leak-k.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: reisizadeh26a
month: 0
tex_title: 'Leak@$k$: Unlearning Does Not Make {LLM}s Forget Under Probabilistic Decoding'
firstpage: 104291
lastpage: 104315
page: 104291-104315
order: 104291
cycles: false
bibtex_author: Reisizadeh, Hadi and Ruan, Jiajun and Chen, Yiwei and Pal, Soumyadeep
  and Liu, Sijia and Hong, Mingyi
author:
- given: Hadi
  family: Reisizadeh
- given: Jiajun
  family: Ruan
- given: Yiwei
  family: Chen
- given: Soumyadeep
  family: Pal
- given: Sijia
  family: Liu
- given: Mingyi
  family: Hong
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/reisizadeh26a/reisizadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
