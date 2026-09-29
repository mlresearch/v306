---
title: 'Rex: A Family of Reversible Exponential (Stochastic) Runge-Kutta Solvers'
openreview: 7pQIzVNctu
abstract: Deep generative models based on neural differential equations have become
  state-of-the-art for many generation tasks. These models rely on ODE/SDE solvers
  that integrate from a prior distribution to the data distribution; in many applications
  it is also highly desirable to integrate in the inverse direction. Standard solvers,
  however, accumulate discretization errors that prohibit <em>exact inversion</em>,
  an inaccuracy that is unacceptable in precision-critical applications. Existing
  inversion methods suffer from poor stability and low order of convergence, and are
  strictly limited to the ODE setting. In this work, we propose <em>Rex</em>, a family
  of reversible exponential (stochastic) Runge-Kutta solvers obtained by applying
  Lawson methods to convert any explicit (stochastic) Runge-Kutta scheme into an algebraically
  reversible one for both diffusion ODEs <em>and</em> SDEs. Beyond a rigorous theoretical
  analysis—establishing arbitrary-order convergence and a non-zero region of linear
  stability—we empirically demonstrate that <em>Rex</em> achieves near-machine-precision
  reconstruction and improves Boltzmann sampling with flow models as well as image
  generation and editing with diffusion models.
software: https://github.com/zblasingame/Rex-solver
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: blasingame26a
month: 0
tex_title: 'Rex: A Family of Reversible Exponential ({S}tochastic) Runge-Kutta Solvers'
firstpage: 8373
lastpage: 8445
page: 8373-8445
order: 8373
cycles: false
bibtex_author: Blasingame, Zander W. and Liu, Chen
author:
- given: Zander W.
  family: Blasingame
- given: Chen
  family: Liu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/blasingame26a/blasingame26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
