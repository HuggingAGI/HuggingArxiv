# [Proxy-RLHF 是一种创新方法，它在大型语言模型中巧妙地运用“代理”手段，成功实现了生成能力与对齐目标的解耦合，尤其适用于提升语言模型在保持高质量文本生成的同时，更好地满足预设规范和要求。](https://arxiv.org/abs/2403.04283)

发布时间：2024年03月07日

`Agent`

> Proxy-RLHF: Decoupling Generation and Alignment in Large Language Model with Proxy

> 当前流行的RLHF技术致力于让大型语言模型（LLMs）遵循人类价值观，但其所需的计算资源较高，原因之一在于RLHF要求LLM同时完成生成内容及价值观对齐两个任务。本文提出了一项创新方案——Proxy-RLHF，它巧妙地分离了LLM的生成和对齐过程，实现了在显著降低计算成本的前提下确保与人类价值观的一致性。我们从构建一种专为对齐任务设计的新颖马尔可夫决策过程（MDP）出发，通过强化学习（RL）训练一个轻量级代理模型，该模型监控LLM的令牌生成而不对其原有结构进行任何改动。实验结果显示，采用我们方法只需消耗其他方法约1%的训练参数量，即可达到相似程度的价值观对齐效果。

> Reinforcement Learning from Human Feedback (RLHF) is the prevailing approach to ensure Large Language Models (LLMs) align with human values. However, existing RLHF methods require a high computational cost, one main reason being that RLHF assigns both the generation and alignment tasks to the LLM simultaneously. In this paper, we introduce Proxy-RLHF, which decouples the generation and alignment processes of LLMs, achieving alignment with human values at a much lower computational cost. We start with a novel Markov Decision Process (MDP) designed for the alignment process and employ Reinforcement Learning (RL) to train a streamlined proxy model that oversees the token generation of the LLM, without altering the LLM itself. Experiments show that our method achieves a comparable level of alignment with only 1\% of the training parameters of other methods.

[Arxiv](https://arxiv.org/abs/2403.04283)