# COHERENT：异构多机器人系统与大型语言模型的协同合作

发布时间：2024年09月23日

`Agent` `机器人` `自动化`

> COHERENT: Collaboration of Heterogeneous Multi-Robot System with Large Language Models

# 摘要

> 借助 LLM 的强大推理能力，基于 LLM 的机器人任务规划方法近期取得了显著进展。然而，这些方法主要针对单一或多个同质机器人在简单任务上的应用。实际上，复杂的长期任务往往需要多个异质机器人协同合作，尤其是在动作空间更为复杂的情况下，这使得任务更具挑战性。为此，我们推出了 COHERENT，一个专为异质多机器人系统（如四旋翼、机器狗和机械臂）协作设计的 LLM 任务规划框架。该框架采用提案-执行-反馈-调整 (PEFA) 机制，通过集中任务分配器将复杂任务分解为子任务并分配给各机器人执行器。每个执行器根据分配的子任务选择可行动作，并反馈自我反思信息以调整计划，直至任务完成。我们还构建了一个包含 100 个复杂长期任务的基准测试，实验结果显示，COHERENT 在成功率和执行效率上均大幅领先于现有方法。相关实验视频、代码及基准已发布在 https://github.com/MrKeee/COHERENT。

> Leveraging the powerful reasoning capabilities of large language models (LLMs), recent LLM-based robot task planning methods yield promising results. However, they mainly focus on single or multiple homogeneous robots on simple tasks. Practically, complex long-horizon tasks always require collaborations among multiple heterogeneous robots especially with more complex action spaces, which makes these tasks more challenging. To this end, we propose COHERENT, a novel LLM-based task planning framework for collaboration of heterogeneous multi-robot systems including quadrotors, robotic dogs, and robotic arms. Specifically, a Proposal-Execution-Feedback-Adjustment (PEFA) mechanism is designed to decompose and assign actions for individual robots, where a centralized task assigner makes a task planning proposal to decompose the complex task into subtasks, and then assigns subtasks to robot executors. Each robot executor selects a feasible action to implement the assigned subtask and reports self-reflection feedback to the task assigner for plan adjustment. The PEFA loops until the task is completed. Moreover, we create a challenging heterogeneous multi-robot task planning benchmark encompassing 100 complex long-horizon tasks. The experimental results show that our work surpasses the previous methods by a large margin in terms of success rate and execution efficiency. The experimental videos, code, and benchmark are released at https://github.com/MrKeee/COHERENT.

[Arxiv](https://arxiv.org/abs/2409.15146)