# 用于共享和动态环境的多模态 3D 场景图更新器

发布时间：2024年11月05日

`LLM应用` `机器人` `场景图`

> Multi-Modal 3D Scene Graph Updater for Shared and Dynamic Environments

# 摘要

> 通用大型语言模型（LLMs）和大型视觉模型（VLMs）的出现简化了语义丰富地图的构建，这些地图能够使机器人将高级推理和规划落实到它们的表示中。最广泛使用的语义地图格式之一是 3D 场景图，它捕获了度量（低级）和语义（高级）信息。然而，这些地图通常假设一个静态的世界，而像家庭和办公室这样的真实环境是动态的。即使这些空间中的小变化也会显著影响任务性能。为了将机器人集成到动态环境中，它们必须检测变化并实时更新场景图。这个更新过程本质上是多模态的，需要来自各种来源的输入，例如人类代理、机器人自身的感知系统、时间和其动作。这项工作提出了一个框架，利用这些多模态输入在实时操作期间保持场景图的一致性，呈现了有希望的初步结果，并勾勒出未来研究的路线图。

> The advent of generalist Large Language Models (LLMs) and Large Vision Models (VLMs) have streamlined the construction of semantically enriched maps that can enable robots to ground high-level reasoning and planning into their representations. One of the most widely used semantic map formats is the 3D Scene Graph, which captures both metric (low-level) and semantic (high-level) information. However, these maps often assume a static world, while real environments, like homes and offices, are dynamic. Even small changes in these spaces can significantly impact task performance. To integrate robots into dynamic environments, they must detect changes and update the scene graph in real-time. This update process is inherently multimodal, requiring input from various sources, such as human agents, the robot's own perception system, time, and its actions. This work proposes a framework that leverages these multimodal inputs to maintain the consistency of scene graphs during real-time operation, presenting promising initial results and outlining a roadmap for future research.

[Arxiv](https://arxiv.org/abs/2411.02938)