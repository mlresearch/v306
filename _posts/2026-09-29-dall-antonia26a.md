---
title: 'Avoid What You Know: Divergent Trajectory Balance for GFlowNets'
openreview: dPDOQs7qHl
abstract: Generative Flow Networks (GFlowNets) are a flexible family of amortized
  samplers trained to generate discrete and compositional objects with probability
  proportional to a reward function. To this end, they learn a policy function over
  an intractably large state graph by minimizing a stochastic objective over sampled
  trajectories. However, learning efficiency is constrained by the model’s ability
  to rapidly explore diverse high-probability regions during training. To mitigate
  this issue, recent works have focused on incentivizing the exploration of unvisited
  and valuable states via curiosity-driven search and self-supervised random network
  distillation, which tend to waste samples on already well-approximated regions of
  the state space. In this context, we propose <em>Adaptive Complementary Exploration</em>
  (ACE), a principled algorithm for the effective exploration of novel and high-probability
  regions when learning GFlowNets. To achieve this, ACE introduces an <em>exploration</em>
  GFlowNet explicitly trained to search for high-reward states in regions underexplored
  by the <em>canonical</em> GFlowNet, which learns to sample from the target distribution.
  Through extensive experiments, we show that ACE consistently and significantly improves
  upon prior work in terms of approximation accuracy to the target distribution and
  discovery rate of diverse high-reward states.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dall-antonia26a
month: 0
tex_title: 'Avoid What You Know: Divergent Trajectory Balance for {GF}low{N}ets'
firstpage: 22671
lastpage: 22688
page: 22671-22688
order: 22671
cycles: false
bibtex_author: Dall'Antonia, Pedro and Silva, Tiago and Csillag, Daniel and Lahlou,
  Salem and Mesquita, Diego
author:
- given: Pedro
  family: Dall’Antonia
- given: Tiago
  family: Silva
- given: Daniel
  family: Csillag
- given: Salem
  family: Lahlou
- given: Diego
  family: Mesquita
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/dall-antonia26a/dall-antonia26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
