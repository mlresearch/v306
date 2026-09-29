---
title: 'On the Interaction of Batch Noise, Adaptivity, and Compression, under $(L_0,L_1)$-Smoothness:
  An SDE Approach'
openreview: Pmsc4yytlf
abstract: 'Distributed stochastic optimization intertwines (i) stochastic gradient
  noise, (ii) communication compression, and (iii) adaptive/normalized updates. While
  each factor has been studied in isolation, their joint effect under realistic assumptions
  remains poorly understood. In this work, we develop a unified theoretical framework
  for Distributed Compressed SGD (DCSGD) and its sign variant Distributed SignSGD
  (DSignSGD) under the recently introduced $(L_0, L_1)$-smoothness condition. From
  a conceptual perspective, we show that the first- and second-order modified equations
  from the literature do not accurately model the discrete-time step-size/stability
  restrictions, especially under $(L_0,L_1)$-smoothness. From a technical perspective,
  we propose new first-order SDEs by carefully incorporating curvature-dependent terms
  into their drift: This helps capture the fine-grained relationship between learning
  rate restrictions, gradient noise, compression, and the geometry of the loss landscape.
  Importantly, we do so under general gradient noise assumptions, including heavy-tailed
  and affine-variance regimes, which extend beyond the classical bounded-variance
  setting. Our results suggest that normalizing the updates of DCSGD emerges as a
  natural condition for stability, with the degree of normalization precisely determined
  by the gradient noise structure, the landscape’s regularity, and the compression
  rate. In contrast, DSignSGD converges even under heavy-tailed noise with standard
  learning rate schedules. Together, these findings offer both new theoretical insights
  and perspectives, and practical guidance.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: monzio-compagnoni26a
month: 0
tex_title: 'On the Interaction of Batch Noise, Adaptivity, and Compression, under
  $(L_0,L_1)$-Smoothness: An {SDE} Approach'
firstpage: 90134
lastpage: 90171
page: 90134-90171
order: 90134
cycles: false
bibtex_author: Monzio Compagnoni, Enea and Islamov, Rustem and Proske, Frank Norbert
  and Lucchi, Aurelien and Orvieto, Antonio and Gorbunov, Eduard
author:
- given: Enea
  family: Monzio Compagnoni
- given: Rustem
  family: Islamov
- given: Frank Norbert
  family: Proske
- given: Aurelien
  family: Lucchi
- given: Antonio
  family: Orvieto
- given: Eduard
  family: Gorbunov
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/monzio-compagnoni26a/monzio-compagnoni26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
