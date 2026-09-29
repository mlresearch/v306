---
title: 'Plan for Speed: Dilated Scheduling for Masked Diffusion Language Models'
openreview: DbzAsMRNhy
abstract: Masked diffusion language models (MDLMs) promise fast, non-autoregressive
  text generation, yet existing samplers, which pick tokens to unmask based on model
  confidence, ignore interactions when unmasking multiple positions in parallel and
  effectively reduce to slow, autoregressive behavior. We propose the Dilated Unmasking
  Scheduler (DUS), an inference-only, planner-model-free method that partitions sequence
  positions into non-adjacent dilated groups and unmasks them in parallel so as to
  minimize an upper bound on joint entropy gain at each denoising step. By explicitly
  trading off the number of network calls against generation quality, DUS recovers
  most of the performance lost under traditional parallel unmasking strategies. Across
  math (GSM8K, MATH500), code (HumanEval, MBPP), general-knowledge (BBH, MMLU-Pro),
  and instruction following (IFEval) benchmarks, DUS outperforms confidence-based
  planners and turns the diffusion-specific quality-speed trade-off into a deterministic,
  predictable speedup set by the block size $B$, yielding up to $5.8\times$ wall-clock
  speedup over token-by-token MDLM decoding without modifying the underlying denoiser.
  Applied as a drop-in post-filter, dilated spacing also improves adaptive samplers.
  Code is available at https://github.com/omerlux/DUS.
software: https://github.com/omerlux/DUS
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: luxembourg26a
month: 0
tex_title: 'Plan for Speed: Dilated Scheduling for Masked Diffusion Language Models'
firstpage: 83451
lastpage: 83474
page: 83451-83474
order: 83451
cycles: false
bibtex_author: Luxembourg, Omer and Permuter, Haim H. and Nachmani, Eliya
author:
- given: Omer
  family: Luxembourg
- given: Haim H.
  family: Permuter
- given: Eliya
  family: Nachmani
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/luxembourg26a/luxembourg26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
