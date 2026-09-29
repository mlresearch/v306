---
title: 'FlashOptim: Optimizers for Memory-Efficient Training'
openreview: Wfe1iJocjF
abstract: Standard mixed-precision training of neural networks requires many bytes
  of accelerator memory for each model parameter. These bytes reflect not just the
  parameter itself, but also its gradient and one or more optimizer state variables.
  With each of these values typically requiring 4 bytes, training even a 7 billion
  parameter model can be impractical for researchers with less than 100 GiB of accelerator
  memory. We introduce FlashOptim, a suite of optimizations that reduces per-parameter
  memory by over 50% while preserving model quality and API compatibility. Our approach
  introduces two key techniques. First, we improve master weight splitting by finding
  and exploiting a tight bound on its quantization error. Second, we design companding
  functions that greatly reduce the error in 8-bit optimizer state quantization. Together
  with 16-bit gradients, these techniques reduce AdamW memory from 16 bytes to 7 bytes
  per parameter, or 5 bytes with gradient release. They also cut model checkpoint
  sizes by more than half. Experiments with FlashOptim applied to SGD, AdamW, and
  Lion show no measurable quality degradation across a collection of standard vision
  and language benchmarks, including Llama-3.1-8B finetuning.
software: https://github.com/databricks/flashoptim
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gonzalez-ortiz26a
month: 0
tex_title: "{F}lash{O}ptim: Optimizers for Memory-Efficient Training"
firstpage: 36180
lastpage: 36196
page: 36180-36196
order: 36180
cycles: false
bibtex_author: Gonzalez Ortiz, Jose Javier and Gupta, Abhay and Rinard, Christopher
  and Blalock, Davis
author:
- given: Jose Javier
  family: Gonzalez Ortiz
- given: Abhay
  family: Gupta
- given: Christopher
  family: Rinard
- given: Davis
  family: Blalock
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/gonzalez-ortiz26a/gonzalez-ortiz26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
