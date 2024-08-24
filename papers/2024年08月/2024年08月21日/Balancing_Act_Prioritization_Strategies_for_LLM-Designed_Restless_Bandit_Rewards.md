# 平衡之道：LLM 设计中无休止强盗奖励的优先策略

发布时间：2024年08月21日

`LLM应用` `公共卫生` `人工智能`

> Balancing Act: Prioritization Strategies for LLM-Designed Restless Bandit Rewards

# 摘要

> LLM 在强化学习中越来越多地被用于根据人类偏好设计奖励函数。我们专注于为 Restless Multi-Armed Bandits 设计 LLM 奖励，这是一个在代理之间分配有限资源的框架。在公共卫生等应用中，这种方法使基层卫生工作者能够根据社区需求定制自动化分配决策。在多个代理存在的情况下，根据人类偏好调整奖励函数可能会对不同子群体产生截然不同的影响，导致复杂的权衡和多目标资源分配问题。我们是第一个提出一种称为社会选择语言模型的原则性方法，用于处理这些权衡。我们模型的新颖之处在于一个透明且可配置的选择组件，称为裁决者，它是一个外部于 LLM 的组件，通过用户选择的社会福利函数控制复杂的权衡。我们的实验表明，与纯 LLM 方法相比，我们的模型可靠地选择了更有效、一致和平衡的奖励函数。

> LLMs are increasingly used to design reward functions based on human preferences in Reinforcement Learning (RL). We focus on LLM-designed rewards for Restless Multi-Armed Bandits, a framework for allocating limited resources among agents. In applications such as public health, this approach empowers grassroots health workers to tailor automated allocation decisions to community needs. In the presence of multiple agents, altering the reward function based on human preferences can impact subpopulations very differently, leading to complex tradeoffs and a multi-objective resource allocation problem. We are the first to present a principled method termed Social Choice Language Model for dealing with these tradeoffs for LLM-designed rewards for multiagent planners in general and restless bandits in particular. The novel part of our model is a transparent and configurable selection component, called an adjudicator, external to the LLM that controls complex tradeoffs via a user-selected social welfare function. Our experiments demonstrate that our model reliably selects more effective, aligned, and balanced reward functions compared to purely LLM-based approaches.

[Arxiv](https://arxiv.org/abs/2408.12112)