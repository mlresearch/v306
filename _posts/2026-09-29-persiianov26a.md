---
title: Inverse Entropic Optimal Transport Solves Semi-supervised Learning via Data
  Likelihood Maximization
openreview: 0p617sK4Z4
abstract: Learning conditional distributions $\pi^\star(\cdot|x)$ is a central problem
  in machine learning, which is typically approached via supervised methods with paired
  data $(x,y) \sim \pi^\star$. However, acquiring paired data samples is often challenging,
  especially in problems such as domain translation. This necessitates the development
  of <em>semi-supervised</em> models that utilize both limited paired data and additional
  unpaired i.i.d. samples $x \sim \pi^\star_x$ and $y \sim \pi^\star_y$ from the marginal
  distributions. The usage of such combined data is complex and often relies on heuristic
  approaches. To tackle this issue, we propose a new learning paradigm that integrates
  both paired and unpaired data seamlessly using data likelihood maximization techniques.
  We demonstrate that our approach also connects intriguingly with inverse entropic
  optimal transport (OT). This finding allows us to apply recent advances in computational
  OT to establish an <em>end-to-end</em> learning algorithm to get $\pi^\star(\cdot|x)$.
  In addition, we derive the universal approximation property, demonstrating that
  our approach can theoretically recover true conditional distributions with arbitrarily
  small error. Finally, we demonstrate through empirical tests that our method effectively
  learns conditional distributions using paired and unpaired data simultaneously.
software: https://github.com/MuXauJl11110/EBiEOT
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: persiianov26a
month: 0
tex_title: Inverse Entropic Optimal Transport Solves Semi-supervised Learning via
  Data Likelihood Maximization
firstpage: 98281
lastpage: 98321
page: 98281-98321
order: 98281
cycles: false
bibtex_author: Persiianov, Mikhail and Asadulaev, Arip and Andreev, Nikita and Starodubcev,
  Nikita and Baranchuk, Dmitry and Kratsios, Anastasis and Burnaev, Evgeny and Korotin,
  Alexander
author:
- given: Mikhail
  family: Persiianov
- given: Arip
  family: Asadulaev
- given: Nikita
  family: Andreev
- given: Nikita
  family: Starodubcev
- given: Dmitry
  family: Baranchuk
- given: Anastasis
  family: Kratsios
- given: Evgeny
  family: Burnaev
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/persiianov26a/persiianov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
