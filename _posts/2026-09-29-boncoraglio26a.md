---
title: 'Single-Head Attention in High Dimensions: A Theory of Generalization, Weights
  Spectra, and Scaling Laws'
openreview: 3qan4Zg9rA
abstract: Trained attention layers exhibit striking and reproducible spectral structure
  of the weights, including low-rank collapse, bulk deformation, and isolated spectral
  outliers, yet the origin of these phenomena and their implications for generalization
  remain poorly understood. We study empirical risk minimization in a single-head
  tied-attention layer trained on synthetic high-dimensional sequence tasks generated
  from the attention-indexed model. Using tools from random matrix theory, spin-glass
  theory, and approximate message passing, we obtain an exact high-dimensional characterization
  of training and test error, interpolation and recovery thresholds, and the spectrum
  of the key and query matrices. Our theory predicts the full singular-value distribution
  of the trained query–key map—including low-rank structure and isolated spectral
  outliers—in qualitative agreement with observations in more realistic transformers.
  Finally, for targets with power-law spectra, we show that learning proceeds through
  sequential spectral recovery, leading to the emergence of power-law scaling laws.
software: https://github.com/SPOC-group/ExtensiveAttention
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: boncoraglio26a
month: 0
tex_title: 'Single-Head Attention in High Dimensions: A Theory of Generalization,
  Weights Spectra, and Scaling Laws'
firstpage: 9058
lastpage: 9093
page: 9058-9093
order: 9058
cycles: false
bibtex_author: Boncoraglio, Fabrizio and Erba, Vittorio and Troiani, Emanuele and
  Xu, Yizhou and Krzakala, Florent and Zdeborov\'{a}, Lenka
author:
- given: Fabrizio
  family: Boncoraglio
- given: Vittorio
  family: Erba
- given: Emanuele
  family: Troiani
- given: Yizhou
  family: Xu
- given: Florent
  family: Krzakala
- given: Lenka
  family: Zdeborová
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/boncoraglio26a/boncoraglio26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
