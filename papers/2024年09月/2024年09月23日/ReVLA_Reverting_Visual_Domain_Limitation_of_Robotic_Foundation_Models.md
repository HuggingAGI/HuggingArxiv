# ReVLA：突破机器人基础模型的视觉领域限制

发布时间：2024年09月23日

`Agent` `机器人` `人工智能`

> ReVLA: Reverting Visual Domain Limitation of Robotic Foundation Models

# 摘要

> 大语言模型和机器人数据集的最新进展，推动了机器人模型向多任务、多场景、多形态的通才转变。开放的视觉语言动作模型在多种任务中表现出色，成为社区的一大进步。我们研究了三个现有机器人模型的视觉泛化能力，并提出了评估框架。研究发现，现有模型在视觉域外场景中表现不佳，可能是训练数据变异不足或灾难性遗忘所致。我们探索了使用预训练视觉模型的OpenVLA，但DINO-v2在深度回归任务中的失败揭示了灾难性遗忘。为解决这一问题，我们提出了基于模型合并的渐进式主干逆转方法，使OpenVLA恢复视觉泛化能力。这使得ReVLA在视觉OOD任务中的抓取和提升性能分别提升了77%和66%。

> Recent progress in large language models and access to large-scale robotic datasets has sparked a paradigm shift in robotics models transforming them into generalists able to adapt to various tasks, scenes, and robot modalities. A large step for the community are open Vision Language Action models which showcase strong performance in a wide variety of tasks. In this work, we study the visual generalization capabilities of three existing robotic foundation models, and propose a corresponding evaluation framework.
  Our study shows that the existing models do not exhibit robustness to visual out-of-domain scenarios. This is potentially caused by limited variations in the training data and/or catastrophic forgetting, leading to domain limitations in the vision foundation models. We further explore OpenVLA, which uses two pre-trained vision foundation models and is, therefore, expected to generalize to out-of-domain experiments. However, we showcase catastrophic forgetting by DINO-v2 in OpenVLA through its failure to fulfill the task of depth regression.
  To overcome the aforementioned issue of visual catastrophic forgetting, we propose a gradual backbone reversal approach founded on model merging. This enables OpenVLA which requires the adaptation of the visual backbones during initial training -- to regain its visual generalization ability. Regaining this capability enables our ReVLA model to improve over OpenVLA by a factor of 77% and 66% for grasping and lifting in visual OOD tasks .

[Arxiv](https://arxiv.org/abs/2409.15250)