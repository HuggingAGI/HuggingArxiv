# 微调DPO拒绝惩罚，增强训练稳定性

发布时间：2024年08月19日

`LLM理论` `人工智能` `机器学习`

> Minor DPO reject penalty to increase training robustness

# 摘要

> 从人类偏好中学习，是一种用于微调大型语言模型（LLM）的方法，旨在更好地匹配人类对特定任务的偏好。以往，这种方法依赖于从人类反馈中进行强化学习（RLHF），以调整模型策略，避免过度偏离原始模型。近期，直接偏好优化（DPO）作为一种简化的无强化学习方法被提出，通过利用选定和拒绝数据的偏好对，将相对对数概率作为隐式奖励函数，直接使用二元交叉熵目标优化模型策略。DPO方法直观易懂，且在多数情况下表现高效。本文深入探讨了DPO中$β$的作用，对比了其与传统RL算法的差异，并指出了DPO简化可能带来的问题。基于这些分析，我们提出了改进版的MinorDPO，它更忠实于原始RL算法，同时增强了偏好优化过程的稳定性。

> Learning from human preference is a paradigm used in large-scale language model (LLM) fine-tuning step to better align pretrained LLM to human preference for downstream task. In the past it uses reinforcement learning from human feedback (RLHF) algorithm to optimize the LLM policy to align with these preferences and not to draft too far from the original model. Recently, Direct Preference Optimization (DPO) has been proposed to solve the alignment problem with a simplified RL-free method. Using preference pairs of chosen and reject data, DPO models the relative log probability as implicit reward function and optimize LLM policy using a simple binary cross entropy objective directly. DPO is quite straight forward and easy to be understood. It perform efficiently and well in most cases. In this article, we analyze the working mechanism of $β$ in DPO, disclose its syntax difference between RL algorithm and DPO, and understand the potential shortage brought by the DPO simplification. With these insights, we propose MinorDPO, which is better aligned to the original RL algorithm, and increase the stability of preference optimization process.

[Arxiv](https://arxiv.org/abs/2408.09834)