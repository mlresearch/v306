---
title: 'FPTQuant: Function-Preserving Transforms for LLM Quantization'
openreview: 2jpCo5lnSZ
abstract: 'Large language models (LLMs) require substantial compute, and thus energy,
  at inference time. While quantizing weights and activations is effective at improving
  efficiency, naive quantization of LLMs can significantly degrade performance due
  to large magnitude outliers. This paper describes FPTQuant, which introduces three
  novel, lightweight, and expressive function-preserving transforms (FPTs) to facilitate
  quantization of transformers: (1) a mergeable pre-RoPE transform for queries and
  keys, (2) a mergeable transform for values, (3) a cheap, dynamic scaling transform.
  By leveraging the equivariances and independencies inherent to canonical transformer
  operation, we designed these FPTs to maintain the model’s function while shaping
  the intermediate activation distributions to be more quantization friendly. FPTQuant
  requires no custom kernels and adds virtually no overhead during inference. The
  FPTs are trained both locally to reduce outliers, and end-to-end such that the outputs
  of the quantized and full-precision models match. FPTQuant enables static INT4 quantization
  with minimal overhead and shows SOTA speed-up of up to 3.9x over FP. Empirically,
  FPTQuant has an excellent accuracy-speed trade-off—it is performing on par or exceeding
  most prior work and only shows slightly lower accuracy compared to a method that
  is up to 29% slower.'
software: https://github.com/Qualcomm-AI-research/fptquant
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-breugel26a
month: 0
tex_title: "{FPTQ}uant: Function-Preserving Transforms for {LLM} Quantization"
firstpage: 123355
lastpage: 123382
page: 123355-123382
order: 123355
cycles: false
bibtex_author: Van Breugel, Boris and Bondarenko, Yelysei and Whatmough, Paul N. and
  Nagel, Markus
author:
- given: Boris
  family: Van Breugel
- given: Yelysei
  family: Bondarenko
- given: Paul N.
  family: Whatmough
- given: Markus
  family: Nagel
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/van-breugel26a/van-breugel26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
