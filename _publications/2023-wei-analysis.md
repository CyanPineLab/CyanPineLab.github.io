---
title: "Analysis of two fully discrete spectral volume schemes for hyperbolic equations"
collection: publications
permalink: /publication/2023-wei-analysis
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
# venue: 'Journal 1'
paperurl: 'https://onlinelibrary.wiley.com/doi/abs/10.1002/num.23072'
citation: 'Wei P, Zou Q. Analysis of two fully discrete spectral volume schemes for hyperbolic equations[J]. Numerical Methods for Partial Differential Equations, 2024, 40(2): e23072.'
---

- **First published:** 20 September 2023

## Abstract

In this paper, we analyze two classes of fully discrete spectral volume schemes (SV) for solving the one-dimensional scalar hyperbolic equation. These two schemes are constructed by using the forward Euler (EU) method or the second-order Runge-Kutta (RK2) method in time-discretization, and by letting a piecewise $k$th degree ($k \geq 1$  is an arbitrary integer) polynomial satisfy the local conservation law in each control volume designed by subdividing the underlying mesh with $k$ Gauss-Legendre points (LSV) or right-Radau points (RRSV). We prove that for the EU-SV schemes, the weak(2) stability holds and the $L_{2}$ norm errors converge with optimal orders $\mathscr{O}\left(h^{k+1}+\tau\right)$, provided that the CFL condition $\tau \leq C h^{2}$ is satisfied. While for the RK2-SV schemes, the weak(4) stability holds and the $L_{2}$ norm errors converge with optimal orders $\mathscr{O}\left(h^{k+1}+\tau^{2}\right)$, provided that the CFL condition $\tau \leq C h^{\frac{4}{3}}$ is satisfied. Here $h$ and $\tau$ are, respectively, the spacial and temporal mesh sizes and the constant $C$ is independent of $h$ and $\tau$. Our theoretical findings have been justified by several numerical experiments.

[Download paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/num.23072)


## Recommended Citation

* Wei P, Zou Q. Analysis of two fully discrete spectral volume schemes for hyperbolic equations[J]. *Numerical Methods for Partial Differential Equations*, 2024, 40(2): e23072.

### BibTeX
```bibtex
@article{wei2024analysis,
  title={Analysis of two fully discrete spectral volume schemes for hyperbolic equations},
  author={Wei, Ping and Zou, Qingsong},
  journal={Numerical Methods for Partial Differential Equations},
  volume={40},
  number={2},
  pages={e23072},
  year={2024},
  publisher={Wiley Online Library}
}
```