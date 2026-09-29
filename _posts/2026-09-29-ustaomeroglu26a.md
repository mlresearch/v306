---
title: 'BLOCK-EM: Preventing Emergent Misalignment via Latent Blocking'
openreview: 8Q2T5GLl8x
abstract: 'Emergent misalignment can arise when a language model is fine-tuned on
  a narrowly scoped supervised objective: the model learns the target behavior, yet
  also develops undesirable out-of-domain behaviors. We investigate a mechanistic
  approach to preventing emergent misalignment by identifying a small set of internal
  features that reliably control the misaligned behavior and then discouraging the
  model from strengthening these features during fine-tuning. Across six fine-tuning
  domains, blocking (i.e., constraining) a fixed set of features achieves up to 95%
  relative reduction in emergent misalignment with no degradation in model quality
  or target-task performance. We strengthen validity with disjoint selection/evaluation
  splits, multiple independent judges, multiple random seeds for key settings, quality
  metrics, and extensive ablations demonstrating that the reduction in misalignment
  is specific to the identified mechanism. We also characterize a limiting regime
  in which misalignment re-emerges under prolonged fine-tuning, present evidence consistent
  with rerouting through alternative features or layers, and evaluate modifications
  that partially restore the misalignment-blocking effect. Overall, our results show
  that targeted training-time constraints on internal mechanisms can mitigate emergent
  misalignment without degrading target-task performance.'
software: https://github.com/ustaomeroglu/block-em
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ustaomeroglu26a
month: 0
tex_title: "{BLOCK}-{EM}: Preventing Emergent Misalignment via Latent Blocking"
firstpage: 123136
lastpage: 123175
page: 123136-123175
order: 123136
cycles: false
bibtex_author: Ustaomeroglu, Muhammed and Qu, Guannan
author:
- given: Muhammed
  family: Ustaomeroglu
- given: Guannan
  family: Qu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ustaomeroglu26a/ustaomeroglu26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
