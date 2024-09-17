# NEUSIS：一个结合神经与符号的框架，专为复杂无人机搜索任务中的自主感知、推理和规划而设计。

发布时间：2024年09月16日

`Agent` `无人机`

> NEUSIS: A Compositional Neuro-Symbolic Framework for Autonomous Perception, Reasoning, and Planning in Complex UAV Search Missions

# 摘要

> 本文探讨了无人机在复杂环境中自主搜索目标的问题。无人机需在有限时间内，根据简短描述，避开危险区域，定位特定目标。为此，我们设计了 NEUSIS，一个结合神经网络与符号逻辑的系统，用于无人机在现实场景中的搜索与导航。NEUSIS 通过神经符号感知、推理与基础模块处理原始数据，构建概率环境模型，并利用分层规划实现高效路径规划。实验表明，NEUSIS 在成功率、搜索效率及 3D 定位上均优于现有最先进模型，展现了其在复杂现实任务中的潜力，为自主无人机搜索提供了新的解决方案。

> This paper addresses the problem of autonomous UAV search missions, where a UAV must locate specific Entities of Interest (EOIs) within a time limit, based on brief descriptions in large, hazard-prone environments with keep-out zones. The UAV must perceive, reason, and make decisions with limited and uncertain information. We propose NEUSIS, a compositional neuro-symbolic system designed for interpretable UAV search and navigation in realistic scenarios. NEUSIS integrates neuro-symbolic visual perception, reasoning, and grounding (GRiD) to process raw sensory inputs, maintains a probabilistic world model for environment representation, and uses a hierarchical planning component (SNaC) for efficient path planning. Experimental results from simulated urban search missions using AirSim and Unreal Engine show that NEUSIS outperforms a state-of-the-art (SOTA) vision-language model and a SOTA search planning model in success rate, search efficiency, and 3D localization. These results demonstrate the effectiveness of our compositional neuro-symbolic approach in handling complex, real-world scenarios, making it a promising solution for autonomous UAV systems in search missions.

[Arxiv](https://arxiv.org/abs/2409.10196)