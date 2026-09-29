---
title: 'Temporal Difference Calibration in Sequential Tasks: Application to Vision-Language-Action
  Models'
openreview: TIru4KuhcB
abstract: Recent advances in vision-language-action (VLA) models for robotics have
  highlighted the importance of reliable uncertainty quantification in sequential
  tasks. However, assessing and improving calibration in such settings remains mostly
  unexplored, especially when only partial trajectories are observed. In this work,
  we formulate <em>sequential calibration</em> for episodic tasks, where task-success
  confidence is produced along an episode, while success is determined at the end
  of it. We introduce a sequential extension of the Brier score and show that, for
  binary outcomes, its risk minimizer coincides with the VLA policy’s value function.
  This connection bridges uncertainty calibration and reinforcement learning, enabling
  the use of temporal-difference (TD) value estimation as a principled calibration
  mechanism over time. We empirically show that TD calibration improves performance
  relative to the state-of-the-art on simulated and real-robot data. Interestingly,
  we show that when calibrated using TD, the VLA’s single-step action probabilities
  can yield competitive uncertainty estimates, in contrast to recent findings that
  employed different calibration techniques.
software: https://github.com/shellytechnion/TDQC
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: francis-meretzki26a
month: 0
tex_title: 'Temporal Difference Calibration in Sequential Tasks: Application to Vision-Language-Action
  Models'
firstpage: 31491
lastpage: 31521
page: 31491-31521
order: 31491
cycles: false
bibtex_author: Francis-Meretzki, Shelly and Mutti, Mirco and Romano, Yaniv and Tamar,
  Aviv
author:
- given: Shelly
  family: Francis-Meretzki
- given: Mirco
  family: Mutti
- given: Yaniv
  family: Romano
- given: Aviv
  family: Tamar
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/francis-meretzki26a/francis-meretzki26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
