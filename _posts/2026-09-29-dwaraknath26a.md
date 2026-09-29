---
title: 'FlashSketch: Sketch-Kernel Co-Design for Fast Sparse Sketching on GPUs'
openreview: cCwxV6rSXF
abstract: 'Sparse sketches such as the sparse Johnson–Lindenstrauss transform are
  a core primitive in randomized numerical linear algebra because they leverage random
  sparsity to reduce the arithmetic cost of sketching, while still offering strong
  approximation guarantees. Their random sparsity, however, is at odds with efficient
  implementations on modern GPUs, since it leads to irregular memory access patterns
  that degrade memory bandwidth utilization. Motivated by this tension, we pursue
  a sketch–kernel co-design approach: we design a new family of sparse sketches, BlockPerm-SJLT,
  whose sparsity structure is chosen to enable FlashSketch, a corresponding optimized
  CUDA kernel that implements these sketches efficiently. The design of BlockPerm-SJLT
  introduces a tunable parameter that explicitly trades off the tension between GPU-efficiency
  and sketching robustness. We provide theoretical guarantees for BlockPerm-SJLT under
  the oblivious subspace embedding (OSE) framework, and also analyze the effect of
  the tunable parameter on sketching quality. We empirically evaluate FlashSketch
  on standard RandNLA benchmarks, as well as an end-to-end ML data attribution pipeline
  called GraSS. FlashSketch pushes the Pareto frontier of sketching quality versus
  speed, across a range of regimes and tasks, and achieves a global geomean speedup
  of roughly $1.7 \times$ over the prior state-of-the-art GPU sketches.'
software: https://github.com/rajatvd/flash-sketch-arxiv
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dwaraknath26a
month: 0
tex_title: "{F}lash{S}ketch: Sketch-Kernel Co-Design for Fast Sparse Sketching on
  {GPU}s"
firstpage: 27401
lastpage: 27451
page: 27401-27451
order: 27401
cycles: false
bibtex_author: Dwaraknath, Rajat Vadiraj and Kim, Sungyoon and Pilanci, Mert
author:
- given: Rajat Vadiraj
  family: Dwaraknath
- given: Sungyoon
  family: Kim
- given: Mert
  family: Pilanci
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/dwaraknath26a/dwaraknath26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
