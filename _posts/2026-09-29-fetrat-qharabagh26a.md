---
title: Learning to Execute Graph Algorithms Exactly with Graph Neural Networks
openreview: YKEmoqwkE9
abstract: Understanding what graph neural networks can learn, especially their ability
  to learn to execute algorithms, remains a central theoretical challenge. In this
  work, we prove exact learnability results for graph algorithms under bounded-degree
  and finite-precision constraints. Our approach follows a two-step process. First,
  we train an ensemble of multi-layer perceptrons (MLPs) to execute the local instructions
  of a single node. Second, during inference, we use the trained MLP ensemble as the
  update function within a graph neural network (GNN). Leveraging Neural Tangent Kernel
  (NTK) theory, we show that local instructions can be learned from a small training
  set, enabling the complete graph algorithm to be executed during inference without
  error and with high probability. To illustrate the learning power of our setting,
  we establish a rigorous learnability result for the LOCAL model of distributed computation.
  We further demonstrate positive learnability results for widely studied algorithms
  such as message flooding, breadth-first and depth-first search, and Bellman-Ford.
software: https://github.com/watcl-lab/exact_gnn
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fetrat-qharabagh26a
month: 0
tex_title: Learning to Execute Graph Algorithms Exactly with Graph Neural Networks
firstpage: 30992
lastpage: 31124
page: 30992-31124
order: 30992
cycles: false
bibtex_author: Fetrat Qharabagh, Muhammad and Back De Luca, Artur and Giapitzakis,
  George and Fountoulakis, Kimon
author:
- given: Muhammad
  family: Fetrat Qharabagh
- given: Artur
  family: Back De Luca
- given: George
  family: Giapitzakis
- given: Kimon
  family: Fountoulakis
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/fetrat-qharabagh26a/fetrat-qharabagh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
