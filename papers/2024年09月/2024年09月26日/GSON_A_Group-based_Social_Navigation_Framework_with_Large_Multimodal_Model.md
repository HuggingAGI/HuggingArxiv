# GSON：结合大型多模态模型的群体社交导航框架

发布时间：2024年09月26日

`Agent` `机器人` `自动驾驶`

> GSON: A Group-based Social Navigation Framework with Large Multimodal Model

# 摘要

> 随着服务机器人和自动驾驶车辆在人类环境中的增多，它们不仅需要导航，还需考虑动态社会背景，确保共享空间中的尊重与舒适，这对感知和规划提出了挑战。本文提出 GSON 框架，通过增强 LMM 的视觉推理能力，使机器人感知并利用周围社会群体。我们使用视觉提示技术零-shot 提取行人社会关系，并结合高效检测跟踪，解决 LMM 推理速度问题。规划系统则避免破坏现有社会结构，采用基于社会结构的中间层规划器，兼顾全局与局部规划。实验证明，该方法在复杂社会结构任务中表现优异，超越了多个基线。

> As the number of service robots and autonomous vehicles in human-centered environments grows, their requirements go beyond simply navigating to a destination. They must also take into account dynamic social contexts and ensure respect and comfort for others in shared spaces, which poses significant challenges for perception and planning. In this paper, we present a group-based social navigation framework GSON to enable mobile robots to perceive and exploit the social group of their surroundings by leveling the visual reasoning capability of the Large Multimodal Model (LMM). For perception, we apply visual prompting techniques to zero-shot extract the social relationship among pedestrians and combine the result with a robust pedestrian detection and tracking pipeline to alleviate the problem of low inference speed of the LMM. Given the perception result, the planning system is designed to avoid disrupting the current social structure. We adopt a social structure-based mid-level planner as a bridge between global path planning and local motion planning to preserve the global context and reactive response. The proposed method is validated on real-world mobile robot navigation tasks involving complex social structure understanding and reasoning. Experimental results demonstrate the effectiveness of the system in these scenarios compared with several baselines.

[Arxiv](https://arxiv.org/abs/2409.18084)