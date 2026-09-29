---
title: Learning to Discover at Test Time
openreview: 96zNuQrH9Y
abstract: 'How can we use AI to discover a new state of the art for a scientific problem?
  Prior work in test-time scaling, such as AlphaEvolve, performs search by prompting
  a frozen LLM. We perform reinforcement learning at test time, so the LLM can continue
  to train, but now with experience specific to the test problem. This form of continual
  learning is quite special, because its goal is to produce one great solution rather
  than many good ones on average, and to solve this very problem rather than generalize
  to other problems. Therefore, our learning objective and search subroutine are designed
  to prioritize the most promising solutions. We call this method Test-Time Training
  to Discover (TTT-Discover). Following prior work, we focus on problems with continuous
  rewards. We report results for every problem we attempted, across mathematics, GPU
  kernel engineering, algorithm design, and biology. TTT-Discover sets the new state
  of the art in almost all of them: (i) Erdős’ minimum overlap problem and an autocorrelation
  inequality; (ii) a GPUMode kernel competition (up to 2$\times$ faster than prior
  art); (iii) past AtCoder algorithm competitions; and (iv) denoising problem in single-cell
  analysis. Our solutions are reviewed by experts or the organizers. All our results
  are achieved with an open model, OpenAI gpt-oss-120b, and can be reproduced with
  our publicly available code, in contrast to previous best results that required
  closed frontier models. Our test-time training runs are performed using Tinker,
  an API by Thinking Machines, with a cost of only a few hundred dollars per problem.'
software: https://github.com/test-time-training/discover
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: yuksekgonul26a
month: 0
tex_title: Learning to Discover at Test Time
firstpage: 152432
lastpage: 152496
page: 152432-152496
order: 152432
cycles: false
bibtex_author: Yuksekgonul, Mert and Koceja, Daniel and Li, Xinhao and Bianchi, Federico
  and Mccaleb, Jed and Wang, Xiaolong and Kautz, Jan and Choi, Yejin and Zou, James
  and Guestrin, Carlos and Sun, Yu
author:
- given: Mert
  family: Yuksekgonul
- given: Daniel
  family: Koceja
- given: Xinhao
  family: Li
- given: Federico
  family: Bianchi
- given: Jed
  family: Mccaleb
- given: Xiaolong
  family: Wang
- given: Jan
  family: Kautz
- given: Yejin
  family: Choi
- given: James
  family: Zou
- given: Carlos
  family: Guestrin
- given: Yu
  family: Sun
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/yuksekgonul26a/yuksekgonul26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
