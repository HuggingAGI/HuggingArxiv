# 基于人类偏好反馈的多轮强化学习

发布时间：2024年05月23日

`Agent

这篇论文主要探讨了如何通过强化学习（RL）方法，特别是从多回合对话中的人类偏好反馈中学习，来改进大型语言模型（LLMs）的性能。论文提出了一种新的策略优化算法，适用于多回合偏好基础的RL问题，并在教育对话环境中进行了测试，显示出优于传统RLHF基线的性能。这种方法涉及开发和优化代理（Agent），以更好地理解和响应人类偏好，特别是在需要规划和多回合交互的场景中。因此，这篇论文更符合Agent分类，因为它专注于通过强化学习改进代理的行为和性能。` `对话系统`

> Multi-turn Reinforcement Learning from Preference Human Feedback

# 摘要

> 从人类反馈中学习的强化学习（RLHF）已成为大型语言模型（LLMs）与人类偏好对齐的标准方法，使其在多任务中表现出色。然而，现有方法仅模拟单个决策级别的人类偏好，这在需要规划或多回合交互以实现长期目标的场景中显得力不从心。本文通过开发新颖的强化学习方法，从两个完整的多回合对话间的偏好反馈中学习，解决了这一问题。我们提出了一种基于镜像下降的策略优化算法，适用于多回合偏好基础的RL问题，并证明了其收敛至纳什均衡。在“教育对话”这一新环境中，教师代理指导学生学习随机主题，我们的深度RL算法变体表现优于RLHF基线。即使在仅依赖较弱偏好信号的情况下，我们的算法在具有明确奖励的环境中也能恢复与基于奖励的RL基线相同的性能。

> Reinforcement Learning from Human Feedback (RLHF) has become the standard approach for aligning Large Language Models (LLMs) with human preferences, allowing LLMs to demonstrate remarkable abilities in various tasks. Existing methods work by emulating the preferences at the single decision (turn) level, limiting their capabilities in settings that require planning or multi-turn interactions to achieve a long-term goal. In this paper, we address this issue by developing novel methods for Reinforcement Learning (RL) from preference feedback between two full multi-turn conversations. In the tabular setting, we present a novel mirror-descent-based policy optimization algorithm for the general multi-turn preference-based RL problem, and prove its convergence to Nash equilibrium. To evaluate performance, we create a new environment, Education Dialogue, where a teacher agent guides a student in learning a random topic, and show that a deep RL variant of our algorithm outperforms RLHF baselines. Finally, we show that in an environment with explicit rewards, our algorithm recovers the same performance as a reward-based RL baseline, despite relying solely on a weaker preference signal.

[Arxiv](https://arxiv.org/abs/2405.14655)