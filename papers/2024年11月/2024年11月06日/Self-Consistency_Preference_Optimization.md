# 自我一致性偏好优化

发布时间：2024年11月06日

`LLM应用` `模型训练`

> Self-Consistency Preference Optimization

# 摘要

> 自我对齐，即模型学会在没有人类注释的情况下自我改进，是一个迅速发展的研究领域。然而，由于难以分配正确的奖励，现有技术往往无法改进复杂的推理任务。一种已知能提高正确性的正交方法是自我一致性，这是一种在推理时基于多次采样应用的方法，以找到最一致的答案。在这项工作中，我们扩展了自我一致性的概念来帮助训练模型。因此，我们引入了自我一致性偏好优化（ScPO），它迭代地训练一致的答案，使其在无监督的新问题上比不一致的答案更受青睐。我们表明，在诸如 GSM8K 和 MATH 等推理任务上，ScPO 相对于传统的奖励模型训练有很大的改进，缩小了与有黄金答案或偏好的监督训练的差距，并且将 ScPO 与标准监督学习相结合进一步提高了结果。在 ZebraLogic 上，ScPO 微调的 Llama-3 8B 优于 Llama-3 70B、Gemma-2 27B 和 Claude-3 Haiku。

> Self-alignment, whereby models learn to improve themselves without human annotation, is a rapidly growing research area. However, existing techniques often fail to improve complex reasoning tasks due to the difficulty of assigning correct rewards. An orthogonal approach that is known to improve correctness is self-consistency, a method applied at inference time based on multiple sampling in order to find the most consistent answer. In this work, we extend the self-consistency concept to help train models. We thus introduce self-consistency preference optimization (ScPO), which iteratively trains consistent answers to be preferred over inconsistent ones on unsupervised new problems. We show ScPO leads to large improvements over conventional reward model training on reasoning tasks such as GSM8K and MATH, closing the gap with supervised training with gold answers or preferences, and that combining ScPO with standard supervised learning improves results even further. On ZebraLogic, ScPO finetunes Llama-3 8B to be superior to Llama-3 70B, Gemma-2 27B, and Claude-3 Haiku.

[Arxiv](https://arxiv.org/abs/2411.04109)