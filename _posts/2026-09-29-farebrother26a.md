---
title: Compositional Planning with Jumpy World Models
openreview: cwztmjMQ77
abstract: The ability to plan with temporal abstractions is central to intelligent
  decision-making. Rather than reasoning over primitive actions, we study agents that
  compose pre-trained policies as temporally extended actions, enabling solutions
  to complex tasks that no constituent alone can solve. Such compositional planning
  remains elusive as compounding errors in long-horizon predictions make it challenging
  to estimate the visitation distribution induced by sequencing policies. Motivated
  by the geometric policy composition framework introduced in Thakoor et al. (2022),
  we address these challenges by learning predictive models of multi-step dynamics
  — so-called jumpy world models — that capture state occupancies induced by pre-trained
  policies across multiple timescales in an off-policy manner. Building on Temporal
  Difference Flows (Farebrother et al., 2025), we enhance these models with a novel
  consistency objective that aligns predictions across timescales, improving long-horizon
  predictive accuracy. We further demonstrate how to combine these generative predictions
  to estimate the value of executing arbitrary sequences of policies over varying
  timescales. Empirically, we find that compositional planning with jumpy world models
  significantly improves zero-shot performance across a wide range of base policies
  on challenging manipulation and navigation tasks, yielding, on average, a 200% relative
  improvement over planning with primitive actions on long-horizon tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: farebrother26a
month: 0
tex_title: Compositional Planning with Jumpy World Models
firstpage: 29601
lastpage: 29637
page: 29601-29637
order: 29601
cycles: false
bibtex_author: Farebrother, Jesse and Pirotta, Matteo and Tirinzoni, Andrea and Bellemare,
  Marc G and Lazaric, Alessandro and Touati, Ahmed
author:
- given: Jesse
  family: Farebrother
- given: Matteo
  family: Pirotta
- given: Andrea
  family: Tirinzoni
- given: Marc G
  family: Bellemare
- given: Alessandro
  family: Lazaric
- given: Ahmed
  family: Touati
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/farebrother26a/farebrother26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
