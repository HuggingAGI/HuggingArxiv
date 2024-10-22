# 在金融情感分析中，将大型语言模型（LLM）与人类指令及股市反馈相结合。

发布时间：2024年10月18日

`RAG`

> Aligning LLMs with Human Instructions and Stock Market Feedback in Financial Sentiment Analysis

# 摘要

> 金融情感分析在交易和投资决策中至关重要。本研究提出了一种自适应检索增强框架，通过指令调优与人类指令对齐，并结合市场反馈，动态调整 RAG 模块内各知识源的权重。基于 LLaMA 2 等基础模型，我们对 7B 到 70B 大小的 LLM 进行了微调，并进一步通过直接反馈和 RL 方法优化了 RAG 的源权重。实验表明，我们的 LLM 在情感分析上比现有最先进模型和对话 AI 系统准确率提高了 1% 到 6%，且更能准确预测股价走势。此外，在牛市中，我们的投资组合夏普比率比 S&P 500 基准高出 3.61%，在熊市中回报损失减少了 5 倍。

> Financial sentiment analysis is crucial for trading and investment decision-making. This study introduces an adaptive retrieval augmented framework for Large Language Models (LLMs) that aligns with human instructions through Instruction Tuning and incorporates market feedback to dynamically adjust weights across various knowledge sources within the Retrieval-Augmented Generation (RAG) module. Building upon foundational models like LLaMA 2, we fine-tune a series of LLMs ranging from 7B to 70B in size, enriched with Instruction Tuning and RAG, and further optimized through direct feedback and Reinforcement Learning (RL)-based refinement methods applied to the source weights of RAG.Through extensive evaluation, we demonstrate that the sentiment outputs from our LLMs more accurately mirror the intrinsic sentiment of textual data, showcasing a 1% to 6% boost in accuracy and F1 score over existing state-of-the-art models and leading conversational AI systems. Moreover, the sentiments extracted are more indicative of the directions in stock price movements. On top of that, we successfully construct portfolios that yield a 3.61% higher Sharpe ratio compared to the S&P 500 baseline in bullish markets. These portfolios also demonstrate resilience in bearish markets, with a 5x reduction in return losses compared to those typically experienced by the S&P 500.

[Arxiv](https://arxiv.org/abs/2410.14926)