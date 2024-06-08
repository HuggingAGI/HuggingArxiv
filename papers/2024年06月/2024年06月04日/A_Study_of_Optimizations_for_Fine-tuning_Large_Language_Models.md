# 探究大型语言模型微调优化之道

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要关注大型语言模型（LLM）的微调优化策略，包括梯度检查点、低秩适应等技术，并评估了这些策略对GPU内存和运行时间的影响。这些内容属于对LLM理论和技术的深入探讨，特别是关于模型优化和资源管理的部分，因此更适合归类于LLM理论。虽然微调技术可以应用于实际场景，但论文的重点在于理论和方法的探讨，而非具体的应用案例。` `机器学习`

> A Study of Optimizations for Fine-tuning Large Language Models

# 摘要

> 微调大型语言模型是适应特定应用的热门选择，但这一过程复杂且对内存要求高。本研究深入探讨了多种微调优化策略，包括梯度检查点、低秩适应等，并评估了它们对GPU内存和运行时间的影响。我们为不同模型大小提供了平衡内存与运行时间的最佳实践，并探讨了如何有效微调巨型模型，以及在资源受限时如何选择合适的优化组合。

> Fine-tuning large language models is a popular choice among users trying to adapt them for specific applications. However, fine-tuning these models is a demanding task because the user has to examine several factors, such as resource budget, runtime, model size and context length among others. A specific challenge is that fine-tuning is memory intensive, imposing constraints on the required hardware memory and context length of training data that can be handled. In this work, we share a detailed study on a variety of fine-tuning optimizations across different fine-tuning scenarios. In particular, we assess Gradient Checkpointing, Low Rank Adaptation, DeepSpeed's ZeRO Redundancy Optimizer and Flash Attention. With a focus on memory and runtime, we examine the impact of different optimization combinations on GPU memory usage and execution runtime during fine-tuning phase. We provide recommendation on best default optimization for balancing memory and runtime across diverse model sizes. We share effective strategies for fine-tuning very large models with tens or hundreds of billions of parameters and enabling large context lengths during fine-tuning. Furthermore, we propose the appropriate optimization mixtures for fine-tuning under GPU resource limitations.

![探究大型语言模型微调优化之道](../../../paper_images/2406.02290/model_states_memory_diagram.png)

![探究大型语言模型微调优化之道](../../../paper_images/2406.02290/best_defaults.png)

![探究大型语言模型微调优化之道](../../../paper_images/2406.02290/long_context_a100_v100_comp.png)

![探究大型语言模型微调优化之道](../../../paper_images/2406.02290/optimization_combinations.png)

[Arxiv](https://arxiv.org/abs/2406.02290)