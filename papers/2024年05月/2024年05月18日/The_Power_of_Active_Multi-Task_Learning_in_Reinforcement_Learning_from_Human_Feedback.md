# 人类反馈强化学习中主动多任务学习的威力

发布时间：2024年05月18日

`LLM理论

理由：这篇论文主要探讨了如何通过多任务表示学习来优化人类反馈强化学习（RLHF）在大型语言模型中的应用，特别是在降低样本复杂度和提高性能方面。论文将RLHF视为一个上下文对决式赌博机问题，并研究了如何通过任务相关性和表示学习来优化这一过程。这些内容更多地涉及LLM的理论和方法论层面，而不是具体的应用或Agent的设计，因此归类为LLM理论。` `人工智能` `机器学习`

> The Power of Active Multi-Task Learning in Reinforcement Learning from Human Feedback

# 摘要

> 人类反馈强化学习（RLHF）助力大型语言模型性能提升，但依赖大量人类标注数据是其瓶颈。多任务表示学习为此提供了解决方案，它从多源任务中提炼出高质量、低维度的表示。本文将RLHF视为上下文对决式赌博机问题，并采用共同的线性表示。我们发现，通过考虑任务相关性并针对不同相关性的任务调整样本量，可以有效降低多任务RLHF中源任务的样本复杂度。我们还设计了一种算法，利用少量额外数据评估任务相关性，进而优化策略。研究表明，与均匀采样相比，这种方法能大幅减少达到$\varepsilon-$最优所需的样本量，且目标任务的样本复杂度仅与潜在空间维度线性相关，这得益于表示学习的优势。

> Reinforcement learning from human feedback (RLHF) has contributed to performance improvements in large language models. To tackle its reliance on substantial amounts of human-labeled data, a successful approach is multi-task representation learning, which involves learning a high-quality, low-dimensional representation from a wide range of source tasks. In this paper, we formulate RLHF as the contextual dueling bandit problem and assume a common linear representation. We demonstrate that the sample complexity of source tasks in multi-task RLHF can be reduced by considering task relevance and allocating different sample sizes to source tasks with varying task relevance. We further propose an algorithm to estimate task relevance by a small number of additional data and then learn a policy. We prove that to achieve $\varepsilon-$optimal, the sample complexity of the source tasks can be significantly reduced compared to uniform sampling. Additionally, the sample complexity of the target task is only linear in the dimension of the latent space, thanks to representation learning.

[Arxiv](https://arxiv.org/abs/2405.11226)