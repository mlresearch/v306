---
title: 'Front-Loaded Robust Conformal Prediction: Heavy Calibration, Minimal Test-Time
  Cost'
openreview: OfXpAituJ9
abstract: 'Robust conformal prediction (RCP) extends conformal prediction (CP) to
  noisy inputs by producing prediction sets with guaranteed coverage, ensuring that
  the true label is contained in the set with a user-specified probability even under
  worst-case perturbations. Recent works use randomized smoothing, as it provides
  robustness for black-box models at larger radii. Currently, there exist two setups
  for smoothing-based RCP: one requires extensive Monte Carlo sampling at calibration
  and test time but results in smaller prediction sets; the other setup produces larger
  prediction sets but uses a single sample at both stages. In deployment, calibration—as
  a one-time pre-processing step—can accommodate substantially higher computational
  overhead than inference. Inspired by this observation, we introduce an RCP framework
  that strikes a balance between the two extremes of this trade-off: we increase the
  sample rate at calibration time while keeping it either one or very low during test
  time. This calibration-time sampling opens the possibility of reducing the size
  of the prediction sets. In production, where the number of test predictions typically
  far exceeds the size of the calibration set, our Front-Loaded RCP matches the computational
  complexity of the state of the art while producing considerably smaller prediction
  sets at larger radii.'
software: https://github.com/soroushzargar/RCP1
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: h-zargarbashi26a
month: 0
tex_title: 'Front-Loaded Robust Conformal Prediction: Heavy Calibration, Minimal Test-Time
  Cost'
firstpage: 39060
lastpage: 39079
page: 39060-39079
order: 39060
cycles: false
bibtex_author: H. Zargarbashi, Soroush and Akhondzadeh, Mohammad Sadegh and Bojchevski,
  Aleksandar
author:
- given: Soroush
  family: H. Zargarbashi
- given: Mohammad Sadegh
  family: Akhondzadeh
- given: Aleksandar
  family: Bojchevski
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/h-zargarbashi26a/h-zargarbashi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
