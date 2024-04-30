# 面对不公平的动态定价，我们探讨了如何通过激励措施来提升交易的公平性。

发布时间：2024年04月22日

`Agent` `经济学` `人工智能`

> Fairness Incentives in Response to Unfair Dynamic Pricing

# 摘要

> 追求最大化利润的企业采用动态定价策略，这可能引发消费者需求公平性的问题，即不同消费群体对特定定价策略的反应差异。动态定价有时会导致购买者分布与总体人口分布不一致，这在需要公平代表性的市场中尤为突出。为了应对这一挑战，政策制定者可以使用税收和补贴等手段，根据社会目标调整政策机制。本文旨在探讨人工智能方法在辅助政策干预策略方面的潜力。我们构建了一个模拟经济模型，并引入了一个动态社会规划者（SP），该规划者设计企业税收计划，旨在鼓励企业采取公平定价策略，同时利用税收预算补贴那些代表性不足的消费群体。为了全面考虑各种可能的政策情境，我们将社会规划者的学习问题构建为多臂老虎机、上下文老虎机，最终形成完整的强化学习（RL）问题，并对每种情境下的福利结果进行评估。为了解决在较少发生的税收档次中保持有意义税率的难题，我们引入了 FairReplayBuffer，确保 RL 代理能够在离散化的公平性空间中均匀地抽取经验。研究结果显示，实施了学习型税收和再分配政策后，社会福利得到了提升，不仅超越了不考虑公平性的基线，而且在多臂和上下文老虎机情境下接近了理论上最优化的公平感知基线，在完全的 RL 情境下更是超出了 13.19%。

> The use of dynamic pricing by profit-maximizing firms gives rise to demand fairness concerns, measured by discrepancies in consumer groups' demand responses to a given pricing strategy. Notably, dynamic pricing may result in buyer distributions unreflective of those of the underlying population, which can be problematic in markets where fair representation is socially desirable. To address this, policy makers might leverage tools such as taxation and subsidy to adapt policy mechanisms dependent upon their social objective. In this paper, we explore the potential for AI methods to assist such intervention strategies. To this end, we design a basic simulated economy, wherein we introduce a dynamic social planner (SP) to generate corporate taxation schedules geared to incentivizing firms towards adopting fair pricing behaviours, and to use the collected tax budget to subsidize consumption among underrepresented groups. To cover a range of possible policy scenarios, we formulate our social planner's learning problem as a multi-armed bandit, a contextual bandit and finally as a full reinforcement learning (RL) problem, evaluating welfare outcomes from each case. To alleviate the difficulty in retaining meaningful tax rates that apply to less frequently occurring brackets, we introduce FairReplayBuffer, which ensures that our RL agent samples experiences uniformly across a discretized fairness space. We find that, upon deploying a learned tax and redistribution policy, social welfare improves on that of the fairness-agnostic baseline, and approaches that of the analytically optimal fairness-aware baseline for the multi-armed and contextual bandit settings, and surpassing it by 13.19% in the full RL setting.

[Arxiv](https://arxiv.org/abs/2404.14620)