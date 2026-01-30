---
title: "FUSION: Dataset Pruning via Fusing Uncertainty with Structural Information for Optimal Neural Training in Crystal Property Prediction"
collection: publications
permalink: /publication/2025-wang-fusion
paperurl: ''
citation: 'Wang X, Chen P, Tan L, Lu Y, Zou Q. FUSION: Dataset Pruning via Fusing Uncertainty with Structural Information for Optimal Neural Training in Crystal Property Prediction. In: Proceedings of the AAAI Conference on Artificial Intelligence, 2025 (accepted).'
---

- **Accepted:** 2025

## Abstract
The rapid expansion of materials databases offers unprecedented opportunities for accelerating materials discovery via machine learning. However, the widespread assumption that larger datasets inherently produce better models does not hold in practice. We propose FUSION (Fusing Uncertainty with Structural Information for Optimal Neural training), an offline dataset pruning strategy that synergistically combines uncertainty quantification with crystallographic structure analysis via geometric fingerprinting, framing dataset pruning as a discrete optimization problem. Through evaluation across 3 benchmark datasets, FUSION consistently outperforms baselines, including random pruning, uncertainty sampling, weighting factor pruning, diversity sampling, and active learning. It demonstrates robust transferability across 11 diverse architectures, outperforming random pruning by 1.91–13.65% across different datasets, with an average improvement of 6.36%. Moreover, our analysis suggests that different models exhibit varying robustness characteristics when faced with pruned training data, highlighting the importance of model selection tailored to dataset composition. We identify optimal pruning points where removing just 0–8% of training data improves model performance, yielding gains up to 12.67% in specific model–dataset combinations. These results establish a new paradigm for materials informatics that prioritizes data quality over quantity, offering a pathway toward more efficient and sustainable machine learning workflows in computational materials science.


## Recommended Citation
* Xiean Wang, Pin Chen, Liqin Tan, Yutong Lu, Qingsong Zou. FUSION: Dataset Pruning via Fusing Uncertainty with Structural Information for Optimal Neural Training in Crystal Property Prediction. In: Proceedings of the AAAI Conference on Artificial Intelligence, 2025 (accepted).

### BibTeX
```bibtex
@inproceedings{wang2026fusion,
  title={FUSION: Dataset Pruning via Fusing Uncertainty with Structural Information for Optimal Neural Training in Crystal Property Prediction},
  author={Wang, Xiean and Chen, Pin and Tan, Liqin and Lu, Yutong and Zou, Qingsong},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  year={2026}
}
```
