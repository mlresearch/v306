---
title: Inference-time optimization for experiment-grounded protein ensemble generation
openreview: kbhIfLokFn
abstract: Protein function relies on dynamic conformational ensembles, yet current
  generative models like AlphaFold3 (AF3) often fail to produce ensembles that match
  experimental data. Recent experiment-guided generators attempt to address this by
  steering the reverse diffusion process. However, these methods are limited by fixed
  sampling horizons and sensitivity to initialization, often yielding thermodynamically
  implausible results. We introduce a general inference-time optimization framework
  to solve these challenges. First, we optimize over latent representations to maximize
  ensemble log-likelihood, rather than perturbing structures post hoc. This approach
  eliminates dependence on diffusion length, removes initialization bias, and easily
  incorporates external constraints. Second, we present novel sampling schemes for
  drawing Boltzmann-weighted ensembles. By combining structural priors from AF3 with
  force-field–based priors, we sample from their product distribution while balancing
  experimental likelihoods. Our results show that this framework consistently outperforms
  state-of-the-art guidance, improving diversity, physical energy, and agreement with
  data in X-ray crystallography and NMR, sometimes fitting the experimental data better
  than deposited PDB structures. Finally, inference-time optimization experiments
  maximizing iPTM scores reveal that perturbing MSA embeddings can artificially inflate
  model confidence. This exposes a vulnerability in current design metrics, whose
  mitigation could offer a pathway to reduce false discovery rates in binder engineering.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: maddipatla26a
month: 0
tex_title: Inference-time optimization for experiment-grounded protein ensemble generation
firstpage: 85483
lastpage: 85523
page: 85483-85523
order: 85483
cycles: false
bibtex_author: Maddipatla, Sai Advaith and Rzayev, Anar and Pegoraro, Marco and Pacesa,
  Martin and Schanda, Paul and Marx, Ailie and Vedula, Sanketh and Bronstein, Alexander
author:
- given: Sai Advaith
  family: Maddipatla
- given: Anar
  family: Rzayev
- given: Marco
  family: Pegoraro
- given: Martin
  family: Pacesa
- given: Paul
  family: Schanda
- given: Ailie
  family: Marx
- given: Sanketh
  family: Vedula
- given: Alexander
  family: Bronstein
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/maddipatla26a/maddipatla26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
