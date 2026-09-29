---
title: 'How Reasoning Evolves from Post-Training Data: An Empirical Study Using Chess'
openreview: w0y3obJwmh
abstract: We study how reasoning evolves in a language model – from supervised fine-tuning
  (SFT) to reinforcement learning (RL) – by analyzing how a set of theoretically-inspired
  datasets impacts language model performance in chess. We find that fine-tuning a
  model to directly predict the best move leads to effective RL and the strongest
  downstream performance – however, the RL stage elicits <em>unfaithful</em> reasoning
  (reasoning inconsistent with the chosen move). Alternatively, training on multi-move
  trajectories yields comparable downstream performance with faithful reasoning and
  more stable RL. We show that RL induces a substantial positive shift in the distribution
  of move quality and reduces hallucination rates as a side effect. Finally, we find
  several SFT-checkpoint metrics – metrics spanning evaluation performance, hallucination
  rates, and reasoning quality – to be predictive of post-RL model performance. We
  release checkpoints and final models as well as training data, evaluations, and
  code that allowed us to surpass leading open-source reasoning models in chess with
  a 7B-parameter model.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dionisopoulos26a
month: 0
tex_title: 'How Reasoning Evolves from Post-Training Data: An Empirical Study Using
  Chess'
firstpage: 25451
lastpage: 25482
page: 25451-25482
order: 25451
cycles: false
bibtex_author: Dionisopoulos, Lucas and Majamaki, Nicklas and Ammanabrolu, Prithviraj
author:
- given: Lucas
  family: Dionisopoulos
- given: Nicklas
  family: Majamaki
- given: Prithviraj
  family: Ammanabrolu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/dionisopoulos26a/dionisopoulos26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
