# 关于个性化自动驾驶车辆运动控制的车载视觉语言模型：系统设计与真实世界验证

发布时间：2024年11月17日

`RAG` `自动驾驶`

> On-Board Vision-Language Models for Personalized Autonomous Vehicle Motion Control: System Design and Real-World Validation

# 摘要

> 个性化驾驶指的是自动驾驶汽车能调适驾驶行为或控制策略，契合个体用户的偏好与驾驶风格，同时保障安全和舒适标准。然而，现有的成果要么难以精准捕捉每个个体的偏好，要么随着用户群体的扩大而计算效率欠佳。视觉语言模型（VLMs）凭借其自然语言理解和场景推理能力，为此提供了颇具潜力的解决方案。在本项工作中，我们提出了一个轻巧但高效的车载 VLM 框架，既能保持强大的推理能力，又能实现低延迟的个性化驾驶表现。我们的方案融入了一个基于检索增强生成（RAG）的存储模块，可通过人类反馈持续学习个体的驾驶偏好。经过全面的真实车辆部署和实验，我们的系统已展现出能在各类场景中提供安全、舒适且个性化的驾驶体验，接管率大幅降低，最高可达 76.9%。据我们所知，此项工作是现实世界自动驾驶汽车中首个基于端到端 VLM 的运动控制系统。

> Personalized driving refers to an autonomous vehicle's ability to adapt its driving behavior or control strategies to match individual users' preferences and driving styles while maintaining safety and comfort standards. However, existing works either fail to capture every individual preference precisely or become computationally inefficient as the user base expands. Vision-Language Models (VLMs) offer promising solutions to this front through their natural language understanding and scene reasoning capabilities. In this work, we propose a lightweight yet effective on-board VLM framework that provides low-latency personalized driving performance while maintaining strong reasoning capabilities. Our solution incorporates a Retrieval-Augmented Generation (RAG)-based memory module that enables continuous learning of individual driving preferences through human feedback. Through comprehensive real-world vehicle deployment and experiments, our system has demonstrated the ability to provide safe, comfortable, and personalized driving experiences across various scenarios and significantly reduce takeover rates by up to 76.9%. To the best of our knowledge, this work represents the first end-to-end VLM-based motion control system in real-world autonomous vehicles.

[Arxiv](https://arxiv.org/abs/2411.11913)