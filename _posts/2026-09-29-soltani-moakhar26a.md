---
title: Decision Tree Learning on Product Spaces
openreview: CWDsuIlJz8
abstract: Decision tree learning has long been a central topic in theoretical computer
  science, driven by its practical importance. A fundamental and widely used method
  for decision tree construction is the top-down greedy heuristic, which recursively
  splits on the most influential variable. Despite its empirical success, theoretical
  analysis of this heuristic has been limited. A recent breakthrough by Blanc et al.
  (ITCS, 2020) provided the first rigorous theoretical guarantees for the greedy approach,
  but only under the uniform distribution. We extend this analysis to the more general
  and practically relevant setting of arbitrary product distributions. Our main result
  shows that for any function $f$ computable by an optimal decision tree of size $s$,
  maximum depth $D_{\text{opt}}$, and average depth $\Delta_{\text{opt}}$, the greedy
  heuristic constructs an $\epsilon$-approximating tree whose size grows at most with
  $\exp(\Delta_{\text{opt}} D_{\text{opt}} \log(e/\epsilon))$. In the special case
  where the optimal tree is a full binary tree, this bound improves upon the bound
  of Blanc et al. and holds under a strictly broader class of distributions. Moreover,
  we present an algorithm based on the top-down greedy heuristic that is entirely
  <b>parameter-free</b>—it requires no prior knowledge of the optimal tree’s size
  or depth—offering a practical advantage over Blanc et al.’s method.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: soltani-moakhar26a
month: 0
tex_title: Decision Tree Learning on Product Spaces
firstpage: 114341
lastpage: 114362
page: 114341-114362
order: 114341
cycles: false
bibtex_author: Soltani Moakhar, Arshia and Ghahremani, Faraz and Banihashem, Kiarash
  and Hajiaghayi, Mohammadtaghi
author:
- given: Arshia
  family: Soltani Moakhar
- given: Faraz
  family: Ghahremani
- given: Kiarash
  family: Banihashem
- given: Mohammadtaghi
  family: Hajiaghayi
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/soltani-moakhar26a/soltani-moakhar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
