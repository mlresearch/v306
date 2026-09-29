---
title: Symbol-Equivariant Recurrent Reasoning Models
openreview: 1YCpxT3t5V
abstract: Reasoning problems such as Sudoku and ARC-AGI remain challenging for neural
  networks. The structured problem solving architecture family of Recurrent Reasoning
  Models (RRMs), including Hierarchical Reasoning Model (HRM) and Tiny Recursive Model
  (TRM), offer a compact alternative to large language models, but currently handle
  symbol symmetries only implicitly via costly data augmentation. We introduce Symbol-Equivariant
  Recurrent Reasoning Models (SE-RRMs), which enforce permutation equivariance at
  the architectural level through symbol-equivariant layers, guaranteeing identical
  solutions under symbol or color permutations. SE-RRMs outperform prior RRMs on 9$\times$9
  Sudoku and generalize from just training on 9$\times$9 to smaller 4$\times$4 and
  larger 16$\times$16 and 25$\times$25 instances, to which existing RRMs cannot extrapolate.
  On ARC-AGI-1 and ARC-AGI-2, SE-RRMs achieve competitive performance with substantially
  less data augmentation and only 2 million parameters, demonstrating that explicitly
  encoding symmetry improves the robustness and scalability of neural reasoning.
software: https://github.com/ml-jku/SE-RRM
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: freinschlag26a
month: 0
tex_title: Symbol-Equivariant Recurrent Reasoning Models
firstpage: 31618
lastpage: 31636
page: 31618-31636
order: 31618
cycles: false
bibtex_author: Freinschlag, Richard and Bertram, Timo and Kobler, Erich and Mayr,
  Andreas and Klambauer, G\"{u}nter
author:
- given: Richard
  family: Freinschlag
- given: Timo
  family: Bertram
- given: Erich
  family: Kobler
- given: Andreas
  family: Mayr
- given: Günter
  family: Klambauer
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/freinschlag26a/freinschlag26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
