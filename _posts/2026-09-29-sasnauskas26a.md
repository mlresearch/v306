---
title: Robust In-Context Reinforcement Learning Under Reward Poisoning Attacks
openreview: s8AbIVtmUg
abstract: We study the corruption-robustness of in-context reinforcement learning
  (ICRL), focusing on the Decision-Pretrained Transformer (DPT, Lee et al., 2023).
  To address the challenge of reward poisoning attacks targeting the DPT, we propose
  a novel adversarial training framework, called Adversarially Trained DPT (AT-DPT).
  Our method simultaneously trains a population of attackers to minimize the true
  reward of the DPT by poisoning environment rewards, and a DPT model to infer optimal
  actions from the poisoned data. We evaluate the effectiveness of our approach against
  standard bandit algorithms, including robust baselines designed to handle reward
  contamination. Our results show that AT-DPT significantly outperforms them in bandit
  settings under a learned attacker, and generalizes to more complex environments
  such as adaptive attackers and MDPs. It shows promise in ICRL as a meta-RL approach
  to learning effective corruption-robust algorithms.
software: https://github.com/PauliusSasnauskas/AT-DPT
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sasnauskas26a
month: 0
tex_title: Robust In-Context Reinforcement Learning Under Reward Poisoning Attacks
firstpage: 107838
lastpage: 107862
page: 107838-107862
order: 107838
cycles: false
bibtex_author: Sasnauskas, Paulius and Yal{\i}n, Yi\u{g}it and Radanovic, Goran
author:
- given: Paulius
  family: Sasnauskas
- given: Yiğit
  family: Yalın
- given: Goran
  family: Radanovic
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/sasnauskas26a/sasnauskas26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
