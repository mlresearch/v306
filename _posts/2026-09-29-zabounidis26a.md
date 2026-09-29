---
title: 'Re-FORC: Adaptive Reward Prediction for Efficient Chain-of-Thought Reasoning'
openreview: 8NNPSNAvTX
abstract: 'We propose Re-FORC, an adaptive reward prediction method that, given a
  query, enables prediction of the expected future rewards as a function of the number
  of future thinking tokens. Re-FORC trains a lightweight adapter on reasoning models,
  demonstrating improved prediction with longer reasoning and larger models. Re-FORC
  enables: 1) early stopping of unpromising reasoning chains, reducing compute by
  up to 26% compared to fixed-budget cutoffs, while maintaining accuracy, 2) optimized
  model and thinking length selection that outperforms the largest model alone— reaching
  1.7 percentage points higher peak accuracy while needing up to 12% less compute
  to match the largest model’s accuracy, 3) adaptive test-time scaling, which increases
  accuracy by 9.9 percentage points (on average at maximum compute) over confidence-based
  baselines. Re-FORC allows dynamic reasoning with length control via cost-per-token
  thresholds while estimating computation time upfront.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zabounidis26a
month: 0
tex_title: 'Re-{FORC}: Adaptive Reward Prediction for Efficient Chain-of-Thought Reasoning'
firstpage: 152695
lastpage: 152715
page: 152695-152715
order: 152695
cycles: false
bibtex_author: Zabounidis, Renos and Golatkar, Aditya and Kleinman, Michael and Achille,
  Alessandro and Xia, Wei and Soatto, Stefano
author:
- given: Renos
  family: Zabounidis
- given: Aditya
  family: Golatkar
- given: Michael
  family: Kleinman
- given: Alessandro
  family: Achille
- given: Wei
  family: Xia
- given: Stefano
  family: Soatto
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/zabounidis26a/zabounidis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
