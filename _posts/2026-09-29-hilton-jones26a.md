---
title: 'Modelling Attention with Aitchison Geometry: Token Distinguishability and
  Temperature Scaling'
openreview: 1hBJuMSEKs
abstract: The attention mechanism with softmax normalisation is a foundational component
  of Transformer-based large language models. However, with very long contexts, attention
  scores are known to diminish, raising fundamental questions about token distinguishability
  and how it can be preserved. In this work, we provide a formal characterisation
  of token distinguishability in attention as a function of context length and embedding
  dimension. We introduce Aitchison distance to quantify relative differences among
  attention probabilities, and show that, with Gaussian queries and keys, even in
  the long-context regime, token distinguishability converges to a finite, non-zero
  limit rather than vanishing. Leveraging the linear relationship between inverse-temperature
  scaling and Aitchison distance, we derive a theoretical lower bound of $\Omega(\sqrt{\log
  L})$ on the logit scaling required to produce a sharp attention distribution. Finally,
  we demonstrate that Aitchison distance provides a principled and practical alternative
  to entropy for monitoring training and inference, as it captures the full compositional
  structure, including the smaller components of the attention probabilities.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hilton-jones26a
month: 0
tex_title: 'Modelling Attention with Aitchison Geometry: Token Distinguishability
  and Temperature Scaling'
firstpage: 43115
lastpage: 43142
page: 43115-43142
order: 43115
cycles: false
bibtex_author: Hilton-Jones, Sam and Norman, Timothy J. and Zhu, Zhanxing
author:
- given: Sam
  family: Hilton-Jones
- given: Timothy J.
  family: Norman
- given: Zhanxing
  family: Zhu
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hilton-jones26a/hilton-jones26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
