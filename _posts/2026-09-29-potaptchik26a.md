---
title: Tilt Matching for Scalable Sampling and Fine-Tuning
openreview: dQA4Gjt4KU
abstract: We propose a simple, scalable algorithm based on stochastic interpolants
  for sampling from unnormalized densities and for fine-tuning generative models.
  The approach, Tilt Matching, arises from a dynamical equation relating the flow
  matching velocity to one targeting the same distribution tilted by a reward, implicitly
  solving a stochastic optimal control problem. The resulting velocity inherits the
  regularity of stochastic interpolant transports while minimizing an objective with
  strictly lower variance than flow matching itself. The update to the velocity field
  can be interpreted as the sum of all joint cumulants between the interpolant velocity
  and the reward, and to first order is their covariance. The method requires neither
  reward gradients nor backpropagation through trajectories of the flow or diffusion.
  We empirically demonstrate that the approach is efficient and highly scalable, providing
  state-of-the-art results on sampling under Lennard-Jones systems and competitive
  performance for fine-tuning Stable Diffusion, without requiring reward multipliers.
  The framework also applies directly to tilting few-step flow map models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: potaptchik26a
month: 0
tex_title: Tilt Matching for Scalable Sampling and Fine-Tuning
firstpage: 99231
lastpage: 99254
page: 99231-99254
order: 99231
cycles: false
bibtex_author: Potaptchik, Peter and Kit, Lee Cheuk and Albergo, Michael Samuel
author:
- given: Peter
  family: Potaptchik
- given: Lee Cheuk
  family: Kit
- given: Michael Samuel
  family: Albergo
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/potaptchik26a/potaptchik26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
