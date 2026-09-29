---
title: Reinforcement Learning with Action-Triggered Observations
openreview: jhNMY6jHJw
abstract: We introduce Action-Triggered Sporadically Traceable Markov Decision Processes
  (ATST-MDPs), a reinforcement learning framework for partial observability in which
  full state observations occur stochastically at each step, with probability determined
  by the chosen action. We derive Bellman equations tailored to this setting and establish
  the existence of an optimal policy. Exploiting the fact that sporadic observations
  reveal the full state, we provide an equivalent formulation in which agents commit
  to action-sequences between consecutive observations. Under the linear MDP assumption,
  we show that the value function over such action-sequences admits a linear representation
  in a finite-dimensional feature map, enabling standard regression-based methods.
  As an application, we derive ATST-LSVI-UCB, an optimistic algorithm achieving regret
  $\widetilde{O}(\sqrt{Kd^3(1-\gamma)^{-3}})$ for episodic learning with geometrically
  distributed horizons, where $K$ is the number of episodes, $d$ the feature dimension,
  and $\gamma$ the discount factor (episode continuation probability), matching the
  known rate for linear MDPs with full observability.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ryabchenko26a
month: 0
tex_title: Reinforcement Learning with Action-Triggered Observations
firstpage: 106402
lastpage: 106430
page: 106402-106430
order: 106402
cycles: false
bibtex_author: Ryabchenko, Alexander and Mou, Wenlong
author:
- given: Alexander
  family: Ryabchenko
- given: Wenlong
  family: Mou
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ryabchenko26a/ryabchenko26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
