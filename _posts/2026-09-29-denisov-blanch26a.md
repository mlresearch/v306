---
title: 'Truthfulness Does Not Scale Like Reasoning: Why Polling Fails as a Proxy Verifier'
openreview: g8bbEh2E2W
abstract: 'Pass@$k$ and other methods of scaling inference compute can improve language
  model performance in domains with external verifiers, including mathematics and
  code, where incorrect candidates can be filtered reliably. This raises a natural
  question: can we similarly scale compute to elicit gains in truthfulness for domains
  without convenient verification? We show that across five benchmarks and models,
  surprisingly, it cannot. Even at $25\times$ the inference cost of naive sampling,
  polling-style aggregation yields no consistent accuracy gains over single-sample
  baselines and often amplifies correlated errors. We find that under uncertainty,
  models are better at predicting what other models will say within model ensembles
  than at identifying what is true, revealing a separation between social prediction
  and truth verification. Across models and benchmarks, aggregation fails to provide
  a robust truth signal because language model errors are strongly correlated. The
  source of correlation goes beyond any individual benchmark: we show that even when
  conditioned on out of distribution random strings and asked to produce pseudo-random
  outputs, different models produce correlated outputs. Confidence-based weighting
  provides no benefit because self-reported confidence fails to reliably distinguish
  correct from incorrect answers. These results delineate a boundary for inference-time
  scaling: in verified domains, additional samples provide more candidates for a verifier
  to filter; in unverified domains, additional samples merely reinforce correlated
  errors.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: denisov-blanch26a
month: 0
tex_title: 'Truthfulness Does Not Scale Like Reasoning: Why Polling Fails as a Proxy
  Verifier'
firstpage: 24461
lastpage: 24477
page: 24461-24477
order: 24461
cycles: false
bibtex_author: Denisov-Blanch, Yegor and Kazdan, Joshua and Chudnovsky, Jessica and
  Schaeffer, Rylan and Guan, Sheng and Adeshina, Soji and Koyejo, Sanmi
author:
- given: Yegor
  family: Denisov-Blanch
- given: Joshua
  family: Kazdan
- given: Jessica
  family: Chudnovsky
- given: Rylan
  family: Schaeffer
- given: Sheng
  family: Guan
- given: Soji
  family: Adeshina
- given: Sanmi
  family: Koyejo
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/denisov-blanch26a/denisov-blanch26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
