---
title: On the Accuracy of Newton Step and Influence Function Data Attributions
openreview: mDo8XNqopd
abstract: 'Data attribution estimates how a trained model would change if a subset
  of training points were removed, and is a central primitive for tasks such as interpretability,
  data valuation, and machine unlearning. Despite its widespread use, our theoretical
  understanding of key data attribution methods – Influence Functions (IF) and a single
  Newton Step (NS) – remains limited: existing guarantees heavily rely on <em>global</em>
  strong convexity and yield bounds with pessimistic dependence on the parameter dimension
  $d$ and the number of removed samples $k$. We give a new analysis of IF and NS for
  convex ERM that replaces global assumptions with <em>local</em> conditions: it suffices
  that the loss is strongly convex and sufficiently smooth only in a neighborhood
  of the first Newton step. As a concrete validation, we analyze logistic regression
  with Gaussian features and show that our bounds capture the correct scaling up to
  polylogarithmic factors, yielding matching upper and lower bounds and explaining
  observed regimes in which NS is markedly more accurate than IF, thereby resolving
  open questions raised by (Koh et al., 2019).'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rubinstein26a
month: 0
tex_title: On the Accuracy of {N}ewton Step and Influence Function Data Attributions
firstpage: 106088
lastpage: 106134
page: 106088-106134
order: 106088
cycles: false
bibtex_author: Rubinstein, Ittai and Hopkins, Samuel B.
author:
- given: Ittai
  family: Rubinstein
- given: Samuel B.
  family: Hopkins
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/rubinstein26a/rubinstein26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
