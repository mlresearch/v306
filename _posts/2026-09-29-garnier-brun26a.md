---
title: Biased Generalization in Diffusion Models
openreview: IqTvyp40O6
abstract: Generalization in generative modeling is defined as the ability to learn
  an underlying distribution from a finite dataset and produce novel samples, with
  evaluation largely driven by held-out performance and perceived sample quality.
  In practice, training is often stopped at the minimum of the test loss, taken as
  an operational indicator of generalization. We challenge this viewpoint by identifying
  a phase of <em>biased generalization</em> during training, in which the model continues
  to decrease the test loss while favoring samples with anomalously high proximity
  to training data. By training the same network on two disjoint datasets and comparing
  the mutual distances of generated samples and their similarity to training data,
  we introduce a quantitative measure of bias and demonstrate its presence on real
  images. We then study the mechanism of bias, using a controlled hierarchical data
  model where access to exact scores and ground-truth statistics allows us to precisely
  characterize its onset. We attribute this phenomenon to the sequential nature of
  feature learning in deep networks, where coarse structure is learned early in a
  data-independent manner, while finer features are resolved later in a way that increasingly
  depends on individual training samples. Our results show that early stopping at
  the test loss minimum, while optimal under standard generalization criteria, may
  be insufficient for privacy-critical applications.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: garnier-brun26a
month: 0
tex_title: Biased Generalization in Diffusion Models
firstpage: 34092
lastpage: 34112
page: 34092-34112
order: 34092
cycles: false
bibtex_author: Garnier-Brun, Jerome and Biggio, Luca and Beltrame, Davide and Mezard,
  Marc and Saglietti, Luca
author:
- given: Jerome
  family: Garnier-Brun
- given: Luca
  family: Biggio
- given: Davide
  family: Beltrame
- given: Marc
  family: Mezard
- given: Luca
  family: Saglietti
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/garnier-brun26a/garnier-brun26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
