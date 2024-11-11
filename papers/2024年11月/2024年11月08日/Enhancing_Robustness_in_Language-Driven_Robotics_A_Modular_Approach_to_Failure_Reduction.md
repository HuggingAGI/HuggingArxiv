# 增强语言驱动机器人的鲁棒性：一种减少故障的模块化方法

发布时间：2024年11月08日

`LLM应用` `机器人` `语言模型`

> Enhancing Robustness in Language-Driven Robotics: A Modular Approach to Failure Reduction

# 摘要

> 大型语言模型（LLMs）的最新进展在机器人技术方面取得了重大进展，使具身智能体能够更好地理解和执行开放式任务。然而，现有的使用 LLMs 的方法在将其输出与物理环境相结合以及与机器人的能力相匹配方面面临限制。对于较小的语言模型，这种挑战变得更加明显，它们在计算上更高效，但在任务规划和执行方面不太稳健。在本文中，我们提出了一种新颖的模块化架构，旨在通过解决这些接地和对齐问题来增强 LLM 驱动的机器人技术的稳健性。我们在目标条件下的 POMDP 框架内将任务规划问题形式化，确定 LLM 驱动规划中的关键故障模式，并提出有针对性的设计原则来缓解这些问题。我们的架构引入了一个“预期结果”模块以防止子目标的错误描述，并引入了一个反馈机制以实现实时错误恢复。实验结果，无论是在模拟还是在物理机器人上，都表明与较大的 LLMs 和标准基线相比，我们的方法显著提高了拾取和放置以及操作任务的任务成功率。通过硬件实验，我们还展示了我们的架构如何能够高效地在本地运行。这项工作突出了较小的、可在本地执行的 LLMs 在机器人技术中的潜力，并为稳健的任务执行提供了可扩展、高效的解决方案。

> Recent advances in large language models (LLMs) have led to significant progress in robotics, enabling embodied agents to better understand and execute open-ended tasks. However, existing approaches using LLMs face limitations in grounding their outputs within the physical environment and aligning with the capabilities of the robot. This challenge becomes even more pronounced with smaller language models, which are more computationally efficient but less robust in task planning and execution. In this paper, we present a novel modular architecture designed to enhance the robustness of LLM-driven robotics by addressing these grounding and alignment issues. We formalize the task planning problem within a goal-conditioned POMDP framework, identify key failure modes in LLM-driven planning, and propose targeted design principles to mitigate these issues. Our architecture introduces an ``expected outcomes'' module to prevent mischaracterization of subgoals and a feedback mechanism to enable real-time error recovery. Experimental results, both in simulation and on physical robots, demonstrate that our approach significantly improves task success rates for pick-and-place and manipulation tasks compared to both larger LLMs and standard baselines. Through hardware experiments, we also demonstrate how our architecture can be run efficiently and locally. This work highlights the potential of smaller, locally-executable LLMs in robotics and provides a scalable, efficient solution for robust task execution.

[Arxiv](https://arxiv.org/abs/2411.05474)