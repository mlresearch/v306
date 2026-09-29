---
title: Guided Star-Shaped Masked Diffusion
openreview: ktRyGKpt9U
abstract: The performance of pre-trained masked diffusion models is often constrained
  by their sampling procedure, which makes decisions irreversible and struggles in
  low-step generation regimes. We introduce a novel sampling algorithm that works
  with pre-trained models and, after a lightweight fine-tuning of a single layer,
  significantly improves sample quality and efficiency. Our method reformulates the
  generation process using a star-shaped paradigm, which inherently allows for error
  correction. To make this process effective, we augment it with a learnable remasking
  module that intelligently identifies and revises likely errors. This approach yields
  a substantial quality boost, particularly when using a small number of sampling
  steps. We extensively ablate key components of our approach and show its usability
  in different scenarios. In experiments on text, and code generation, our sampling
  algorithm outperforms or matches existing methods. Code is available at https://github.com/EgorShibaev/G-Star.
software: https://github.com/EgorShibaev/G-Star
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: meshchaninov26a
month: 0
tex_title: Guided Star-Shaped Masked Diffusion
firstpage: 88261
lastpage: 88286
page: 88261-88286
order: 88261
cycles: false
bibtex_author: Meshchaninov, Viacheslav and Shibaev, Egor and Makoian, Artem and Klimov,
  Ivan and Balagansky, Nikita and Gavrilov, Daniil and Alanov, Aibek and Vetrov, Dmitry
author:
- given: Viacheslav
  family: Meshchaninov
- given: Egor
  family: Shibaev
- given: Artem
  family: Makoian
- given: Ivan
  family: Klimov
- given: Nikita
  family: Balagansky
- given: Daniil
  family: Gavrilov
- given: Aibek
  family: Alanov
- given: Dmitry
  family: Vetrov
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/meshchaninov26a/meshchaninov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
