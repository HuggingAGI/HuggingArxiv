# MARLIN：通过语言引导的机器人间协商实现的多智能体强化学习

发布时间：2024年10月18日

`Agent` `机器人` `人工智能`

> MARLIN: Multi-Agent Reinforcement Learning Guided by Language-Based Inter-Robot Negotiation

# 摘要

> 多智能体强化学习是训练多机器人系统的关键，通过奖励和惩罚机制，系统在达到一定标准后才能投入实际应用。若训练不足，任务可能失败，甚至危及环境。因此，缩短训练周期并提高性能至关重要。我们提出了MARLIN，一种基于语言协商的多智能体强化学习方法，使训练更快且更透明。机器人通过大型语言模型协商任务，生成计划指导训练。我们动态切换强化学习和协商方法，相比传统方法，训练速度更快，系统能更早部署。通过自然语言协商，我们能更深入理解机器人行为。实验表明，MARLIN在性能损失极小的情况下，训练速度显著提升。

> Multi-agent reinforcement learning is a key method for training multi-robot systems over a series of episodes in which robots are rewarded or punished according to their performance; only once the system is trained to a suitable standard is it deployed in the real world. If the system is not trained enough, the task will likely not be completed and could pose a risk to the surrounding environment. Therefore, reaching high performance in a shorter training period can lead to significant reductions in time and resource consumption. We introduce Multi-Agent Reinforcement Learning guided by Language-based Inter-Robot Negotiation (MARLIN), which makes the training process both faster and more transparent. We equip robots with large language models that negotiate and debate the task, producing a plan that is used to guide the policy during training. We dynamically switch between using reinforcement learning and the negotiation-based approach throughout training. This offers an increase in training speed when compared to standard multi-agent reinforcement learning and allows the system to be deployed to physical hardware earlier. As robots negotiate in natural language, we can better understand the behaviour of the robots individually and as a collective. We compare the performance of our approach to multi-agent reinforcement learning and a large language model to show that our hybrid method trains faster at little cost to performance.

[Arxiv](https://arxiv.org/abs/2410.14383)