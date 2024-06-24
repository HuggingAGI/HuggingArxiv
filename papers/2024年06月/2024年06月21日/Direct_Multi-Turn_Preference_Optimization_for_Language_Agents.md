# 语言代理的直接多轮偏好优化

发布时间：2024年06月21日

`Agent

理由：这篇论文主要讨论了如何优化大型语言模型（LLMs）以适应代理任务，特别是在多轮任务中的应用。它提出了一种新的损失函数DMPO，专门设计来处理多轮代理任务，并通过实验验证了其有效性。这与“Agent”分类下的研究内容相符，即如何设计和优化代理以完成特定任务。` `人工智能`

> Direct Multi-Turn Preference Optimization for Language Agents

# 摘要

> 在开发语言代理时，将大型语言模型（LLMs）适配到代理任务至关重要。直接偏好优化（DPO）通过减少累积误差，为直接优化强化学习（RL）目标提供了一种有效途径。然而，DPO在处理多轮任务时遇到了难题，主要是由于无法解决分区函数的问题。为了克服这一挑战，我们使分区函数与当前状态无关，并调整了偏好与非偏好轨迹之间的长度差异。具体而言，我们在RL目标中引入了状态-动作占用度量约束，并对Bradley-Terry模型进行了长度归一化处理，从而创造了一个名为DMPO的新损失函数，专门针对多轮代理任务，并附有理论支持。通过在三个多轮代理任务数据集上的广泛测试，DMPO损失展现出了其卓越的性能和有效性。

> Adapting Large Language Models (LLMs) for agent tasks is critical in developing language agents. Direct Preference Optimization (DPO) is a promising technique for this adaptation with the alleviation of compounding errors, offering a means to directly optimize Reinforcement Learning (RL) objectives. However, applying DPO to multi-turn tasks presents challenges due to the inability to cancel the partition function. Overcoming this obstacle involves making the partition function independent of the current state and addressing length disparities between preferred and dis-preferred trajectories. In this light, we replace the policy constraint with the state-action occupancy measure constraint in the RL objective and add length normalization to the Bradley-Terry model, yielding a novel loss function named DMPO for multi-turn agent tasks with theoretical explanations. Extensive experiments on three multi-turn agent task datasets confirm the effectiveness and superiority of the DMPO loss.

[Arxiv](https://arxiv.org/abs/2406.14868)