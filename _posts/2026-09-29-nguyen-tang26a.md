---
title: Exact Unlearning in Reinforcement Learning
openreview: oLmwqIhzqj
abstract: We formulate the problem of <em>exact unlearning</em> in reinforcement learning,
  where the goal is to design an efficient framework that enables the removal of any
  user’s data upon deletion request, i.e., the online learner’s output after unlearning
  be <em>indistinguishable</em> from what would have been produced had the deleted
  user never interacted with the learner. For any $\rho >0$, we show that there exists
  a reinforcement learning (RL) algorithm that is $\rho$-TV-stable and supports an
  exact unlearning procedure whose expected computational cost is only a $\rho \sqrt{\ln
  T}$ fraction of the computational cost of retraining from scratch. We construct
  such a $\rho$-TV-stable RL algorithm for tabular Markov decision processes (MDPs),
  which achieves a regret bound of $\mathcal{O}(H^2 \sqrt{SAT} + H^3 S^2 A + {H^{2.5}
  S^2 A}/{\rho})$, where $S, A, H$, and $T$ denote the number of states, the number
  of actions, the episode horizon, and the number of episodes, respectively. We also
  establish a lower bound of $\Omega(H\sqrt{SAT}+{SAH}/{\rho})$ for $\rho$-TV-stable
  RL algorithms, showing that our algorithm is nearly minimax optimal.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nguyen-tang26a
month: 0
tex_title: Exact Unlearning in Reinforcement Learning
firstpage: 92851
lastpage: 92874
page: 92851-92874
order: 92851
cycles: false
bibtex_author: Nguyen-Tang, Thanh and Arora, Raman
author:
- given: Thanh
  family: Nguyen-Tang
- given: Raman
  family: Arora
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/nguyen-tang26a/nguyen-tang26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
