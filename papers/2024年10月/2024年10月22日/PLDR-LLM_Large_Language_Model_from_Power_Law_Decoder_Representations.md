# PLDR-LLM：来自幂律解码器表示的大型语言模型

发布时间：2024年10月22日

`LLM理论` `语言模型` `预训练`

> PLDR-LLM: Large Language Model from Power Law Decoder Representations

# 摘要

> 我们提出了来自幂律解码器表示的大型语言模型（PLDR-LLM），这是一种通过幂律图注意力机制利用非线性和线性变换来生成定义明确的演绎和归纳输出的语言模型。我们使用小批量大小为 32 和来自 RefinedWeb 数据集的约 80 亿个标记对不同层大小的 PLDR-LLM 进行预训练，并表明与文献中报道的类似模型大小的缩放点积 LLM 相比，它们在零样本和少样本设置中实现了有竞争力的性能。我们表明，PLDR-LLM 的演绎输出可以通过引入有向无环图（DAG）损失作为度量和正则化器来比较模型特征或提高性能。我们的结果表明，初始最大学习率和预热步骤在整个预训练过程中对演绎输出具有持久影响。我们提供了 PLDR-LLM 架构、其实现和预训练过程的详细描述。

> We present the Large Language Model from Power Law Decoder Representations (PLDR-LLM), a language model that leverages non-linear and linear transformations through Power Law Graph Attention mechanism to generate well-defined deductive and inductive outputs. We pretrain the PLDR-LLMs of varying layer sizes with a small batch size of 32 and $\sim$8B tokens from the RefinedWeb dataset, and show that they achieve competitive performance in zero-shot and few-shot settings compared to scaled dot-product LLMs of similar model size reported in the literature. We show that deductive outputs of PLDR-LLMs can be used to compare model characteristics or improve the performance by introducing the Directed Acyclic Graph (DAG) loss as a metric and regularizer. Our results indicate that the initial maximum learning rate and warm-up steps have a lasting impact on deductive outputs throughout the pretraining. We provide a detailed description of PLDR-LLM architecture, its implementation and the pretraining procedure.

[Arxiv](https://arxiv.org/abs/2410.16703)