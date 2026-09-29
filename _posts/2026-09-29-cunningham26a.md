---
title: 'Contribution Weights: A Geometrical Analysis of Self-Attention Transformers'
openreview: evMzHrKyYR
abstract: Analyzing attention weights has become a standard approach for interpreting
  the information flow of Large Language Models (LLMs). However, this approach has
  significant limitations as it neglects the geometric properties of the value vectors
  being aggregated. To address this gap, we introduce <em>Contribution Weights</em>,
  a projection-based metric that quantifies a token’s influence by accounting for
  it’s attention weight, value magnitude, and directional alignment with the layer
  output. We demonstrate that contribution weights provide a more faithful measure
  of token importance, consistently outperforming attention-based metrics in identifying
  semantically critical tokens across different decoder-only models, tasks, and datasets.
  Further, our metric enables novel mechanistic analysis of <em>attention sinks</em>.
  While previous work characterized sinks as passive repositories for excess attention,
  we reveal they serve an active functional role, suppressing information through
  a convex relationship between sink rate and output norm, stabilizing representations
  by opposing the semantic drift of low-confidence tokens.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cunningham26a
month: 0
tex_title: 'Contribution Weights: A Geometrical Analysis of Self-Attention Transformers'
firstpage: 22160
lastpage: 22180
page: 22160-22180
order: 22160
cycles: false
bibtex_author: Cunningham, Harry Jake and Muca Cirone, Nicola
author:
- given: Harry Jake
  family: Cunningham
- given: Nicola
  family: Muca Cirone
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/cunningham26a/cunningham26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
