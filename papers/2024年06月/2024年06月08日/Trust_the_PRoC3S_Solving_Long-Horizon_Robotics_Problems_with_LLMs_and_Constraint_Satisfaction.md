# 信赖 PRoC3S：借助 LLMs 与约束满足，攻克长视野机器人难题

发布时间：2024年06月08日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）在机器人领域的应用，特别是在规划和执行受物理和环境约束的连续参数化技能方面的能力。论文中提到的策略PRoC3S展示了LLM如何生成和调整技能序列以满足特定约束，并在模拟环境中进行了验证。这种应用涉及到创建和操作智能代理（Agent），以解决复杂的机器人任务，因此属于Agent分类。` `机器人技术` `自动化控制`

> Trust the PRoC3S: Solving Long-Horizon Robotics Problems with LLMs and Constraint Satisfaction

# 摘要

> 预训练的大型语言模型（LLMs）在机器人领域的最新进展展示了它们将一系列离散技能有序组合以达成简单机器人任务中开放式目标的能力。本文聚焦于LLM如何规划一组需遵循运动学、几何学和物理学约束的连续参数化技能。我们引导LLM生成一个开放参数的函数代码，该函数与环境约束结合，构成了一个连续约束满足问题（CCSP）。通过采样或优化解决此CCSP，可找到既达成目标又遵守约束的技能序列及参数设置。我们还处理了LLM提出的不可行CCSP，如运动学不可行、动力学不稳定或引发碰撞的情况，并指导LLM重新构建新的CCSP。在三个模拟3D环境中的实验证明，我们的策略PRoC3S在处理具有现实约束的复杂操作任务时，比现有方法更高效且有效。

> Recent developments in pretrained large language models (LLMs) applied to robotics have demonstrated their capacity for sequencing a set of discrete skills to achieve open-ended goals in simple robotic tasks. In this paper, we examine the topic of LLM planning for a set of continuously parameterized skills whose execution must avoid violations of a set of kinematic, geometric, and physical constraints. We prompt the LLM to output code for a function with open parameters, which, together with environmental constraints, can be viewed as a Continuous Constraint Satisfaction Problem (CCSP). This CCSP can be solved through sampling or optimization to find a skill sequence and continuous parameter settings that achieve the goal while avoiding constraint violations. Additionally, we consider cases where the LLM proposes unsatisfiable CCSPs, such as those that are kinematically infeasible, dynamically unstable, or lead to collisions, and re-prompt the LLM to form a new CCSP accordingly. Experiments across three different simulated 3D domains demonstrate that our proposed strategy, PRoC3S, is capable of solving a wide range of complex manipulation tasks with realistic constraints on continuous parameters much more efficiently and effectively than existing baselines.

[Arxiv](https://arxiv.org/abs/2406.05572)