# 基于大型语言模型的 COLREGs 决策及自主水面车辆的控制

发布时间：2024年11月25日

`LLM应用` `自动驾驶`

> Large Language Model-based Decision-making for COLREGs and the Control of Autonomous Surface Vehicles

# 摘要

> 在自主水面车辆（ASVs）领域，为解决主要面向人类操作员所定义的海上 COLREGs（碰撞规则）的决策与避障难题，一直是当务之急。解释性人工智能（AI）和机器学习的新进展，在达成类人决策方面展现出良好前景。尤为突出的是，大型语言模型（LLMs）在诸如自动驾驶汽车等复杂系统的决策应用中已获重大突破。不过，COLREGs 在文本表述及一定程度的模糊性（从算法视角）所带来的挑战，恰好与 LLMs 的能力相适配，这意味着 LLMs 或许很快就会更适用于此类应用。本文提出并演示了基于 LLM 的 ASVs 决策与控制的首次应用。所提方法构建了一个高级决策者，其借助在线碰撞风险指数和关键测量值来做出安全操控的决策。还开发了定制的设计和运行时结构，以支持在实际的 ASV 模型上进行训练和实时动作生成。同时集成了本地规划和控制算法，用于在较低层级执行航点跟踪和避障的指令。据作者所知，此项研究是首次将可解释的 AI 应用于遵循 COLREGs 规则的海事系统动态控制问题，为这一充满挑战的领域开辟了新的研究方向。在多个测试场景中取得的结果表明，该系统能够保持在线 COLREGs 合规、精准的航点跟踪和可行的控制，并且为每个决策提供了人类可理解的推理。

> In the field of autonomous surface vehicles (ASVs), devising decision-making and obstacle avoidance solutions that address maritime COLREGs (Collision Regulations), primarily defined for human operators, has long been a pressing challenge. Recent advancements in explainable Artificial Intelligence (AI) and machine learning have shown promise in enabling human-like decision-making. Notably, significant developments have occurred in the application of Large Language Models (LLMs) to the decision-making of complex systems, such as self-driving cars. The textual and somewhat ambiguous nature of COLREGs (from an algorithmic perspective), however, poses challenges that align well with the capabilities of LLMs, suggesting that LLMs may become increasingly suitable for this application soon. This paper presents and demonstrates the first application of LLM-based decision-making and control for ASVs. The proposed method establishes a high-level decision-maker that uses online collision risk indices and key measurements to make decisions for safe manoeuvres. A tailored design and runtime structure is developed to support training and real-time action generation on a realistic ASV model. Local planning and control algorithms are integrated to execute the commands for waypoint following and collision avoidance at a lower level. To the authors' knowledge, this study represents the first attempt to apply explainable AI to the dynamic control problem of maritime systems recognising the COLREGs rules, opening new avenues for research in this challenging area. Results obtained across multiple test scenarios demonstrate the system's ability to maintain online COLREGs compliance, accurate waypoint tracking, and feasible control, while providing human-interpretable reasoning for each decision.

[Arxiv](https://arxiv.org/abs/2411.16587)