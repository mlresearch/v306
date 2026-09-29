---
title: Critique-Guided Distillation for Robust Reasoning via Refinement
openreview: HxyRSeT8z2
abstract: 'Supervised fine-tuning with expert demonstrations often produces models
  that imitate outputs without internalizing the reasoning processes needed for robust
  generalization. While critique-based approaches show promise, training models to
  generate critiques directly, such as Critique Fine-Tuning (CFT), can lead to output-format
  drift and degradation of general capabilities. We propose $\textbf{C}$ritique-$\textbf{G}$uided
  $\textbf{D}$istillation (CGD), a training framework that decouples critique consumption
  from critique generation. During fine-tuning, the student is trained to refine flawed
  responses conditioned on teacher critiques. CGD treats critiques as a $\textit{training-time-only}$
  supervision signal, encouraging internalization of error-aware reasoning: critiques
  guide learning but are absent at inference. Across five model families, CGD consistently
  outperforms CFT and standard distillation on mathematical reasoning benchmarks,
  yielding 7% average improvements and gains of up to +15.0% on AMC23 and +12.2% on
  MATH-500. On challenging competition problems such as AIME24 and AIME25, CGD achieves
  substantially higher Pass@1 and stronger performance at low Pass@k, indicating improved
  reasoning quality per sample. Importantly, CGD preserves general instruction-following
  capabilities where CFT degrades significantly ($-$21.3% on IFEval). These results
  position CGD as a practical and compute-efficient intermediate training paradigm
  for reasoning-centric tasks without introducing architectural inference-time overhead.'
software: https://github.com/CapitalOne-Research/Critique-Guided-Distillation
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kapusuzoglu26a
month: 0
tex_title: Critique-Guided Distillation for Robust Reasoning via Refinement
firstpage: 55993
lastpage: 56024
page: 55993-56024
order: 55993
cycles: false
bibtex_author: Kapusuzoglu, Berkcan and Chakraborty, Supriyo and Sarwar, Zain and
  Lee, Chia-Hsuan and Sahu, Sambit
author:
- given: Berkcan
  family: Kapusuzoglu
- given: Supriyo
  family: Chakraborty
- given: Zain
  family: Sarwar
- given: Chia-Hsuan
  family: Lee
- given: Sambit
  family: Sahu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/kapusuzoglu26a/kapusuzoglu26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
