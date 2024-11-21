# 利用高分辨率组织学图像进行空间转录组学的多模态空间聚类

发布时间：2024年10月30日

`其他`

> Multi-modal Spatial Clustering for Spatial Transcriptomics Utilizing High-resolution Histology Images

# 摘要

> 理解生物组织内复杂的细胞环境对于探究复杂生物功能的奥秘至关重要。尽管单细胞 RNA 测序极大地增进了我们对细胞状态的认知，但它缺少全面理解细胞环境所需的空间背景。空间转录组学（ST）能够在保留空间背景的情况下进行转录组范围的基因表达谱分析，从而解决了这一难题。ST 数据分析的主要挑战之一是空间聚类，它依据组织内的斑点来揭示空间域。现代 ST 测序流程通常包含高分辨率的组织学图像，以往研究表明其与基因表达谱紧密相连。然而，当下的空间聚类方法常常难以将高分辨率组织学图像特征与基因表达数据充分融合，限制了其捕捉关键空间和细胞相互作用的能力。
在本研究中，我们提出了空间转录组学多模态聚类（stMMC）模型，这是一种基于对比学习的新型深度学习方法，通过多模态并行图自动编码器将基因表达数据与组织学图像特征加以整合。我们在两个公共 ST 数据集上对 stMMC 与四个前沿的基线模型：Leiden、GraphST、SpaGCN 和 stLearn 进行了测试，总计 13 个样本切片。实验表明，stMMC 在 ARI 和 NMI 方面均优于所有基线模型。消融研究进一步证实了对比学习以及组织学图像特征整合的作用。

> Understanding the intricate cellular environment within biological tissues is crucial for uncovering insights into complex biological functions. While single-cell RNA sequencing has significantly enhanced our understanding of cellular states, it lacks the spatial context necessary to fully comprehend the cellular environment. Spatial transcriptomics (ST) addresses this limitation by enabling transcriptome-wide gene expression profiling while preserving spatial context. One of the principal challenges in ST data analysis is spatial clustering, which reveals spatial domains based on the spots within a tissue. Modern ST sequencing procedures typically include a high-resolution histology image, which has been shown in previous studies to be closely connected to gene expression profiles. However, current spatial clustering methods often fail to fully integrate high-resolution histology image features with gene expression data, limiting their ability to capture critical spatial and cellular interactions.
  In this study, we propose the spatial transcriptomics multi-modal clustering (stMMC) model, a novel contrastive learning-based deep learning approach that integrates gene expression data with histology image features through a multi-modal parallel graph autoencoder. We tested stMMC against four state-of-the-art baseline models: Leiden, GraphST, SpaGCN, and stLearn on two public ST datasets with 13 sample slices in total. The experiments demonstrated that stMMC outperforms all the baseline models in terms of ARI and NMI. An ablation study further validated the contributions of contrastive learning and the incorporation of histology image features.

[Arxiv](https://arxiv.org/abs/2411.02534)