---
title: 'MatchFixAgent: Language-Agnostic Autonomous Repository-Level Code Translation
  Validation and Repair'
openreview: MuyXpH3GL1
abstract: Code translation transforms source code from one programming language (PL)
  to another. Validating the functional equivalence of translation and repairing,
  if necessary, are critical steps in code translation. Existing automated validation
  and repair approaches struggle to generalize to many PLs due to high engineering
  overhead, and they rely on existing and often inadequate test suites, which results
  in false claims of equivalence and ineffective translation repair. To bridge this
  gap, we develop MatchFixAgent, a large language model (LLM)-based, PL-agnostic framework
  for equivalence validation and repair of translations. MatchFixAgent features a
  multi-agent architecture that divides equivalence validation into several sub-tasks
  to ensure thorough and consistent semantic analysis of the translation. We compare
  MatchFixAgent’s validation and repair results with four repository-level code translation
  techniques. Our results demonstrate that MatchFixAgent produces (in)equivalence
  verdicts for $99.2$% of translation pairs, with the same equivalence validation
  result as prior work on $72.8$% of them. When MatchFixAgent’s result disagrees with
  prior work, we find that $60.7$% of the time MatchFixAgent’s result is actually
  correct. In addition, we show that MatchFixAgent can repair $50.6$% of inequivalent
  translation, compared to prior work’s $18.5$%.
software: https://github.com/Intelligent-CAT-Lab/MatchFixAgent
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ibrahimzada26a
month: 0
tex_title: "{M}atch{F}ix{A}gent: Language-Agnostic Autonomous Repository-Level Code
  Translation Validation and Repair"
firstpage: 49428
lastpage: 49451
page: 49428-49451
order: 49428
cycles: false
bibtex_author: Ibrahimzada, Ali Reza and Paulsen, Brandon and Jabbarvand, Reyhaneh
  and Dodds, Joey and Kroening, Daniel
author:
- given: Ali Reza
  family: Ibrahimzada
- given: Brandon
  family: Paulsen
- given: Reyhaneh
  family: Jabbarvand
- given: Joey
  family: Dodds
- given: Daniel
  family: Kroening
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ibrahimzada26a/ibrahimzada26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
