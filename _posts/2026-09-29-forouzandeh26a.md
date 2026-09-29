---
title: 'LINGUA: Bridging the Grounding Gap in VideoQA via Typed Memory and Belief-State
  Reasoning'
openreview: IBLJ5MNcgy
abstract: 'VideoQA models can be accurate yet often fail to align answers with the
  correct video segments (the <em>grounding gap</em>). We introduce <b>LINGUA</b>
  (<b>L</b>anguage-based <b>IN</b>ference for <b>G</b>rounded Video <b>U</b>nderstanding
  <b>A</b>gent), a memory-based agent that performs grounded VideoQA by reasoning
  in an explicit <em>linguistic belief state</em>. LINGUA uses five mechanisms: (1)
  event-driven perception (retains 8–12% of frames while preserving 94% of question-relevant
  events); (2) typed memory for episodic narratives, semantic affordances, and procedural
  scripts; (3) Belief-Action-Verification loops with postcondition and temporal checks;
  (4) meta reflection with contrastive refinement; and (5) Bayesian reliability tracking
  for continual learning without gradient updates. Built with Gemma3-4B (Ollama, 4-bit),
  LINGUA outperforms strong baselines on five VideoQA benchmarks, reaching 82.4% on
  NExT-QA and 42.3% Acc@GQA on NExT-GQA (answer + IoU$\geq$0.5 temporal localization),
  while running 2.6$\times$ faster than dense-frame methods. In continual learning
  over 100 videos, accuracy rises from 45.2% (first 10) to 61.8% (last 10) without
  catastrophic forgetting, indicating online adaptation via memory refinement.'
software: https://github.com/S-Forouzandeh/LINGUA
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: forouzandeh26a
month: 0
tex_title: "{LINGUA}: Bridging the Grounding Gap in {V}ideo{QA} via Typed Memory and
  Belief-State Reasoning"
firstpage: 31437
lastpage: 31490
page: 31437-31490
order: 31437
cycles: false
bibtex_author: Forouzandeh, Saman and Peng, Wei and Yu, Xinghuo and Jalili, Mahdi
author:
- given: Saman
  family: Forouzandeh
- given: Wei
  family: Peng
- given: Xinghuo
  family: Yu
- given: Mahdi
  family: Jalili
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/forouzandeh26a/forouzandeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
