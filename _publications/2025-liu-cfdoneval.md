---
title: "CFDONEval: a comprehensive evaluation of operator-learning neural network models for computational fluid dynamics"
collection: publications
permalink: /publication/2025-liu-cfdoneval
paperurl: 'https://www.ijcai.org/proceedings/2025/640'
citation: 'Liu M, Cen J, Zhou Z, et al. CFDONEval: a comprehensive evaluation of operator-learning neural network models for computational fluid dynamics[C]//Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence. 2025: 5752-5760.'
---

- **First Online:** 2025

## Abstract
In this paper, we introduce CFDONEval, a comprehensive evaluation of 12 operator-learning-based neural network (ON) models to simulate 7 benchmark fluid dynamics problems. These problems cover a range of 2D scenarios, including Darcy flow, two-phase flow, Taylor-Green vortex, lid-driven cavity flow, tube flow, circular cylinder flow, and 3D periodic hill flow. For a rigorous evaluation, we establish 22 fluid dynamics datasets for these benchmark problems, 18 of which are newly generated using traditional numerical methods, such as the finite element method. Our evaluation tackles 5 key challenges: multiscale phenomena, convection dominance, long-term predictions, multiphase flows, and unstructured meshes over complex geometries. We assess computational accuracy, efficiency, and flow field visualization, offering valuable insights into the application of ON models in fluid dynamics research. Our findings show that attention-based models perform well in handling almost all challenges; models with a U-shaped structure excel in handling multiscale problems; and the NU-FNO model demonstrates the smallest relative error in L2 norm when processing nonuniform grid data. The related code, dataset, and appendix are publicly available at: https://github.com/Sysuzqs/CFDNNEval.

## Recommended Citation
* Liu M, Cen J, Zhou Z, et al. CFDONEval: a comprehensive evaluation of operator-learning neural network models for computational fluid dynamics[C]//Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence. 2025: 5752-5760.

### BibTeX
```bibtex
@inproceedings{ijcai2025p640,
  title     = {CFDONEval: A Comprehensive Evaluation of Operator-Learning Neural Network Models for Computational Fluid Dynamics},
  author    = {Liu, Menghan and Cen, Jianhuan and Zhou, Ziyang and Fan, Haolong and Li, Hongji and Wei, Ping and Peng, Guohang and He, Changye and Qin, Yuzhe and Lu, Yutong and Zou, Qingsong},
  booktitle = {Proceedings of the Thirty-Fourth International Joint Conference on
               Artificial Intelligence, {IJCAI-25}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {James Kwok},
  pages     = {5752--5760},
  year      = {2025},
  month     = {8},
  note      = {Main Track},
  doi       = {10.24963/ijcai.2025/640},
  url       = {https://doi.org/10.24963/ijcai.2025/640},
}

```
