---
title: 'PACER: Acyclic Causal Discovery from Large-scale Interventional Data'
openreview: BS8upx3Smw
abstract: Inferring the structure of directed acyclic graphs (DAGs) from data is a
  central challenge in causal discovery, particularly in modern high-dimensional settings
  where large-scale interventional data are increasingly available. While interventional
  data can improve identifiability, existing methods remain limited by soft acyclicity
  constraints, leading to optimization over invalid cyclic graphs, numerical instability,
  and reduced scalability. We introduce PACER (Perturbation-driven Acyclic Causal
  Edge Recovery), a scalable framework for causal discovery that guarantees acyclicity
  by construction. PACER parameterizes a distribution over DAGs through a joint model
  of variable permutations and edge probabilities, enabling direct optimization over
  valid causal structures without surrogate penalties. The framework supports a unified
  likelihood-based treatment of observational and interventional data, flexible conditional
  density models, and the incorporation of structural prior knowledge. For linear-Gaussian
  mechanisms, we derive closed-form expressions for the expected interventional log-likelihood
  and its gradients, yielding substantial computational gains. Empirically, PACER
  matches or exceeds state-of-the-art methods on protein signaling and large-scale
  genetic perturbation benchmarks, while scaling efficiently to networks with thousands
  of variables and achieving up to two orders of magnitude speedups over penalty-based
  differentiable approaches. These results demonstrate that exact and scalable causal
  discovery from high-dimensional perturbation data is achievable through principled
  search space design.
software: https://github.com/mlbio-epfl/PACER
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vinas-torne26a
month: 0
tex_title: "{PACER}: Acyclic Causal Discovery from Large-scale Interventional Data"
firstpage: 124008
lastpage: 124047
page: 124008-124047
order: 124008
cycles: false
bibtex_author: Vi\~{n}as Torn\'{e}, Ramon and Salazar, S\'{\i}lvia F\'{a}bregas and
  Park, Soyon and Ban, Ivo and Gadetsky, Artyom and Doikov, Nikita and Brbic, Maria
author:
- given: Ramon
  family: Viñas Torné
- given: Sı́lvia Fábregas
  family: Salazar
- given: Soyon
  family: Park
- given: Ivo
  family: Ban
- given: Artyom
  family: Gadetsky
- given: Nikita
  family: Doikov
- given: Maria
  family: Brbic
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/vinas-torne26a/vinas-torne26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
