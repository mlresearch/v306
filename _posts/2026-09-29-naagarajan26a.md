---
title: 'Hierarchical Causal Abduction: A Foundation Framework for Explainable Model
  Predictive Control'
openreview: 22XF7II0Hd
abstract: Model Predictive Control (MPC) is widely used to operate safety-critical
  infrastructure by predicting future trajectories and optimizing control actions.
  However, nonlinear dynamics, hard safety constraints, and numerical optimization
  often render individual control moves opaque to human operators, undermining trust
  and hindering deployment. This paper presents Hierarchical Causal Abduction (HCA),
  which combines (i) physics-informed reasoning via domain knowledge graphs, (ii)
  optimization evidence from Karush–Kuhn–Tucker (KKT) multipliers, and (iii) temporal
  causal discovery via the PCMCI algorithm to generate faithful, human-interpretable
  explanations for control actions computed by nonlinear MPC. Across three diverse
  control applications (greenhouse climate, building HVAC, chemical process engineering)
  with expert validation, HCA improves explanation accuracy by 53% over LIME (0.478
  vs. 0.311) using a single set of cross-domain parameters without per-domain tuning;
  domain-specific KKT-threshold calibration over 2–3 days further increases accuracy
  to 0.88. Ablation studies confirm that each evidence source is essential, with 32–37%
  accuracy degradation when any component is removed, and HCA’s ranking-and-validation
  methodology generalizes beyond MPC to other prediction-based decision systems, including
  learning-based control and trajectory planning.
software: https://gitlab.hrz.tu-chemnitz.de/rnaa-at-tu-chemnitz.de/icml
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: naagarajan26a
month: 0
tex_title: 'Hierarchical Causal Abduction: A Foundation Framework for Explainable
  Model Predictive Control'
firstpage: 91509
lastpage: 91536
page: 91509-91536
order: 91509
cycles: false
bibtex_author: Naagarajan, Ramesh Arvind and Wagner, Z\"{u}hal and Streif, Stefan
author:
- given: Ramesh Arvind
  family: Naagarajan
- given: Zühal
  family: Wagner
- given: Stefan
  family: Streif
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/naagarajan26a/naagarajan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
