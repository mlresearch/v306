---
title: Optimal Transport Group Counterfactual Explanations
openreview: DIWkLvYXuP
abstract: Group counterfactual explanations find a set of counterfactual instances
  to explain a group of input instances contrastively. However, existing methods either
  (i) optimize counterfactuals only for a fixed group and do not generalize to new
  group members, (ii) strictly rely on strong model assumptions (e.g., linearity)
  for tractability and/or (iii) poorly control the counterfactual group geometry distortion.
  We instead learn an explicit optimal transport map that sends any group instance
  to its counterfactual without re-optimization, minimizing the group’s total transport
  cost. This enables generalization with fewer parameters, making it easier to interpret
  the common actionable recourse. For linear classifiers, we prove that functions
  representing group counterfactuals are derived via mathematical optimization, identifying
  the underlying convex optimization type (QP, QCQP, ...). Experiments show that they
  accurately generalize, preserve group geometry and incur only negligible additional
  transport cost compared to baseline methods. If model linearity cannot be exploited,
  our approach also significantly outperforms the baselines.
software: https://github.com/Enrique-Val/ot-group-counterfactual
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: valero-leal26a
month: 0
tex_title: Optimal Transport Group Counterfactual Explanations
firstpage: 123331
lastpage: 123354
page: 123331-123354
order: 123331
cycles: false
bibtex_author: Valero-Leal, Enrique and Bischl, Bernd and Larra\~{n}aga, Pedro and
  Bielza, Concha and Casalicchio, Giuseppe
author:
- given: Enrique
  family: Valero-Leal
- given: Bernd
  family: Bischl
- given: Pedro
  family: Larrañaga
- given: Concha
  family: Bielza
- given: Giuseppe
  family: Casalicchio
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/valero-leal26a/valero-leal26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
