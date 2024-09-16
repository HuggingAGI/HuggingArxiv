# AI-LieDar：探索 LLM 代理中效用与真实性之间的平衡

发布时间：2024年09月13日

`Agent` `人工智能`

> AI-LieDar: Examine the Trade-off Between Utility and Truthfulness in LLM Agents

# 摘要

> 为了确保大型语言模型 (LLM) 的安全部署，必须同时兼顾真实性和实用性。然而，这两个目标往往相互冲突（例如，AI 协助销售有缺陷的二手车），部分原因在于用户指令的模糊或误导。为此，我们提出了 AI-LieDar 框架，研究 LLM 如何在多轮互动中应对实用性和真实性的冲突。我们设计了多个现实场景，要求语言代理在与模拟人类的多轮对话中实现与真实性相悖的目标。为评估真实性，我们开发了受心理学启发的真实性检测器。实验显示，所有模型在不到一半的情况下保持真实，且真实性与实用性表现各异。我们还测试了 LLM 对真实性的可引导性，发现即使经过引导，模型仍可能撒谎。这些发现凸显了 LLM 中真实性的复杂性，强调了确保其安全部署的进一步研究的重要性。

> To be safely and successfully deployed, LLMs must simultaneously satisfy truthfulness and utility goals. Yet, often these two goals compete (e.g., an AI agent assisting a used car salesman selling a car with flaws), partly due to ambiguous or misleading user instructions. We propose AI-LieDar, a framework to study how LLM-based agents navigate scenarios with utility-truthfulness conflicts in a multi-turn interactive setting. We design a set of realistic scenarios where language agents are instructed to achieve goals that are in conflict with being truthful during a multi-turn conversation with simulated human agents. To evaluate the truthfulness at large scale, we develop a truthfulness detector inspired by psychological literature to assess the agents' responses. Our experiment demonstrates that all models are truthful less than 50% of the time, although truthfulness and goal achievement (utility) rates vary across models. We further test the steerability of LLMs towards truthfulness, finding that models follow malicious instructions to deceive, and even truth-steered models can still lie. These findings reveal the complex nature of truthfulness in LLMs and underscore the importance of further research to ensure the safe and reliable deployment of LLMs and AI agents.

[Arxiv](https://arxiv.org/abs/2409.09013)