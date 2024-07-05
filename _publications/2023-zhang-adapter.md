---
title: "Adapter Learning in Pretrained Feature Extractor for Continual Learning of Diseases"
collection: publications
permalink: /publication/2023-zhang-adapter
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
# venue: 'Journal 1'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-43895-0_7'
citation: 'Zhang, W., Huang, Y., Zhang, T., Zou, Q., Zheng, WS., Wang, R. (2023). Adapter Learning in Pretrained Feature Extractor for Continual Learning of Diseases. In: Greenspan, H., et al. Medical Image Computing and Computer Assisted Intervention – MICCAI 2023. MICCAI 2023. Lecture Notes in Computer Science, vol 14221. Springer, Cham.'
---

- **Published:** 01 October 2023

## Abstract

Currently intelligent diagnosis systems lack the ability of continually learning to diagnose new diseases once deployed, under the condition of preserving old disease knowledge. In particular, updating an intelligent diagnosis system with training data of new diseases would cause catastrophic forgetting of old disease knowledge. To address the catastrophic forgetting issue, an Adapter-based Continual Learning framework called ACL is proposed to help effectively learn a set of new diseases at each round (or task) of continual learning, without changing the shared feature extractor. The learnable lightweight task-specific adapter(s) can be flexibly designed (e.g., two convolutional layers) and then added to the pretrained and fixed feature extractor. Together with a specially designed task-specific head which absorbs all previously learned old diseases as a single ‘out-of-distribution’ category, task-specific adapter(s) can help the pretrained feature extractor more effectively extract discriminative features between diseases. In addition, a simple yet effective fine-tuning is applied to collaboratively fine-tune multiple task-specific heads such that outputs from different heads are comparable and consequently the appropriate classifier head can be more accurately selected during model inference. Extensive empirical evaluations on three image datasets demonstrate the superior performance of ACL in continual learning of new diseases. The source code is available at https://github.com/GiantJun/CL_Pytorch.

[Download paper](https://link.springer.com/chapter/10.1007/978-3-031-43895-0_7)


## Recommended Citation

* Zhang, W., Huang, Y., Zhang, T., Zou, Q., Zheng, WS., Wang, R. (2023). Adapter Learning in Pretrained Feature Extractor for Continual Learning of Diseases. In: Greenspan, H., et al. Medical Image Computing and Computer Assisted Intervention – MICCAI 2023. MICCAI 2023. Lecture Notes in Computer Science, vol 14221. Springer, Cham.

### BibTeX
```bibtex
@inproceedings{zhang2023adapter,
  title={Adapter learning in pretrained feature extractor for continual learning of diseases},
  author={Zhang, Wentao and Huang, Yujun and Zhang, Tong and Zou, Qingsong and Zheng, Wei-Shi and Wang, Ruixuan},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={68--78},
  year={2023},
  organization={Springer}
}
```