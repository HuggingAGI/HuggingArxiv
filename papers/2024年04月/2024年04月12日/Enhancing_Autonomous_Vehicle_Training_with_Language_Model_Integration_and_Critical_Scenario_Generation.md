# 融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。

发布时间：2024年04月12日

`Agent` `自动驾驶` `机器学习`

> Enhancing Autonomous Vehicle Training with Language Model Integration and Critical Scenario Generation

# 摘要

> 本文提出了 CRITICAL，一个创新的闭环系统，专为自动驾驶车辆（AV）的训练与测试设计。CRITICAL 的特色在于其能够创造出多样化的驾驶情境，特别关注那些针对强化学习（RL）代理中发现的学习与性能缺陷的关键驾驶时刻。该系统通过融合现实交通流动、驾驶行为解析、替代性安全指标，以及一个可选的大规模语言模型（LLM）模块来实现这一点。研究证实，数据生成流程与训练过程之间的闭环反馈机制能够提升训练效率，增强系统性能，并提高安全防护能力。通过近端策略优化（PPO）算法和 HighwayEnv 仿真环境的测试，我们发现结合关键案例生成和 LLM 分析可以显著提升性能，这表明 CRITICAL 在增强 AV 系统鲁棒性、优化关键情境生成以及加速 AV 代理开发和 RL 训练范围扩展方面具有巨大潜力，同时也有助于提高 AV 安全性的验证效率。

> This paper introduces CRITICAL, a novel closed-loop framework for autonomous vehicle (AV) training and testing. CRITICAL stands out for its ability to generate diverse scenarios, focusing on critical driving situations that target specific learning and performance gaps identified in the Reinforcement Learning (RL) agent. The framework achieves this by integrating real-world traffic dynamics, driving behavior analysis, surrogate safety measures, and an optional Large Language Model (LLM) component. It is proven that the establishment of a closed feedback loop between the data generation pipeline and the training process can enhance the learning rate during training, elevate overall system performance, and augment safety resilience. Our evaluations, conducted using the Proximal Policy Optimization (PPO) and the HighwayEnv simulation environment, demonstrate noticeable performance improvements with the integration of critical case generation and LLM analysis, indicating CRITICAL's potential to improve the robustness of AV systems and streamline the generation of critical scenarios. This ultimately serves to hasten the development of AV agents, expand the general scope of RL training, and ameliorate validation efforts for AV safety.

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/Banner.jpg)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/Scenario_Diagram.jpg)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/Architecture.jpg)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/loss_plot.png)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/risk_metrics.png)

[Arxiv](https://arxiv.org/abs/2404.08570)