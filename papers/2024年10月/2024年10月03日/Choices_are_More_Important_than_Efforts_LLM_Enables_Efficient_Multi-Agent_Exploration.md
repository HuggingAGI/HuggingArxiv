# 选择胜于努力：LLM 助力高效多智能体探索

发布时间：2024年10月03日

`Agent` `人工智能`

> Choices are More Important than Efforts: LLM Enables Efficient Multi-Agent Exploration

# 摘要

> 在广阔的状态-动作空间中，高效的多智能体探索一直是强化学习的难题。尽管新颖性、多样性和不确定性备受关注，但缺乏指导的探索往往导致冗余努力。本文提出的LEMAE方法，通过从大型语言模型（LLM）中提取任务相关指导，实现了高效的多智能体探索。我们以低成本将LLM的语言知识转化为关键状态，并设计了SHIR奖励机制和KSMT记忆树，以引导智能体朝向关键状态。实验证明，LEMAE在SMAC和MPE等基准测试中显著优于现有方法，某些场景下加速达10倍。

> With expansive state-action spaces, efficient multi-agent exploration remains a longstanding challenge in reinforcement learning. Although pursuing novelty, diversity, or uncertainty attracts increasing attention, redundant efforts brought by exploration without proper guidance choices poses a practical issue for the community. This paper introduces a systematic approach, termed LEMAE, choosing to channel informative task-relevant guidance from a knowledgeable Large Language Model (LLM) for Efficient Multi-Agent Exploration. Specifically, we ground linguistic knowledge from LLM into symbolic key states, that are critical for task fulfillment, in a discriminative manner at low LLM inference costs. To unleash the power of key states, we design Subspace-based Hindsight Intrinsic Reward (SHIR) to guide agents toward key states by increasing reward density. Additionally, we build the Key State Memory Tree (KSMT) to track transitions between key states in a specific task for organized exploration. Benefiting from diminishing redundant explorations, LEMAE outperforms existing SOTA approaches on the challenging benchmarks (e.g., SMAC and MPE) by a large margin, achieving a 10x acceleration in certain scenarios.

[Arxiv](https://arxiv.org/abs/2410.02511)