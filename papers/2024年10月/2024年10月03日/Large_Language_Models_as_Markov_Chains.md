# 大型语言模型：马尔可夫链视角

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Large Language Models as Markov Chains

# 摘要

> 大型语言模型 (LLM) 在 NLP 任务及更广泛领域中表现卓越，但其性能的理论根源仍未完全揭示。本文通过将自回归语言模型与马尔可夫链等价，探索了 LLM 的推理能力、收敛速度及温度影响等关键问题。我们不仅证明了预训练和上下文泛化的理论边界，还通过实验验证了这些理论在实际 LLM 中的应用。

> Large language models (LLMs) have proven to be remarkably efficient, both across a wide range of natural language processing tasks and well beyond them. However, a comprehensive theoretical analysis of the origins of their impressive performance remains elusive. In this paper, we approach this challenging task by drawing an equivalence between generic autoregressive language models with vocabulary of size $T$ and context window of size $K$ and Markov chains defined on a finite state space of size $\mathcal{O}(T^K)$. We derive several surprising findings related to the existence of a stationary distribution of Markov chains that capture the inference power of LLMs, their speed of convergence to it, and the influence of the temperature on the latter. We then prove pre-training and in-context generalization bounds and show how the drawn equivalence allows us to enrich their interpretation. Finally, we illustrate our theoretical guarantees with experiments on several recent LLMs to highlight how they capture the behavior observed in practice.

[Arxiv](https://arxiv.org/abs/2410.02724)