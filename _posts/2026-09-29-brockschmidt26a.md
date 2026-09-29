---
title: 'SurvDiff: A Diffusion Model for Generating Synthetic Data in Survival Analysis'
openreview: boeY2syj2r
abstract: Survival analysis is a cornerstone of clinical research by modeling time-to-event
  outcomes such as metastasis, disease relapse, or patient death. Unlike standard
  tabular data, survival data often come with incomplete event information due to
  dropout, or loss to follow-up. This poses unique challenges for synthetic data generation,
  where it is crucial for clinical research to faithfully reproduce both the event-time
  distribution and the censoring mechanism. In this paper, we propose SurvDiff, an
  end-to-end diffusion model specifically designed for generating synthetic data in
  survival analysis. SurvDiff is tailored to capture the data-generating mechanism
  by jointly generating mixed-type covariates, event times, and right-censoring, guided
  by a survival-tailored loss function. The loss encodes the time-to-event structure
  and directly optimizes for downstream survival tasks, which ensures that SurvDiff
  (i) reproduces realistic event-time distributions and (ii) preserves the censoring
  mechanism. Across multiple datasets, we show that SurvDiff outperforms state-of-the-art
  generative baselines in both distributional fidelity and survival model evaluation
  metrics across multiple medical datasets. To the best of our knowledge, SurvDiff
  is the first end-to-end diffusion model explicitly designed for generating synthetic
  survival data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: brockschmidt26a
month: 0
tex_title: "{S}urv{D}iff: A Diffusion Model for Generating Synthetic Data in Survival
  Analysis"
firstpage: 9899
lastpage: 9932
page: 9899-9932
order: 9899
cycles: false
bibtex_author: Brockschmidt, Marie and Schr\"{o}der, Maresa and Feuerriegel, Stefan
author:
- given: Marie
  family: Brockschmidt
- given: Maresa
  family: Schröder
- given: Stefan
  family: Feuerriegel
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/brockschmidt26a/brockschmidt26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
