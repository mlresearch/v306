---
title: 'One-shot Conditional Sampling: MMD meets Nearest Neighbors'
openreview: 1KEObQsUKW
abstract: How can we generate samples from a conditional distribution that we never
  fully observe? This question arises across a broad range of applications in both
  modern machine learning and classical statistics, including image post-processing
  in computer vision, approximate posterior sampling in simulation-based inference,
  and conditional distribution modeling in complex data settings. In such settings,
  compared with unconditional sampling, additional feature information can be leveraged
  to enable more adaptive and efficient sampling. Building on this, we introduce Conditional
  Generator using MMD (CGMMD), a novel framework for conditional sampling. Unlike
  many contemporary approaches, our method frames the training objective as a simple,
  adversary-free direct minimization problem. A key feature of CGMMD is its ability
  to produce conditional samples in a single forward pass of the generator, enabling
  practical one-shot sampling with low test-time complexity. We establish rigorous
  theoretical bounds on the loss incurred when sampling from the CGMMD sampler, and
  prove convergence of the estimated distribution to the true conditional distribution.
  In the process, we also develop a uniform concentration result for nearest-neighbor
  based functionals, which may be of independent interest. Finally, we show that CGMMD
  performs competitively on synthetic tasks involving complex conditional densities,
  as well as on practical applications such as image denoising and image super-resolution.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chatterjee26a
month: 0
tex_title: 'One-shot Conditional Sampling: {MMD} meets Nearest Neighbors'
firstpage: 13115
lastpage: 13163
page: 13115-13163
order: 13115
cycles: false
bibtex_author: Chatterjee, Anirban and Choudhury, Sayantan and Hore, Rohan
author:
- given: Anirban
  family: Chatterjee
- given: Sayantan
  family: Choudhury
- given: Rohan
  family: Hore
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/chatterjee26a/chatterjee26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
