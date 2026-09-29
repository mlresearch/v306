---
title: Density-Aware Translation of Spurious Correlations in Zero-Shot VLMs
openreview: ZXYcM3QuAR
abstract: 'Vision-Language models (VLMs), such as CLIP, achieve powerful zero-shot
  classification. However, their predictions remain sensitive to spurious correlations,
  where contextual cues dominate over semantic content. Earlier solutions typically
  rely on fine-tuning or prompt engineering, which either undermine the advantages
  of pre-trained models or are prone to hallucination. In this work, we propose Density-Aware
  Translation (DAT) that refines image-text similarity scores using a local geometric
  density term derived from group reference sets. Our approach is motivated by the
  phenomenon that CLIP embeddings exhibit a modality gap and lie on an anisotropic
  shell in the feature space: common patterns cluster near the mean, while rare patterns
  are pushed outward. This geometry creates uneven alignment, where spurious correlations
  are amplified while semantically meaningful but rare cues are marginalised. To address
  this, we employ a relative measure to rescale similarities based on embedding density,
  suppressing overconfident scores in diffuse regions while preserving dense, semantically
  consistent matches. Experimental results on benchmark datasets demonstrate consistent
  improvements in worst-group and average accuracy, highlighting density-aware translation
  as a simple and effective calibration mechanism for reliable zero-shot classification
  using multimodal models.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hasanebrahimi26a
month: 0
tex_title: Density-Aware Translation of Spurious Correlations in Zero-Shot {VLM}s
firstpage: 40748
lastpage: 40771
page: 40748-40771
order: 40748
cycles: false
bibtex_author: Hasanebrahimi, Afsaneh and Huang, Hanxun and Leckie, Christopher and
  Erfani, Sarah Monazam
author:
- given: Afsaneh
  family: Hasanebrahimi
- given: Hanxun
  family: Huang
- given: Christopher
  family: Leckie
- given: Sarah Monazam
  family: Erfani
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hasanebrahimi26a/hasanebrahimi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
