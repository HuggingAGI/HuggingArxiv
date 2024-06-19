# 利用多目标奖励建模与专家混合策略，揭示偏好之可解释性

发布时间：2024年06月18日

`Agent

这篇论文主要讨论了人类反馈强化学习（RLHF）在大型语言模型（LLMs）中的应用，特别是在与人类偏好对齐方面的技术。论文提出了一种两阶段方法，通过训练一个多维绝对评分模型ArmoRM，并结合专家混合策略来提高模型的解释性和适应性。这种方法可以被视为一种智能代理（Agent），因为它能够根据上下文自动选择最合适的奖励目标，从而更好地模拟人类偏好。因此，这篇论文更适合归类为Agent。` `人工智能` `语言模型`

> Interpretable Preferences via Multi-Objective Reward Modeling and Mixture-of-Experts

# 摘要

> 人类反馈强化学习（RLHF）已成为大型语言模型（LLMs）与人类偏好对齐的关键技术。该过程首先通过人类偏好数据训练奖励模型（RM），传统上基于成对响应的相对评分进行。尽管RM作为人类偏好的代理，但其黑盒特性导致输出难以解释，人类难以理解其评价依据。因此，我们提出了一种两阶段方法：首先，训练一个多维绝对评分模型ArmoRM，每个维度代表一个人类可解释的目标；其次，采用专家混合策略，通过门控网络根据上下文自动选择最合适的奖励目标。我们的模型ArmoRM-Llama3-8B在RewardBench上表现卓越，不仅超越了GPT-4评判的LLM-as-a-judge方法，还接近了巨型Nemotron-4 340B奖励模型的性能。

> Reinforcement learning from human feedback (RLHF) has emerged as the primary method for aligning large language models (LLMs) with human preferences. The RLHF process typically starts by training a reward model (RM) using human preference data. Conventional RMs are trained on pairwise responses to the same user request, with relative ratings indicating which response humans prefer. The trained RM serves as a proxy for human preferences. However, due to the black-box nature of RMs, their outputs lack interpretability, as humans cannot intuitively understand why an RM thinks a response is good or not. As RMs act as human preference proxies, we believe they should be human-interpretable to ensure that their internal decision processes are consistent with human preferences and to prevent reward hacking in LLM alignment. To build RMs with interpretable preferences, we propose a two-stage approach: i) train an Absolute-Rating Multi-Objective Reward Model (ArmoRM) with multi-dimensional absolute-rating data, each dimension corresponding to a human-interpretable objective (e.g., honesty, verbosity, safety); ii) employ a Mixture-of-Experts (MoE) strategy with a gating network that automatically selects the most suitable reward objectives based on the context. We efficiently trained an ArmoRM with Llama-3 8B and a gating network consisting of a shallow MLP on top of the ArmoRM. Our trained model, ArmoRM-Llama3-8B, obtains state-of-the-art performance on RewardBench, a benchmark evaluating RMs for language modeling. Notably, the performance of our model surpasses the LLM-as-a-judge method with GPT-4 judges by a margin, and approaches the performance of the much larger Nemotron-4 340B reward model.

![利用多目标奖励建模与专家混合策略，揭示偏好之可解释性](../../../paper_images/2406.12845/x1.png)

[Arxiv](https://arxiv.org/abs/2406.12845)