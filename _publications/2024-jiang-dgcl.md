---
title: "DGCL: dual-graph neural networks contrastive learning for molecular property prediction"
collection: publications
permalink: /publication/2024-jiang-dgcl
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
# venue: 'Journal 1'
paperurl: 'https://academic.oup.com/bib/article/25/6/bbae474/7779242'
citation: 'Jiang, X., Tan, L., & Zou, Q. (2024). DGCL: dual-graph neural networks contrastive learning for molecular property prediction. Briefings in Bioinformatics, 25(6), bbae474.'
---

- **First Online:** 27 September 2024

## Abstract

In this paper, we propose DGCL, a dual-graph neural networks (GNNs)-based contrastive learning (CL) integrated with mixed molecular fingerprints (MFPs) for molecular property prediction. The DGCL-MFP method contains two stages. In the first pretraining stage, we utilize two different GNNs as encoders to construct CL, rather than using the method of generating enhanced graphs as before. Precisely, DGCL aggregates and enhances features of the same molecule by the Graph Isomorphism Network and the Graph Attention Network, with representations extracted from the same molecule serving as positive samples, and others marked as negative ones. In the downstream tasks training stage, features extracted from the two above pretrained graph networks and the meticulously selected MFPs are concated together to predict molecular properties. Our experiments show that DGCL enhances the performance of existing GNNs by achieving or surpassing the state-of-the-art self-supervised learning models on multiple benchmark datasets. Specifically, DGCL increases the average performance of classification tasks by 3.73% and improves the performance of regression task Lipo by 0.126. Through ablation studies, we validate the impact of network fusion strategies and MFPs on model performance. In addition, DGCL’s predictive performance is further enhanced by weighting different molecular features based on the Extended Connectivity Fingerprint. The code and datasets of DGCL will be made publicly available.

[Download paper](https://academic.oup.com/bib/article/25/6/bbae474/7779242)


## Recommended Citation

* Jiang, X., Tan, L., & Zou, Q. (2024). DGCL: dual-graph neural networks contrastive learning for molecular property prediction. Briefings in Bioinformatics, 25(6), bbae474.

### BibTeX
```bibtex
@article{jiang2024dgcl,
  title={DGCL: dual-graph neural networks contrastive learning for molecular property prediction},
  author={Jiang, Xiuyu and Tan, Liqin and Zou, Qingsong},
  journal={Briefings in Bioinformatics},
  volume={25},
  number={6},
  pages={bbae474},
  year={2024},
  publisher={Oxford University Press}
}
```