# OrionNav：结合上下文感知 LLM 与开放词汇语义场景图，实现机器人自主在线规划。

发布时间：2024年10月08日

`Agent` `机器人` `自动驾驶`

> OrionNav: Online Planning for Robot Autonomy with Context-Aware LLM and Open-Vocabulary Semantic Scene Graphs

# 摘要

> 让机器人自主应对未知、复杂、动态的环境并执行多样任务，仍是开发强大自主机器人的核心难题。机器人需精准感知环境，并运用世界知识决策。尽管现有方法借助视觉-语言和大型语言模型提升场景理解和规划，但常依赖离线处理、外部计算或环境假设的限制。我们创新提出一个高效、可扩展的实时车载导航框架，整合多层次感知与规划，适用于不断变化的大型未知环境。系统融合多传感器数据，结合开放词汇语义，生成层次场景图。基于LLM的规划器利用这些图制定高级任务策略，引导低级控制器安全达成目标。实时更新场景图和计划，使系统能迅速响应环境变化，实时纠错，超越静态或规则规划系统。我们在四足机器人上验证了系统在大型动态环境中的适应性和鲁棒性。

> Enabling robots to autonomously navigate unknown, complex, dynamic environments and perform diverse tasks remains a fundamental challenge in developing robust autonomous physical agents. They must effectively perceive their surroundings while leveraging world knowledge for decision-making. While recent approaches utilize vision-language and large language models for scene understanding and planning, they often rely on offline processing, external computing, or restrictive environmental assumptions. We present a novel framework for efficient and scalable real-time, onboard autonomous navigation that integrates multi-level abstraction in both perception and planning in unknown large-scale environments that change over time. Our system fuses data from multiple onboard sensors for localization and mapping and integrates it with open-vocabulary semantics to generate hierarchical scene graphs. An LLM-based planner leverages these graphs to generate high-level task execution strategies, which guide low-level controllers in safely accomplishing goals. Our framework's real-time operation enables continuous updates to scene graphs and plans, allowing swift responses to environmental changes and on-the-fly error correction. This is a key advantage over static or rule-based planning systems. We demonstrate our system's efficacy on a quadruped robot navigating large-scale, dynamic environments, showcasing its adaptability and robustness in diverse scenarios.

[Arxiv](https://arxiv.org/abs/2410.06239)