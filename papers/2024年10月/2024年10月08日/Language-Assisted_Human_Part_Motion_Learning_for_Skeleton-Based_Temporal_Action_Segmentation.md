# 语言助力骨架动作分割：人体运动学习新篇章

发布时间：2024年10月08日

`LLM应用` `人工智能`

> Language-Assisted Human Part Motion Learning for Skeleton-Based Temporal Action Segmentation

# 摘要

> 基于骨架的时间动作分割涉及对可变长度骨架序列的密集动作分类。当前方法主要通过图网络提取全身运动表示，并使用独热编码标签进行模型优化。然而，这些方法无法捕捉细粒度的部分级运动，且忽略了动作定义中的语义关系。为此，我们提出了语言辅助人体部分运动表示学习（LPL）方法，包含解耦部分运动编码器（DPE）和语言辅助分布对齐（LDA）策略。DPE提取双层运动表示，LDA则通过生成双层动作描述，借助大规模语言模型构建文本嵌入空间，并促使文本与运动嵌入空间对齐。这种对齐不仅增强了类内紧凑性，还将语义相关性转移到骨架运动学习中。此外，我们设计了语义偏移适配器，以平滑跨域对齐误差。实验表明，LPL在多个数据集上达到了最先进性能，且LDA能有效提升现有方法的性能，而无需额外推理成本。

> Skeleton-based Temporal Action Segmentation involves the dense action classification of variable-length skeleton sequences. Current approaches primarily apply graph-based networks to extract framewise, whole-body-level motion representations, and use one-hot encoded labels for model optimization. However, whole-body motion representations do not capture fine-grained part-level motion representations and the one-hot encoded labels neglect the intrinsic semantic relationships within the language-based action definitions. To address these limitations, we propose a novel method named Language-assisted Human Part Motion Representation Learning (LPL), which contains a Disentangled Part Motion Encoder (DPE) to extract dual-level (i.e., part and whole-body) motion representations and a Language-assisted Distribution Alignment (LDA) strategy for optimizing spatial relations within representations. Specifically, after part-aware skeleton encoding via DPE, LDA generates dual-level action descriptions to construct a textual embedding space with the help of a large-scale language model. Then, LDA motivates the alignment of the embedding space between text descriptions and motions. This alignment allows LDA not only to enhance intra-class compactness but also to transfer the language-encoded semantic correlations among actions to skeleton-based motion learning. Moreover, we propose a simple yet efficient Semantic Offset Adapter to smooth the cross-domain misalignment. Our experiments indicate that LPL achieves state-of-the-art performance across various datasets (e.g., +4.4\% Accuracy, +5.6\% F1 on the PKU-MMD dataset). Moreover, LDA is compatible with existing methods and improves their performance (e.g., +4.8\% Accuracy, +4.3\% F1 on the LARa dataset) without additional inference costs.

[Arxiv](https://arxiv.org/abs/2410.06353)