---
title: Personalized Image Generation via Human-in-the-loop Bayesian Optimization
openreview: sq3JUR4IDd
abstract: Imagine Alice has a specific image $x^\ast$ in her mind, say, the view of
  the street in which she grew up during her childhood. To generate that exact image,
  she guides a generative model with multiple rounds of prompting and arrives at an
  image $x^{p*}$. Although $x^{p*}$ is reasonably close to $x^\ast$, Alice finds it
  difficult to close that gap using language prompts. This paper aims to narrow this
  gap by observing that even after language has reached its limits, humans can still
  tell when a new image $x^+$ is closer to $x^\ast$ than $x^{p*}$. Leveraging this
  observation, we develop <b>MultiBO</b> (Multi-Choice Preferential Bayesian Optimization)
  that carefully generates $K$ new images as a function of $x^{p*}$, gets preferential
  feedback from the user, uses the feedback to guide the diffusion model, and ultimately
  generates a new set of $K$ images. We show that within $B$ rounds of user feedback,
  it is possible to arrive much closer to $x^\ast$, even though the generative model
  has no information about $x^\ast$. Qualitative scores from $30$ users, combined
  with quantitative metrics compared across $5$ baselines, show promising results,
  suggesting that multi-choice feedback from humans can be effectively harnessed for
  personalized image generation.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rajagopalan26a
month: 0
tex_title: Personalized Image Generation via Human-in-the-loop {B}ayesian Optimization
firstpage: 103193
lastpage: 103224
page: 103193-103224
order: 103193
cycles: false
bibtex_author: Rajagopalan, Rajalaxmi and Dutta, Debottam and Wei, Yu-Lin and Roy
  Choudhury, Romit
author:
- given: Rajalaxmi
  family: Rajagopalan
- given: Debottam
  family: Dutta
- given: Yu-Lin
  family: Wei
- given: Romit
  family: Roy Choudhury
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rajagopalan26a/rajagopalan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
