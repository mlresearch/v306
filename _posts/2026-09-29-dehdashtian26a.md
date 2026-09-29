---
title: 'FoeGlass: Simple In-Context Learning Is Enough for Red Teaming Audio Deepfake
  Detectors'
openreview: J6amahDTKV
abstract: 'Audio deepfake detection (ADD) models are critical for countering the malicious
  use of text-to-speech (TTS) models. Evaluating and strengthening ADD models requires
  developing datasets that span the space of generated audio and highlight high-error
  regions. Existing dataset development strategies face two challenges: (i) manual
  collection, and (ii) inefficient discovery of blind spots in the ADD models. To
  address these challenges, we propose FoeGlass, the first black-box automated red-teaming
  method for ADDs, which effectively discovers ADD failure modes in the space of generated
  audio underexplored by state-of-the-art deepfake benchmarks. FoeGlass uses the in-context
  learning capabilities of an LLM to explore the input space of a TTS model, generating
  audio samples that fool the target ADD using only black-box access to all components.
  By using a carefully designed context based on diversity measurements, FoeGlass
  mitigates the common problem of mode collapse in automated red-teaming systems.
  Empirical evaluations on several open-source ADD and TTS models demonstrate that
  data generated from FoeGlass substantially improves the false negative rates over
  unconditional sampling baselines and recent spoofing datasets by up to 94%, while
  requiring no manual supervision. Furthermore, we show that the attacks generated
  by FoeGlass are transferable across different target ADDs, demonstrating its broad
  applicability and ease of use for the automated red teaming of ADD systems. Finally,
  fine-tuning ADD models on FoeGlass-generated samples notably enhances the robustness
  of the detectors (up 41%).'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dehdashtian26a
month: 0
tex_title: "{F}oe{G}lass: Simple In-Context Learning Is Enough for Red Teaming Audio
  Deepfake Detectors"
firstpage: 23591
lastpage: 23612
page: 23591-23612
order: 23591
cycles: false
bibtex_author: Dehdashtian, Sepehr and Seidman, Jacob H and Boddeti, Vishnu and Bharaj,
  Gaurav
author:
- given: Sepehr
  family: Dehdashtian
- given: Jacob H
  family: Seidman
- given: Vishnu
  family: Boddeti
- given: Gaurav
  family: Bharaj
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/dehdashtian26a/dehdashtian26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
