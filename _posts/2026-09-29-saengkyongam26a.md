---
title: 'Anti-causal domain generalization: Leveraging unlabeled data'
openreview: VOrzQ8GBDh
abstract: The problem of domain generalization concerns learning predictive models
  that are robust to distribution shifts when deployed in new, previously unseen environments.
  Existing methods typically require labeled data from multiple training environments,
  limiting their applicability when labeled data are scarce. In this work, we study
  domain generalization in an anti-causal setting, where the outcome causes the observed
  covariates. Under this structure, environment perturbations that affect the covariates
  do not propagate to the outcome, which motivates regularizing the model’s sensitivity
  to these perturbations. Crucially, estimating these perturbation directions does
  not require labels, enabling us to leverage unlabeled data from multiple environments.
  We propose two methods that penalize the model’s sensitivity to variations in the
  mean and covariance of the covariates across environments, respectively, and prove
  that these methods have worst-case optimality guarantees under certain classes of
  environments. Finally, we demonstrate the empirical performance of our approach
  on a controlled physical system and a physiological signal dataset.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: saengkyongam26a
month: 0
tex_title: 'Anti-causal domain generalization: Leveraging unlabeled data'
firstpage: 106794
lastpage: 106817
page: 106794-106817
order: 106794
cycles: false
bibtex_author: Saengkyongam, Sorawit and Gamella, Juan L. and Miller, Andrew and Peters,
  Jonas and Meinshausen, Nicolai and Heinze-Deml, Christina
author:
- given: Sorawit
  family: Saengkyongam
- given: Juan L.
  family: Gamella
- given: Andrew
  family: Miller
- given: Jonas
  family: Peters
- given: Nicolai
  family: Meinshausen
- given: Christina
  family: Heinze-Deml
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/saengkyongam26a/saengkyongam26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
