# 稀疏自编码器揭秘了大型语言模型中的时间差异学习机制。

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Sparse Autoencoders Reveal Temporal Difference Learning in Large Language Models

# 摘要

> In-context learning 是大语言模型 (LLM) 的常见能力，即根据输入提示中的几个示例进行适应。随着 LLM 的这种能力不断增强，从机制上理解它变得尤为重要。特别是，LLM 如何在 in-context 中解决强化学习 (RL) 等特定问题，仍需深入探讨。我们通过三个任务展示了 Llama $3$ $70$B 能解决简单的 RL 问题。接着，我们用 Sparse Autoencoders (SAEs) 分析 Llama 的残差流，发现与时间差 (TD) 误差相关的表示，尽管模型仅被训练来预测下一个 token。通过精心设计的干预，我们验证了这些表示在 TD 误差和 $Q$-values 计算中的因果作用。这项工作为使用 SAEs 研究和操纵 in-context learning 提供了方法，推动了更深入的机制理解。

> In-context learning, the ability to adapt based on a few examples in the input prompt, is a ubiquitous feature of large language models (LLMs). However, as LLMs' in-context learning abilities continue to improve, understanding this phenomenon mechanistically becomes increasingly important. In particular, it is not well-understood how LLMs learn to solve specific classes of problems, such as reinforcement learning (RL) problems, in-context. Through three different tasks, we first show that Llama $3$ $70$B can solve simple RL problems in-context. We then analyze the residual stream of Llama using Sparse Autoencoders (SAEs) and find representations that closely match temporal difference (TD) errors. Notably, these representations emerge despite the model only being trained to predict the next token. We verify that these representations are indeed causally involved in the computation of TD errors and $Q$-values by performing carefully designed interventions on them. Taken together, our work establishes a methodology for studying and manipulating in-context learning with SAEs, paving the way for a more mechanistic understanding.

[Arxiv](https://arxiv.org/abs/2410.01280)