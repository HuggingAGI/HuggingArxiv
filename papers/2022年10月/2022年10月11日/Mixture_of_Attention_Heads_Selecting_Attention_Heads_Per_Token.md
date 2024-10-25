# 注意力头的混合：为每个标记选择注意力头

发布时间：2022年10月11日

`其他` `机器翻译` `语言建模`

> Mixture of Attention Heads: Selecting Attention Heads Per Token

# 摘要

> 摘要：混合专家（MoE）网络已被提出作为一种有效的方式来扩大模型容量和实现条件计算。然而，对 MoE 组件的研究主要集中在 Transformer 架构中的前馈层。本文提出了注意力头的混合（MoA），这是一种将多头注意力与 MoE 机制相结合的新架构。MoA 包括一组注意力头，每个头都有自己的一组参数。给定一个输入，路由器为每个标记动态选择 k 个注意力头的子集。这种条件计算模式使 MoA 能够实现比标准多头注意力层更强的性能。此外，稀疏门控的 MoA 可以在保持计算效率的同时轻松扩大注意力头的数量和参数的数量。除了性能改进之外，MoA 还自动区分了头的效用，为讨论模型的可解释性提供了新的视角。我们在几个重要任务上进行了实验，包括机器翻译和掩码语言建模。实验在几个任务上针对涉及大型和非常深的模型的强大基线显示出了有希望的结果。

> 
Abstract:Mixture-of-Experts (MoE) networks have been proposed as an efficient way to scale up model capacity and implement conditional computing. However, the study of MoE components mostly focused on the feedforward layer in Transformer architecture. This paper proposes the Mixture of Attention Heads (MoA), a new architecture that combines multi-head attention with the MoE mechanism. MoA includes a set of attention heads that each has its own set of parameters. Given an input, a router dynamically selects a subset of $k$ attention heads per token. This conditional computation schema allows MoA to achieve stronger performance than the standard multi-head attention layer. Furthermore, the sparsely gated MoA can easily scale up the number of attention heads and the number of parameters while preserving computational efficiency. In addition to the performance improvements, MoA also automatically differentiates heads' utilities, providing a new perspective to discuss the model's interpretability. We conducted experiments on several important tasks, including Machine Translation and Masked Language Modeling. Experiments have shown promising results on several tasks against strong baselines that involve large and very deep models.
    

[Arxiv](https://arxiv.org/pdf/2210.05144)