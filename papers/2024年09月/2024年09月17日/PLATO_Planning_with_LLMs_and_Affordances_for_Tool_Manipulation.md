# PLATO：借助 LLM 和 Affordances 实现工具操作的智能规划

发布时间：2024年09月17日

`Agent` `机器人` `人工智能`

> PLATO: Planning with LLMs and Affordances for Tool Manipulation

# 摘要

> 随着机器人系统深入复杂现实世界，如何让机器人理解并执行自然语言指令，而不依赖预设环境知识，成为迫切需求。本文介绍的 PLATO 系统，通过专用大型语言模型代理，处理自然语言输入、理解环境、预测工具功能并生成机器人动作，创新应对这一挑战。与传统硬编码环境系统不同，PLATO 采用模块化代理架构，无需初始环境知识。这些代理识别对象、生成高级计划、转化为低级动作并验证完成情况。系统在复杂工具使用任务中表现出色，适应动态非结构化环境，显著提升灵活性和鲁棒性。通过多场景评估，展示其多样化任务处理能力，并提出 LLM 与机器人平台集成的新方案，推动自主机器人任务执行技术进步。详情请访问项目网站：https://sites.google.com/andrew.cmu.edu/plato

> As robotic systems become increasingly integrated into complex real-world environments, there is a growing need for approaches that enable robots to understand and act upon natural language instructions without relying on extensive pre-programmed knowledge of their surroundings. This paper presents PLATO, an innovative system that addresses this challenge by leveraging specialized large language model agents to process natural language inputs, understand the environment, predict tool affordances, and generate executable actions for robotic systems. Unlike traditional systems that depend on hard-coded environmental information, PLATO employs a modular architecture of specialized agents to operate without any initial knowledge of the environment. These agents identify objects and their locations within the scene, generate a comprehensive high-level plan, translate this plan into a series of low-level actions, and verify the completion of each step. The system is particularly tested on challenging tool-use tasks, which involve handling diverse objects and require long-horizon planning. PLATO's design allows it to adapt to dynamic and unstructured settings, significantly enhancing its flexibility and robustness. By evaluating the system across various complex scenarios, we demonstrate its capability to tackle a diverse range of tasks and offer a novel solution to integrate LLMs with robotic platforms, advancing the state-of-the-art in autonomous robotic task execution. For videos and prompt details, please see our project website: https://sites.google.com/andrew.cmu.edu/plato

[Arxiv](https://arxiv.org/abs/2409.11580)