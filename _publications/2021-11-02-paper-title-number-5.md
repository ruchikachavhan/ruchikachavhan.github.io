---
title: "Multi-Stage Semantic Graph Embeddings for Compositional Zero-Shot Learning"
collection: publications
permalink: /publication/2021-11-02-paper-title-number-5
excerpt: ''
venue: 'Pattern Recognition Letters'
---
We tackle the problem of compositional zero-shot learning (CZSL) where the task is to recognize novel composite semantic concepts (like red-tomato, wet-dog) consisting of states (red, wet) and ob- jects (tomato, dog) characterizing the visual primitives. We postulate that existing techniques do not fully explore the compositional nature of the semantic space where states, objects, and pairs follow different neigh- borhood topologies. To this end, we introduce the concept of multi-stage graph embeddings where separate GCNs are used to initially model the pairwise interactions for the states, objects, and the composition label embeddings, respectively. A composite GCN subsequently combines this informa- tion to learn a discriminative and neighborhood preserving latent semantic space ensuring the strong coupling of a composition label with its respective state and object.

<img width="832" alt="Screenshot 2023-02-01 at 15 16 25" src="https://user-images.githubusercontent.com/32021556/216082958-21d92c6d-948b-44ac-a6b6-112112c228c5.png">


Please find the [paper](https://www.researchgate.net/profile/Hitesh_Kandala/publication/362064793_Multi-Stage_Semantic_Graph_Embeddings_for_Compositional_Zero-Shot_Learning/links/6320eb3b70cc936cd3061232/Multi-Stage-Semantic-Graph-Embeddings-for-Compositional-Zero-Shot-Learning.pdf).

If you find this work useful, please cite our paper
```
@article{kandalaa2022multi,
  title={Multi-Stage Semantic Graph Embeddings for Compositional Zero-Shot Learning},
  author={Kandalaa, Hitesh and Chavhanb, Ruchika and Chaudhuric, Ushasi and Banerjeea, Biplab},
  year={2022}
}
```
