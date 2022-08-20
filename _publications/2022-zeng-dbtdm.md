---
title: "Deep Neural Networks Based Temporal-Difference Methods for High-Dimensional Parabolic Partial Differential Equations"
collection: publications
permalink: /publication/2022-zeng-dbtdm
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
# venue: 'Journal 1'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0021999122005654'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

- **Received:**  18 April 2022
- **Accepted:**  21 July 2022
- **Published:** 28 July 2022


## Abstract

Solving high-dimensional partial differential equations (PDEs) is a long-standing challenge, for which classical numerical methods suffer from the well-known curse of dimensionality. In this paper, we propose deep neural networks (NN) based temporal-difference (TD) learning methods for numerically solving high-dimensional parabolic PDEs. To this end, we approximate the solution of the original PDE with an NN function. To calculate this neural network function, we first transform the deterministic parabolic PDE to a forward-backward stochastic differential equations (FBSDE) system with the nonlinear Feynman-Kac formula, and then transform the forward updating process of FBSDE as a Markov reward process (MRP). On this basis, we approximate the solution of the PDE by training an NN function with a reinforcement learning technique described as below: we first discretize the temporal interval to a finite number of time steps and then at each time step, we generate many trajectories and design the loss function as the mean square of temporal difference error on all trajectories. With this loss function, we update the parameters of the NN function with the stochastic gradient descent (SGD) method. Numerical experiments show that comparing to some other existed deep learning methods, our method not only accelerates the computational speed but also improves the computational accuracy. In particular, the relative errors of our algorithm achieve the order of $O(10^{-4}) even the dimension of the problem is as high as 100.

[Download paper](https://www.sciencedirect.com/science/article/pii/S0021999122005654)


## Recommended Citation

> 

### BibTeX
```bibtex
@article{zeng2022deep,
  title={Deep neural networks based temporal-difference methods for high-dimensional parabolic partial differential equations},
  author={Zeng, Shaojie and Cai, Yihua and Zou, Qingsong},
  journal={Journal of Computational Physics},
  pages={111503},
  year={2022},
  publisher={Elsevier}
}
```