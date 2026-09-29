---
title: 'Dirichlet-Prior Shaping: Guiding Expert Specialization in Upcycled MoEs'
openreview: BfkrQiC0Ss
abstract: Upcycling pre-trained dense models into sparse Mixture-of-Experts (MoEs)
  efficiently increases model capacity but often suffers from poor expert specialization
  due to naive weight replication. We introduce Dirichlet-Prior Shaping Loss (DPSL),
  a novel router regularization technique that directly shapes routing probability
  distributions by matching expert assignments to a target Dirichlet prior resulting
  in enhanced expert specialization. DPSL enables encoding of inductive biases such
  as encouraging experts to focus on specific modalities or tasks, without requiring
  manual intervention. DPSL is a general tool applicable to any module that outputs
  categorical probability distributions, extending its utility beyond MoE training.
  Experiments on upcycled MoE vision-language models show that DPSL consistently outperforms
  upcycling strategies and regularization techniques across standard vision-language
  benchmarks, addressing the critical issue of poor specialization and fostering higher-performing
  models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mirvakhabova26a
month: 0
tex_title: "{D}irichlet-Prior Shaping: Guiding Expert Specialization in Upcycled {M}o{E}s"
firstpage: 89134
lastpage: 89155
page: 89134-89155
order: 89134
cycles: false
bibtex_author: Mirvakhabova, Leyla and Ehteshami Bejnordi, Babak and Kumar, Gaurav
  and Liang, Hanxue and Zhao, Wanru and Whatmough, Paul N.
author:
- given: Leyla
  family: Mirvakhabova
- given: Babak
  family: Ehteshami Bejnordi
- given: Gaurav
  family: Kumar
- given: Hanxue
  family: Liang
- given: Wanru
  family: Zhao
- given: Paul N.
  family: Whatmough
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/mirvakhabova26a/mirvakhabova26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
