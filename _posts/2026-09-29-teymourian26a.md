---
title: 'SORA: Free Second-Order Attacks in Fast Adversarial Training'
openreview: uynAkGdnmj
abstract: Adversarial Training (AT) is a leading defense against adversarial examples
  but often suffers from <em>Catastrophic Overfitting</em> (CO) in efficient single-step
  variants, where robustness to multi-step attacks collapses despite high single-step
  performance. We address this failure mode with two contributions. First, we formalize
  <em>Epsilon Overfitting</em> (EO), a perspective in which fixed perturbation magnitudes
  and directions exacerbate CO, and show that introducing perturbation variability
  significantly improves robust generalization across different architectures and
  datasets. Second, we propose <b>PertAlign</b> (Perturbation Alignment), a theoretically
  grounded, computationally negligible metric that predicts CO onset by measuring
  gradient alignment across attack stages. Leveraging these insights, we introduce
  <b>SORA</b>, an adaptive step-size AT method that dynamically adjusts perturbations
  based on loss surface geometry. SORA consistently prevents CO, achieves state-of-the-art
  robustness and clean accuracy, and generalizes across datasets and architectures
  using a single fixed set of hyperparameters, which is essential for applicability
  in fast AT. Extensive experiments on diverse datasets and architectures show that
  SORA matches or surpasses the robustness of prior methods while delivering higher
  clean accuracy and superior efficiency. Code is available at https://github.com/SecondOrderAT/SORA.
software: https://github.com/SecondOrderAT/SORA
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: teymourian26a
month: 0
tex_title: "{SORA}: Free Second-Order Attacks in Fast Adversarial Training"
firstpage: 120288
lastpage: 120347
page: 120288-120347
order: 120288
cycles: false
bibtex_author: Teymourian, Mazdak and Moslemi, Ramtin and Rahmani, Farzan and Rohban,
  Mohammad Hossein
author:
- given: Mazdak
  family: Teymourian
- given: Ramtin
  family: Moslemi
- given: Farzan
  family: Rahmani
- given: Mohammad Hossein
  family: Rohban
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/teymourian26a/teymourian26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
