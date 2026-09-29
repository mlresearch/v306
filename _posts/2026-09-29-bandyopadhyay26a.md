---
title: 'RSF-GLLM: Bridging the Semantic Gap in Multi-Hop Knowledge Graph QA via Recurrent
  Soft-Flow and Decoupled LLM Generation'
openreview: iSNHlYLxsw
abstract: 'Multi-hop Question Answering over Knowledge Graphs faces a critical challenge:
  traditional retrieve-then-read pipelines break differentiability, preventing the
  retriever from learning to bridge the semantic gap where intermediate nodes lack
  lexical overlap with the query. To address this, we propose RSF-GLLM, a framework
  decoupling differentiable graph reasoning from answer generation. Our Recurrent
  Soft-Flow (RSF) module employs a GRU-guided query updater to propagate continuous
  relevance scores, utilizing a dynamic gating mechanism to traverse semantically
  dissimilar bridge nodes via structural cues. We introduce flow sparsity regularization
  to theoretically guarantee convergence from soft probabilities to discrete reasoning
  paths. These paths are extracted and textualized to fine-tune a Large Language Model
  (LLM), ensuring generation is grounded in factual topology. Experiments on WebQSP
  and CWQ demonstrate that RSF-GLLM achieves competitive performance with superior
  inference efficiency compared to LLM based computationally expensive approaches.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bandyopadhyay26a
month: 0
tex_title: "{RSF}-{GLLM}: Bridging the Semantic Gap in Multi-Hop Knowledge Graph {QA}
  via Recurrent Soft-Flow and Decoupled {LLM} Generation"
firstpage: 6151
lastpage: 6171
page: 6151-6171
order: 6151
cycles: false
bibtex_author: Bandyopadhyay, Sambaran and Muppidi, Ananth
author:
- given: Sambaran
  family: Bandyopadhyay
- given: Ananth
  family: Muppidi
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/bandyopadhyay26a/bandyopadhyay26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
