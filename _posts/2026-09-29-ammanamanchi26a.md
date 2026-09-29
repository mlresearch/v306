---
title: 'Faults in Our Formal Benchmarking: Dataset Defects and Evaluation Failures
  in Lean Theorem Proving'
openreview: bHYAWawd4A
abstract: Benchmarks for LLM-assisted theorem proving in Lean are often treated as
  intrinsically reliable because every solved instance comes with a machine-checked
  proof. However, the kernel only checks that a proof establishes a <em>formal</em>
  statement; it does not verify that the statement faithfully encodes the intended
  informal problem, nor that evaluation harnesses are robust to trivial or adversarial
  solutions. We audit five widely used Lean theorem-proving benchmarks and their forks,
  using corpus-scale static checkers to surface 4,833 findings, including 398 mechanically
  certified issues such as counterexamples, vacuous theorems, and unsound axioms.
  We also document semantic defects such as missing hypotheses, problem simplification,
  incomplete or incorrect translations, and Lean-specific specification hazards. Beyond
  dataset construction, we survey evaluation-time failure modes and show, on corrected
  subsets, that defects can both inflate and deflate reported prover scores. We propose
  a fault taxonomy, a suite of automated checkers and recall-oriented semantic-audit
  prompts, and release standards to guide the creation of formal math datasets and
  make evaluation more reproducible and trustworthy. Our checkers, audit prompts,
  and corrected dataset snapshots are available at https://github.com/Shashi456/atp-checkers.
software: https://github.com/Shashi456/atp-checkers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ammanamanchi26a
month: 0
tex_title: 'Faults in Our Formal Benchmarking: Dataset Defects and Evaluation Failures
  in Lean Theorem Proving'
firstpage: 2431
lastpage: 2462
page: 2431-2462
order: 2431
cycles: false
bibtex_author: Ammanamanchi, Pawan Sasanka and Bhat, Siddharth and Biderman, Stella
author:
- given: Pawan Sasanka
  family: Ammanamanchi
- given: Siddharth
  family: Bhat
- given: Stella
  family: Biderman
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/ammanamanchi26a/ammanamanchi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
