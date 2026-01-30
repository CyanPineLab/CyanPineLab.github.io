---
title: "PPFNet: A Parameter-Guided Operator Network for Solving Phase Field Equations"
collection: publications
permalink: /publication/2025-chen-ppfnet
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-96-9894-3_27'
citation: 'Chen L, Zou Q. PPFNet: A Parameter-Guided Operator Network for Solving Phase Field Equations[C]//International Conference on Intelligent Computing. Singapore: Springer Nature Singapore, 2025: 324-335.'
---

- **First Online:** 26 July 2025

## Abstract
This paper focuses on the numerical solutions of phase field equations with small parameters. Traditional numerical methods struggle considerably when handling these small-parameter cases, as attaining the required computational accuracy necessitates a complex design and incurs high computational expenses. Deep learning algorithms also grapple with issues like algorithmic failure or low accuracy.

To address these challenges, we propose PPFNet, a novel deep learning approach. PPFNet innovatively embeds a parameter branch network within the DeepONet architecture, allowing it to interact with DeepONet and further refine its representations through the proposed multi-branch fusion modules, significantly enhancing interpolation and extrapolation capabilities. Moreover, we further propose a pre-training algorithm for the parameter branch network. For relatively larger labeled parameters, it constructs parameter-solution sample pairs and utilizes a contrastive loss function to capture parameter features more effectively. For all parameters, including small inferred ones, an unsupervised learning strategy is employed, utilizing a separate decoder and a reconstruction loss function to capture transferable features. These improvements enhance the model’s generalization capabilities. Experimental results from the Allen–Cahn, Cahn–Hilliard, and MBE equations clearly show that PPFNet achieves both lower approximation error and significantly reduced inference time compared to FEM, especially for extremely small parameter values.

## Recommended Citation
* Chen L, Zou Q. PPFNet: A Parameter-Guided Operator Network for Solving Phase Field Equations[C]//International Conference on Intelligent Computing. Singapore: Springer Nature Singapore, 2025: 324-335.

### BibTeX
```bibtex
@InProceedings{10.1007/978-981-96-9894-3_27,
author="Chen, Liao
and Zou, Qingsong",
editor="Huang, De-Shuang
and Zhang, Qinhu
and Zhang, Chuanlei
and Chen, Wei",
title="PPFNet: A Parameter-Guided Operator Network for Solving Phase Field Equations",
booktitle="Advanced Intelligent Computing Technology and Applications",
year="2025",
publisher="Springer Nature Singapore",
address="Singapore",
pages="324--335",
abstract="This paper focuses on the numerical solutions of phase field equations with small parameters. Traditional numerical methods struggle considerably when handling these small-parameter cases, as attaining the required computational accuracy necessitates a complex design and incurs high computational expenses. Deep learning algorithms also grapple with issues like algorithmic failure or low accuracy.",
isbn="978-981-96-9894-3"
}

```
