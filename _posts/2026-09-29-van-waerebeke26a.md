---
title: Variance-Reduced $(\varepsilon, δ)-$Unlearning using Forget Set Gradients
openreview: 6XIwgtbcTa
abstract: In machine unlearning, $(\varepsilon,\delta)-$unlearning is a popular framework
  that provides formal guarantees on the effectiveness of the removal of a subset
  of training data, the <em>forget set</em>, from a trained model. For strongly convex
  objectives, existing first-order methods achieve $(\varepsilon,\delta)-$unlearning,
  but they only use the forget set to calibrate injected noise, never as a direct
  optimization signal. In contrast, efficient empirical heuristics often exploit the
  forget samples (e.g., via gradient ascent) but come with no formal unlearning guarantees.
  We bridge this gap by presenting the Variance-Reduced Unlearning (<em>VRU</em>)
  algorithm. To the best of our knowledge, <em>VRU</em> is the first first-order algorithm
  that directly includes forget set gradients in its update rule, while provably satisfying
  $(\varepsilon,\delta)-$unlearning. We establish the convergence of <em>VRU</em>
  and show that incorporating the forget set yields strictly improved rates, <em>i.e.</em>,
  a better dependence on the achieved error compared to existing first-order $(\varepsilon,\delta)-$unlearning
  methods. Moreover, we prove that, in a low-error regime <em>VRU</em> asymptotically
  outperforms any first-order methods that ignores the forget set. Experiments corroborate
  our theory, showing consistent gains over both state-of-the-art certified unlearning
  methods and over empirical baselines that explicitly leverage the forget set.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-waerebeke26a
month: 0
tex_title: Variance-Reduced $(\varepsilon, δ)-$Unlearning using Forget Set Gradients
firstpage: 123465
lastpage: 123483
page: 123465-123483
order: 123465
cycles: false
bibtex_author: Van Waerebeke, Martin and Neglia, Giovanni and Scaman, Kevin and Lorenzi,
  Marco and El-Mhamdi, El-Mahdi
author:
- given: Martin
  family: Van Waerebeke
- given: Giovanni
  family: Neglia
- given: Kevin
  family: Scaman
- given: Marco
  family: Lorenzi
- given: El-Mahdi
  family: El-Mhamdi
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/van-waerebeke26a/van-waerebeke26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
