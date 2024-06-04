# 语言模型嵌入对齐

发布时间：2024年05月24日

`Agent

理由：这篇论文介绍了一种名为EAGLE的代理，它通过强化学习训练，目的是引导大型语言模型（LLMs）生成内容朝向嵌入空间中的最优区域。这个代理的设计和应用是针对特定目标的，即优化LLM的输出以满足预设标准。因此，这篇论文更符合Agent分类，因为它主要关注的是一个用于优化LLM输出的代理系统。` `电影推荐` `内容生成`

> Embedding-Aligned Language Models

# 摘要

> 我们创新性地提出了一种训练大型语言模型（LLMs）遵循嵌入空间内隐含目标的方法。通过强化学习（RL），我们将预训练的LLM视为环境，并训练嵌入对齐引导语言（EAGLE）代理，使其能够引导LLM生成内容朝向嵌入空间中的最优区域，满足预设标准。我们利用MovieLens 25M数据集验证了EAGLE代理的效果，揭示了满足用户潜在需求的内容缺口。此外，我们还展示了通过优化状态依赖动作集设计来提升EAGLE效率的益处。这一研究为LLMs在特定领域知识和数据表示基础上进行受控文本生成奠定了基础。

> We propose a novel approach for training large language models (LLMs) to adhere to objectives defined within a latent embedding space. Our method leverages reinforcement learning (RL), treating a pre-trained LLM as an environment. Our embedding-aligned guided language (EAGLE) agent is trained to iteratively steer the LLM's generation towards optimal regions of the latent embedding space, w.r.t. some predefined criterion. We demonstrate the effectiveness of the EAGLE agent using the MovieLens 25M dataset to surface content gaps that satisfy latent user demand. We also demonstrate the benefit of using an optimal design of a state-dependent action set to improve EAGLE's efficiency. Our work paves the way for controlled and grounded text generation using LLMs, ensuring consistency with domain-specific knowledge and data representations.

[Arxiv](https://arxiv.org/abs/2406.00024)