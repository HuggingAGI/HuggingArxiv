# 大型语言模型对齐的离线正则化强化学习

发布时间：2024年05月29日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）的对齐问题，并提出了一个新的框架DRO（直接奖励优化），用于优化模型性能。这个研究关注的是LLM的理论和方法改进，特别是如何利用单轨迹数据集进行模型优化，而不是具体的应用场景或Agent的行为。因此，它更符合LLM理论的分类。` `人工智能` `语言模型`

> Offline Regularised Reinforcement Learning for Large Language Models Alignment

# 摘要

> 大型语言模型（LLM）的对齐主要依赖于从偏好数据中学习，这些数据通常由一个提示、两个独立响应以及人类对这两个响应的偏好组成，但这类数据稀缺且成本高。相比之下，包含提示、响应和人类反馈的单轨迹数据集则更为丰富。在本研究中，我们提出了DRO（直接奖励优化）框架，该框架无需成对偏好，采用简单的均方目标，并可通过多种方式实施。通过使用T5编码器-解码器语言模型进行的实证研究，我们验证了DRO的有效性，并展示了其在特定基准（如卡尼曼-特维斯基优化）上的优越性能。因此，DRO被证实为单轨迹策略优化的简单而有效的解决方案。

> The dominant framework for alignment of large language models (LLM), whether through reinforcement learning from human feedback or direct preference optimisation, is to learn from preference data. This involves building datasets where each element is a quadruplet composed of a prompt, two independent responses (completions of the prompt) and a human preference between the two independent responses, yielding a preferred and a dis-preferred response. Such data is typically scarce and expensive to collect. On the other hand, \emph{single-trajectory} datasets where each element is a triplet composed of a prompt, a response and a human feedback is naturally more abundant. The canonical element of such datasets is for instance an LLM's response to a user's prompt followed by a user's feedback such as a thumbs-up/down. Consequently, in this work, we propose DRO, or \emph{Direct Reward Optimisation}, as a framework and associated algorithms that do not require pairwise preferences. DRO uses a simple mean-squared objective that can be implemented in various ways. We validate our findings empirically, using T5 encoder-decoder language models, and show DRO's performance over selected baselines such as Kahneman-Tversky Optimization (KTO). Thus, we confirm that DRO is a simple and empirically compelling method for single-trajectory policy optimisation.

[Arxiv](https://arxiv.org/abs/2405.19107)