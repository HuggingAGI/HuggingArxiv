# 人类反馈强化学习中主动多任务学习的威力

发布时间：2024年05月18日

`LLM理论

理由：这篇论文主要探讨了如何通过多任务表示学习方法来优化从人类反馈中进行强化学习（RLHF）的过程，以减少对大量人类标记数据的依赖。它将RLHF视为上下文双臂老虎机问题，并研究了如何通过评估任务相关性和调整源任务的样本量来降低样本复杂度。这些内容更多地涉及大型语言模型（LLM）的理论和算法优化，而不是具体的应用、Agent行为或RAG（检索增强生成）技术。因此，将其归类为LLM理论是合适的。`

> The Power of Active Multi-Task Learning in Reinforcement Learning from Human Feedback

# 摘要

> 从人类反馈中进行强化学习（RLHF）已显著提升大型语言模型的性能。为减少对大量人类标记数据的依赖，我们采用多任务表示学习方法，从多样的源任务中提取高质量、低维度的表示。本文将RLHF视为上下文双臂老虎机问题，并采用共同的线性表示。我们发现，通过评估任务相关性并根据相关性调整源任务的样本量，可以有效降低多任务RLHF中源任务的样本复杂度。此外，我们提出一种算法，利用少量额外数据估计任务相关性，进而优化策略。研究表明，与均匀采样相比，这种方法能大幅减少源任务的样本复杂度，同时目标任务的样本复杂度仅与潜在空间维度成线性关系，这得益于表示学习的优势。

> Reinforcement learning from human feedback (RLHF) has contributed to performance improvements in large language models. To tackle its reliance on substantial amounts of human-labeled data, a successful approach is multi-task representation learning, which involves learning a high-quality, low-dimensional representation from a wide range of source tasks. In this paper, we formulate RLHF as the contextual dueling bandit problem and assume a common linear representation. We demonstrate that the sample complexity of source tasks in multi-task RLHF can be reduced by considering task relevance and allocating different sample sizes to source tasks with varying task relevance. We further propose an algorithm to estimate task relevance by a small number of additional data and then learn a policy. We prove that to achieve $\varepsilon-$optimal, the sample complexity of the source tasks can be significantly reduced compared to uniform sampling. Additionally, the sample complexity of the target task is only linear in the dimension of the latent space, thanks to representation learning.

[Arxiv](https://arxiv.org/abs/2405.11226)