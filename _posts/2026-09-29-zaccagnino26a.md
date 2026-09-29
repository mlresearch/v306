---
title: Shifting the Breaking Point of Flow Matching for Multi-Instance Editing
openreview: n2An7C7n7e
abstract: Flow matching models have recently emerged as an efficient alternative to
  diffusion, especially for text-guided image generation and editing, offering faster
  inference through continuous-time dynamics. However, existing flow-based editors
  predominantly support global or single-instruction edits and struggle with multi-instance
  scenarios, where multiple parts of a reference input must be edited independently
  without semantic interference. We identify this limitation as a consequence of globally
  conditioned velocity fields and joint attention mechanisms, which entangle concurrent
  edits. To address this issue, we introduce Instance-Disentangled Attention, a mechanism
  that partitions joint attention operations, enforcing binding between instance-specific
  textual instructions and spatial regions during velocity field estimation. We evaluate
  our approach on both natural image editing and a newly introduced benchmark of text-dense
  infographics with region-level editing instructions. Experimental results demonstrate
  that our approach promotes edit disentanglement and locality while preserving global
  output coherence, enabling single-pass, instance-level editing.
software: https://github.com/Blowing-Up-Groundhogs/IDAttn
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zaccagnino26a
month: 0
tex_title: Shifting the Breaking Point of Flow Matching for Multi-Instance Editing
firstpage: 152716
lastpage: 152740
page: 152716-152740
order: 152716
cycles: false
bibtex_author: Zaccagnino, Carmine and Quattrini, Fabio and Simsar, Enis and Gazulla,
  Marta Tintore and Cucchiara, Rita and Tonioni, Alessio and Cascianelli, Silvia
author:
- given: Carmine
  family: Zaccagnino
- given: Fabio
  family: Quattrini
- given: Enis
  family: Simsar
- given: Marta Tintore
  family: Gazulla
- given: Rita
  family: Cucchiara
- given: Alessio
  family: Tonioni
- given: Silvia
  family: Cascianelli
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/zaccagnino26a/zaccagnino26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
