# 探究 LLM 在强化学习中动作评估的零-shot 表现

发布时间：2024年09月19日

`LLM应用` `人工智能`

> Assessing the Zero-Shot Capabilities of LLMs for Action Evaluation in RL

# 摘要

> 时间信用分配是强化学习中的核心难题，涉及如何合理评估轨迹中每个动作对达成目标的贡献。然而，当反馈延迟且稀疏时，学习信号弱化，动作评估变得棘手。传统方法如奖励塑造和选项，依赖大量领域知识和人工干预，限制了其应用范围。为此，我们提出了基于语言模型的信用分配（CALM），利用大型语言模型（LLM）自动化奖励塑造和选项发现。CALM 通过 LLM 将任务分解为子目标，并在状态-动作转换中评估子目标达成情况。每当选项终止，子目标达成，CALM 即提供辅助奖励，增强稀疏延迟任务奖励下的学习过程，无需人工设计奖励。初步评估显示，LLM 在零样本设置中有效分配信用，无需示例或微调。这表明 LLM 的知识有望成为强化学习中信用分配的宝贵先验，促进人类知识向价值函数的转化。

> The temporal credit assignment problem is a central challenge in Reinforcement Learning (RL), concerned with attributing the appropriate influence to each actions in a trajectory for their ability to achieve a goal. However, when feedback is delayed and sparse, the learning signal is poor, and action evaluation becomes harder. Canonical solutions, such as reward shaping and options, require extensive domain knowledge and manual intervention, limiting their scalability and applicability. In this work, we lay the foundations for Credit Assignment with Language Models (CALM), a novel approach that leverages Large Language Models (LLMs) to automate credit assignment via reward shaping and options discovery. CALM uses LLMs to decompose a task into elementary subgoals and assess the achievement of these subgoals in state-action transitions. Every time an option terminates, a subgoal is achieved, and CALM provides an auxiliary reward. This additional reward signal can enhance the learning process when the task reward is sparse and delayed without the need for human-designed rewards. We provide a preliminary evaluation of CALM using a dataset of human-annotated demonstrations from MiniHack, suggesting that LLMs can be effective in assigning credit in zero-shot settings, without examples or LLM fine-tuning. Our preliminary results indicate that the knowledge of LLMs is a promising prior for credit assignment in RL, facilitating the transfer of human knowledge into value functions.

[Arxiv](https://arxiv.org/abs/2409.12798)