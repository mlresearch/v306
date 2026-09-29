---
title: Learning the Minimum Action Distance
openreview: ZnOnnJJghs
abstract: This paper presents a state representation framework for Markov decision
  processes (MDPs) that can be learned solely from state trajectories, requiring neither
  reward signals nor the actions executed by the agent. We propose learning the $\textit{minimum
  action distance}$ (MAD), defined as the minimum number of actions required to transition
  between states, as a fundamental metric that captures the underlying structure of
  an environment. The MAD naturally enables critical downstream tasks such as goal-conditioned
  reinforcement learning and reward shaping by providing a dense, geometrically meaningful
  measure of progress. Our self-supervised learning approach constructs an embedding
  space where the distances between embedded state pairs correspond to their MAD,
  accommodating both symmetric and asymmetric approximations. We evaluate the framework
  on a comprehensive suite of environments with known MAD values, encompassing both
  deterministic and stochastic transition dynamics, discrete and continuous state
  spaces, and environments with noisy observations. Empirical results show that the
  proposed approach learns MAD representations more efficiently than existing methods,
  produces more accurate estimates of the true MAD, and improves performance on downstream
  goal-reaching tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: steccanella26a
month: 0
tex_title: Learning the Minimum Action Distance
firstpage: 115677
lastpage: 115710
page: 115677-115710
order: 115677
cycles: false
bibtex_author: Steccanella, Lorenzo and Evans, Joshua Benjamin and \c{S}im\c{s}ek,
  \"{O}zg\"{u}r and Jonsson, Anders
author:
- given: Lorenzo
  family: Steccanella
- given: Joshua Benjamin
  family: Evans
- given: Özgür
  family: Şimşek
- given: Anders
  family: Jonsson
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/steccanella26a/steccanella26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
