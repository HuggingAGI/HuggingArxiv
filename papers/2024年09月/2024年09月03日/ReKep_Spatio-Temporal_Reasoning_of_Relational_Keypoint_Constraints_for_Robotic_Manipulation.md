# ReKep：针对机器人操作，探究关系关键点约束的空间与时间推理

发布时间：2024年09月03日

`Agent` `机器人技术` `自动化`

> ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation

# 摘要

> 将机器人操作任务转化为关联机器人与环境的约束，是一种创新的编码方式，旨在实现期望的机器人行为。然而，如何设计这些约束，使其既适应多变任务，又免去繁琐的手动标注，还能通过现成的优化工具实时生成机器人动作，仍是一个未解之谜。本研究中，我们提出了关系关键点约束（ReKep），一种视觉驱动的约束表示法。ReKep通过Python函数，将环境中的3D关键点转化为数值成本，从而实现对操作任务的精准表达。我们展示了，通过一系列ReKep的序列化表示，可以运用分层优化策略，实时求解机器人动作，实现高效的感知-动作循环。为避免对每个新任务进行手动约束设定，我们开发了一种自动化流程，借助大型视觉与视觉-语言模型，从自由文本指令和RGB-D数据中自动生成ReKep。我们在轮式单臂与固定双臂平台上验证了这一系统的实用性，展示了其在多阶段、复杂环境、双手协作及反应性行为中的广泛应用，且无需预设任务数据或环境模型。更多详情，请访问：https://rekep-robot.github.io。

> Representing robotic manipulation tasks as constraints that associate the robot and the environment is a promising way to encode desired robot behaviors. However, it remains unclear how to formulate the constraints such that they are 1) versatile to diverse tasks, 2) free of manual labeling, and 3) optimizable by off-the-shelf solvers to produce robot actions in real-time. In this work, we introduce Relational Keypoint Constraints (ReKep), a visually-grounded representation for constraints in robotic manipulation. Specifically, ReKep is expressed as Python functions mapping a set of 3D keypoints in the environment to a numerical cost. We demonstrate that by representing a manipulation task as a sequence of Relational Keypoint Constraints, we can employ a hierarchical optimization procedure to solve for robot actions (represented by a sequence of end-effector poses in SE(3)) with a perception-action loop at a real-time frequency. Furthermore, in order to circumvent the need for manual specification of ReKep for each new task, we devise an automated procedure that leverages large vision models and vision-language models to produce ReKep from free-form language instructions and RGB-D observations. We present system implementations on a wheeled single-arm platform and a stationary dual-arm platform that can perform a large variety of manipulation tasks, featuring multi-stage, in-the-wild, bimanual, and reactive behaviors, all without task-specific data or environment models. Website at https://rekep-robot.github.io.

[Arxiv](https://arxiv.org/abs/2409.01652)