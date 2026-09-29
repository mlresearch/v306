---
title: Stabilizing In-Context Multi-Source Domain Adaptation for Biomedical Images
  Through Controls
openreview: oUGeAcxuz5
abstract: 'Biomedical imaging data presents enormous potential for deep learning models
  to predict invaluable properties, such as diseases and drug effects. However, unavoidable
  alterations of the technical conditions cause <em>batch effects</em>: variations
  between groups of samples that are not due to any biological signal of interest.
  Batch effects greatly hinder the generalization abilities of deep learning models,
  preventing their practical use in the real world. Unsupervised Domain Adaptation
  (UDA) methods have been proposed to mitigate batch effects, but they usually assume
  that the data is comprised of only one source domain and one target domain, whereas
  biological datasets are comprised of multiple domains, both at training and at inference
  time. While Batch Normalization–based test-time and meta-learning adaptation methods
  offer a promising mechanism for domain alignment, we show that existing approaches
  exhibit degraded performance under the usual inference scenarios of small target
  batch sizes and label shift. We address these limitations by leveraging negative
  control samples, which are consistently present in every experimental batch in biological
  datasets, as stable context for adaptation. We propose CS-ARM-BN, a meta-learning
  BN adaptation method that uses controls both during training and inference to stabilize
  domain statistics. We perform a suite of experiments of Mechanism-Of-Action (MoA)
  classification, a crucial task for drug discovery, on the large JUMP-CP imaging
  dataset. Our experiments show that CS-ARM-BN substantially improves robustness to
  batch size and class distribution shifts, enabling practical use of deep learning
  models for biomedical images.'
software: https://github.com/ml-jku/cs-arm-bn/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sanchez-fernandez26a
month: 0
tex_title: Stabilizing In-Context Multi-Source Domain Adaptation for Biomedical Images
  Through Controls
firstpage: 107472
lastpage: 107498
page: 107472-107498
order: 107472
cycles: false
bibtex_author: Sanchez-Fernandez, Ana and Pinetz, Thomas and Zellinger, Werner and
  Klambauer, G\"{u}nter
author:
- given: Ana
  family: Sanchez-Fernandez
- given: Thomas
  family: Pinetz
- given: Werner
  family: Zellinger
- given: Günter
  family: Klambauer
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/sanchez-fernandez26a/sanchez-fernandez26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
