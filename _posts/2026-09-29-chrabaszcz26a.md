---
title: Efficient LLM Moderation with Multi-Layer Latent Prototypes
openreview: IdfwoUzREG
abstract: Although modern LLMs are aligned with human values during post-training,
  robust moderation remains essential to prevent harmful outputs at deployment time.
  Existing approaches suffer from performance-efficiency trade-offs and are difficult
  to customize to user-specific requirements. Motivated by this gap, we introduce
  Multi-Layer Prototype Moderator (MLPM), a lightweight and highly customizable input
  moderation tool. We propose leveraging prototypes of intermediate representations
  across multiple layers to improve moderation quality while maintaining high efficiency.
  By design, our method adds negligible overhead to the generation pipeline and can
  be seamlessly applied to any model. MLPM achieves state-of-the-art performance on
  diverse moderation benchmarks and demonstrates strong scalability across model families
  of various sizes. Moreover, we show that it integrates smoothly into end-to-end
  moderation pipelines and further improves response safety when combined with output
  moderation techniques. Overall, our work provides a practical and adaptable solution
  for safe, robust, and efficient LLM deployment.
software: https://github.com/maciejchrabaszcz/latent-prototype-moderator
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chrabaszcz26a
month: 0
tex_title: Efficient {LLM} Moderation with Multi-Layer Latent Prototypes
firstpage: 20660
lastpage: 20685
page: 20660-20685
order: 20660
cycles: false
bibtex_author: Chrabaszcz, Maciej and Szatkowski, Filip and W\'{o}jcik, Bartosz and
  Dubi\'{n}ski, Jan and Trzcinski, Tomasz and Cygert, Sebastian
author:
- given: Maciej
  family: Chrabaszcz
- given: Filip
  family: Szatkowski
- given: Bartosz
  family: Wójcik
- given: Jan
  family: Dubiński
- given: Tomasz
  family: Trzcinski
- given: Sebastian
  family: Cygert
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/chrabaszcz26a/chrabaszcz26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
