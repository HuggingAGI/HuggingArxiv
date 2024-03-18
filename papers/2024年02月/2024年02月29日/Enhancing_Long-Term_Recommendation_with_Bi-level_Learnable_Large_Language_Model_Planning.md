# 通过运用双层可学习大型语言模型规划技术，提升长期推荐效果。这项研究致力于探索如何借助大型语言模型进行前瞻性的策划，以改善长期推荐性能。

发布时间：2024年02月29日

`LLM应用`

> Enhancing Long-Term Recommendation with Bi-level Learnable Large Language Model Planning

> 传统推荐系统倾向于过度迎合用户短期喜好，却忽视了其长期参与度。为了改进这一点，我们建议在推荐决策过程中整合规划能力，构建既能满足即时兴趣又能保持长期参与度的策略。尽管强化学习（RL）能通过累计奖励优化学习规划，但面对推荐数据稀少的问题，在从头训练RL模型时易出现不稳定性和过拟合等挑战。鉴于此，我们创新性地提出利用大型语言模型（LLMs）在稀疏数据上出色的规划能力，应用于长期推荐场景。关键在于引导语言模型理解和有效运用个性化推荐任务中的解决方案原则，因预训练阶段可能并未充分涵盖这些原则，故需启发或教授模型。为此，我们设计了一个双层可学习LLM规划器框架，它通过层级机制结合宏观学习与微观学习，包含用于提炼高层指导原则的Planner和Reflector模块，以及负责个性化规划的Actor-Critic组件。大量实验证明，该框架在学习长期推荐规划方面表现出色。

> Traditional recommendation setting tends to excessively cater to users' immediate interests and neglect their long-term engagement. To address it, it is crucial to incorporate planning capabilities into the recommendation decision-making process to develop policies that take into account both immediate interests and long-term engagement. Despite Reinforcement Learning (RL) can learn planning capacity by maximizing cumulative reward, the scarcity of recommendation data presents challenges such as instability and susceptibility to overfitting when training RL models from scratch.
  In this context, we propose to leverage the remarkable planning capabilities over sparse data of Large Language Models (LLMs) for long-term recommendation. The key lies in enabling a language model to understand and apply task-solving principles effectively in personalized recommendation scenarios, as the model's pre-training may not naturally encompass these principles, necessitating the need to inspire or teach the model. To achieve this, we propose a Bi-level Learnable LLM Planner framework, which combines macro-learning and micro-learning through a hierarchical mechanism. The framework includes a Planner and Reflector for acquiring high-level guiding principles and an Actor-Critic component for planning personalization. Extensive experiments validate the superiority of the framework in learning to plan for long-term recommendations.

[Arxiv](https://arxiv.org/abs/2403.00843)