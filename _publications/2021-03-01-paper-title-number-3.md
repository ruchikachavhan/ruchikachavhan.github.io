---
title: "SketRet: Bi-Level Domain Adaptation for Zero-Shot Sketch-Based Image Retrieval"
collection: publications
permalink: /publication/2021-03-01-paper-title-number-1
excerpt: ''
venue: 'Neurocomputing'
---

The efficacy of zero-shot sketch-based image retrieval (ZS-SBIR) models is governed by two challenges. The immense distributions-gap between the sketches and the images requires a proper domain alignment. Moreover, the fine-grained nature of the task and the high intra-class variance of many categories necessitates a class-wise discriminative mapping among the sketch, image, and the semantic spaces. Under this premise, we propose BDA-SketRet, a novel ZS-SBIR framework performing a bi-level domain adaptation for aligning the spatial and semantic features of the visual data pairs progressively. we propose a novel symmetric loss function based on the notion of information bottleneck for aligning the semantic features while a cross-entropy-based adversarial loss is introduced to align the spatial feature maps.

![1-s2 0-S0925231222011961-gr1](https://user-images.githubusercontent.com/32021556/216078527-2cc8db9b-91db-454a-8fe8-cb0fcdfb06e0.jpeg)

Please find the [paper](https://www.sciencedirect.com/science/article/pii/S0925231222011961)

If you find this work useful, please cite our paper
```
@article{CHAUDHURI2022245,
title = {BDA-SketRet: Bi-level domain adaptation for zero-shot SBIR},
journal = {Neurocomputing},
year = {2022},
author = {Ushasi Chaudhuri and Ruchika Chavan and Biplab Banerjee and Anjan Dutta and Zeynep Akata},
}
```