---
title: Intentional Updates for Streaming Reinforcement Learning
openreview: K9lUSMMI0h
abstract: 'In gradient-based learning, a step size chosen in parameter units does
  not produce a predictable per-step change in function output. This often leads to
  instability in the streaming setting (i.e., batch size$=1$), where stochasticity
  is not averaged out and update magnitudes can momentarily become arbitrarily big
  or small. Instead, we propose intentional updates: first specify the intended outcome
  of an update and then solve for the step size that approximately achieves it. This
  strategy has precedent in online supervised linear regression via Normalized Least
  Mean Squares (NLMS) algorithm, which selects a step size to yield a specified change
  in the function output proportional to the current error. We extend this principle
  to streaming deep reinforcement learning by defining appropriate intended outcomes:
  Intentional TD aims for a fixed fractional reduction of the TD error, and Intentional
  Policy Gradient aims for a bounded per-step change in the policy, limiting local
  KL divergence. We propose practical algorithms combining eligibility traces and
  diagonal scaling. Empirically, these methods yield state-of-the-art streaming performance,
  frequently performing on par with batch and replay-buffer approaches.'
software: https://github.com/sharifnassab/Intentional_RL
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sharifnassab26a
month: 0
tex_title: Intentional Updates for Streaming Reinforcement Learning
firstpage: 110478
lastpage: 110496
page: 110478-110496
order: 110478
cycles: false
bibtex_author: Sharifnassab, Arsalan and Elsayed, Mohamed and De Asis, Kris and Mahmood,
  A. Rupam and Sutton, Richard S
author:
- given: Arsalan
  family: Sharifnassab
- given: Mohamed
  family: Elsayed
- given: Kris
  family: De Asis
- given: A. Rupam
  family: Mahmood
- given: Richard S
  family: Sutton
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/sharifnassab26a/sharifnassab26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
