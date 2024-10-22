# 全面评估大型语言模型在 RNA 二级结构预测中的表现

发布时间：2024年10月21日

`LLM应用` `生物信息学` `RNA研究`

> Comprehensive benchmarking of large language models for RNA secondary structure prediction

# 摘要

> 受 LLM 在 DNA 和蛋白质领域的成功启发，近期涌现了多个针对 RNA 的 LLM。RNA-LLM 通过自监督学习，利用大量 RNA 序列数据，将每个 RNA 碱基转化为富含语义的数值向量。这一方法基于假设：高质量的 RNA 表示能提升数据密集型下游任务的效果。其中，预测 RNA 的二级结构是理解其功能机制的关键。本文对多个预训练的 RNA-LLM 进行了深入实验分析，在统一深度学习框架下，比较了它们在 RNA 二级结构预测任务中的表现。实验结果表明，两款 LLM 表现尤为突出，但在低同源性场景下，泛化能力面临显著挑战。

> Inspired by the success of large language models (LLM) for DNA and proteins, several LLM for RNA have been developed recently. RNA-LLM uses large datasets of RNA sequences to learn, in a self-supervised way, how to represent each RNA base with a semantically rich numerical vector. This is done under the hypothesis that obtaining high-quality RNA representations can enhance data-costly downstream tasks. Among them, predicting the secondary structure is a fundamental task for uncovering RNA functional mechanisms. In this work we present a comprehensive experimental analysis of several pre-trained RNA-LLM, comparing them for the RNA secondary structure prediction task in an unified deep learning framework. The RNA-LLM were assessed with increasing generalization difficulty on benchmark datasets. Results showed that two LLM clearly outperform the other models, and revealed significant challenges for generalization in low-homology scenarios.

[Arxiv](https://arxiv.org/abs/2410.16212)