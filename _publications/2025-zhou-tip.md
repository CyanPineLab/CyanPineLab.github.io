---
title: "Tip-Adapter-SA: Training-Free CLIP-Adapter Enhanced by Semantic Alignment for Multi-Label Few-Shot Classification with Single Positive Labels"
collection: publications
permalink: /publication/2025-zhou-tip
paperurl: 'https://ieeexplore.ieee.org/document/11189294'
citation: 'Zhou Z, Zou Q. Tip-Adapter-SA: Training-Free CLIP-Adapter Enhanced by Semantic Alignment for Multi-Label Few-Shot Classification with Single Positive Labels[C]//2025 IEEE 5th International Conference on Computer Communication and Artificial Intelligence (CCAI). IEEE, 2025: 1-8.'
---

- **First Online:** October 2025

## Abstract
Multi-label classification is a fundamental task that requires predicting all applicable labels for each sample. Previous methods often rely heavily on training models with large-scale multi-label datasets. However, constructing such datasets with full annotations is labor-consuming. To drastically reduce the annotation burden, we introduce a novel problem setting termed multi-label few-shot classification with single positive labels, where only a small number of training samples per class are available, each annotated with a single positive label. In this paper, we propose a Training-Free CLIP-Adapter enhanced by Semantic Alignment (Tip-Adapter-SA), which not only inherits the training-free advantage of CLIP but also efficiently leverages the limited supervision from few-shot single positive labels to address this setting. Our method comprises two key modules: (1) a CLIP-based semantic-driven feature extractor that extracts class-specific features guided by class semantics, and (2) a cachebased training-free CLIP-Adapter constructed from the few-shot training set, serving as a distance-based classifier. Comprehensive experiments and analyses demonstrate that our method significantly outperforms state-of-the-art methods in the newly proposed setting on MS-COCO 2014 and PASCAL VOC 2012. The code is available at https://github.com/zhouzy36/Tip-Adapter-SA.

## Recommended Citation
* Zhou Z, Zou Q. Tip-Adapter-SA: Training-Free CLIP-Adapter Enhanced by Semantic Alignment for Multi-Label Few-Shot Classification with Single Positive Labels[C]//2025 IEEE 5th International Conference on Computer Communication and Artificial Intelligence (CCAI). IEEE, 2025: 1-8.

### BibTeX
```bibtex
@INPROCEEDINGS{11189294,
  author={Zhou, Ziyang and Zou, Qingsong},
  booktitle={2025 IEEE 5th International Conference on Computer Communication and Artificial Intelligence (CCAI)}, 
  title={Tip-Adapter-SA: Training-Free CLIP-Adapter Enhanced by Semantic Alignment for Multi-Label Few-Shot Classification with Single Positive Labels}, 
  year={2025},
  volume={},
  number={},
  pages={1-8},
  keywords={Training;Learning systems;Image recognition;Image resolution;Annotations;Semantics;Multi label classification;Feature extraction;Few shot learning;Image classification;Multi-Label Classification;Few-Shot Learning;Image Recognition;Vision-Language Models},
  doi={10.1109/CCAI65422.2025.11189294}}
```
