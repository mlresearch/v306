---
title: Categorical Reparameterization with Denoising Diffusion Models
openreview: lxKyBy8NDn
abstract: Learning models with categorical variables requires optimizing expectations
  over discrete distributions, a setting in which stochastic gradient-based optimization
  is challenging due to the non-differentiability of categorical sampling. A common
  workaround is to replace the discrete distribution with a continuous relaxation,
  yielding a smooth surrogate that admits reparameterized gradient estimates via the
  reparameterization trick. Building on this idea, we introduce ReDGE, a novel and
  efficient diffusion-based soft reparameterization method for categorical distributions.
  Our approach defines a flexible class of gradient estimators that includes the Straight-Through
  estimator as a special case. Experiments spanning latent variable models and inference-time
  reward guidance in discrete diffusion models demonstrate ReDGE consistently matches
  or outperforms existing gradient-based methods.
software: https://github.com/samsongourevitch/redge
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gourevitch26a
month: 0
tex_title: Categorical Reparameterization with Denoising Diffusion Models
firstpage: 36504
lastpage: 36537
page: 36504-36537
order: 36504
cycles: false
bibtex_author: Gourevitch, Samson and Oliviero Durmus, Alain and Moulines, Eric and
  Olsson, Jimmy and Janati, Yazid
author:
- given: Samson
  family: Gourevitch
- given: Alain
  family: Oliviero Durmus
- given: Eric
  family: Moulines
- given: Jimmy
  family: Olsson
- given: Yazid
  family: Janati
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/gourevitch26a/gourevitch26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
