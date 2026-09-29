---
title: Reusing Trajectories in Policy Gradients Enables Fast Convergence
openreview: gcYvvxTLRA
abstract: "<em>Policy gradient</em> (PG) methods are a class of effective <em>reinforcement
  learning</em> algorithms, particularly when dealing with continuous control problems.
  They rely on fresh <em>on-policy</em> data, making them sample-inefficient and requiring
  $\\mathcal{O}(\\epsilon^{-2})$ trajectories to reach an $\\epsilon$-approximate
  stationary point. A common strategy to improve efficiency is to <em>reuse</em> information
  from past iterations, such as previous <em>gradients</em> or <em>trajectories</em>,
  leading to <em>off-policy</em> PG methods. While gradient reuse has received substantial
  attention, leading to improved rates up to $\\mathcal{O}(\\epsilon^{-3/2})$, the
  reuse of past trajectories, although intuitive, remains largely unexplored from
  a theoretical perspective. In this work, we provide the first rigorous theoretical
  evidence that reusing past off-policy trajectories can significantly accelerate
  PG convergence. We propose RT-PG (Reusing Trajectories - Policy Gradient), a novel
  algorithm that leverages a <em>power mean</em>-corrected multiple importance weighting
  estimator to effectively combine on-policy and off-policy data coming from the most
  recent $\\omega$ iterations. Through a novel analysis, we prove that RT-PG achieves
  a sample complexity of $\\widetilde{\\mathcal{O}}(\\epsilon^{-2}\\omega^{-1})$.
  When reusing <em>all</em> available past trajectories, this leads to a rate of $\\widetilde{\\mathcal{O}}(\\epsilon^{-1})$,
  the best known one in the literature for PG methods. We further validate our approach
  empirically, demonstrating its effectiveness against baselines with state-of-the-art
  rates."
software: https://github.com/MontenegroAlessandro/MagicRL/tree/offpolicy
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: montenegro26a
month: 0
tex_title: Reusing Trajectories in Policy Gradients Enables Fast Convergence
firstpage: 90041
lastpage: 90082
page: 90041-90082
order: 90041
cycles: false
bibtex_author: Montenegro, Alessandro and Mansutti, Federico and Mussi, Marco and
  Papini, Matteo and Metelli, Alberto Maria
author:
- given: Alessandro
  family: Montenegro
- given: Federico
  family: Mansutti
- given: Marco
  family: Mussi
- given: Matteo
  family: Papini
- given: Alberto Maria
  family: Metelli
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/montenegro26a/montenegro26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
