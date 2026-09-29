---
title: 'CoFrGeNet: Continued Fraction Architectures for Language Generation'
openreview: wjc6oz63WL
abstract: Transformers are arguably the preferred architecture for language generation.
  In this paper, inspired by continued fractions, we introduce a new function class
  for generative modeling. The architecture family implementing this function class
  is named CoFrGeNets - Continued Fraction Generative Networks. We design novel architectural
  components based on this function class that can replace Multi-head Attention and
  Feed-Forward Networks in Transformer blocks while requiring much fewer parameters.
  We derive custom gradient formulations to optimize the proposed components more
  accurately and efficiently than using standard PyTorch-based gradients. Our components
  are a plug-in replacement requiring little change in training or inference procedures
  that have already been put in place for Transformer-based models thus making our
  approach easy to incorporate in large industrial workflows. We experiment on two
  very different transformer architectures GPT2-xl (1.5B) and Llama3 (3.2B), where
  the former we pre-train on OpenWebText and GneissWeb, while the latter we pre-train
  on the docling data mix which consists of nine different datasets. Results show
  that the performance on downstream classification, Q& A, reasoning and text understanding
  tasks of our models is competitive and sometimes even superior to the original models
  with two thirds to half the parameters and shorter pre-training time. We believe
  that future implementations customized to hardware will further bring out the true
  potential of our architectures.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dhurandhar26a
month: 0
tex_title: "{C}o{F}r{G}e{N}et: Continued Fraction Architectures for Language Generation"
firstpage: 24576
lastpage: 24593
page: 24576-24593
order: 24576
cycles: false
bibtex_author: Dhurandhar, Amit and Chenthamarakshan, Vijil and Wei, Dennis and Pedapati,
  Tejaswini and Natesan Ramamurthy, Karthikeyan and Nair, Rahul
author:
- given: Amit
  family: Dhurandhar
- given: Vijil
  family: Chenthamarakshan
- given: Dennis
  family: Wei
- given: Tejaswini
  family: Pedapati
- given: Karthikeyan
  family: Natesan Ramamurthy
- given: Rahul
  family: Nair
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/dhurandhar26a/dhurandhar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
