---
title: Steering Out-of-Distribution Generalization with Concept Ablation Fine-Tuning
openreview: yuJehN4oMW
abstract: Fine-tuning large language models (LLMs) can lead to unintended out-of-distribution
  generalization. Standard approaches to this problem rely on modifying the training
  data, for example by adding data that better specify the intended generalization.
  However, this is not always practical. We introduce Concept Ablation Fine-Tuning
  (CAFT), a technique that leverages interpretability tools to control how LLMs generalize
  from fine-tuning, without needing to modify the training data or otherwise use data
  from the target distribution. Given a set of directions in an LLM’s latent space
  corresponding to undesired concepts, CAFT works by ablating these concepts with
  linear projections during fine-tuning, steering the model away from unintended generalizations.
  We successfully apply CAFT to three fine-tuning tasks, including emergent misalignment,
  a phenomenon where LLMs fine-tuned on a narrow task generalize to give egregiously
  misaligned responses to general questions. Without any changes to the fine-tuning
  data, CAFT reduces misaligned responses by 10x without degrading performance on
  the training distribution. Overall, CAFT represents a novel approach for steering
  LLM generalization without modifying training data.
software: https://github.com/cadentj/caft
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: casademunt26a
month: 0
tex_title: Steering Out-of-Distribution Generalization with Concept Ablation Fine-Tuning
firstpage: 11922
lastpage: 11975
page: 11922-11975
order: 11922
cycles: false
bibtex_author: Casademunt, Helena and Juang, Caden and Karvonen, Adam and Marks, Samuel
  and Rajamanoharan, Senthooran and Nanda, Neel
author:
- given: Helena
  family: Casademunt
- given: Caden
  family: Juang
- given: Adam
  family: Karvonen
- given: Samuel
  family: Marks
- given: Senthooran
  family: Rajamanoharan
- given: Neel
  family: Nanda
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/casademunt26a/casademunt26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
