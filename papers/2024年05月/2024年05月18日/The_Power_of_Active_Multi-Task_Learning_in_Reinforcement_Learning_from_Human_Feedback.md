# 人类反馈强化学习中主动多任务学习的威力

发布时间：2024年05月18日

`LLM理论

这篇论文主要探讨了人类反馈强化学习（RLHF）在大型语言模型中的应用，并提出了一种新的算法来优化多任务表示学习。它涉及了理论层面的研究，如任务相关性的考量、样本复杂度的降低以及表示学习的精妙之处。因此，这篇论文更适合归类于LLM理论，因为它深入探讨了大型语言模型的理论基础和优化方法，而不是直接应用于特定的Agent或RAG系统，也不是关于LLM的具体应用案例。` `机器学习` `人工智能`

> The Power of Active Multi-Task Learning in Reinforcement Learning from Human Feedback

# 摘要

> 人类反馈强化学习（RLHF）已助力大型语言模型性能飞跃。为摆脱对海量标注数据的依赖，多任务表示学习崭露头角，它从多样任务中提炼出精炼的低维表示。本文将RLHF视作上下文决斗式老虎机问题，并假设存在一种通用线性表示。我们揭示，通过考量任务相关性并灵活分配样本量，多任务RLHF的样本复杂度得以降低。进一步，我们提出一种算法，利用少量额外数据估算任务相关性，进而优化策略。理论证明，相较于均匀采样，此法能大幅减少源任务的样本复杂度，且目标任务的样本复杂度仅与潜在空间维度线性相关，这得益于表示学习的精妙。

> Reinforcement learning from human feedback (RLHF) has contributed to performance improvements in large language models. To tackle its reliance on substantial amounts of human-labeled data, a successful approach is multi-task representation learning, which involves learning a high-quality, low-dimensional representation from a wide range of source tasks. In this paper, we formulate RLHF as the contextual dueling bandit problem and assume a common linear representation. We demonstrate that the sample complexity of source tasks in multi-task RLHF can be reduced by considering task relevance and allocating different sample sizes to source tasks with varying task relevance. We further propose an algorithm to estimate task relevance by a small number of additional data and then learn a policy. We prove that to achieve $\varepsilon-$optimal, the sample complexity of the source tasks can be significantly reduced compared to uniform sampling. Additionally, the sample complexity of the target task is only linear in the dimension of the latent space, thanks to representation learning.

[Arxiv](https://arxiv.org/abs/2405.11226)