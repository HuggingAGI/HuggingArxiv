# 利用大型语言模型进行零-shot 模型强化学习

发布时间：2024年10月15日

`LLM应用` `人工智能`

> Zero-shot Model-based Reinforcement Learning using Large Language Models

# 摘要

> 大型语言模型 (LLM) 的零-shot 能力不仅限于自然语言处理，还扩展到了强化学习等领域。尽管 LLM 在文本环境中应用广泛，但与连续状态空间的结合仍待深入研究。本文探讨了如何利用预训练 LLM 预测连续马尔可夫决策过程的动态，并提出了 Disentangled In-Context Learning (DICL) 来应对处理多变量数据和整合控制信号的挑战。我们在基于模型的策略评估和数据增强的离策略强化学习中展示了 DICL 的应用，并提供了理论分析。实验表明，DICL 能生成准确的不确定性估计。代码已发布在 https://github.com/abenechehab/dicl。

> The emerging zero-shot capabilities of Large Language Models (LLMs) have led to their applications in areas extending well beyond natural language processing tasks. In reinforcement learning, while LLMs have been extensively used in text-based environments, their integration with continuous state spaces remains understudied. In this paper, we investigate how pre-trained LLMs can be leveraged to predict in context the dynamics of continuous Markov decision processes. We identify handling multivariate data and incorporating the control signal as key challenges that limit the potential of LLMs' deployment in this setup and propose Disentangled In-Context Learning (DICL) to address them. We present proof-of-concept applications in two reinforcement learning settings: model-based policy evaluation and data-augmented off-policy reinforcement learning, supported by theoretical analysis of the proposed methods. Our experiments further demonstrate that our approach produces well-calibrated uncertainty estimates. We release the code at https://github.com/abenechehab/dicl.

[Arxiv](https://arxiv.org/abs/2410.11711)