# 完美融合：以多元评委视角重塑 RLHF

发布时间：2024年09月30日

`LLM理论` `人工智能`

> The Perfect Blend: Redefining RLHF with Mixture of Judges

# 摘要

> 从人类反馈中进行强化学习 (RLHF) 已成为微调大型语言模型 (LLM) 的主流方法。然而，RLHF 在多任务学习 (MTL) 中面临奖励作弊和极端多目标优化的挑战，导致其在 MTL 中的应用受限。目前，RLHF 在 MTL 中的应用需要依赖人类直觉进行复杂的权重调整，缺乏普适性。为此，我们提出了一种新的后训练范式——约束生成策略优化 (CGPO)。CGPO 的核心是混合法官 (MoJ)，结合成本高效的约束策略优化和分层技术，能够系统化地优化 RLHF。CGPO 不仅在理论上有保障，实证结果优异，还无需繁琐的超参数调整，适用于常见的后训练流程。此外，CGPO 能有效检测并缓解奖励作弊行为，在大量目标中实现帕累托最优。实证评估显示，CGPO 在一般聊天、STEM 问题、指令跟随和编码等任务中，显著优于 PPO 和 DPO 等标准 RLHF 算法。特别是在 AlpacaEval-2 中提升 7.4%，在 Arena-Hard 中提升 12.5%，并在数学和编码等领域持续进步。尤其值得一提的是，CGPO 成功解决了 PPO 在编码基准测试中常见的严重奖励作弊问题。这一突破不仅克服了 RLHF 在多任务学习中的难题，还推动了通用 LLM 在多样化应用中的前沿发展。

> Reinforcement learning from human feedback (RLHF) has become the leading approach for fine-tuning large language models (LLM). However, RLHF has limitations in multi-task learning (MTL) due to challenges of reward hacking and extreme multi-objective optimization (i.e., trade-off of multiple and/or sometimes conflicting objectives). Applying RLHF for MTL currently requires careful tuning of the weights for reward model and data combinations. This is often done via human intuition and does not generalize. In this work, we introduce a novel post-training paradigm which we called Constrained Generative Policy Optimization (CGPO). The core of CGPO is Mixture of Judges (MoJ) with cost-efficient constrained policy optimization with stratification, which can identify the perfect blend in RLHF in a principled manner. It shows strong empirical results with theoretical guarantees, does not require extensive hyper-parameter tuning, and is plug-and-play in common post-training pipelines. Together, this can detect and mitigate reward hacking behaviors while reaching a pareto-optimal point across an extremely large number of objectives.
  Our empirical evaluations demonstrate that CGPO significantly outperforms standard RLHF algorithms like PPO and DPO across various tasks including general chat, STEM questions, instruction following, and coding. Specifically, CGPO shows improvements of 7.4% in AlpacaEval-2 (general chat), 12.5% in Arena-Hard (STEM & reasoning), and consistent gains in other domains like math and coding. Notably, PPO, while commonly used, is prone to severe reward hacking in popular coding benchmarks, which CGPO successfully addresses. This breakthrough in RLHF not only tackles reward hacking and extreme multi-objective optimization challenges but also advances the state-of-the-art in aligning general-purpose LLMs for diverse applications.

[Arxiv](https://arxiv.org/abs/2409.20370)