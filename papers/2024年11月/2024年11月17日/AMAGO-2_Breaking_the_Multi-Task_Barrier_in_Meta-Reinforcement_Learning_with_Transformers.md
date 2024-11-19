# AMAGO-2：凭借 Transformer 在元强化学习中打破多任务的壁垒

发布时间：2024年11月17日

`Agent` `多任务优化`

> AMAGO-2: Breaking the Multi-Task Barrier in Meta-Reinforcement Learning with Transformers

# 摘要

> 语言模型在多样的数据集上训练，借由上下文学习实现泛化。强化学习（RL）策略能通过序列模型内存中的元学习达成相似效果。然而，元 RL 研究主要着眼于适应单个任务的细微变化，若不应对多任务优化的挑战，就难以拓展至更通用的行为，且少有解决方案能契合元 RL 从大量未标注任务的训练集中学习的目标。为应对此挑战，我们重新审视了多任务 RL 因不同任务不均衡的回报规模导致训练损失不平衡而受瓶颈制约的观点。基于基于 Transformer 的（上下文）元 RL 最新进展，我们评估了一个简单却可扩展的方案，即把代理的执行者和评论家目标都转化为分类术语，使优化与当前的回报规模脱钩。在 Meta-World ML45、Multi-Game Procgen、Multi-Task POPGym、Multi-Game Atari 和 BabyAI 中的大规模对比发现，此设计在无明确任务标签的情况下，于在线多任务适应和内存问题上取得显著进展。

> Language models trained on diverse datasets unlock generalization by in-context learning. Reinforcement Learning (RL) policies can achieve a similar effect by meta-learning within the memory of a sequence model. However, meta-RL research primarily focuses on adapting to minor variations of a single task. It is difficult to scale towards more general behavior without confronting challenges in multi-task optimization, and few solutions are compatible with meta-RL's goal of learning from large training sets of unlabeled tasks. To address this challenge, we revisit the idea that multi-task RL is bottlenecked by imbalanced training losses created by uneven return scales across different tasks. We build upon recent advancements in Transformer-based (in-context) meta-RL and evaluate a simple yet scalable solution where both an agent's actor and critic objectives are converted to classification terms that decouple optimization from the current scale of returns. Large-scale comparisons in Meta-World ML45, Multi-Game Procgen, Multi-Task POPGym, Multi-Game Atari, and BabyAI find that this design unlocks significant progress in online multi-task adaptation and memory problems without explicit task labels.

[Arxiv](https://arxiv.org/abs/2411.11188)