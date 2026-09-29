---
title: 'Fairness in Aggregation: Optimal Top-$k$ and Improved Full Ranking'
openreview: CeyNBFDCdB
abstract: Ensuring fairness in algorithmic ranking systems is a critical challenge
  with significant societal implications for hiring, recommendations, web search,
  and data management. Standard methods for aggregating multiple preference orders
  into a consensus ranking may perpetuate and even amplify the lack of representation
  of underrepresented groups. To address this, recent research has focused on incorporating
  fairness constraints to ensure the presence of different groups in the top-$k$ positions
  of the final aggregate ranking. We study two fairness-aware variants under the well-known
  Spearman footrule, which corresponds to the $L_1$ distance between rankings. First,
  we address the practically salient task of computing a fair aggregate top-$k$ ranking
  – crucial in settings like recommendations and hiring where selection is primarily
  based on the top-$k$ results – and present the first optimal algorithm for this
  problem. Second, we consider fair (full) rank aggregation over all candidates (not
  specifically on top-$k$). We already know of a $3$-approximation for this fair rank
  aggregation variant (Wei et al., SIGMOD’22; Chakraborty et al., NeurIPS’22), whereas
  an exact algorithm exists for the corresponding unconstrained (unfair) version (Dwork
  et al., WWW’01). Closing the computational gap between fair and unconstrained rank
  aggregation has remained a tantalizing open problem. We make significant progress
  by giving a $2$-approximation algorithm for fair (full) rank aggregation, improving
  substantially over the previous $3$-approximation. Further, we complement our theoretical
  contributions with experiments on different real-world datasets, which corroborate
  our theoretical results and demonstrate strong empirical performance relative to
  state-of-the-art baselines.
software: https://github.com/Aussiroth/Spearman-FRA
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26b
month: 0
tex_title: 'Fairness in Aggregation: Optimal Top-$k$ and Improved Full Ranking'
firstpage: 12460
lastpage: 12474
page: 12460-12474
order: 12460
cycles: false
bibtex_author: Chakraborty, Diptarka and Mazumdar, Arya and Saha, Barna and Yan, Alvin
  Hong Yao
author:
- given: Diptarka
  family: Chakraborty
- given: Arya
  family: Mazumdar
- given: Barna
  family: Saha
- given: Alvin Hong Yao
  family: Yan
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
pdf: https://raw.githubusercontent.com/mlresearch/v306/main/assets/chakraborty26b/chakraborty26b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
