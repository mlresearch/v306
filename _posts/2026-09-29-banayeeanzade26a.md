---
title: 'EPSVec: Efficient and Private Synthetic Data Generation via Dataset Vectors'
openreview: aaFfUg013C
abstract: 'High-quality data is essential for modern machine learning, yet many valuable
  corpora are sensitive and cannot be freely shared. Synthetic data offers a practical
  substitute for downstream development, and large language models (LLMs) have emerged
  as powerful engines for generating it. However, existing private text generation
  methods are severely inefficient: they are data-intensive, computationally slow,
  and often require large private corpora or batch sizes to achieve usable quality.
  We introduce EPSVec, a differentially-private lightweight alternative that steers
  LLM generation using <em>dataset vectors</em>-directions in activation space that
  capture the distributional gap between private data and public priors. EPSVec extracts
  and sanitizes steering vectors just once and then performs standard decoding. This
  decouples the privacy budget from generation, enabling arbitrarily many synthetic
  samples without additional privacy cost and yielding strong fidelity even in low-data
  regimes. Furthermore, we enhance our method by utilizing pretrained (base) models
  and introducing fixed-shot prompting to boost generation diversity and fidelity.
  Our experiments demonstrate that EPSVec outperforms existing baselines in distributional
  alignment and downstream utility, particularly in low-data regimes, while significantly
  reducing computational overhead.'
software: https://github.com/noiseeboi/EPSVec
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: banayeeanzade26a
month: 0
tex_title: "{EPSV}ec: Efficient and Private Synthetic Data Generation via Dataset
  Vectors"
firstpage: 6128
lastpage: 6150
page: 6128-6150
order: 6128
cycles: false
bibtex_author: Banayeeanzade, Amin and Yang, Qingchuan and Fu, Deqing and Hong, Spencer
  and Babinsky, Erin and Samuel, Alfy and Kumar, Anoop and Jia, Robin and Karimireddy,
  Sai Praneeth
author:
- given: Amin
  family: Banayeeanzade
- given: Qingchuan
  family: Yang
- given: Deqing
  family: Fu
- given: Spencer
  family: Hong
- given: Erin
  family: Babinsky
- given: Alfy
  family: Samuel
- given: Anoop
  family: Kumar
- given: Robin
  family: Jia
- given: Sai Praneeth
  family: Karimireddy
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/banayeeanzade26a/banayeeanzade26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
