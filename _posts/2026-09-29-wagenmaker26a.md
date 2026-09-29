---
title: 'Posterior Behavioral Cloning: Pretraining BC Policies for Efficient RL Finetuning'
openreview: HJ5F3R9Tmd
abstract: Standard practice across domains from robotics to language is to first pretrain
  a policy on a large-scale demonstration dataset, and then finetune this policy,
  typically with reinforcement learning (RL), in order to improve performance on deployment
  domains. This finetuning step has proved critical in achieving human or super-human
  performance, yet while much attention has been given to developing more effective
  finetuning algorithms, little attention has been given to ensuring the pretrained
  policy is an effective initialization for RL finetuning. In this work we seek to
  understand how the pretrained policy affects finetuning performance, and how to
  pretrain policies in order to ensure they are effective initializations for finetuning.
  We first show theoretically that standard behavioral cloning (BC) can fail to ensure
  coverage over the demonstrator’s actions, a minimal condition necessary for effective
  RL finetuning. We then show that if, instead of exactly fitting the observed demonstrations,
  we train a policy to model the posterior distribution of the demonstrator’s behavior
  given the demonstration dataset, we do obtain a policy that ensures coverage over
  the demonstrator’s actions, enabling more effective finetuning. Furthermore, this
  policy achieves this while ensuring pretrained performance is no worse than that
  of the BC policy. We then show this approach is practically implementable with modern
  generative models and leads to significantly improved RL finetuning performance
  on both realistic robotic control benchmarks and real-world robotic manipulation
  tasks, as compared to standard behavioral cloning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wagenmaker26a
month: 0
tex_title: 'Posterior Behavioral Cloning: Pretraining {BC} Policies for Efficient
  {RL} Finetuning'
firstpage: 124171
lastpage: 124204
page: 124171-124204
order: 124171
cycles: false
bibtex_author: Wagenmaker, Andrew and Dong, Perry and Tsao, Raymond and Finn, Chelsea
  and Levine, Sergey
author:
- given: Andrew
  family: Wagenmaker
- given: Perry
  family: Dong
- given: Raymond
  family: Tsao
- given: Chelsea
  family: Finn
- given: Sergey
  family: Levine
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/wagenmaker26a/wagenmaker26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
