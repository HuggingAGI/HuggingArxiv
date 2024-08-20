# RoarGraph：一款专为跨模态近似最近邻搜索设计的高效投影二分图项目

发布时间：2024年08月16日

`LLM应用` `推荐系统` `多媒体`

> RoarGraph: A Projected Bipartite Graph for Efficient Cross-Modal Approximate Nearest Neighbor Search

# 摘要

> 近似最近邻搜索（ANNS）在推荐系统和大型语言模型应用中至关重要。随着多模态神经模型的发展，跨模态ANNS成为研究热点，旨在通过文本查询检索图像或视频中的相似项。然而，模态间的嵌入分布差异导致跨模态查询成为分布外（OOD）查询，影响ANNS性能。本文通过定量分析OOD查询特性，揭示了其在空间上的偏离和最近邻间的距离，挑战了现有ANNS方法的假设。为此，我们提出投影二分图（RoarGraph），一种在查询分布指导下构建的高效ANNS图索引。实验证明，RoarGraph在跨模态数据集上显著提升搜索速度，OOD查询在90%召回率下速度提升高达3.56倍。

> Approximate Nearest Neighbor Search (ANNS) is a fundamental and critical component in many applications, including recommendation systems and large language model-based applications. With the advancement of multimodal neural models, which transform data from different modalities into a shared high-dimensional space as feature vectors, cross-modal ANNS aims to use the data vector from one modality (e.g., texts) as the query to retrieve the most similar items from another (e.g., images or videos). However, there is an inherent distribution gap between embeddings from different modalities, and cross-modal queries become Out-of-Distribution (OOD) to the base data. Consequently, state-of-the-art ANNS approaches suffer poor performance for OOD workloads. In this paper, we quantitatively analyze the properties of the OOD workloads to gain an understanding of their ANNS efficiency. Unlike single-modal workloads, we reveal OOD queries spatially deviate from base data, and the k-nearest neighbors of an OOD query are distant from each other in the embedding space. The property breaks the assumptions of existing ANNS approaches and mismatches their design for efficient search. With insights from the OOD workloads, we propose pRojected bipartite Graph (RoarGraph), an efficient ANNS graph index built under the guidance of query distribution. Extensive experiments show that RoarGraph significantly outperforms state-of-the-art approaches on modern cross-modal datasets, achieving up to 3.56x faster search speed at a 90% recall rate for OOD queries.

[Arxiv](https://arxiv.org/abs/2408.08933)