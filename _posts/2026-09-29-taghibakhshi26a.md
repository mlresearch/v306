---
title: 'Star Elastic: Many-in-One Reasoning LLMs with Efficient Budget Control'
openreview: n1fQYnj30I
abstract: 'Training a family of large language models (LLMs), either from scratch
  or via iterative compression, is prohibitively expensive and inefficient, requiring
  separate training runs for each model in the family. In this paper, we introduce
  Star Elastic, a novel LLM post-training method that adds N nested submodels to a
  given parent reasoning model using the compute of one run (Nx savings) via a single
  post-training job. Beyond reducing training costs, Star Elastic also addresses a
  fundamental limitation in efficient reasoning: the rigidity of static architectures,
  which forces the allocation of constant resources regardless of token difficulty.
  By unlocking elastic budget control, Star Elastic enables a novel approach that
  uses different submodels for each reasoning phase (thinking and answering). Star
  Elastic supports (1) nesting along the SSM, embedding channel, MoE and FFN axes,
  (2) learning nested submodels via an end-to-end trainable router, and (3) curriculum-based
  knowledge distillation. We apply Star Elastic to the NVIDIA Nemotron Nano models;
  in particular, we demonstrate its effectiveness on hybrid MoE architectures with
  Nemotron Nano v3 (30B/3.6A), generating 23B (2.8A) and 12B (2.0A) variants with
  160B training tokens. For Nemotron Nano v2 (12B), we produce 9B and 6B nested models
  using only 110B training tokens, achieving a 360x reduction versus training from
  scratch and a 7x reduction over state-of-the-art compression methods. All nested
  models match or outperform independently trained baselines of comparable size. Crucially,
  elastic budget control advances the accuracy–latency Pareto frontier, achieving
  up to 16% higher accuracy and 1.9x lower latency via dynamic per-phase model selection.'
software: https://github.com/NVIDIA/Megatron-LM/tree/main/megatron/elastification
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: taghibakhshi26a
month: 0
tex_title: 'Star Elastic: Many-in-One Reasoning {LLM}s with Efficient Budget Control'
firstpage: 117988
lastpage: 118008
page: 117988-118008
order: 117988
cycles: false
bibtex_author: Taghibakhshi, Ali and Cai, Ruisi and Muralidharan, Saurav and Turuvekere
  Sreenivas, Sharath and Mahabaleshwarkar, Ameya Sunil and Chochowski, Marcin and
  Bercovich, Akhiad and Zilberstein, Ran and El-Yaniv, Ran and Geifman, Yonatan and
  Korzekwa, Daniel and Suhara, Yoshi and Olabiyi, Oluwatobi and Aithal, Ashwath and
  Tajbakhsh, Nima and Molchanov, Pavlo
author:
- given: Ali
  family: Taghibakhshi
- given: Ruisi
  family: Cai
- given: Saurav
  family: Muralidharan
- given: Sharath
  family: Turuvekere Sreenivas
- given: Ameya Sunil
  family: Mahabaleshwarkar
- given: Marcin
  family: Chochowski
- given: Akhiad
  family: Bercovich
- given: Ran
  family: Zilberstein
- given: Ran
  family: El-Yaniv
- given: Yonatan
  family: Geifman
- given: Daniel
  family: Korzekwa
- given: Yoshi
  family: Suhara
- given: Oluwatobi
  family: Olabiyi
- given: Ashwath
  family: Aithal
- given: Nima
  family: Tajbakhsh
- given: Pavlo
  family: Molchanov
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/taghibakhshi26a/taghibakhshi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
