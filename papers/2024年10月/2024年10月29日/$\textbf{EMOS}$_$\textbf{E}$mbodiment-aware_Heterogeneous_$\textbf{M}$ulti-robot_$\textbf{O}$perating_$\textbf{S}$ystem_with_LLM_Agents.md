# $	extbf{EMOS}$: 具有 LLM 代理的具身感知异构多机器人操作系统

发布时间：2024年10月29日

`Agent` `机器人` `多智能体系统`

> $\textbf{EMOS}$: $\textbf{E}$mbodiment-aware Heterogeneous $\textbf{M}$ulti-robot $\textbf{O}$perating $\textbf{S}$ystem with LLM Agents

# 摘要

> 异构多机器人系统（HMRS）已成为处理单个机器人无法独立完成的复杂任务的有力手段。当前基于大型语言模型的多智能体系统（基于LLM的MAS）在软件开发和操作系统等领域成绩斐然，但应用于机器人控制时却面临独特挑战。尤其要指出的是，多机器人系统中每个智能体的能力本质上取决于机器人的物理构成，而非预先设定的角色。为解决此问题，我们引入了新颖的多智能体框架，旨在促进不同实体和能力的异构机器人间的有效协作，并推出了名为Habitat-MAS的新基准。我们的关键设计之一是$	extit{Robot Resume}$：我们提出了自提示的方法，而非采用人为设计的角色扮演。在此方法中，智能体理解机器人URDF文件，并调用机器人运动学工具生成其物理能力的描述，以指导其在任务规划和动作执行中的行为。Habitat-MAS基准旨在评估多智能体框架如何处理需要具身感知推理的任务，包括1）操作，2）感知，3）导航，4）综合多层对象重新排列。实验结果表明，机器人的“简历”以及我们多智能体系统的分层设计对于此复杂问题情境下异构多机器人系统的有效运行至关重要。

> Heterogeneous multi-robot systems (HMRS) have emerged as a powerful approach for tackling complex tasks that single robots cannot manage alone. Current large-language-model-based multi-agent systems (LLM-based MAS) have shown success in areas like software development and operating systems, but applying these systems to robot control presents unique challenges. In particular, the capabilities of each agent in a multi-robot system are inherently tied to the physical composition of the robots, rather than predefined roles. To address this issue, we introduce a novel multi-agent framework designed to enable effective collaboration among heterogeneous robots with varying embodiments and capabilities, along with a new benchmark named Habitat-MAS. One of our key designs is $\textit{Robot Resume}$: Instead of adopting human-designed role play, we propose a self-prompted approach, where agents comprehend robot URDF files and call robot kinematics tools to generate descriptions of their physics capabilities to guide their behavior in task planning and action execution. The Habitat-MAS benchmark is designed to assess how a multi-agent framework handles tasks that require embodiment-aware reasoning, which includes 1) manipulation, 2) perception, 3) navigation, and 4) comprehensive multi-floor object rearrangement. The experimental results indicate that the robot's resume and the hierarchical design of our multi-agent system are essential for the effective operation of the heterogeneous multi-robot system within this intricate problem context.

[Arxiv](https://arxiv.org/abs/2410.22662)