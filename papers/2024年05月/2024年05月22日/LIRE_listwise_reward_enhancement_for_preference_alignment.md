# LIRE：通过列表级奖励增强优化偏好对齐

发布时间：2024年05月22日

`RAG

理由：这篇论文主要介绍了一种新的方法——列表级奖励增强偏好对齐（LIRE），用于优化大型语言模型（LLMs）与人类价值观的对齐。这种方法通过整合多个响应的离线奖励来简化对齐过程，无需在线采样，且适用于多响应场景。这与RAG（Retrieval-Augmented Generation）的概念相符，即通过增强检索机制来改进生成模型的性能。LIRE方法的提出和实验验证表明其在多个任务上超越现有方法，这属于RAG领域的应用和改进。` `对话系统` `内容过滤`

> LIRE: listwise reward enhancement for preference alignment

# 摘要

> 为了减少有害内容，近期在使大型语言模型（LLMs）与人类价值观对齐方面取得了显著进展。采用人类反馈强化学习（RLHF）已被证实有效，但实施复杂，且对超参数敏感，难以保证稳定性和可扩展性。当前偏好对齐方法多依赖成对比较，对多响应情况探索不足，忽略了候选集的丰富潜力。为此，我们提出列表级奖励增强偏好对齐（LIRE），一种基于梯度的奖励优化方法，它将多个响应的离线奖励整合进一个简化的列表级框架，无需在线采样。LIRE易于实施，几乎无需调整参数，既能与成对范式兼容，也自然适用于多响应场景。我们还开发了一种自我增强算法，用于训练中迭代优化奖励。实验证明，LIRE在多个对话和摘要任务基准上超越现有方法，且在跨分布数据上表现出色，通过代理奖励模型和人工评估验证。

> Recently, tremendous strides have been made to align the generation of Large Language Models (LLMs) with human values to mitigate toxic or unhelpful content. Leveraging Reinforcement Learning from Human Feedback (RLHF) proves effective and is widely adopted by researchers. However, implementing RLHF is complex, and its sensitivity to hyperparameters renders achieving stable performance and scalability challenging. Furthermore, prevailing approaches to preference alignment primarily concentrate on pairwise comparisons, with limited exploration into multi-response scenarios, thereby overlooking the potential richness within the candidate pool. For the above reasons, we propose a new approach: Listwise Reward Enhancement for Preference Alignment (LIRE), a gradient-based reward optimization approach that incorporates the offline rewards of multiple responses into a streamlined listwise framework, thus eliminating the need for online sampling during training. LIRE is straightforward to implement, requiring minimal parameter tuning, and seamlessly aligns with the pairwise paradigm while naturally extending to multi-response scenarios. Moreover, we introduce a self-enhancement algorithm aimed at iteratively refining the reward during training. Our experiments demonstrate that LIRE consistently outperforms existing methods across several benchmarks on dialogue and summarization tasks, with good transferability to out-of-distribution data, assessed using proxy reward models and human annotators.

[Arxiv](https://arxiv.org/abs/2405.13516)