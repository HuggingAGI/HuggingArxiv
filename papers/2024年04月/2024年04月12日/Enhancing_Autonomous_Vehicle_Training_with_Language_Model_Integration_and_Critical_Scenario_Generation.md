# 融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。

发布时间：2024年04月12日

`分类：Agent

这篇论文描述了一个名为 CRITICAL 的闭环系统，它专为自动驾驶汽车（AV）的训练与测试而设计。系统通过创造多样化的驾驶情境，特别是针对强化学习（RL）智能体中发现的学习与性能缺陷的关键驾驶时刻，来提高训练效率、增强系统性能和提高安全防护能力。这表明该系统是一个智能体，能够自主地进行决策和学习，因此将其归类为Agent。` `自动驾驶`

> Enhancing Autonomous Vehicle Training with Language Model Integration and Critical Scenario Generation

# 摘要

> 本文提出了 CRITICAL，一个创新的闭环系统，专为自动驾驶汽车（AV）的训练与测试设计。CRITICAL 的特色在于其能够创造多样化的驾驶情境，特别关注那些针对强化学习（RL）智能体中发现的学习与性能缺陷的关键驾驶时刻。该系统通过融合现实交通流动、驾驶行为分析、替代性安全措施，以及一个可选的大型语言模型（LLM）组件来实现这一目标。研究证实，数据生成流程与训练过程之间的闭环反馈机制能够提升训练效率，增强系统性能，并提高安全防护能力。通过近端策略优化（PPO）算法和 HighwayEnv 仿真环境的测试，我们发现，结合关键案例生成和 LLM 分析的整合显著提升了性能，这表明 CRITICAL 在增强 AV 系统的稳健性、简化关键情境生成方面具有巨大潜力。这不仅加速了 AV 智能体的发展，也拓宽了 RL 训练的应用范围，并提升了 AV 安全性的验证效率。

> This paper introduces CRITICAL, a novel closed-loop framework for autonomous vehicle (AV) training and testing. CRITICAL stands out for its ability to generate diverse scenarios, focusing on critical driving situations that target specific learning and performance gaps identified in the Reinforcement Learning (RL) agent. The framework achieves this by integrating real-world traffic dynamics, driving behavior analysis, surrogate safety measures, and an optional Large Language Model (LLM) component. It is proven that the establishment of a closed feedback loop between the data generation pipeline and the training process can enhance the learning rate during training, elevate overall system performance, and augment safety resilience. Our evaluations, conducted using the Proximal Policy Optimization (PPO) and the HighwayEnv simulation environment, demonstrate noticeable performance improvements with the integration of critical case generation and LLM analysis, indicating CRITICAL's potential to improve the robustness of AV systems and streamline the generation of critical scenarios. This ultimately serves to hasten the development of AV agents, expand the general scope of RL training, and ameliorate validation efforts for AV safety.

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/Banner.jpg)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/Scenario_Diagram.jpg)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/Architecture.jpg)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/loss_plot.png)

![融入语言模型并生成关键场景，提升自动驾驶车辆的训练效果。](../../../paper_images/2404.08570/risk_metrics.png)

[Arxiv](https://arxiv.org/abs/2404.08570)