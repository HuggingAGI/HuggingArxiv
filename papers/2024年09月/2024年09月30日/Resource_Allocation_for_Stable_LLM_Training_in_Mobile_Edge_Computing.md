# 移动边缘计算中稳定 LLM 训练的资源分配策略

发布时间：2024年09月30日

`LLM应用` `移动计算` `边缘计算`

> Resource Allocation for Stable LLM Training in Mobile Edge Computing

# 摘要

> 随着移动设备在高级应用中的地位日益重要，边缘计算为解决其计算限制提供了有效途径，尤其是在部署大型语言模型（LLM）时。然而，尽管边缘计算有所进步，但高效训练和部署 LLM 仍面临计算需求和数据隐私的挑战。本文提出一种协作训练框架，整合移动用户与边缘服务器，优化资源分配，提升性能与效率。我们采用参数高效微调（PEFT）方法，让移动用户调整 LLM 的初始层，而边缘服务器处理复杂的后层。通过多目标优化，我们旨在最小化训练中的能量消耗与延迟，并通过稳定性增强解决模型性能不稳定的问题。利用创新的分数规划技术，我们找到了问题的平稳点。仿真显示，该方法不仅降低了能量消耗和延迟，还提高了 LLM 在不同移动环境中的可靠性。

> As mobile devices increasingly become focal points for advanced applications, edge computing presents a viable solution to their inherent computational limitations, particularly in deploying large language models (LLMs). However, despite the advancements in edge computing, significant challenges remain in efficient training and deploying LLMs due to the computational demands and data privacy concerns associated with these models. This paper explores a collaborative training framework that integrates mobile users with edge servers to optimize resource allocation, thereby enhancing both performance and efficiency. Our approach leverages parameter-efficient fine-tuning (PEFT) methods, allowing mobile users to adjust the initial layers of the LLM while edge servers handle the more demanding latter layers. Specifically, we formulate a multi-objective optimization problem to minimize the total energy consumption and delay during training. We also address the common issue of instability in model performance by incorporating stability enhancements into our objective function. Through novel fractional programming technique, we achieve a stationary point for the formulated problem. Simulations demonstrate that our method reduces the energy consumption as well as the latency, and increases the reliability of LLMs across various mobile settings.

[Arxiv](https://arxiv.org/abs/2409.20247)