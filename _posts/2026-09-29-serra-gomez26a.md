---
title: A KL-regularization framework for learning to plan with adaptive priors
openreview: zO8vzSGgTn
abstract: Effective exploration remains a key challenge in model-based reinforcement
  learning (MBRL), especially in high-dimensional continuous control tasks where sample
  efficiency is critical. Recent work addresses this by using learned policies as
  proposal distributions for Model-Predictive Path Integral (MPPI) planning. Early
  approaches update the sampling policy independently of the planner, typically via
  deterministic policy gradients with entropy regularization. However, since the data
  distribution is induced by the MPPI planner, misalignment between the policy and
  planner degrades value estimation and long-term performance. To address this, recent
  methods explicitly align the policy with the planner by minimizing KL divergence
  to the planner distribution or by incorporating planner-guided regularization. In
  this work, we unify these approaches under the Policy Optimization–Model Predictive
  Control (PO-MPC) framework, a family of KL-regularized MBRL methods that treat the
  planner’s action distribution as a prior in policy optimization. We show how existing
  methods emerge as special cases of this family and explore previously unstudied
  variants. Experiments demonstrate that these variants yield significant performance
  gains, advancing the state of the art in MPPI-based RL.
software: 'https: //github.com/alvaro-serra/pompc.git'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: serra-gomez26a
month: 0
tex_title: A {KL}-regularization framework for learning to plan with adaptive priors
firstpage: 109178
lastpage: 109204
page: 109178-109204
order: 109178
cycles: false
bibtex_author: Serra-Gomez, Alvaro and Jarne Ornia, Daniel and Tirumala, Dhruva and
  Moerland, Thomas M.
author:
- given: Alvaro
  family: Serra-Gomez
- given: Daniel
  family: Jarne Ornia
- given: Dhruva
  family: Tirumala
- given: Thomas M.
  family: Moerland
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/serra-gomez26a/serra-gomez26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
