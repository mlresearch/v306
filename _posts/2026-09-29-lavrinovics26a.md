---
title: 'MultiHal: Multilingual Dataset for Knowledge-Graph Grounded Evaluation of
  LLM Hallucinations'
openreview: kGSwStubjL
abstract: Large Language Models (LLMs) have inherent limitations of faithfulness and
  factuality, commonly referred to as hallucinations. Several benchmarks have been
  developed that provide a test bed for factuality evaluation within the context of
  English-centric datasets, while relying on supplementary informative context like
  web links or text passages but ignoring the available structured factual resources.
  To this end, Knowledge Graphs (KGs) have been identified as a useful aid for hallucination
  mitigation, as they provide a structured way to represent the facts about entities
  and their relations with minimal linguistic overhead. We bridge the lack of KG paths
  and multilinguality for factual language modeling within the existing hallucination
  evaluation benchmarks and propose a KG-based multilingual, multihop benchmark called
  MultiHal framed for generative text evaluation. As part of our data collection pipeline,
  we mined 140k KG-paths from open-domain KGs, from which we pruned noisy KG-paths,
  curating a high-quality subset of 25.9k. Our baseline evaluation shows an absolute
  scale improvement by approximately 0.12 to 0.36 points for the semantic similarity
  score, 0.16 to 0.36 for NLI entailment and 0.29 to 0.42 for hallucination detection
  in KG-RAG over vanilla QA across multiple languages and multiple models, demonstrating
  the potential of KG integration. We anticipate MultiHal will foster future research
  towards several graph-based hallucination mitigation and fact-checking tasks.
software: https://github.com/ernlavr/multihal
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lavrinovics26a
month: 0
tex_title: "{M}ulti{H}al: Multilingual Dataset for Knowledge-Graph Grounded Evaluation
  of {LLM} Hallucinations"
firstpage: 62914
lastpage: 62940
page: 62914-62940
order: 62914
cycles: false
bibtex_author: Lavrinovics, Ernests and Biswas, Russa and Hose, Katja and Bjerva,
  Johannes
author:
- given: Ernests
  family: Lavrinovics
- given: Russa
  family: Biswas
- given: Katja
  family: Hose
- given: Johannes
  family: Bjerva
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/lavrinovics26a/lavrinovics26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
