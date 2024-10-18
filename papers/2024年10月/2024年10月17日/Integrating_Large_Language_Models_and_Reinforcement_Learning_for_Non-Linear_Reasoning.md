# 融合大型语言模型与强化学习，探索非线性推理的新路径

发布时间：2024年10月17日

`Agent` `人工智能` `软件工程`

> Integrating Large Language Models and Reinforcement Learning for Non-Linear Reasoning

# 摘要

> 大型语言模型 (LLM) 在长期规划上表现不佳，原因可能是它们探索解决方案空间的方式有限。我们提出了一种架构，通过强化学习 (RL) 代理引导 LLM 的探索：(1) 代理利用特定领域信息，根据未被 LLM 训练目标明确考虑的特定指标，评估候选解决方案的质量；(2) LLM 专注于生成下一步，无需长期规划。我们通过探索替代路径和回溯实现非线性推理。在程序等价任务上，我们的方法与思维链 (CoT) 和思维树 (ToT) 相比表现优异，不仅在下游任务（二元分类）上，也在中间推理步骤上。

> Large Language Models (LLMs) were shown to struggle with long-term planning, which may be caused by the limited way in which they explore the space of possible solutions. We propose an architecture where a Reinforcement Learning (RL) Agent guides an LLM's space exploration: (1) the Agent has access to domain-specific information, and can therefore make decisions about the quality of candidate solutions based on specific and relevant metrics, which were not explicitly considered by the LLM's training objective; (2) the LLM can focus on generating immediate next steps, without the need for long-term planning. We allow non-linear reasoning by exploring alternative paths and backtracking. We evaluate this architecture on the program equivalence task, and compare it against Chain of Thought (CoT) and Tree of Thoughts (ToT). We assess both the downstream task, denoting the binary classification, and the intermediate reasoning steps. Our approach compares positively against CoT and ToT.

[Arxiv](https://arxiv.org/abs/2410.13501)