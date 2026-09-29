---
title: Matroid Algorithms Under Size-Sensitive Independence Oracles
openreview: 80Job2F5eb
abstract: 'The standard oracle model for matroid algorithms assumes that each independence
  query can be answered in constant time, regardless of the size of the queried set.
  While this abstraction has underpinned much of the theoretical progress in matroid
  optimization, it masks the true computational effort required by these algorithms.
  In particular, for natural and widely studied classes such as graphic matroids,
  even a single independence query can require work linear in the size of the set,
  making the constant-time assumption implausible. We address this gap by introducing
  a size-sensitive cost model where the cost of a query $Q$ scales with $|Q|$. Nearly
  linear-time oracle implementations exist for broad families of matroids, and this
  refined abstraction therefore captures the true cost of query evaluation while allowing
  for a more faithful comparison between general matroids and their natural special
  cases. Within this framework we study three fundamental algorithmic tasks: finding
  a basis of a matroid, approximating its rank, and approximating its partition size.
  We establish tight results, proving nearly matching upper and lower bounds that
  show the optimal query cost is (up to logarithmic factors) quadratic in the size
  of the matroid. On the algorithmic side, our upper bounds are realized by explicit
  procedures that construct the desired solution. On the complexity side, our lower
  bounds are unconditional and already hold even for weaker distinguishing formulations
  of the problems. Finally, for matroids with maximum circuit size at most $c$, we
  show that the quadratic barrier can be broken, providing an algorithm that calculates
  the maximum-weight basis with expected query cost $\mathcal{O}(n^{2-1/c} \log n)$.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: banihashem26d
month: 0
tex_title: Matroid Algorithms Under Size-Sensitive Independence Oracles
firstpage: 6309
lastpage: 6324
page: 6309-6324
order: 6309
cycles: false
bibtex_author: Banihashem, Kiarash and Hajiaghayi, Mohammadtaghi and Jafariraviz,
  Mahdi and Mittal, Danny
author:
- given: Kiarash
  family: Banihashem
- given: Mohammadtaghi
  family: Hajiaghayi
- given: Mahdi
  family: Jafariraviz
- given: Danny
  family: Mittal
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/banihashem26d/banihashem26d.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
