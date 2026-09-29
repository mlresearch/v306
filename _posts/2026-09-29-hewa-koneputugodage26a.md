---
title: 'Factored Gossip DiLoCo: Reducing Blocking Communication in DiLoCo'
openreview: 1MynM9hkFH
abstract: To make large-scale distributed training practical outside high-bandwidth
  datacenters, we must reduce blocking, high-volume synchronization. While DiLoCo
  communicates infrequently, its outer synchronization remains bandwidth-heavy and
  brittle to stragglers and transient failures. We relax exact synchronization to
  <em>approximate synchronization</em> via mixing/gossip, which degrades gracefully
  under delays and communication failures. This allows us to factorize DiLoCo synchronization
  into a <em>non-blocking</em> mixing step that overlaps computation with no staleness,
  and a <em>blocking</em> mixing step that tightens worker agreement, yielding a tunable
  trade-off between compute utilization and optimization stability. On up to billion-parameter
  language models in low-bandwidth settings, our framework substantially improves
  compute utilization compared to DiLoCo, with training progress ranging from comparable
  to closely matching it, and is more robust to failures.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hewa-koneputugodage26a
month: 0
tex_title: 'Factored Gossip {D}i{L}o{C}o: Reducing Blocking Communication in {D}i{L}o{C}o'
firstpage: 42946
lastpage: 42967
page: 42946-42967
order: 42946
cycles: false
bibtex_author: Hewa Koneputugodage, Chamin P and Ajanthan, Thalaiyasingam and Ramasinghe,
  Sameera and Mohaghegh Dolatabadi, Hadi and Siriwardhana, Shamane and Avraham, Gil
  and Shevchenko, Violetta and Pajak, Karol and Snewin, James and Long, Alexander
author:
- given: Chamin P
  family: Hewa Koneputugodage
- given: Thalaiyasingam
  family: Ajanthan
- given: Sameera
  family: Ramasinghe
- given: Hadi
  family: Mohaghegh Dolatabadi
- given: Shamane
  family: Siriwardhana
- given: Gil
  family: Avraham
- given: Violetta
  family: Shevchenko
- given: Karol
  family: Pajak
- given: James
  family: Snewin
- given: Alexander
  family: Long
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/hewa-koneputugodage26a/hewa-koneputugodage26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
