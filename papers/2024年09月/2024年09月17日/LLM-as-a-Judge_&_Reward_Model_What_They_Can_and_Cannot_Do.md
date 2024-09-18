# LLM 作为评判者与奖励模型：它们的能与不能

发布时间：2024年09月17日

`LLM应用` `人工智能` `语言评估`

> LLM-as-a-Judge & Reward Model: What They Can and Cannot Do

# 摘要

> LLM-as-a-Judge 和奖励模型在 LLM 评估中广泛替代了多选题和人工注释，尤其在长篇回复评估中表现出色，是排行榜评估和强化学习对齐 LLM 的关键工具。然而，它们在非英语环境中的有效性仍未被充分探索。本文全面分析了自动化评估器在非英语环境中的表现，发现英语评估能力对特定语言能力的影响甚至超过语言本身，使英语训练的评估器能轻松适应其他语言。同时，我们也揭示了 LLM 在检测和惩罚事实错误、文化误解和不恰当语言方面的不足。最后，我们推出了首个非英语元评估数据集 Kudge，包含 5,012 个韩语人工注释。

> LLM-as-a-Judge and reward models are widely used alternatives of multiple-choice questions or human annotators for large language model (LLM) evaluation. Their efficacy shines in evaluating long-form responses, serving a critical role as evaluators of leaderboards and as proxies to align LLMs via reinforcement learning. However, despite their popularity, their effectiveness outside of English remains largely unexplored. In this paper, we conduct a comprehensive analysis on automated evaluators, reporting key findings on their behavior in a non-English environment. First, we discover that English evaluation capabilities significantly influence language-specific capabilities, often more than the language proficiency itself, enabling evaluators trained in English to easily transfer their skills to other languages. Second, we identify critical shortcomings, where LLMs fail to detect and penalize errors, such as factual inaccuracies, cultural misrepresentations, and the presence of unwanted language. Finally, we release Kudge, the first non-English meta-evaluation dataset containing 5,012 human annotations in Korean.

[Arxiv](https://arxiv.org/abs/2409.11239)