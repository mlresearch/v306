---
title: Updating Parametric Knowledge with Context Distillation Retains Post-Training
  Capabilities
openreview: OJsGhlTayF
abstract: Post-training endows pretrained LLMs with a variety of desirable skills,
  including instruction-following, reasoning, and others. However, these post-trained
  LLMs only encode knowledge up to a cut-off date, necessitating continual adaptation.
  Unfortunately, existing solutions cannot simultaneously learn new knowledge from
  an adaptation document corpora and mitigate the forgetting of earlier learned capabilities.
  To address this, we introduce Distillation via Split Contexts (DiSC), a simple context-distillation
  based approach for continual knowledge adaptation. DiSC derives student and teacher
  distributions by conditioning on distinct segments of the training example and minimizes
  the KL divergence between the shared tokens. This allows us to efficiently apply
  context-distillation without requiring explicit generation steps during training.
  We run experiments on four post-trained models and two adaptation domains. Compared
  to prior finetuning and distillation methods for continual adaptation, DiSC consistently
  reports the best trade-off between learning new knowledge and mitigating forgetting
  of previously learned skills like instruction-following, reasoning, and factual
  knowledge.
software: https://github.com/shankarp8/distillation-retains-capabilities
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: padmanabhan26a
month: 0
tex_title: Updating Parametric Knowledge with Context Distillation Retains Post-Training
  Capabilities
firstpage: 95479
lastpage: 95495
page: 95479-95495
order: 95479
cycles: false
bibtex_author: Padmanabhan, Shankar and Gul, Mustafa Omer and Goyal, Tanya
author:
- given: Shankar
  family: Padmanabhan
- given: Mustafa Omer
  family: Gul
- given: Tanya
  family: Goyal
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/padmanabhan26a/padmanabhan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
