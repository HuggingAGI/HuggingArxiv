# 在多智能体强化学习中，用于协同驾驶的语言驱动策略提炼

发布时间：2024年10月31日

`Agent` `自动驾驶`

> Language-Driven Policy Distillation for Cooperative Driving in Multi-Agent Reinforcement Learning

# 摘要

> 联网自动驾驶汽车（CAVs）的协同驾驶技术对提升交通系统的效率与安全性极为关键。像多智能体强化学习（MARL）这类基于学习的方法，在协同决策任务中展现出了强大的能力。不过，现有的 MARL 方法在学习效率和性能方面依旧面临挑战。近些年来，大型语言模型（LLMs）迅速进步，在各类顺序决策任务中彰显出非凡的能力。为在保证决策效率和成本效益的同时增强协同代理的学习能力，我们提出了 LDPD，这是一种用于引导 MARL 探索的语言驱动策略蒸馏方法。在此框架中，基于 LLM 的教师代理训练较小的学生代理，凭借自身的决策示范达成协同决策。教师代理强化了 CAVs 的观察信息，借助 LLMs 进行复杂的协同决策推理，还运用精心设计的决策工具实现专家级决策，提供优质教学体验。随后，学生代理通过梯度策略更新，将教师的先验知识提炼融入自身模型。实验表明，学生在教师极少的指导下就能迅速提升能力，最终超越教师的表现。大量实验显示，与基线方法相比，我们的方法具有更出色的性能和学习效率。

> The cooperative driving technology of Connected and Autonomous Vehicles (CAVs) is crucial for improving the efficiency and safety of transportation systems. Learning-based methods, such as Multi-Agent Reinforcement Learning (MARL), have demonstrated strong capabilities in cooperative decision-making tasks. However, existing MARL approaches still face challenges in terms of learning efficiency and performance. In recent years, Large Language Models (LLMs) have rapidly advanced and shown remarkable abilities in various sequential decision-making tasks. To enhance the learning capabilities of cooperative agents while ensuring decision-making efficiency and cost-effectiveness, we propose LDPD, a language-driven policy distillation method for guiding MARL exploration. In this framework, a teacher agent based on LLM trains smaller student agents to achieve cooperative decision-making through its own decision-making demonstrations. The teacher agent enhances the observation information of CAVs and utilizes LLMs to perform complex cooperative decision-making reasoning, which also leverages carefully designed decision-making tools to achieve expert-level decisions, providing high-quality teaching experiences. The student agent then refines the teacher's prior knowledge into its own model through gradient policy updates. The experiments demonstrate that the students can rapidly improve their capabilities with minimal guidance from the teacher and eventually surpass the teacher's performance. Extensive experiments show that our approach demonstrates better performance and learning efficiency compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2410.24152)