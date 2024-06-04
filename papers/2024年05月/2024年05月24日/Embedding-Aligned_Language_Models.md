# 语言模型嵌入对齐

发布时间：2024年05月24日

`Agent

理由：这篇论文介绍了一种名为EAGLE的代理，它通过强化学习训练大型语言模型（LLMs），以遵循嵌入空间内的隐含目标。这种方法涉及代理引导LLM生成内容，使其趋向于嵌入空间中的最优区域，符合预设标准。这与Agent分类相关，因为它涉及使用代理来控制和优化LLM的行为。此外，论文中提到的使用MovieLens 25M数据集来验证代理的有效性，以及优化状态依赖动作集设计，都强调了代理在特定领域知识和数据表示下的作用，这与Agent分类的定义相符。` `电影推荐` `用户需求分析`

> Embedding-Aligned Language Models

# 摘要

> 我们提出了一种创新方法，通过强化学习训练大型语言模型（LLMs），使其遵循嵌入空间内的隐含目标。我们的EAGLE代理能够引导LLM生成内容，使其趋向于嵌入空间中的最优区域，符合预设标准。通过MovieLens 25M数据集，我们验证了EAGLE代理在揭示潜在用户需求方面的有效性，并展示了优化状态依赖动作集设计对提升EAGLE效率的益处。此研究为LLMs在特定领域知识和数据表示下的受控文本生成奠定了基础，确保了内容与领域知识的一致性。

> We propose a novel approach for training large language models (LLMs) to adhere to objectives defined within a latent embedding space. Our method leverages reinforcement learning (RL), treating a pre-trained LLM as an environment. Our embedding-aligned guided language (EAGLE) agent is trained to iteratively steer the LLM's generation towards optimal regions of the latent embedding space, w.r.t. some predefined criterion. We demonstrate the effectiveness of the EAGLE agent using the MovieLens 25M dataset to surface content gaps that satisfy latent user demand. We also demonstrate the benefit of using an optimal design of a state-dependent action set to improve EAGLE's efficiency. Our work paves the way for controlled and grounded text generation using LLMs, ensuring consistency with domain-specific knowledge and data representations.

[Arxiv](https://arxiv.org/abs/2406.00024)