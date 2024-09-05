# Cog-GA：一款基于大型语言模型的生成代理，专为连续环境中的视觉-语言导航设计

发布时间：2024年09月04日

`Agent` `人工智能` `虚拟现实`

> Cog-GA: A Large Language Models-based Generative Agent for Vision-Language Navigation in Continuous Environments

# 摘要

> 连续环境中的视觉语言导航（VLN-CE）是具身AI的前沿领域，要求代理仅凭自然语言指令在无界3D空间中自由导航。这项任务在多模态理解、空间推理和决策制定方面提出了独特挑战。为此，我们推出了Cog-GA，一个基于大型语言模型的生成代理，专为VLN-CE任务设计。Cog-GA通过双策略模拟人类认知过程：首先，构建整合时间、空间和语义的认知地图，促进空间记忆发展；其次，运用预测机制选择路径点，优化探索轨迹以提高导航效率。每个路径点都附带双通道场景描述，区分环境线索为“什么”和“哪里”，增强注意力集中，便于识别导航相关信息。此外，反思机制通过捕捉过往导航反馈，支持持续学习和适应性规划。在VLN-CE基准测试中，Cog-GA展现了卓越性能和模拟人类导航行为的能力，对开发战略性和可解释的VLN-CE代理具有重要贡献。

> Vision Language Navigation in Continuous Environments (VLN-CE) represents a frontier in embodied AI, demanding agents to navigate freely in unbounded 3D spaces solely guided by natural language instructions. This task introduces distinct challenges in multimodal comprehension, spatial reasoning, and decision-making. To address these challenges, we introduce Cog-GA, a generative agent founded on large language models (LLMs) tailored for VLN-CE tasks. Cog-GA employs a dual-pronged strategy to emulate human-like cognitive processes. Firstly, it constructs a cognitive map, integrating temporal, spatial, and semantic elements, thereby facilitating the development of spatial memory within LLMs. Secondly, Cog-GA employs a predictive mechanism for waypoints, strategically optimizing the exploration trajectory to maximize navigational efficiency. Each waypoint is accompanied by a dual-channel scene description, categorizing environmental cues into 'what' and 'where' streams as the brain. This segregation enhances the agent's attentional focus, enabling it to discern pertinent spatial information for navigation. A reflective mechanism complements these strategies by capturing feedback from prior navigation experiences, facilitating continual learning and adaptive replanning. Extensive evaluations conducted on VLN-CE benchmarks validate Cog-GA's state-of-the-art performance and ability to simulate human-like navigation behaviors. This research significantly contributes to the development of strategic and interpretable VLN-CE agents.

[Arxiv](https://arxiv.org/abs/2409.02522)