---
title: Randomized Feasibility Methods for Constrained Optimization with Adaptive Step
  Sizes
openreview: 1BchRVONfp
abstract: 'We consider minimizing an objective function subject to constraints defined
  by the intersection of lower-level sets of convex functions. We study two cases:
  (i) strongly convex and Lipschitz-smooth objective function and (ii) convex but
  possibly nonsmooth objective function. To deal with the constraints that are not
  easy to project on, we use a randomized feasibility algorithm with Polyak steps
  and a random number of sampled constraints per iteration, while taking (sub)gradient
  steps to minimize the objective function. For case (i), we prove linear convergence
  in expectation of the objective function values to any prescribed tolerance using
  an adaptive stepsize. For case (ii), we develop a fully problem parameter-free and
  adaptive stepsize scheme that yields an $O(1/\sqrt{T})$ worst-case rate in expectation.
  The infeasibility of the iterates decreases geometrically with the number of feasibility
  updates almost surely, while for the averaged iterates, we establish an expected
  lower bound on the function values relative to the optimal value that depends on
  the distribution for the random number of sampled constraints. For certain choices
  of sample-size growth, optimal rates are achieved. Finally, simulations on a Quadratically
  Constrained Quadratic Programming (QCQP) problem, Support Vector Machines (SVM),
  and logistic regression with group fairness constraints demonstrate the computational
  efficiency of our algorithm compared to other state-of-the-art methods.'
software: https://github.com/AbhishekChak/Ada-method-random-feas.git
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26c
month: 0
tex_title: Randomized Feasibility Methods for Constrained Optimization with Adaptive
  Step Sizes
firstpage: 12475
lastpage: 12516
page: 12475-12516
order: 12475
cycles: false
bibtex_author: Chakraborty, Abhishek and Nedich, Angelia
author:
- given: Abhishek
  family: Chakraborty
- given: Angelia
  family: Nedich
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/chakraborty26c/chakraborty26c.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
