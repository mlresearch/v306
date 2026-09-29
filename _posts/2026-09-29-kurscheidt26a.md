---
title: The Theory and Practice of MAP Inference over Non-Convex Constraints
openreview: jIZqAemuqk
abstract: In many safety-critical settings, probabilistic ML systems have to make
  predictions subject to algebraic constraints, e.g., predicting the most likely trajectory
  that does not cross obstacles. These real-world constraints are rarely convex, nor
  the densities considered are (log-)concave. This makes computing this constrained
  maximum a posteriori (MAP) prediction in an efficient and reliable way extremely
  challenging. In this paper, we first investigate under which conditions we can perform
  constrained MAP inference over continuous variables exactly and efficiently and
  devise a scalable message-passing algorithm for this tractable fragment. Then, we
  devise a general constrained MAP strategy that interleaves partitioning the domain
  into convex feasible regions with numerical constrained optimization. We evaluate
  both methods on synthetic and real-world benchmarks, showing our structure aware
  approach outperforms constraint-agnostic baselines.
software: https://github.com/april-tools/constrained-map
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kurscheidt26a
month: 0
tex_title: The Theory and Practice of {MAP} Inference over Non-Convex Constraints
firstpage: 61830
lastpage: 61872
page: 61830-61872
order: 61830
cycles: false
bibtex_author: Kurscheidt, Leander and Masina, Gabriele and Sebastiani, Roberto and
  Vergari, Antonio
author:
- given: Leander
  family: Kurscheidt
- given: Gabriele
  family: Masina
- given: Roberto
  family: Sebastiani
- given: Antonio
  family: Vergari
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/kurscheidt26a/kurscheidt26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
