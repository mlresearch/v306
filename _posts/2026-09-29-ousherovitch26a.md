---
title: 'Learning to Extrapolate to New Tasks: A Relational Approach to Task Extrapolation'
openreview: 6cUXJo03zv
abstract: 'Modern learning systems excel at interpolation but struggle to generalize
  to unseen tasks outside the training distribution’s support. This failure occurs
  even in simple settings, such as handling task parameters beyond the training range,
  and persists despite advances in foundation models. To this end, we develop the
  Relational Task Extrapolator (RTE), an algorithm designed to enable systematic extrapolation
  to novel tasks. The key observation is that extrapolation is inherently relational:
  extrapolating to unseen tasks requires learning how tasks transform into one another.
  If a model learns the transformation between tasks A and B during training, it can
  apply that same transformation to relate known tasks to unseen ones at test time.
  RTE operationalizes this idea by decomposing each target task into a known anchor
  task and a transformation linking the anchor and target. It then learns a relational
  operator, mapping an anchor–transformation pair to predictions for the target task.
  We instantiate RTE across multiple task extrapolation regimes in function prediction,
  e.g. where target tasks use out-of-range parameters (parameter extrapolation), has
  greater compositional depth (length extrapolation), and/or recombine function primitives
  in unseen ways (compositional extrapolation). We further extend RTE to sequence
  prediction, integrating it into fine-tuning algorithms for foundation models. Across
  empirical studies, we find that RTE substantially outperforms existing approaches
  on extrapolation to novel, unseen tasks.'
software: https://github.com/yixinw-lab/TaskExtrapolation
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ousherovitch26a
month: 0
tex_title: 'Learning to Extrapolate to New Tasks: A Relational Approach to Task Extrapolation'
firstpage: 95141
lastpage: 95169
page: 95141-95169
order: 95141
cycles: false
bibtex_author: Ousherovitch, Adam and Wang, Yixin
author:
- given: Adam
  family: Ousherovitch
- given: Yixin
  family: Wang
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ousherovitch26a/ousherovitch26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
