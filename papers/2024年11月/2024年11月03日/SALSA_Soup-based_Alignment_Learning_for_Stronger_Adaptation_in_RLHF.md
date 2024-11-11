# SALSA：用于强化学习中的人类反馈强化学习（RLHF）中更强适应能力的基于汤的对齐学习

发布时间：2024年11月03日

`LLM应用` `语言模型`

> SALSA: Soup-based Alignment Learning for Stronger Adaptation in RLHF

# 摘要

> 在大型语言模型（LLM）的开发中，基于人类反馈的强化学习（RLHF）对于使模型与人类价值观和偏好保持一致至关重要。RLHF 传统上依赖于当前策略和冻结的初始策略之间的 Kullback-Leibler（KL）散度作为参考，该散度在诸如近端策略优化（PPO）等策略优化算法中作为惩罚项添加。虽然此约束可防止模型偏离初始检查点太远，但它限制了对奖励格局的探索，降低了模型发现更高质量解决方案的能力。结果，策略优化常常被困在参数空间的狭窄区域，导致次优的对齐和性能。本文提出了 SALSA（用于更强适应的基于汤的对齐学习），这是一种通过对两个独立的有监督微调（SFT）模型进行权重空间平均来创建更灵活和定位更好的参考模型从而克服这些限制的新方法。这种模型汤允许在 KL 散度中有更大的偏差，并在不牺牲稳定性的情况下探索解决方案空间的有希望的区域。通过利用这个更强大的参考模型，SALSA 促进了更好的探索，实现了更高的奖励，并提高了模型的鲁棒性、分布外泛化和性能。我们通过在各种基准（MT-Bench、Arena-Hard、UltraFeedback）上对流行的开放模型（Llama2-7B、Mistral-7B 和 Gemma-2B）进行广泛实验验证了 SALSA 的有效性，在这些实验中，它通过促进更深入的探索并在 LLM 中实现更优的对齐，始终超越 PPO。

> In Large Language Model (LLM) development, Reinforcement Learning from Human Feedback (RLHF) is crucial for aligning models with human values and preferences. RLHF traditionally relies on the Kullback-Leibler (KL) divergence between the current policy and a frozen initial policy as a reference, which is added as a penalty in policy optimization algorithms like Proximal Policy Optimization (PPO). While this constraint prevents models from deviating too far from the initial checkpoint, it limits exploration of the reward landscape, reducing the model's ability to discover higher-quality solutions. As a result, policy optimization is often trapped in a narrow region of the parameter space, leading to suboptimal alignment and performance. This paper presents SALSA (Soup-based Alignment Learning for Stronger Adaptation), a novel approach designed to overcome these limitations by creating a more flexible and better located reference model through weight-space averaging of two independent supervised fine-tuned (SFT) models. This model soup allows for larger deviation in KL divergence and exploring a promising region of the solution space without sacrificing stability. By leveraging this more robust reference model, SALSA fosters better exploration, achieving higher rewards and improving model robustness, out-of-distribution generalization, and performance. We validate the effectiveness of SALSA through extensive experiments on popular open models (Llama2-7B, Mistral-7B, and Gemma-2B) across various benchmarks (MT-Bench, Arena-Hard, UltraFeedback), where it consistently surpasses PPO by fostering deeper exploration and achieving superior alignment in LLMs.

[Arxiv](https://arxiv.org/abs/2411.01798)