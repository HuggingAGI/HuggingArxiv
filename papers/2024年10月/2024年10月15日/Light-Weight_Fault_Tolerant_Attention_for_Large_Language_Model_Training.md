# 轻量级容错注意力机制助力大型语言模型训练

发布时间：2024年10月15日

`LLM理论` `人工智能`

> Light-Weight Fault Tolerant Attention for Large Language Model Training

# 摘要

> 大型语言模型（LLM）在自然语言处理任务中表现出色，但其训练过程复杂且易出错，尤其是在关键的注意力机制中。本文探讨了故障对 LLM 训练的影响，特别是 INF、NaN 和近 INF 值的传播模式，这些错误可能导致训练中断，需从检查点恢复。为应对这一挑战，我们推出了 ATTNChecker，首个专为 LLM 注意力机制设计的基于算法的容错技术。ATTNChecker 不仅优化了性能，还为快速训练提供了轻量级保护，平均仅增加 7% 的训练开销，却能有效检测并纠正所有极端错误。与现有技术相比，ATTNChecker 将恢复开销大幅降低了 49 倍。

> Large Language Models (LLMs) have demonstrated remarkable performance in various natural language processing tasks. However, the training of these models is computationally intensive and susceptible to faults, particularly in the attention mechanism, which is a critical component of transformer-based LLMs. In this paper, we investigate the impact of faults on LLM training, focusing on INF, NaN, and near-INF values in the computation results with systematic fault injection experiments. We observe the propagation patterns of these errors, which can trigger non-trainable states in the model and disrupt training, forcing the procedure to load from checkpoints.To mitigate the impact of these faults, we propose ATTNChecker, the first Algorithm-Based Fault Tolerance (ABFT) technique tailored for the attention mechanism in LLMs. ATTNChecker is designed based on fault propagation patterns of LLM and incorporates performance optimization to adapt to both system reliability and model vulnerability while providing lightweight protection for fast LLM training. Evaluations on four LLMs show that ATTNChecker on average incurs on average 7% overhead on training while detecting and correcting all extreme errors. Compared with the state-of-the-art checkpoint/restore approach, ATTNChecker reduces recovery overhead by up to 49x.

[Arxiv](https://arxiv.org/abs/2410.11720)