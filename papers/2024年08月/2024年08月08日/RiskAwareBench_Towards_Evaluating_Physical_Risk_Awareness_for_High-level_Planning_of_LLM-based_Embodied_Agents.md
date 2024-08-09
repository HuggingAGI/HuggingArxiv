# RiskAwareBench：评估基于 LLM 的具身代理在高级规划中的物理风险意识

发布时间：2024年08月08日

`Agent` `机器人技术` `安全标准`

> RiskAwareBench: Towards Evaluating Physical Risk Awareness for High-level Planning of LLM-based Embodied Agents

# 摘要

> 将大型语言模型 (LLM) 融入机器人技术，极大提升了实体代理处理复杂自然语言指令的能力。但现实中无节制地部署这些系统，可能引发财产损失或人身伤害等物理风险。现有安全标准未充分考虑这些风险。为此，我们设计了 RiskAwareBench 框架，通过安全提示、风险场景、计划生成和评估四个模块，自动化评估实体代理的风险意识，减少人工干预。基于此框架，我们创建了 PhysicalRisk 数据集，包含多样化的安全提示和场景。实验显示，多数 LLM 风险意识不足，基本风险缓解措施效果有限，凸显了未来提升风险意识的重要性和紧迫性。

> The integration of large language models (LLMs) into robotics significantly enhances the capabilities of embodied agents in understanding and executing complex natural language instructions. However, the unmitigated deployment of LLM-based embodied systems in real-world environments may pose potential physical risks, such as property damage and personal injury. Existing security benchmarks for LLMs overlook risk awareness for LLM-based embodied agents. To address this gap, we propose RiskAwareBench, an automated framework designed to assess physical risks awareness in LLM-based embodied agents. RiskAwareBench consists of four modules: safety tips generation, risky scene generation, plan generation, and evaluation, enabling comprehensive risk assessment with minimal manual intervention. Utilizing this framework, we compile the PhysicalRisk dataset, encompassing diverse scenarios with associated safety tips, observations, and instructions. Extensive experiments reveal that most LLMs exhibit insufficient physical risk awareness, and baseline risk mitigation strategies yield limited enhancement, which emphasizes the urgency and cruciality of improving risk awareness in LLM-based embodied agents in the future.

[Arxiv](https://arxiv.org/abs/2408.04449)