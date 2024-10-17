# 重审基准与评估：为大型语言模型构建基于代理的探索性动态评估框架

发布时间：2024年10月16日

`Agent` `人工智能`

> Revisiting Benchmark and Assessment: An Agent-based Exploratory Dynamic Evaluation Framework for LLMs

# 摘要

> 尽管已有多种垂直领域的大型语言模型 (LLM) 问世，但如何自动评估其在不同领域的表现，以满足现实用户需求，仍是一大难题。现有的基准评估方法僵化且缺乏目的性，依赖于预先收集的静态数据集，这些数据集构建成本高、跨领域不灵活，且与实际用户需求脱节。为此，我们重新审视评估体系，提出两个新概念：**Benchmark+**，将传统 QA 基准扩展为更灵活的“策略-标准”格式；以及 **Assessment+**，增强交互过程，实现更深入的探索，并能从多轮丰富交互中捕捉 LLM 行为的细微差别。我们设计了基于代理的评估框架 *TestAgent*，通过检索增强生成和强化学习实现这两个概念。实验证明，*TestAgent* 在多种场景下均表现出色。这项工作为 LLM 的自动评估提供了新的视角。

> While various vertical domain large language models (LLMs) have been developed, the challenge of automatically evaluating their performance across different domains remains significant. Current benchmark-based evaluation methods exhibit rigid, aimless interactions and rely on pre-collected static datasets that are costly to build, inflexible across domains, and misaligned with practical user needs. To address this issue, we revisit the evaluation components and introduce two concepts: Benchmark+, which extends traditional question-answer benchmark into a more flexible "strategy-criterion" format; and Assessment+, which enhances the interaction process, enabling deeper exploration and supporting both quantitative metrics and qualitative insights. These concepts capture the nuanced behaviors of LLMs through richer, multi-turn interactions. We propose an agent-based evaluation framework called TestAgent, which implements these concepts through retrieval augmented generation and reinforcement learning. Experiments on tasks ranging from constructing vertical domain evaluation to activating existing benchmarks demonstrate the effectiveness of TestAgent across various scenarios. We believe this work offers an interesting perspective on automatic evaluation for LLMs.

[Arxiv](https://arxiv.org/abs/2410.11507)