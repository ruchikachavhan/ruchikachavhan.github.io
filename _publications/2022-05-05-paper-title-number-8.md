---
title: "Amortised invariance learning for contrastive self-supervision"
collection: publications
permalink: /publication/2022-05-05-paper-title-number-8
excerpt: ''
venue: 'International Conference on Learning Representations, ICLR 2023'
---
Contrastive self-supervised learning methods famously produce high quality transferable representations by learning invariances to different data augmentations. Invariances established during pre-training can be interpreted as strong inductive biases. However these may or may not be helpful, depending on if they match the invariance requirements of downstream tasks or not. This has led to several attempts to learn task-specific invariances during pre-training, however, these methods are highly compute intensive and tedious to train. We introduce the notion of amortised invariance learning for contrastive self supervision. In the pre-training stage, we parameterize the feature extractor by differentiable invariance hyper-parameters that control the invariances encoded by the representation. Then, for any downstream task, both linear readout and task-specific invariance requirements can be efficiently and effectively learned by gradient-descent. We evaluate the notion of amortised invariances for contrastive learning over two different modalities: vision and audio, on two widely-used contrastive learning methods in vision: SimCLR and MoCo-v2 with popular architectures like ResNets and Vision Transformers, and SimCLR with ResNet-18 for audio. We show that our amortised features provide a reliable way to learn diverse downstream tasks with different invariance requirements, while using a single feature and avoiding task-specific pre-training. This provides an exciting perspective that opens up new horizons in the field of general purpose representation learning.

[Paper](https://arxiv.org/pdf/2302.12712), [Code](https://github.com/ruchikachavhan/amortized-invariance-learning-ssl)

If you find this work useful, please cite our paper
```
@inproceedings{
chavhan2023amortised,
title={Amortised invariance learning for contrastive self-supervision},
author={Ruchika Chavhan and Henry Gouk and Jan Stuehmer and Calum Heggan and Mehrdad Yaghoobi and Timothy Hospedales},
booktitle={International Conference on Learning Representations},
year={2023},
}
```
