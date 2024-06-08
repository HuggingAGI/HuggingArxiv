# 大型语言模型微调优化研究

发布时间：2024年06月04日

`LLM应用

这篇论文主要关注大型语言模型（LLM）的微调优化策略，特别是在资源受限的环境下如何有效地进行微调。论文探讨了多种优化技术，如梯度检查点和低秩适应，并评估了这些技术对GPU内存和微调时间的影响。这些内容直接关联到LLM在特定应用中的实际部署和优化，因此属于LLM应用分类。` `机器学习`

> A Study of Optimizations for Fine-tuning Large Language Models

# 摘要

> 微调大型语言模型是适应特定应用的热门选择，但这一过程复杂且对内存要求极高。本文深入探讨了多种微调优化策略，并评估了梯度检查点、低秩适应等技术。我们特别关注了这些优化如何影响GPU内存和微调时间，并提供了针对不同模型大小的最佳优化建议。此外，我们还探讨了如何在资源受限的情况下，有效微调拥有庞大参数量的模型，并支持更长的上下文长度。

> Fine-tuning large language models is a popular choice among users trying to adapt them for specific applications. However, fine-tuning these models is a demanding task because the user has to examine several factors, such as resource budget, runtime, model size and context length among others. A specific challenge is that fine-tuning is memory intensive, imposing constraints on the required hardware memory and context length of training data that can be handled. In this work, we share a detailed study on a variety of fine-tuning optimizations across different fine-tuning scenarios. In particular, we assess Gradient Checkpointing, Low Rank Adaptation, DeepSpeed's ZeRO Redundancy Optimizer and Flash Attention. With a focus on memory and runtime, we examine the impact of different optimization combinations on GPU memory usage and execution runtime during fine-tuning phase. We provide recommendation on best default optimization for balancing memory and runtime across diverse model sizes. We share effective strategies for fine-tuning very large models with tens or hundreds of billions of parameters and enabling large context lengths during fine-tuning. Furthermore, we propose the appropriate optimization mixtures for fine-tuning under GPU resource limitations.

![大型语言模型微调优化研究](../../../paper_images/2406.02290/model_states_memory_diagram.png)

![大型语言模型微调优化研究](../../../paper_images/2406.02290/best_defaults.png)

![大型语言模型微调优化研究](../../../paper_images/2406.02290/long_context_a100_v100_comp.png)

![大型语言模型微调优化研究](../../../paper_images/2406.02290/optimization_combinations.png)

[Arxiv](https://arxiv.org/abs/2406.02290)