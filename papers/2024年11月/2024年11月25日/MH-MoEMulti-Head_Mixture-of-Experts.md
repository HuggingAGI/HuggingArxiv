# MH-MoE:多头部的专家混合模式

发布时间：2024年11月25日

`LLM应用` `语言模型` `计算机科学`

> MH-MoE:Multi-Head Mixture-of-Experts

# 摘要

> 多头专家混合模型（MH-MoE）借助多头机制共同处理来自不同专家的各种表示空间的信息，从而展现出出色的性能。在本文中，我们给出了一种全新的 MH-MoE 实现方案，其浮点运算次数（FLOPs）和参数数量与稀疏专家混合模型相当。针对语言模型的实验结果显示，新的实现方式在质量上优于普通的 MoE 和细粒度的 MoE 模型。另外，我们的实验证明，MH-MoE 与像 BitNet 这样的 1 位大型语言模型（LLMs）兼容。

> Multi-Head Mixture-of-Experts (MH-MoE) demonstrates superior performance by using the multi-head mechanism to collectively attend to information from various representation spaces within different experts. In this paper, we present a novel implementation of MH-MoE that maintains both FLOPs and parameter parity with sparse Mixture of Experts models. Experimental results on language models show that the new implementation yields quality improvements over both vanilla MoE and fine-grained MoE models. Additionally, our experiments demonstrate that MH-MoE is compatible with 1-bit Large Language Models (LLMs) such as BitNet.

[Arxiv](https://arxiv.org/abs/2411.16205)