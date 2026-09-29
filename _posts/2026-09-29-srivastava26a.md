---
title: 'EffGen: Enabling Small Language Models as Capable Autonomous Agents'
openreview: WUBn9uJuvj
abstract: 'Most existing language model agentic systems today are built and optimized
  for large language models (e.g., GPT, Claude, Gemini) via API calls; while powerful,
  this approach faces several limitations including high token costs and privacy concerns
  for sensitive applications. We introduce <b>EffGen</b>, an open-source agentic framework
  optimized for small language models (SLMs) that enables effective, efficient, and
  secure local deployment. EffGen makes four major contributions: <b>(1) Enhanced
  tool-calling</b> with prompt optimization that compresses input prompts by up to
  70-80% (and 57% on average across our benchmarks) while preserving task semantics,
  <b>(2) Intelligent task decomposition</b> that breaks complex queries into parallel
  or sequential subtasks based on dependencies, <b>(3) Complexity-based routing</b>
  using five factors to make smart pre-execution decisions, and <b>(4) Unified memory
  system</b> combining short-term, long-term, and vector-based storage. Additionally,
  EffGen unifies multiple agent protocols (MCP, A2A, ACP) for cross-protocol communication.
  Results on 13 benchmarks show EffGen outperforms LangChain, AutoGen, and Smolagents
  with <b>higher success rates</b>, <b>faster execution</b>, and <b>lower memory</b>.
  Our results reveal that <b>prompt optimization and complexity routing have complementary
  scaling behavior</b>: optimization benefits SLMs more (11.2% gain at 1.5B vs 2.4%
  at 32B), while routing benefits large models more (3.6% at 1.5B vs 7.9% at 32B),
  providing consistent gains across all scales when combined. EffGen is open-source
  under the Apache 2.0 License, with the code available at https://github.com/ctrl-gaurav/effGen,
  the Python package at https://pypi.org/project/effgen/ (pip install effgen), and
  the project website and documentation at https://effgen.org/ and https://docs.effgen.org/.'
software: https://github.com/ctrl-gaurav/effGen
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srivastava26a
month: 0
tex_title: "{E}ff{G}en: Enabling Small Language Models as Capable Autonomous Agents"
firstpage: 115470
lastpage: 115609
page: 115470-115609
order: 115470
cycles: false
bibtex_author: Srivastava, Gaurav and Hussain, Aafiya and Wang, Chi and Lin, Yingyan
  Celine and Wang, Xuan
author:
- given: Gaurav
  family: Srivastava
- given: Aafiya
  family: Hussain
- given: Chi
  family: Wang
- given: Yingyan Celine
  family: Lin
- given: Xuan
  family: Wang
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/srivastava26a/srivastava26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
