---
title: 'Cerebellar-Inspired Residual Control for Fault Recovery: From Inference-Time
  Adaptation to Structural Consolidation'
openreview: 3vNaSvdEAc
abstract: Robotic policies deployed in real-world environments often encounter post-training
  faults, where retraining, exploration, or system identification are impractical.
  We introduce an inference-time, cerebellar-inspired residual control framework that
  augments a frozen reinforcement learning policy with online corrective actions,
  enabling fault recovery without modifying base policy parameters. The framework
  instantiates core cerebellar principles, including high-dimensional pattern separation
  via fixed feature expansion, parallel microzone-style residual pathways, and local
  error-driven plasticity with excitatory and inhibitory eligibility traces operating
  at distinct time scales. These mechanisms enable fast, localized correction under
  post-training disturbances while avoiding destabilizing global policy updates. A
  conservative, performance-driven meta-adaptation regulates residual gain and plasticity,
  preserving nominal behavior and suppressing unnecessary intervention. Experiments
  on MuJoCo benchmarks under actuator, dynamic, and environmental perturbations show
  improvements of up to $+66$% on $\texttt{HalfCheetah-v5}$ and $+53$% on $\texttt{Humanoid-v5}$
  under moderate faults, with graceful degradation under severe shifts and complementary
  robustness from consolidating persistent residual corrections into policy parameters.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jayasinghe26a
month: 0
tex_title: 'Cerebellar-Inspired Residual Control for Fault Recovery: From Inference-Time
  Adaptation to Structural Consolidation'
firstpage: 50986
lastpage: 51010
page: 50986-51010
order: 50986
cycles: false
bibtex_author: Jayasinghe, Nethmi and Gontero, Diana and Brown, Spencer T. and Sangwan,
  Vinod K and Hersam, Mark C. and Trivedi, Amit Ranjan
author:
- given: Nethmi
  family: Jayasinghe
- given: Diana
  family: Gontero
- given: Spencer T.
  family: Brown
- given: Vinod K
  family: Sangwan
- given: Mark C.
  family: Hersam
- given: Amit Ranjan
  family: Trivedi
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/jayasinghe26a/jayasinghe26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
