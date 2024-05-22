# 能量秩对齐：通过偏好优化，我们在广阔的化学空间中探索新领域。

发布时间：2024年05月21日

`Agent

这篇论文介绍了一种名为能量排名对齐（ERA）的新算法，用于指导自回归策略的优化，以生成具有特定属性的分子。虽然这项研究侧重于化学领域，但其提出的算法ERA具有通用性和可扩展性，可以应用于其他领域，如LLM对齐的AI监督任务。因此，这篇论文更符合Agent分类，因为它涉及开发和应用算法来指导和优化特定任务的执行，类似于一个智能代理的行为。` `人工智能`

> Energy Rank Alignment: Using Preference Optimization to Search Chemical Space at Scale

# 摘要

> 在化学空间中寻找分子是一项艰巨的任务，因为可能的分子组合随着原子数量的增加而爆炸性增长。尽管大型自回归模型在化学数据库上训练后能生成强大的分子，但我们仍缺乏有效策略来创造具有特定属性的分子。这种挑战与大型语言模型的“对齐”问题相似，尽管化学任务通常有一个明确且易于评估的目标。我们提出了一种名为能量排名对齐（ERA）的新算法，它利用明确的奖励函数来指导自回归策略的优化。理论上，ERA与近端策略优化（PPO）和直接偏好优化（DPO）有紧密联系，但它的优化目标更趋向于理想的吉布斯-玻尔兹曼分布，其中奖励函数作为能量函数。ERA不仅高度可扩展，无需强化学习，而且在偏好观察较少时表现优于DPO。我们应用ERA来调整分子转换器，使其生成具有特定属性的分子，并发现它在化学空间的广泛区域中表现稳健。虽然我们的研究侧重于化学搜索，但ERA在LLM对齐的AI监督任务上也展现了出色的通用性和可扩展性。

> Searching through chemical space is an exceptionally challenging problem because the number of possible molecules grows combinatorially with the number of atoms. Large, autoregressive models trained on databases of chemical compounds have yielded powerful generators, but we still lack robust strategies for generating molecules with desired properties. This molecular search problem closely resembles the "alignment" problem for large language models, though for many chemical tasks we have a specific and easily evaluable reward function. Here, we introduce an algorithm called energy rank alignment (ERA) that leverages an explicit reward function to produce a gradient-based objective that we use to optimize autoregressive policies. We show theoretically that this algorithm is closely related to proximal policy optimization (PPO) and direct preference optimization (DPO), but has a minimizer that converges to an ideal Gibbs-Boltzmann distribution with the reward playing the role of an energy function. Furthermore, this algorithm is highly scalable, does not require reinforcement learning, and performs well relative to DPO when the number of preference observations per pairing is small. We deploy this approach to align molecular transformers to generate molecules with externally specified properties and find that it does so robustly, searching through diverse parts of chemical space. While our focus here is on chemical search, we also obtain excellent results on an AI supervised task for LLM alignment, showing that the method is scalable and general.

[Arxiv](https://arxiv.org/abs/2405.12961)