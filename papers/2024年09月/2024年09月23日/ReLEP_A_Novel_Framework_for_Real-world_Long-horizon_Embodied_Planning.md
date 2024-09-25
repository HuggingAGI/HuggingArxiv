# ReLEP：开创性的现实世界长期具身规划框架

发布时间：2024年09月23日

`Agent` `机器人` `人工智能`

> ReLEP: A Novel Framework for Real-world Long-horizon Embodied Planning

# 摘要

> 具身AI的核心在于长时程的现实世界规划。为了应对复杂任务，代理需将抽象指令细化为具体步骤。传统方法多依赖GPT-4V，但其有限的技能理解限制了任务多样性。为此，我们推出了ReLEP，一个革命性的长时程具身规划框架，能处理各类日常任务。其核心是经过优化的视觉语言模型，根据指令和场景生成技能序列。这些技能源自精心构建的库。ReLEP还集成了记忆模块和机器人配置模块，确保跨平台适应性。此外，我们设计了半自动数据生成流程，以应对数据稀缺。实验证明，ReLEP在多个日常任务中表现卓越，超越了现有顶尖方法。

> Real-world long-horizon embodied planning underpins embodied AI. To accomplish long-horizon tasks, agents need to decompose abstract instructions into detailed steps. Prior works mostly rely on GPT-4V for task decomposition into predefined actions, which limits task diversity due to GPT-4V's finite understanding of larger skillsets. Therefore, we present ReLEP, a groundbreaking framework for Real world Long-horizon Embodied Planning, which can accomplish a wide range of daily tasks. At its core lies a fine-tuned large vision language model that formulates plans as sequences of skill functions according to input instruction and scene image. These functions are selected from a carefully designed skill library. ReLEP is also equipped with a Memory module for plan and status recall, and a Robot Configuration module for versatility across robot types. In addition, we propose a semi-automatic data generation pipeline to tackle dataset scarcity. Real-world off-line experiments across eight daily embodied tasks demonstrate that ReLEP is able to accomplish long-horizon embodied tasks and outperforms other state-of-the-art baseline methods.

[Arxiv](https://arxiv.org/abs/2409.15658)