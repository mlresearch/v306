---
title: Differentiable Conformal Training for LLM Reasoning Factuality
openreview: XfndtVLIub
abstract: 'Large Language Models (LLMs) frequently hallucinate, limiting their reliability
  in critical applications. Conformal Prediction (CP) addresses this by calibrating
  error rates on held-out data to provide statistically valid confidence guarantees.
  Recent work extends CP to LLM factuality: outputs are decomposed into subclaims,
  each assigned a risk score, and a calibrated threshold filters out risky claims
  to guarantee hallucination rates below a user-specified level (e.g., 10%). While
  prior methods treat claims independently, Coherent Factuality extends to multi-step
  reasoning by representing outputs as dependency graphs and jointly validating claims
  with their logical ancestors. A key limitation is that Coherent Factuality is not
  differentiable, requiring hand-crafted scorers that at high reliability levels remove
  nearly 60% of true claims. We introduce Differentiable Coherent Factuality (DCF),
  a fully differentiable relaxation that enables learning improved scorers while provably
  recovering the original algorithm’s guarantees. Experiments on two reasoning datasets
  demonstrate DCF achieves up to 141% improvement in claim retention while maintaining
  reliability guarantees, representing a significant step towards reliable conformal
  LLM systems.'
software: https://github.com/NathanHitt/Differentiable_Coherent_Factuality
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hittesdorf26a
month: 0
tex_title: Differentiable Conformal Training for {LLM} Reasoning Factuality
firstpage: 43209
lastpage: 43238
page: 43209-43238
order: 43209
cycles: false
bibtex_author: Hittesdorf, Nathan and Salzetta, Marco and Cheng, Lu
author:
- given: Nathan
  family: Hittesdorf
- given: Marco
  family: Salzetta
- given: Lu
  family: Cheng
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hittesdorf26a/hittesdorf26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
