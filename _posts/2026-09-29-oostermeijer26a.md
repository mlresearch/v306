---
title: 'Accuracy and Normalized Accuracy under Length Bias: Analysis, Guidelines,
  and a Bayesian Alternative'
openreview: SbSFZ9N6DN
abstract: 'Multiple-choice benchmarks that rank candidate completions by conditional
  log-probability suffer from a length bias: because log-probabilities sum over tokens,
  longer answers tend to be penalized relative to shorter ones in practice. A common
  mitigation is to normalize scores by completion length, but we show empirically
  that this heuristic frequently over-corrects, introducing a bias toward longer answers
  instead. We first analyze these scoring rules, characterizing when standard and
  length-normalized accuracy are appropriate and how their length biases depend on
  the distribution of completion lengths. Motivated by this analysis, we introduce
  <em>Bayesian accuracy</em>, a scoring rule that computes the posterior probability
  of each candidate under an explicit prior over answer length, thereby removing linear
  length effects. Bayesian accuracy is a drop-in replacement for likelihood-based
  multiple-choice evaluation, requires no additional forward passes, and consistently
  exhibits lower empirical length bias than both standard and length-normalized accuracy
  across benchmarks and few-shot settings.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: oostermeijer26a
month: 0
tex_title: 'Accuracy and Normalized Accuracy under Length Bias: Analysis, Guidelines,
  and a {B}ayesian Alternative'
firstpage: 94698
lastpage: 94713
page: 94698-94713
order: 94698
cycles: false
bibtex_author: Oostermeijer, Koen
author:
- given: Koen
  family: Oostermeijer
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/oostermeijer26a/oostermeijer26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
