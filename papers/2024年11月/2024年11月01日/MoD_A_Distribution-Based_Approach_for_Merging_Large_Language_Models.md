# MoD：一种基于分布来合并大型语言模型的方法

发布时间：2024年11月01日

`LLM应用` `语言模型` `数学推理`

> MoD: A Distribution-Based Approach for Merging Large Language Models

# 摘要

> 大型语言模型（LLMs）推动了众多专门化、任务特定的变体的发展。但这些个体模型的维护和部署在资源利用及运营效率方面面临重大挑战。在本研究中，我们提出了	extit{分布混合（MoD）}框架，这是一种合并 LLMs 的新方法，直接作用于其输出概率分布，而非模型权重。和传统的权重平均法不同，MoD 有效保留了个体模型的专长，同时实现了任务间的高效知识共享。通过使用 Qwen2.5 模型在数学推理基准上的大量实验，我们表明 MoD 在多个基准中显著优于现有的模型合并技术。所有代码、数据和实验材料均发布于 https://github.com/knovel-eng/mod 。

> Large language models (LLMs) have enabled the development of numerous specialized, task-specific variants. However, the maintenance and deployment of these individual models present substantial challenges in terms of resource utilization and operational efficiency. In this work, we propose the \textit{Mixture of Distributions (MoD)} framework, a novel approach for merging LLMs that operates directly on their output probability distributions, rather than on model weights. Unlike traditional weight-averaging methods, MoD effectively preserves the specialized capabilities of individual models while enabling efficient knowledge sharing across tasks. Through extensive experimentation on mathematical reasoning benchmarks using Qwen2.5 models, we demonstrate that MoD significantly outperforms existing model merging techniques across multiple benchmarks. All code, data, and experimental materials are published at https://github.com/knovel-eng/mod.

[Arxiv](https://arxiv.org/abs/2411.00406)