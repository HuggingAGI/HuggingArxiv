# 一次训练，随处可用：多萝西卡表示学习助力多模态推荐

发布时间：2024年09月25日

`LLM应用` `推荐系统` `电子商务`

> Train Once, Deploy Anywhere: Matryoshka Representation Learning for Multimodal Recommendation

# 摘要

> 尽管语言和视觉建模有所进步，但将多模态知识融入推荐系统仍具挑战。这主要源于高效推荐对适应性和交互性的需求。本研究聚焦于序列推荐，提出轻量级框架 fMRLRec。该框架在不同粒度捕捉项目特征，优化多维度推荐。通过简单映射，fMRLRec 整合多模态特征至对齐空间，并设计高效线性变换，大幅降低大规模训练的内存需求。结合先进状态空间建模，fMRLRec 仅需一次训练，即可生成适应不同粒度的多模型。实验表明，fMRLRec 在多个基准数据集上表现优异，超越了现有最先进方法。

> Despite recent advancements in language and vision modeling, integrating rich multimodal knowledge into recommender systems continues to pose significant challenges. This is primarily due to the need for efficient recommendation, which requires adaptive and interactive responses. In this study, we focus on sequential recommendation and introduce a lightweight framework called full-scale Matryoshka representation learning for multimodal recommendation (fMRLRec). Our fMRLRec captures item features at different granularities, learning informative representations for efficient recommendation across multiple dimensions. To integrate item features from diverse modalities, fMRLRec employs a simple mapping to project multimodal item features into an aligned feature space. Additionally, we design an efficient linear transformation that embeds smaller features into larger ones, substantially reducing memory requirements for large-scale training on recommendation data. Combined with improved state space modeling techniques, fMRLRec scales to different dimensions and only requires one-time training to produce multiple models tailored to various granularities. We demonstrate the effectiveness and efficiency of fMRLRec on multiple benchmark datasets, which consistently achieves superior performance over state-of-the-art baseline methods.

[Arxiv](https://arxiv.org/abs/2409.16627)