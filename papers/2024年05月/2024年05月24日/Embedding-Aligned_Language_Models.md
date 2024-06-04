# 语言模型与嵌入精准对齐

发布时间：2024年05月24日

`Agent

这篇论文介绍了一种名为EAGLE的代理，它通过强化学习在嵌入空间中定义目标，训练大型语言模型（LLMs）。EAGLE代理被设计来引导LLM生成朝向嵌入空间中的最优区域，遵循预设标准。这种方法特别强调了在特定领域内进行受控且基于知识的文本生成，确保与领域知识和数据表示的一致性。因此，这篇论文属于Agent分类，因为它主要讨论了一个特定的代理系统如何影响和优化LLM的行为。` `电影推荐` `用户需求分析`

> Embedding-Aligned Language Models

# 摘要

> 我们创新性地提出了一种方法，通过强化学习在嵌入空间中定义目标，训练大型语言模型（LLMs）。我们的EAGLE代理，一种嵌入对齐引导语言代理，被训练来引导LLM生成朝向嵌入空间中的最优区域，遵循预设标准。通过MovieLens 25M数据集，我们验证了EAGLE代理揭示潜在用户需求内容缺口的能力，并展示了优化状态依赖动作集设计对提升EAGLE效率的益处。此研究为LLMs在特定领域内进行受控且基于知识的文本生成奠定了基础，确保了与领域知识和数据表示的一致性。

> We propose a novel approach for training large language models (LLMs) to adhere to objectives defined within a latent embedding space. Our method leverages reinforcement learning (RL), treating a pre-trained LLM as an environment. Our embedding-aligned guided language (EAGLE) agent is trained to iteratively steer the LLM's generation towards optimal regions of the latent embedding space, w.r.t. some predefined criterion. We demonstrate the effectiveness of the EAGLE agent using the MovieLens 25M dataset to surface content gaps that satisfy latent user demand. We also demonstrate the benefit of using an optimal design of a state-dependent action set to improve EAGLE's efficiency. Our work paves the way for controlled and grounded text generation using LLMs, ensuring consistency with domain-specific knowledge and data representations.

[Arxiv](https://arxiv.org/abs/2406.00024)