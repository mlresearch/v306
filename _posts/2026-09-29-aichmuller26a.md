---
title: Learning to Search and Searching to Learn for Generalization in Planning
openreview: Ck6Ort0wqc
abstract: 'Combinatorial generalization remains a central challenge in Deep Reinforcement
  Learning (DRL). Classical planning provides a simple yet challenging setting to
  study this problem through explicit relational descriptions, without requiring learning
  from perception. In sparse-reward domains, standard RL exploration via real-time
  search is ineffective, and learning-based planning methods often rely on expert
  demonstrations, hindsight relabeling, or random walks from the goal state. In contrast,
  planners rely on best-first search methods such as $\mathrm{A}^\star$ to solve problems
  from scratch. We propose a self-improving $\mathrm{WA}^\star$ learning framework
  in combination with a value heuristic represented by a Relational Graph Neural Network:
  the heuristic guides search, and the resulting search data updates the heuristic
  via $Q$-learning. This loop yields heuristics that can function as general policies
  and solve new instances even without search, where DRL otherwise fails, as we show
  on puzzles such as Sokoban, PushWorld, The Witness, and the 2023 International Planning
  Competition benchmarks. Notably, we demonstrate strong zero-shot generalization:
  For example, heuristics trained on Blocksworld instances with fewer than $30$ blocks
  successfully solve instances with $488$ blocks without search.'
software: https://github.com/maichmueller/generalized-search-for-planning
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aichmuller26a
month: 0
tex_title: Learning to Search and Searching to Learn for Generalization in Planning
firstpage: 1434
lastpage: 1450
page: 1434-1450
order: 1434
cycles: false
bibtex_author: Aichm\"{u}ller, Michael and Hesse, Yannik and Geffner, Hector
author:
- given: Michael
  family: Aichmüller
- given: Yannik
  family: Hesse
- given: Hector
  family: Geffner
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/aichmuller26a/aichmuller26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
