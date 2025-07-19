---
title: "Deep finite volume method for partial differential equations"
collection: publications
permalink: /publication/2024-cen-dfvm
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
# venue: 'Journal 1'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0021999124005552'
citation: 'Cen, J., & Zou, Q. (2024). Deep finite volume method for partial differential equations. Journal of Computational Physics, 517, 113307.'
---

- **First Online:** 31 July 2024

## Abstract

In this paper, we introduce the Deep Finite Volume Method (DFVM), an innovative deep learning framework tailored for solving high-order (order ≥2) partial differential equations (PDEs). Our approach centers on a novel loss function crafted from local conservation laws derived from the original PDE, distinguishing DFVM from traditional deep learning methods. By formulating DFVM in the weak form of the PDE rather than the strong form, we enhance accuracy, particularly beneficial for PDEs with less smooth solutions compared to strong-form-based methods like Physics-Informed Neural Networks (PINNs). A key technique of DFVM lies in its transformation of all second-order or higher derivatives of neural networks into first-order derivatives which can be computed directly using Automatic Differentiation (AD). This adaptation significantly reduces computational overhead, particularly advantageous for solving high-dimensional PDEs. Numerical experiments demonstrate that DFVM achieves equal or superior solution accuracy compared to existing deep learning methods such as PINN, Deep Ritz Method (DRM), and Weak Adversarial Networks (WAN), while drastically reducing computational costs. Notably, for PDEs with nonsmooth solutions, DFVM yields approximate solutions with relative errors up to two orders of magnitude lower than those obtained by PINN. The implementation of DFVM is available on GitHub at https://github.com/Sysuzqs/DFVM.

[Download paper](https://www.sciencedirect.com/science/article/pii/S0021999124005552)


## Recommended Citation

* Cen, J., & Zou, Q. (2024). Deep finite volume method for partial differential equations. Journal of Computational Physics, 517, 113307.

### BibTeX
```bibtex
@article{cen2024deep,
  title={Deep finite volume method for partial differential equations},
  author={Cen, Jianhuan and Zou, Qingsong},
  journal={Journal of Computational Physics},
  volume={517},
  pages={113307},
  year={2024},
  publisher={Elsevier}
}
```