# CREAM：一种基于比较的无参考 ELO 排名方法，用于自动评估会议摘要。

发布时间：2024年09月17日

`LLM应用` `自动化` `会议摘要`

> CREAM: Comparison-Based Reference-Free ELO-Ranked Automatic Evaluation for Meeting Summarization

# 摘要

> LLM 推动了自动摘要评估方法的发展，提供了一种比人工评估更快、更经济的替代方案。然而，现有方法在处理长文本摘要和对话式会议摘要等复杂任务时往往力不从心。本文介绍的 CREAM 框架，通过结合链式思维推理和关键事实对齐，无需参考即可评估摘要的简洁性和完整性。借助 ELO 排名系统，CREAM 为比较不同模型或提示配置的质量提供了坚实基础。

> Large Language Models (LLMs) have spurred interest in automatic evaluation methods for summarization, offering a faster, more cost-effective alternative to human evaluation. However, existing methods often fall short when applied to complex tasks like long-context summarizations and dialogue-based meeting summarizations. In this paper, we introduce CREAM (Comparison-Based Reference-Free Elo-Ranked Automatic Evaluation for Meeting Summarization), a novel framework that addresses the unique challenges of evaluating meeting summaries. CREAM leverages a combination of chain-of-thought reasoning and key facts alignment to assess conciseness and completeness of model-generated summaries without requiring reference. By employing an ELO ranking system, our approach provides a robust mechanism for comparing the quality of different models or prompt configurations.

[Arxiv](https://arxiv.org/abs/2409.10883)