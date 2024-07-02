# 迭代纳什策略优化：借助无悔学习，使大型语言模型与广泛偏好相契合

发布时间：2024年06月30日

`LLM理论` `人工智能` `博弈论`

> Iterative Nash Policy Optimization: Aligning LLMs with General Preferences via No-Regret Learning

# 摘要

> 基于人类反馈的强化学习（RLHF）在使大型语言模型与人类偏好对齐方面取得了显著成就。然而，现有的基于奖励的RLHF方法，如遵循Bradley-Terry模型假设，可能未能充分捕捉人类偏好的复杂性。本文中，我们提出了一种新的博弈论视角下的RLHF方法，通过将问题建模为双人博弈，并引入迭代纳什策略优化（INPO）算法。该算法通过策略自我对抗学习，无需估计单个响应的胜率，从而降低了计算成本。我们在多个基准测试中验证了INPO的有效性，显著超越了现有方法。此外，研究还表明，结合KL正则化能有效提升响应长度控制的性能。

> Reinforcement Learning with Human Feedback (RLHF) has achieved great success in aligning large language models (LLMs) with human preferences. Prevalent RLHF approaches are reward-based, following the Bradley-Terry (BT) model assumption, which may not fully capture the complexity of human preferences. In this paper, we explore RLHF under a general preference framework and approach it from a game-theoretic perspective. Specifically, we formulate the problem as a two-player game and propose a novel algorithm, iterative Nash policy optimization (INPO). The key idea is to let the policy play against itself via no-regret learning, thereby approximating the Nash policy. Unlike previous methods, INPO bypasses the need for estimating the expected win rate for individual responses, which typically incurs high computational or annotation costs. Instead, we introduce a new loss objective that is directly minimized over a preference dataset. We provide theoretical analysis for our approach and demonstrate its effectiveness through experiments on various representative benchmarks. With an LLaMA-3-8B-based SFT model, INPO achieves a 41.5% length-controlled win rate on AlpacaEval 2.0 and a 38.3% win rate on Arena-Hard, showing substantial improvement over the state-of-the-art iterative algorithm [Dong et al., 2024] under the BT model assumption. Additionally, our ablation study highlights the benefits of incorporating KL regularization for response length control.

[Arxiv](https://arxiv.org/abs/2407.00617)