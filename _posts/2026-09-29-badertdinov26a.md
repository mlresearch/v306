---
title: 'SWE-rebench V2: Language-Agnostic SWE Task Collection at Scale'
openreview: UCAda9kS57
abstract: Software engineering agents (SWE) are improving rapidly, with recent gains
  largely driven by reinforcement learning (RL). However, RL training is constrained
  by the scarcity of large-scale task collections with reproducible execution environments
  and reliable test suites. Although a growing number of benchmarks have emerged,
  datasets suitable for training remain limited in scale and diversity or often target
  a limited set of high-resource language ecosystems. We introduce SWE-rebench V2,
  a language-agnostic automated pipeline for harvesting executable real-world SWE
  tasks and constructing RL training environments at scale. The pipeline synthesizes
  repository-specific installation and test procedures via an interactive setup agent,
  and filters unsound instances using an ensemble of LLM judges, validated against
  human-verified SWE-bench annotations. Using this pipeline, we construct a dataset
  of 32,079 tasks spanning 20 languages and 3,617 repositories, with pre-built images
  for reproducible execution. To further scale training data, we additionally release
  120,000+ tasks with installation instructions, fail-to-pass tests and rich metadata,
  where the problem statement is generated based on the original pull request description.
  We validate the collected instances through a diagnostic study that covers a subset
  of tasks in five programming languages across seven popular models, and provide
  instance-level metadata that flags common confounders such as overly restrictive
  tests and underspecified descriptions. We release the datasets, the collection and
  execution code, and associated artifacts to enable large-scale training of SWE agents
  across diverse languages and repositories.
software: https://github.com/SWE-rebench/SWE-rebench-V2
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: badertdinov26a
month: 0
tex_title: "{SWE}-rebench V2: Language-Agnostic {SWE} Task Collection at Scale"
firstpage: 4820
lastpage: 4843
page: 4820-4843
order: 4820
cycles: false
bibtex_author: Badertdinov, Ibragim and Nekrashevich, Maksim and Shevtsov, Anton and
  Golubev, Alexander
author:
- given: Ibragim
  family: Badertdinov
- given: Maksim
  family: Nekrashevich
- given: Anton
  family: Shevtsov
- given: Alexander
  family: Golubev
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/badertdinov26a/badertdinov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
