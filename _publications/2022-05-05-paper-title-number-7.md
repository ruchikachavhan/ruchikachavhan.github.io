---
title: "HyperInvariances: Amortizing Invariance Learning"
collection: publications
permalink: /publication/2022-05-05-paper-title-number-7
excerpt: ''
venue: 'ICML 2022, Workshop on Spurious Correlations, Invariances, and Stability'
---
Providing invariances in a given learning task conveys a key inductive bias that can lead to sample-efficient learning and good generalisation, if correctly specified. However, the ideal invariances for many problems of interest are often not known, which has led both to a body of engineering lore as well as attempts to provide frameworks for  invariance learning. However, invariance learning is expensive and data intensive for popular neural architectures. We introduce the notion of amortizing invariance learning. In an up-front learning phase, we learn a low-dimensional manifold of feature extractors spanning invariance to different transformations using a hyper-network. Then, for any problem of interest, both model and invariance learning are rapid and efficient by fitting a low-dimensional invariance descriptor an output head. Empirically, this framework can identify appropriate invariances in different downstream tasks and lead to comparable or better test performance than conventional approaches. Our HyperInvariance framework is also theoretically appealing as it enables generalisation-bounds that provide an interesting new operating point in the trade-off between model fit and complexity.


Please find the [paper](https://openreview.net/forum?id=mRyCWpF8t2W). Code will be available soon. 

If you find this work useful, please cite our paper
```
@inproceedings{
chavhan2022hyperinvariances,
title={HyperInvariances: Amortizing Invariance Learning},
author={Ruchika Chavhan and Henry Gouk and Jan Stuehmer and Timothy Hospedales},
booktitle={ICML 2022: Workshop on Spurious Correlations, Invariance and Stability},
year={2022},
url={https://openreview.net/forum?id=mRyCWpF8t2W}
}
```
