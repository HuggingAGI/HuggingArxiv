# R3HF：用于增强来自人类反馈的强化学习的奖励再分配

发布时间：2024年11月12日

`LLM应用` `语言模型`

> R3HF: Reward Redistribution for Enhancing Reinforcement Learning from Human Feedback

# 摘要

> 强化学习从人类反馈（RLHF）为使大型语言模型（LLMs）与人类偏好保持一致提供了一种范例。这涉及基于成对的人类反馈对奖励模型进行初始训练。随后，该奖励模型在强化学习中用于评估每个生成的句子作为一个整体的分数，进一步指导 LLMs 的优化。然而，当前的方法有一个显著的缺点：\emph{它们为整个输出序列分配一个单一、稀疏和延迟的奖励}。这可能会忽略每个标记对期望结果的一些重要的个体贡献。为了克服这个限制，我们的论文提出了一种称为 R3HF 的新颖奖励再分配方法，它有助于更细粒度、标记级别的奖励分配。具体来说，我们的方法将奖励模型的奖励预测任务视为回归问题。因此，通过评估每个标记对奖励模型输出的特定贡献来计算重新分配的奖励。这种详细的方法提高了模型对语言细微差别的理解，导致其性能更精确地提升。我们的方法旨在与大多数当前技术无缝集成，同时产生最小的计算成本。通过在不同的数据集和任务上进行全面的实验，我们已经验证了我们方法的有效性和优越性。

> Reinforcement learning from human feedback (RLHF) provides a paradigm for aligning large language models (LLMs) with human preferences. This involves the initial training of a reward model based on pairwise human feedback. The reward model is subsequently utilized in reinforcement learning to assess the scores of each generated sentence as a whole, further guiding the optimization of LLMs. However, current approaches have a significant shortcoming: \emph{They allocate a single, sparse, and delayed reward to an entire sequence of output}. This may overlook some significant individual contributions of each token towards the desired outcome. To overcome this limitation, our paper proposes a novel reward redistribution method called R3HF, which facilitates a more fine-grained, token-level reward allocation. Specifically, our method treats the reward prediction task of the reward model as a regression problem. As a result, the redistributed rewards are computed by evaluating the specific contribution of each token to the reward model's output. This detailed approach improves the model's understanding of language nuances, leading to more precise enhancements in its performance. Our method is crafted to integrate seamlessly with most current techniques while incurring minimal computational costs. Through comprehensive experiments across diverse datasets and tasks, we have verified the effectiveness and superiority of our approach.

[Arxiv](https://arxiv.org/abs/2411.08302)