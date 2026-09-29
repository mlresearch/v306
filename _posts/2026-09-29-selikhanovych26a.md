---
title: One-Step Residual Shifting Diffusion for Image Super-Resolution via Distillation
openreview: 3WTFzAFHr3
abstract: Diffusion models for super-resolution (SR) produce high-quality visual results
  but require expensive computational costs. Despite the development of several methods
  to accelerate diffusion-based SR models, some (e.g., SinSR) fail to produce realistic
  perceptual details, while others (e.g., OSEDiff) may hallucinate non-existent structures.
  To overcome these issues, we present <b>RSD</b>, a new distillation method for ResShift.
  Our method is based on training the student network to produce images such that
  a new fake ResShift model trained on them will coincide with the teacher model.
  RSD achieves single-step restoration and outperforms the teacher by a noticeable
  margin in various perceptual metrics (LPIPS, CLIPIQA, MUSIQ). We show that our distillation
  method can surpass SinSR, the other distillation-based method for ResShift, making
  it on par with state-of-the-art diffusion SR distillation methods with limited computational
  costs in terms of perceptual quality. Compared to SR methods based on pre-trained
  text-to-image models, RSD produces competitive perceptual quality and requires fewer
  parameters, GPU memory, and training cost. We provide experimental results on various
  real-world and synthetic datasets, including RealSR, RealSet65, DRealSR, ImageNet,
  and DIV2K. We provide the code at https://github.com/Daniil-Selikhanovych/RSD.
software: https://github.com/Daniil-Selikhanovych/RSD
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: selikhanovych26a
month: 0
tex_title: One-Step Residual Shifting Diffusion for Image Super-Resolution via Distillation
firstpage: 108862
lastpage: 108904
page: 108862-108904
order: 108862
cycles: false
bibtex_author: Selikhanovych, Daniil and Li, David and Leonov, Aleksei and Gushchin,
  Nikita and Kushneriuk, Sergei and Filippov, Alexander and Burnaev, Evgeny and Koshelev,
  Iaroslav Sergeevich and Korotin, Alexander
author:
- given: Daniil
  family: Selikhanovych
- given: David
  family: Li
- given: Aleksei
  family: Leonov
- given: Nikita
  family: Gushchin
- given: Sergei
  family: Kushneriuk
- given: Alexander
  family: Filippov
- given: Evgeny
  family: Burnaev
- given: Iaroslav Sergeevich
  family: Koshelev
- given: Alexander
  family: Korotin
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/selikhanovych26a/selikhanovych26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
