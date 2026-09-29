---
title: Abductive Reasoning with Probabilistic Commonsense
openreview: SayI5V4CBC
abstract: Recent efforts to improve the reasoning abilities of Large Language Models
  (LLMs) have focused on integrating formal logic solvers within neurosymbolic frameworks.
  A key challenge is that formal solvers lack commonsense world knowledge, preventing
  them from making reasoning steps that humans find obvious. Prior methods address
  this by using LLMs to supply missing commonsense assumptions, but these approaches
  implicitly assume universal agreement on such commonsense facts. In reality, commonsense
  beliefs vary across individuals. We propose a probabilistic framework for abductive
  commonsense reasoning that explicitly models this variation, aiming to determine
  whether most people would judge a statement as true or false. We introduce Probabilistic
  Abductive CommonSense (PACS), a novel algorithm that uses an LLM and a formal solver
  to sample proofs as observations of individuals’ distinct commonsense beliefs, and
  aggregates conclusions across these samples. Empirically, PACS outperforms chain-of-thought
  reasoning, prior neurosymbolic methods, and search-based approaches across multiple
  benchmarks.
software: https://github.com/networkslab/PACS
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cotnareanu26a
month: 0
tex_title: Abductive Reasoning with Probabilistic Commonsense
firstpage: 21584
lastpage: 21595
page: 21584-21595
order: 21584
cycles: false
bibtex_author: Cotnareanu, Joseph and Roverato, Chiara and Zhou, Han and Ch\'{e}telat,
  Didier and Zhang, Yingxue and Coates, Mark
author:
- given: Joseph
  family: Cotnareanu
- given: Chiara
  family: Roverato
- given: Han
  family: Zhou
- given: Didier
  family: Chételat
- given: Yingxue
  family: Zhang
- given: Mark
  family: Coates
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/cotnareanu26a/cotnareanu26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
