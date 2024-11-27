# MALMM：用于零样本机器人操控的多智能体大型语言模型

发布时间：2024年11月26日

`Agent` `机器人` `语言模型`

> MALMM: Multi-Agent Large Language Models for Zero-Shot Robotics Manipulation

# 摘要

> 大型语言模型（LLMs）在诸如机器人操作和导航等众多领域展现出了非凡的规划能力。然而，机器人领域近来虽在高级和低级规划中运用了 LLMs，但此类方法常遭遇重大难题，像长期任务中的幻觉现象，以及因单次生成计划且无实时反馈导致的适应性受限。为应对这些局限，我们提出了一种全新的多智能体 LLM 框架——用于操作的多智能体大型语言模型（MALMM），它将高级规划和低级控制代码生成分配给专门的 LLM 智能体，并由一个额外的智能体进行动态管理转换的监督。通过在每一步后纳入来自环境的观察，我们的框架能有效处理中间失败，实现自适应重新规划。与现有方法不同，我们的方法不依赖预训练的技能策略或上下文学习示例，且能推广到各类新任务。我们在九个 RLBench 任务（包含长期任务）上对我们的方法进行了评估，并展示了其在零样本设置下解决机器人操作问题的能力，从而克服了现有基于 LLM 的操作方法的关键局限。

> Large Language Models (LLMs) have demonstrated remarkable planning abilities across various domains, including robotics manipulation and navigation. While recent efforts in robotics have leveraged LLMs both for high-level and low-level planning, these approaches often face significant challenges, such as hallucinations in long-horizon tasks and limited adaptability due to the generation of plans in a single pass without real-time feedback. To address these limitations, we propose a novel multi-agent LLM framework, Multi-Agent Large Language Model for Manipulation (MALMM) that distributes high-level planning and low-level control code generation across specialized LLM agents, supervised by an additional agent that dynamically manages transitions. By incorporating observations from the environment after each step, our framework effectively handles intermediate failures and enables adaptive re-planning. Unlike existing methods, our approach does not rely on pre-trained skill policies or in-context learning examples and generalizes to a variety of new tasks. We evaluate our approach on nine RLBench tasks, including long-horizon tasks, and demonstrate its ability to solve robotics manipulation in a zero-shot setting, thereby overcoming key limitations of existing LLM-based manipulation methods.

[Arxiv](https://arxiv.org/abs/2411.17636)