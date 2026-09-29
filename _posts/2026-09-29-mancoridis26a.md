---
title: 'The Consistency Dilemma in LLMs: Generator-Evaluator Agreement and Vulnerability
  to Mistakes'
openreview: 07wKh5x0Ef
abstract: 'Large language models are increasingly deployed in agentic pipelines that
  depend on the model evaluating its own outputs without external verification. The
  reliability of these pipelines depends on an implicit assumption: that the model
  applies relevant concepts the same way when it generates an output and later evaluates
  that output. We propose a new measure, <em>generator–evaluator self-consistency</em>,
  to test this assumption directly and apply it to 10 frontier models across 491 concepts.
  We find, first, that there is substantial variation in self-consistency. Second,
  we find that in a clinical setting with physician-validated mistakes (Proniakin
  et al., 2025), across models, those with higher self-consistency are linked to <em>greater</em>
  vulnerability to mistakes. Thus, even when models consistently apply concepts they
  may not be safe to deploy. This is evidence of a <em>consistency dilemma</em> in
  LLMs: self-consistency is operationally useful, but models that are more consistent
  are also more prone to mistakes.'
software: https://github.com/MarinaMancoridis/ConsistencyDilemma
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mancoridis26a
month: 0
tex_title: 'The Consistency Dilemma in {LLM}s: Generator-Evaluator Agreement and Vulnerability
  to Mistakes'
firstpage: 86097
lastpage: 86142
page: 86097-86142
order: 86097
cycles: false
bibtex_author: Mancoridis, Marina and Hitzig, Zoe
author:
- given: Marina
  family: Mancoridis
- given: Zoe
  family: Hitzig
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/mancoridis26a/mancoridis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
