---
title: Operationalising the Superficial Alignment Hypothesis via Task Complexity
openreview: W1P3l4rI60
abstract: 'The superficial alignment hypothesis (SAH) posits that large language models
  learn most of their knowledge during pre-training, and that post-training merely
  surfaces this knowledge. The SAH, however, lacks a precise definition, which has
  led to (i) different and seemingly orthogonal arguments supporting it, and (ii)
  important critiques to it. We propose a new metric called <b>task complexity</b>:
  the length of the shortest program that achieves a target performance on a task.
  In this framework, the SAH simply claims that pre-trained models drastically reduce
  the complexity of achieving high performance on many tasks. Our definition unifies
  prior arguments supporting the SAH, interpreting them as different strategies to
  find such short programs. Experimentally, we estimate the task complexity of mathematical
  reasoning, machine translation, and instruction following; we then show that these
  complexities can be remarkably low when conditioned on a pre-trained model. Further,
  we find that pre-training enables access to strong performances on our tasks, but
  it can require programs of gigabytes of length to access them. Post-training, on
  the other hand, collapses the complexity of reaching this same performance by several
  orders of magnitude. Overall, our results highlight that task adaptation often requires
  surprisingly little information—often just a few kilobytes'
software: https://github.com/tvergara/sah
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vergara-browne26a
month: 0
tex_title: Operationalising the Superficial Alignment Hypothesis via Task Complexity
firstpage: 123795
lastpage: 123815
page: 123795-123815
order: 123795
cycles: false
bibtex_author: Vergara Browne, Tom\'{a}s and Patil, Darshan and Titov, Ivan and Reddy,
  Siva and Pimentel, Tiago and Mosbach, Marius
author:
- given: Tomás
  family: Vergara Browne
- given: Darshan
  family: Patil
- given: Ivan
  family: Titov
- given: Siva
  family: Reddy
- given: Tiago
  family: Pimentel
- given: Marius
  family: Mosbach
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/vergara-browne26a/vergara-browne26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
