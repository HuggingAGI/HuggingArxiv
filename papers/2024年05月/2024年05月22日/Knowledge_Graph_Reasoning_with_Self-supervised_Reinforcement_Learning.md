# 利用自监督强化学习进行知识图谱推理

发布时间：2024年05月22日

`Agent

理由：这篇论文主要讨论了在知识图谱推理任务中使用强化学习（RL）的方法，特别是引入了一种自监督预训练策略（SSRL）来提升策略网络的性能。论文中提到的“代理依据策略网络自主选择动作”以及“自监督的机制”表明这是一个关于智能体（Agent）的研究，即如何通过自监督学习来优化智能体在知识图谱推理任务中的表现。此外，论文中提到的实验结果和性能提升也强调了这种方法在智能体设计中的应用。因此，这篇论文应归类为Agent。` `知识图谱` `人工智能`

> Knowledge Graph Reasoning with Self-supervised Reinforcement Learning

# 摘要

> 强化学习（RL）在不完备知识图谱中探索推理路径表现出色。面对庞大的动作空间，我们提出了一种自监督预训练策略，以在正式RL训练前为策略网络预热。为了解决自监督RL（SSRL）中常见的分布不匹配问题，我们在监督学习阶段，让代理依据策略网络自主选择动作，并从自我生成的标签中学习，这种自我监督的机制正是其名称的由来。此训练框架提升了SL目标的信息密度，避免了代理过早陷入奖励路径。我们的SSRL方法通过与预训练中SL的广泛覆盖相结合，显著提升了RL性能，因为SL目标的广度使得单独训练代理变得不切实际。实验证明，我们的SSRL模型在四个大型KG数据集的所有Hits@k和MRR指标上，均达到了或超越了当前最佳水平。此方法可作为任何知识图谱推理任务的RL架构的即插即用组件。我们以MINERVA和MultiHopKG为基线，实验结果显示，我们的SSRL模型在这些KG推理任务上始终优于这两个基线。论文代码已公开于https://github.com/owenonline/Knowledge-Graph-Reasoning-with-Self-supervised-Reinforcement-Learning。

> Reinforcement learning (RL) is an effective method of finding reasoning pathways in incomplete knowledge graphs (KGs). To overcome the challenges of a large action space, a self-supervised pre-training method is proposed to warm up the policy network before the RL training stage. To alleviate the distributional mismatch issue in general self-supervised RL (SSRL), in our supervised learning (SL) stage, the agent selects actions based on the policy network and learns from generated labels; this self-generation of labels is the intuition behind the name self-supervised. With this training framework, the information density of our SL objective is increased and the agent is prevented from getting stuck with the early rewarded paths. Our self-supervised RL (SSRL) method improves the performance of RL by pairing it with the wide coverage achieved by SL during pretraining, since the breadth of the SL objective makes it infeasible to train an agent with that alone. We show that our SSRL model meets or exceeds current state-of-the-art results on all Hits@k and mean reciprocal rank (MRR) metrics on four large benchmark KG datasets. This SSRL method can be used as a plug-in for any RL architecture for a KGR task. We adopt two RL architectures, i.e., MINERVA and MultiHopKG as our baseline RL models and experimentally show that our SSRL model consistently outperforms both baselines on all of these four KG reasoning tasks. Full code for the paper available at https://github.com/owenonline/Knowledge-Graph-Reasoning-with-Self-supervised-Reinforcement-Learning.

[Arxiv](https://arxiv.org/abs/2405.13640)