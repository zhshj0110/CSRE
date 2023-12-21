# STD-CL
The official implementation of the paper 'Spatial-Temporal Decoupling Contrastive Learning for Skeleton-based Human Action Recognition'

### Abstract

```latex
Skeleton-based action recognition is a central task of human-computer interaction. Current methods apply the modeling paradigm of image recognition to it directly. However, the skeleton sequences abstracted from the human body is a sparse representation. The features extracted from the skeleton encoder are spatiotemporal decoupled, which may confuse the semantics. To reduce the coupling and improve the semantics of the global features, we propose a framework (STD-CL) for skeleton-based action recognition. We first decouple the spatial-specific and temporal-specific features from the spatiotemporal features. Then we apply the attentive features to contrastive learning, which pulls together the features from the positive pairs and pushes away the feature embedding from the negative pairs. Moreover, the proposed training strategy STD-CL can be incorporated into current methods. Without additional compute consumption in the testing phase, our STD-CL with four various backbones (HCN, 2S-AGCN, CTR-GCN, and Hyperformer) achieves improvement on NTU60, NTU120, and NW-UCLA benchmarks.
```

