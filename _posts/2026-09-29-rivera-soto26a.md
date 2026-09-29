---
title: Attacks on Machine-Text Detectors Retain Stylistic Fingerprints
openreview: 0BfnRKdTXH
abstract: 'Despite considerable progress in the development of machine-text detectors,
  the ease with which machine-text can be manipulated to evade detection has led to
  suggestions that the problem is inherently intractable. In this work, we investigate
  the limits of such evasion strategies. We demonstrate that while current attacks,
  ranging from prompt engineering to detector-guided optimization can effectively
  degrade performance of standard detectors, they fail to erase the underlying stylistic
  "fingerprints" of machine text. We show that few-shot detectors that utilize the
  stylistic feature space are robust to these evasion attempts, reliably detecting
  samples even from models explicitly tuned to prevent detection. This raises the
  question: does style represent a universal defense against machine-detection attacks?
  We demonstrate that the answer is "no" by introducing a novel paraphrasing approach
  that simultaneously optimizes for undetectability and adherence to specific human
  styles. We show that unlike prior methods, this attack effectively evades all considered
  detectors, including those that utilize writing style. However, we find that this
  evasion is not absolute: as the number of documents available for analysis grows,
  the human and machine distributions become distinguishable again. Overall, our findings
  suggest that reliable machine-text detection requires moving beyond single-document
  analysis to multi-document analysis.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rivera-soto26a
month: 0
tex_title: Attacks on Machine-Text Detectors Retain Stylistic Fingerprints
firstpage: 105258
lastpage: 105279
page: 105258-105279
order: 105258
cycles: false
bibtex_author: Rivera Soto, Rafael Alberto and Chen, Barry Y. and Andrews, Nicholas
author:
- given: Rafael Alberto
  family: Rivera Soto
- given: Barry Y.
  family: Chen
- given: Nicholas
  family: Andrews
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rivera-soto26a/rivera-soto26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
