---
title: Robust Bayes-Assisted Conformal Prediction
openreview: eopPyXUmDk
abstract: 'Bayes–assisted conformal prediction combines the strengths of Bayesian
  modelling with exact, distribution–free frequentist coverage guarantees. Although
  conformal validity is preserved even when the Bayesian working model (BWM) is misspecified,
  the size of the resulting prediction sets can degrade substantially when the prior
  is poorly aligned with the observed data. We address this limitation by introducing
  <b>RoBAS</b> (<b>Ro</b>bust <b>B</b>ayes-<b>A</b>ssisted <b>S</b>hrinkage): a Bayes–assisted
  framework for constructing robust nonconformity scores, with two instantiations:
  one induced by a heavy–tailed BWM, and a closed–form empirical Bayes shrinkage score.
  The resulting scores adapt to the quality of the working information encoded in
  the prior: when this information is reliable, they exploit it to produce efficient
  prediction sets; when it is weak or inaccurate, they revert to the Distance–To–Average
  (DTA) score, a robust non–informative baseline. We evaluate the proposed scores
  on tabular and image regression tasks where the training distribution may differ
  from the calibration and test distributions, while the calibration and test data
  themselves remain exchangeable. We find that they are competitive with widely used
  scores in the absence of such shift, while substantially reducing interval widths
  in shifted settings.'
software: https://github.com/kiaashour/RoBAS
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ashouritaklimi26a
month: 0
tex_title: Robust {B}ayes-Assisted Conformal Prediction
firstpage: 4158
lastpage: 4202
page: 4158-4202
order: 4158
cycles: false
bibtex_author: Ashouritaklimi, Kianoosh and Cortinovis, Stefano and Caron, Francois
author:
- given: Kianoosh
  family: Ashouritaklimi
- given: Stefano
  family: Cortinovis
- given: Francois
  family: Caron
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ashouritaklimi26a/ashouritaklimi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
