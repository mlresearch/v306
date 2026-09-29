---
title: Global Convergence of Adaptive Sensing for Principal Eigenvector Estimation
openreview: XXYhEGXPPF
abstract: Principal component analysis classically requires full $d$-dimensional samples,
  yet in various applications hardware limits acquisition to a few scalar measurements
  per sample. We analyze a compressed variant of Oja’s algorithm for estimating the
  principal eigenvector of the data covariance matrix using only two adaptive measurements
  per sample. At each iteration, we observe one measurement along the current estimate
  and one in a random orthogonal direction. We prove that after $t$ iterations, the
  expected sine-squared error to the true eigenvector is $\mathcal{O}(\lambda_1\lambda_2
  d^2 / (\Delta^2 t))$, where $d$ is the ambient dimension, $\lambda_1, \lambda_2$
  are the leading eigenvalues, and $\Delta = \lambda_1 - \lambda_2$ is the eigengap.
  We complement this with a matching information-theoretic lower bound of $\Omega(\lambda_1\lambda_2
  d^2 / (\Delta^2 t))$ — the first for compressed eigenvector estimation — proving
  that the $d^2$ factor, an additional factor of $d$ compared to the fully-observed
  minimax rate $\Theta(\lambda_1\lambda_2 d / (\Delta^2 t))$, is the fundamental cost
  of compression and cannot be improved. In contrast, any non-adaptive scheme with
  two measurements per iteration suffers $\Omega(\lambda_2^2 d^3 / (\Delta^2 t))$,
  an additional power of $d$. This separates fully-observed, adaptive-compressed,
  and non-adaptive-compressed PCA across three powers of $d$. Our analysis handles
  the noisy setting where the covariance has nonzero trailing eigenvalues, providing
  the first convergence guarantee for adaptive compressed subspace tracking beyond
  the noiseless case.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: saad-falcon26a
month: 0
tex_title: Global Convergence of Adaptive Sensing for Principal Eigenvector Estimation
firstpage: 106501
lastpage: 106533
page: 106501-106533
order: 106501
cycles: false
bibtex_author: Saad-Falcon, Alex and Ancelin, Brighton and Romberg, Justin
author:
- given: Alex
  family: Saad-Falcon
- given: Brighton
  family: Ancelin
- given: Justin
  family: Romberg
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/saad-falcon26a/saad-falcon26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
