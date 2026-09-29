---
title: 'ViTok-v2: Scaling Native Resolution Autoencoders to 5 Billion Parameters'
openreview: GkNfX22VXf
abstract: 'Vision Transformer (ViT) tokenizers offer a scalable alternative to convolutional
  auto-encoders, yet current architectures have two key limitations: their performance
  degrades when images vary in aspect ratio or resolution, and their reliance on adversarial
  losses makes them harder to train at scale. To address this, we introduce ViTok-v2,
  a ViT tokenizer building on ViTok. We add native resolution support via NaFlex with
  2D RoPE and stabilize training by replacing the standard LPIPS-plus-discriminator
  objective with our novel DINO perceptual loss. We scale our model to 5B parameters,
  training the largest ViT-based image compression autoencoder to date and demonstrate
  continued improvements with scale. In downstream generation experiments with flow
  matching models, we find that smaller generators perform best with aggressive channel
  compression while larger generators effectively leverage higher channel counts.
  ViTokv2 matches state-of-the-art reconstruction at 256p and outperforms across benchmarks
  at 512p and higher resolutons, while remaining compatible with any pipeline requiring
  flexible aspect ratios.'
software: https://github.com/Na-VAE/vitok-release
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hansen-estruch26a
month: 0
tex_title: "{V}i{T}ok-v2: Scaling Native Resolution Autoencoders to 5 Billion Parameters"
firstpage: 40405
lastpage: 40419
page: 40405-40419
order: 40405
cycles: false
bibtex_author: Hansen-Estruch, Philippe and Chen, Jiahui and Ramanujan, Vivek and
  Zohar, Orr and Georgopoulos, Markos and Sinha, Animesh and Hou, Ji and Sch\"{o}nfeld,
  Edgar and Juefei-Xu, Felix and Vishwanath, Sriram and Thabet, Ali
author:
- given: Philippe
  family: Hansen-Estruch
- given: Jiahui
  family: Chen
- given: Vivek
  family: Ramanujan
- given: Orr
  family: Zohar
- given: Markos
  family: Georgopoulos
- given: Animesh
  family: Sinha
- given: Ji
  family: Hou
- given: Edgar
  family: Schönfeld
- given: Felix
  family: Juefei-Xu
- given: Sriram
  family: Vishwanath
- given: Ali
  family: Thabet
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hansen-estruch26a/hansen-estruch26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
