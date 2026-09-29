---
title: Learning Long Range Spatio-Temporal Representations over Continuous Time Dynamic
  Graphs with State Space Models
openreview: S2jfT6EMqr
abstract: Continuous-time dynamic graphs (CTDGs) provide a richer framework to capture
  fine-grained temporal patterns in evolving relational data. Long-range information
  propagation is a key challenge while learning representations, wherein it is important
  to retain and update information over long temporal horizons. Existing approaches
  restrict models to capture one-hop or local temporal neighborhoods and fail to capture
  multi-hop or global structural patterns. To mitigate this, we derive a parameter-efficient
  state-space modeling framework for continuous-time dynamic graphs $\texttt{(CTDG-SSM)}$
  from first principles. We first introduce continuous-time Topology-Aware higher
  order polynomial projection operator ($\texttt{CTT-HiPPO}$), a novel memory-based
  reformulation of $\texttt{HiPPO}$ to jointly encode temporal dynamics and graph
  structure. The solution from $\texttt{CTT-HiPPO}$ is obtained by projecting the
  classical HiPPO solution through a polynomial of the Laplacian matrix, yielding
  topology-aware memory updates that admit an equivalent state-space formulation for
  CTDGs ($\texttt{CTDG-SSM}$). Then a computationally efficient discrete formulation
  is obtained using the zero-order hold approach for model implementation. Across
  benchmarks on dynamic link prediction, dynamic node classification, and sequence
  classification, $\texttt{CTDG-SSM}$ achieves state-of-the-art performance. Notably,
  it achieves large performance gains on datasets that require long range temporal
  (LRT) and spatial reasoning.
software: https://github.com/adhocmp122/CTDG-SSM
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: raghuvanshi26a
month: 0
tex_title: Learning Long Range Spatio-Temporal Representations over Continuous Time
  Dynamic Graphs with State Space Models
firstpage: 103033
lastpage: 103059
page: 103033-103059
order: 103033
cycles: false
bibtex_author: Raghuvanshi, Ayushman and Reddy, Thummaluru Siddartha and Chepuri,
  Sundeep Prabhakar and Chandran, Mahesh
author:
- given: Ayushman
  family: Raghuvanshi
- given: Thummaluru Siddartha
  family: Reddy
- given: Sundeep Prabhakar
  family: Chepuri
- given: Mahesh
  family: Chandran
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/raghuvanshi26a/raghuvanshi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
