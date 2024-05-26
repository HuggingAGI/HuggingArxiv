# 利用自监督强化学习进行知识图谱推理
发布时间：2024年05月22日

`知识图谱`
> Knowledge Graph Reasoning with Self-supervised Reinforcement Learning
>
> 强化学习（RL）在不完备知识图谱中探索推理路径表现出色。面对庞大的动作空间，我们提出了一种自监督预训练策略，以在正式RL训练前为策略网络预热。为了解决自监督RL（SSRL）中常见的分布不匹配问题，我们在监督学习阶段，让代理依据策略网络自主选择动作，并从自我生成的标签中学习，这种自我监督的机制正是其名称的由来。此训练框架提升了SL目标的信息密度，避免了代理过早陷入奖励路径。我们的SSRL方法通过与预训练中SL的广泛覆盖相结合，显著提升了RL性能，因为SL目标的广度使得单独训练代理变得不切实际。实验证明，我们的SSRL模型在四个大型KG数据集的所有Hits@k和MRR指标上，均达到了或超越了当前最佳水平。此方法可作为任何知识图谱推理任务的RL架构的即插即用组件。我们以MINERVA和MultiHopKG为基线，实验结果显示，我们的SSRL模型在这些KG推理任务上始终优于这两个基线。论文代码已公开于https://github.com/owenonline/Knowledge-Graph-Reasoning-with-Self-supervised-Reinforcement-Learning。
>
> https://arxiv.org/abs/2405.13640


<hr />

- 论文原文: [https://arxiv.org/abs/2405.13640](https://arxiv.org/abs/2405.13640)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886