---
title: 'd$^2$p: Structured Soft Attention Is All You Need'
openreview: ZPtK8LKcvi
abstract: 'Classical dynamic programming algorithms such as Smith-Waterman, edit distance,
  and constituency parsing solve structured combinatorial problems using hard constraints.
  Soft relaxations replace hard $\max$ or $\min$ operators with differentiable probabilistic
  models whose gradients correspond to alignment or parsing marginals, but existing
  approaches typically treat the DP algorithm itself as fixed, relying on hand-tuned
  gap penalties, edit costs, span penalties, and temperatures. We show how to learn
  these parameters directly from data: the marginals these algorithms produce are
  themselves first-order derivatives, so learning them is inherently a second-order
  problem. We derive efficient Hessian-vector products and cross-Jacobians for twelve
  dynamic programming algorithms spanning alignment, edit distance, and parsing; both
  derivative families admit closed-form covariance expressions under the induced Gibbs
  distribution. We implement these operators as fused CUDA kernels in d$^2$p, achieving
  $100$-$20{,}000\times$ speedups over standard PyTorch and making end-to-end parameter
  learning practical at modern scales. We then demonstrate that learning these parameters
  is critical in practice. In protein structure alignment, freezing gap penalties
  collapses performance from $0.74$ to $0.32$ $F_1$ (and to $0.13$ at lower encoder
  capacity), while jointly learning them recovers biologically meaningful gap regimes
  and reaches $0.75$ $F_1$ and $0.445$ lDDT, $91$% of the TM-align lDDT ceiling. The
  same machinery transfers to constituency parsing, where a structured CKY CRF matches
  dense per-span supervision to within $0.003$ $F_1$ on English with no direct parse-tree
  structural supervision.'
software: https://github.com/orikata-bio/d2p
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mogilevsky26a
month: 0
tex_title: 'd$^2$p: Structured Soft Attention Is All You Need'
firstpage: 89656
lastpage: 89734
page: 89656-89734
order: 89656
cycles: false
bibtex_author: Mogilevsky, Casey Sumagaysay and Liang, Kimberly
author:
- given: Casey Sumagaysay
  family: Mogilevsky
- given: Kimberly
  family: Liang
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/mogilevsky26a/mogilevsky26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
