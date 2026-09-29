---
title: 'MAS-ProVe: Understanding the Process Verification of Multi-Agent Systems'
openreview: UoM3G7nKr0
abstract: Multi-Agent Systems (MAS) built on Large Language Models (LLMs) often exhibit
  high variance in their reasoning trajectories. Process verification, which evaluates
  intermediate steps in trajectories, has shown promise in general reasoning settings,
  and has been suggested as a potential tool for guiding coordination of MAS; however,
  its actual effectiveness in MAS remains unclear. To fill this gap, we present MAS-ProVe,
  a systematic empirical study of process verification for multi-agent systems (MAS).
  Our study spans <em>three verification paradigms</em> (LLM-as-a-Judge, reward models,
  and process reward models), evaluated across <em>two levels of verification granularity</em>
  (agent-level and iteration-level). We further examine <em>five representative verifiers</em>
  and <em>four context management strategies,</em> and conduct experiments over <em>six
  diverse MAS frameworks</em> on multiple reasoning benchmarks. We find that process-level
  verification does not consistently improve performance and frequently exhibits high
  variance, highlighting the difficulty of reliably evaluating partial multi-agent
  trajectories. Among the methods studied, LLM-as-a-Judge generally outperforms reward-based
  approaches, with trained judges surpassing general-purpose LLMs. We further observe
  a small performance gap between LLMs acting as judges and as single agents, and
  identify a context-length-performance trade-off in verification. Overall, our results
  suggest that effective and robust process verification for MAS remains an open challenge,
  requiring further advances beyond current paradigms.
software: https://github.com/Wang-ML-Lab/MAS-ProVe
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: venkataramani26a
month: 0
tex_title: "{MAS}-{P}ro{V}e: Understanding the Process Verification of Multi-Agent
  Systems"
firstpage: 123733
lastpage: 123764
page: 123733-123764
order: 123733
cycles: false
bibtex_author: Venkataramani, Vishal and Shi, Haizhou and Ke, Zixuan and Xu, Austin
  and He, Xiaoxiao and Zhou, Yingbo and Yavuz, Semih and Wang, Hao and Joty, Shafiq
author:
- given: Vishal
  family: Venkataramani
- given: Haizhou
  family: Shi
- given: Zixuan
  family: Ke
- given: Austin
  family: Xu
- given: Xiaoxiao
  family: He
- given: Yingbo
  family: Zhou
- given: Semih
  family: Yavuz
- given: Hao
  family: Wang
- given: Shafiq
  family: Joty
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/venkataramani26a/venkataramani26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
