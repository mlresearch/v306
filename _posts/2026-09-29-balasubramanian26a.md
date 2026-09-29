---
title: Dependence-Aware Label Aggregation for LLM-as-a-Judge via Ising Models
openreview: VCU3hGm0O6
abstract: Large-scale AI evaluation increasingly relies on aggregating binary judgments
  from $K$ annotators, including LLMs used as judges. Most classical methods, e.g.,
  Dawid-Skene or (weighted) majority voting, assume annotators are conditionally independent
  given the true label $Y\in{0,1}$, an assumption often violated by LLM judges due
  to shared data, architectures, prompts, and failure modes. Ignoring such dependencies
  can yield miscalibrated posteriors and even confidently incorrect predictions. We
  study label aggregation through a hierarchy of dependence-aware models based on
  Ising graphical models and latent factors. For class-dependent Ising models, the
  Bayes log-odds is generally quadratic in votes; for class-independent couplings,
  it reduces to a linear weighted vote with correlation-adjusted parameters. We present
  finite-$K$ examples showing that methods based on conditional independence can flip
  the Bayes label despite matching per-annotator marginals. We prove separation results
  demonstrating that these methods remain strictly suboptimal as the number of judges
  grows, incurring nonvanishing excess risk under latent factors. Finally, we evaluate
  the proposed method on three real-world datasets, demonstrating improved performance
  over the classical baselines.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: balasubramanian26a
month: 0
tex_title: Dependence-Aware Label Aggregation for {LLM}-as-a-Judge via Ising Models
firstpage: 5748
lastpage: 5785
page: 5748-5785
order: 5748
cycles: false
bibtex_author: Balasubramanian, Krishna and Podkopaev, Aleksandr and Kasiviswanathan,
  Shiva
author:
- given: Krishna
  family: Balasubramanian
- given: Aleksandr
  family: Podkopaev
- given: Shiva
  family: Kasiviswanathan
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/balasubramanian26a/balasubramanian26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
