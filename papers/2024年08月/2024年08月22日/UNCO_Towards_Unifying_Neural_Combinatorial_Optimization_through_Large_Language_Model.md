# UNCO：借助大型语言模型，迈向神经组合优化的统一之路

发布时间：2024年08月22日

`LLM应用` `人工智能`

> UNCO: Towards Unifying Neural Combinatorial Optimization through Large Language Model

# 摘要

> 近期，神经网络在解决组合优化问题 (COPs) 方面的应用备受瞩目。然而，现有方法往往针对特定问题独立训练模型，缺乏一个能同时应对多种 COPs 的统一框架。为此，我们提出了一个名为 UNCO 的统一神经组合优化框架，通过单一模型解决各类 COPs。该框架利用自然语言为不同 COPs 生成文本实例，并借助大型语言模型 (LLM) 在同一嵌入空间中进行编码。这些嵌入通过一个无特定问题模块的编码器-解码器模型得到进一步优化，简化了解决方案的构建过程。此外，我们采用冲突梯度擦除强化学习 (CGERL) 算法训练 UNCO 模型，显著提升了其在不同 COPs 上的性能。实验结果显示，UNCO 模型经过一次训练即可解决多个 COPs，性能与传统或基于学习的基线相当。我们更注重探索任务间的协同效应和基于 LLM 的少样本泛化能力，以期为未来研究提供新思路。

> Recently, applying neural networks to address combinatorial optimization problems (COPs) has attracted considerable research attention. The prevailing methods always train deep models independently on specific problems, lacking a unified framework for concurrently tackling various COPs. To this end, we propose a unified neural combinatorial optimization (UNCO) framework to solve different types of COPs by a single model. Specifically, we use natural language to formulate text-attributed instances for different COPs and encode them in the same embedding space by the large language model (LLM). The obtained embeddings are further advanced by an encoder-decoder model without any problem-specific modules, thereby facilitating a unified process of solution construction. We further adopt the conflict gradients erasing reinforcement learning (CGERL) algorithm to train the UNCO model, delivering better performance across different COPs than vanilla multi-objective learning. Experiments show that the UNCO model can solve multiple COPs after a single-session training, and achieves satisfactory performance that is comparable to several traditional or learning-based baselines. Instead of pursuing the best performance for each COP, we explore the synergy between tasks and few-shot generalization based on LLM to inspire future work.

[Arxiv](https://arxiv.org/abs/2408.12214)