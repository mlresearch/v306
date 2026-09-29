---
title: Particle Flow for Learning from Label Proportions
openreview: WkPYWGHQR2
abstract: 'This work proposes a novel method for solving learning from label proportion
  problems. For this purpose, we learn a classifier that minimizes three key objectives:
  (i) a bag-level loss, which quantifies the discrepancy between true and predicted
  label proportions in bags, (ii) an instance-level loss, inspired from domain adaptation,
  which leverages anchor samples with known labels and trainable supports and (iii)
  a distribution discrepancy that aims at aligning anchor’s learned support with those
  of the bag samples. The problem is formulated as an alternating optimization process,
  iteratively updating the classifier and aligning distributions via a particle flow
  method. The flow of anchor samples is governed by a vector field designed to minimize
  the anchor loss while ensuring alignment between anchor and bag distributions. We
  provide a theoretical analysis, guaranteeing the convergence of the flow and identifying
  conditions under which the method achieves effective alignment. Our analysis highlights
  that gap and diversity in label proportions within bags is a critical factor for
  learnability. Empirical results on tabular and image datasets demonstrate the method’s
  effectiveness, outperforming state-of-the-art approaches.'
software: https://github.com/arakotom/flowllp
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rakotomamonjy26a
month: 0
tex_title: Particle Flow for Learning from Label Proportions
firstpage: 103407
lastpage: 103433
page: 103407-103433
order: 103407
cycles: false
bibtex_author: Rakotomamonjy, Alain and Vono, Maxime and Ralaivola, Liva
author:
- given: Alain
  family: Rakotomamonjy
- given: Maxime
  family: Vono
- given: Liva
  family: Ralaivola
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rakotomamonjy26a/rakotomamonjy26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
