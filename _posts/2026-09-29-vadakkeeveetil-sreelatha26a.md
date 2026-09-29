---
title: 'RAIGen: Rare Attribute Identification in Text-to-Image Generative Models'
openreview: oXxf72fqb6
abstract: 'Text-to-image diffusion models achieve impressive generation quality but
  inherit and amplify training-data biases, skewing coverage of semantic attributes.
  Prior work addresses this in two ways. Closed-set approaches mitigate biases in
  predefined fairness categories (e.g., gender, race), assuming socially salient minority
  attributes are known a priori. Open-set approaches frame the task as bias identification,
  highlighting majority attributes that dominate outputs. Both overlook a complementary
  task: uncovering rare or minority features underrepresented in the data distribution
  (social, cultural, or stylistic) yet still encoded in model representations. We
  introduce RAIGen, the first framework, to our knowledge, for label-free rare-attribute
  discovery in diffusion models, requiring no predefined minority categories. RAIGen
  leverages Matryoshka Sparse Autoencoders and a novel minority metric combining neuron
  activation frequency with semantic distinctiveness to identify interpretable neurons
  whose top-activating images reveal underrepresented attributes. Experiments show
  RAIGen discovers attributes beyond fixed fairness categories in Stable Diffusion,
  scales to larger models such as SDXL, supports systematic auditing across architectures,
  and enables targeted amplification of rare attributes during generation. The project
  page is available at https://vssilpa.github.io/RAIGen_webpage/.'
software: https://github.com/VSSILPA/RAIGen
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vadakkeeveetil-sreelatha26a
month: 0
tex_title: "{RAIG}en: Rare Attribute Identification in Text-to-Image Generative Models"
firstpage: 123203
lastpage: 123233
page: 123203-123233
order: 123203
cycles: false
bibtex_author: Vadakkeeveetil Sreelatha, Silpa and Wang, Dan and Belongie, Serge and
  Awais, Muhammad and Dutta, Anjan
author:
- given: Silpa
  family: Vadakkeeveetil Sreelatha
- given: Dan
  family: Wang
- given: Serge
  family: Belongie
- given: Muhammad
  family: Awais
- given: Anjan
  family: Dutta
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/vadakkeeveetil-sreelatha26a/vadakkeeveetil-sreelatha26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
