# SEED：利用计划推测解码技术，加速推理树的构建过程

发布时间：2024年06月26日

`LLM理论

这篇论文主要探讨了大型语言模型在复杂推理与规划方面的不足，并提出了一种名为SeeD的新型推理机制。该机制通过计划性推测执行和轮次调度策略来优化推理过程的效率和GPU内存使用。因此，这篇论文更偏向于对大型语言模型理论层面的研究和改进，而不是具体的应用案例或Agent的设计，也不是关于RAG（Retrieval-Augmented Generation）的研究。所以，将其归类为LLM理论是合适的。` `人工智能` `推理系统`

> SEED: Accelerating Reasoning Tree Construction via Scheduled Speculative Decoding

# 摘要

> 大型语言模型虽在多任务中表现出色，但在复杂推理与规划上仍显不足。基于树搜索的推理方法超越了传统的思维链提示，鼓励深入探索推理的中间步骤，但这也带来了显著的推理延迟。为此，本文提出了SeeD框架，一种创新的推理机制，旨在提升运行效率并优化GPU内存使用。SeeD通过计划性推测执行，高效管理思维生成与状态评估的迭代过程，并采用轮次调度策略精准分发草稿模型。实验结果表明，SeeD在三个推理数据集上均实现了显著加速，为无训练推测解码中的批量推理开辟了新路径。

> Large Language Models (LLMs) demonstrate remarkable emergent abilities across various tasks, yet fall short of complex reasoning and planning tasks. The tree-search-based reasoning methods address this by surpassing the capabilities of chain-of-thought prompting, encouraging exploration of intermediate steps. However, such methods introduce significant inference latency due to the systematic exploration and evaluation of multiple thought paths. This paper introduces SeeD, a novel and efficient inference framework to optimize runtime speed and GPU memory management concurrently. By employing a scheduled speculative execution, SeeD efficiently handles multiple iterations for the thought generation and the state evaluation, leveraging a rounds-scheduled strategy to manage draft model dispatching. Extensive experimental evaluations on three reasoning datasets demonstrate superior speedup performance of SeeD, providing a viable path for batched inference in training-free speculative decoding.

[Arxiv](https://arxiv.org/abs/2406.18200)