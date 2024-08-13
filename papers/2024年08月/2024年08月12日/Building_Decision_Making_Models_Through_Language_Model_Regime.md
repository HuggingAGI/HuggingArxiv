# 利用语言模型体系构建决策模型

发布时间：2024年08月12日

`LLM应用` `电子商务` `人工智能`

> Building Decision Making Models Through Language Model Regime

# 摘要

> 我们创新地利用大型语言模型的泛化能力，提出了一种解决决策问题的新方法。与传统方法相比，LLM 在处理多样语言任务时表现出色，启发了我们采用“先学习后使用”（LTU）策略。LTU 分为两个阶段：首先，通过融合多领域知识构建坚实的基础决策模型；接着，针对具体场景进行优化。我们的方法不同于依赖监督学习的传统方式，而是结合了广泛预训练与精准微调。实验证明，在电子商务领域，LTU 在决策与泛化能力上超越了传统方法。作为首个结合 LLM 的单步与多步决策任务的实用架构，LTU 不仅限于游戏和机器人领域，为决策提供了强有力的灵活框架，提升了系统应对挑战的效能与适应性。

> We propose a novel approach for decision making problems leveraging the generalization capabilities of large language models (LLMs). Traditional methods such as expert systems, planning algorithms, and reinforcement learning often exhibit limited generalization, typically requiring the training of new models for each unique task. In contrast, LLMs demonstrate remarkable success in generalizing across varied language tasks, inspiring a new strategy for training decision making models. Our approach, referred to as "Learning then Using" (LTU), entails a two-stage process. Initially, the \textit{learning} phase develops a robust foundational decision making model by integrating diverse knowledge from various domains and decision making contexts. The subsequent \textit{using} phase refines this foundation model for specific decision making scenarios. Distinct from other studies that employ LLMs for decision making through supervised learning, our LTU method embraces a versatile training methodology that combines broad pre-training with targeted fine-tuning. Experiments in e-commerce domains such as advertising and search optimization have shown that LTU approach outperforms traditional supervised learning regimes in decision making capabilities and generalization. The LTU approach is the first practical training architecture for both single-step and multi-step decision making tasks combined with LLMs, which can be applied beyond game and robot domains. It provides a robust and adaptable framework for decision making, enhances the effectiveness and flexibility of various systems in tackling various challenges.

[Arxiv](https://arxiv.org/abs/2408.06087)