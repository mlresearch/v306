---
title: 'KAGE-Bench: Fast Known-Axis Visual Generalization Evaluation for Reinforcement
  Learning'
openreview: fTwFUnHvKr
abstract: 'Pixel-based reinforcement learning agents often fail under purely visual
  distribution shift even when latent dynamics and rewards are unchanged, but existing
  benchmarks entangle multiple sources of shift and hinder systematic analysis. We
  introduce KAGE-Env, a JAX-native 2D platformer that factorizes the observation process
  into independently controllable visual axes while keeping the underlying control
  problem fixed. By construction, varying a visual axis affects performance only through
  the induced state-conditional action distribution of a pixel policy, providing a
  clean abstraction for visual generalization. Building on this environment, we define
  KAGE-Bench, a benchmark of six known-axis suites comprising 34 train-evaluation
  configuration pairs that isolate individual visual shifts. Using a standard PPO-CNN
  baseline, we observe strong axis-dependent failures, with background and photometric
  shifts often collapsing success, while agent-appearance shifts are comparatively
  benign. Several shifts preserve forward motion while breaking task completion, showing
  that return alone can obscure generalization failures. Finally, the fully vectorized
  JAX implementation enables up to 33M environment steps per second on a single GPU,
  enabling fast and reproducible sweeps over visual factors. Code: https://avanturist322.github.io/KAGEBench/'
software: https://avanturist322.github.io/KAGEBench/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cherepanov26a
month: 0
tex_title: "{KAGE}-Bench: Fast Known-Axis Visual Generalization Evaluation for Reinforcement
  Learning"
firstpage: 19313
lastpage: 19353
page: 19313-19353
order: 19313
cycles: false
bibtex_author: Cherepanov, Egor and Zelezetsky, Daniil and Panov, Aleksandr and Kovalev,
  Alexey
author:
- given: Egor
  family: Cherepanov
- given: Daniil
  family: Zelezetsky
- given: Aleksandr
  family: Panov
- given: Alexey
  family: Kovalev
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/cherepanov26a/cherepanov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
