# Can-Do! 数据集与神经符号基础框架，助力大型多模态模型的具身规划

发布时间：2024年09月21日

`Agent` `人工智能` `机器人`

> Can-Do! A Dataset and Neuro-Symbolic Grounded Framework for Embodied Planning with Large Multimodal Models

# 摘要

> 大型多模态模型在视觉和语言任务中表现出色，具备编码广泛世界知识的潜力，但在现实环境中感知、推理、规划和行动的能力仍待提升。为此，我们推出了 Can-Do 数据集，通过更多样化和复杂的场景来评估具身规划能力。该数据集包含 400 个多模态样本，涵盖自然语言指令、视觉图像、状态变化及行动计划，涉及常识、物理和安全等多方面知识。分析显示，包括 GPT-4V 在内的顶尖模型在视觉感知、理解和推理方面存在瓶颈。为此，我们提出了 NeuroGround 框架，先基于感知环境生成计划，再利用符号规划引擎增强计划。实验证明，该框架优于现有基线。代码和数据集已公开，访问地址为 https://embodied-planning.github.io。

> Large multimodal models have demonstrated impressive problem-solving abilities in vision and language tasks, and have the potential to encode extensive world knowledge. However, it remains an open challenge for these models to perceive, reason, plan, and act in realistic environments. In this work, we introduce Can-Do, a benchmark dataset designed to evaluate embodied planning abilities through more diverse and complex scenarios than previous datasets. Our dataset includes 400 multimodal samples, each consisting of natural language user instructions, visual images depicting the environment, state changes, and corresponding action plans. The data encompasses diverse aspects of commonsense knowledge, physical understanding, and safety awareness. Our fine-grained analysis reveals that state-of-the-art models, including GPT-4V, face bottlenecks in visual perception, comprehension, and reasoning abilities. To address these challenges, we propose NeuroGround, a neurosymbolic framework that first grounds the plan generation in the perceived environment states and then leverages symbolic planning engines to augment the model-generated plans. Experimental results demonstrate the effectiveness of our framework compared to strong baselines. Our code and dataset are available at https://embodied-planning.github.io.

[Arxiv](https://arxiv.org/abs/2409.14277)