# 用于深度状态空间模型的层自适应状态修剪

发布时间：2024年11月05日

`其他` `模型优化`

> Layer-Adaptive State Pruning for Deep State Space Models

# 摘要

> 由于缺乏状态维度优化方法，深度状态空间模型（SSMs）为了减轻高状态维度导致的计算成本，牺牲了模型容量、训练搜索空间或稳定性。在这项工作中，我们为 SSMs 提供了一种结构化剪枝方法，即层自适应状态剪枝（LAST），它通过为单个系统扩展模态截断来降低每层的状态维度，以最小化模型级能量损失。LAST 得分使用每个状态和逐层能量归一化的子系统的 $\mathcal{H}_{\infty}$ 范数进行评估。这些得分作为全局剪枝标准，能够实现状态的跨层比较和层自适应剪枝。在各种序列基准测试中，LAST 优化了以前的 SSMs，揭示了它们状态空间的冗余性和可压缩性。值得注意的是，我们证明，在多输入多输出 SSMs 中，平均剪枝 33％的状态仍能保持性能，精度损失为 0.52％，无需重新训练。代码可在 $\href{https://github.com/msgwak/LAST}{	ext{这个 https 网址}}$ 获取。

> Due to the lack of state dimension optimization methods, deep state space models (SSMs) have sacrificed model capacity, training search space, or stability to alleviate computational costs caused by high state dimensions. In this work, we provide a structured pruning method for SSMs, Layer-Adaptive STate pruning (LAST), which reduces the state dimension of each layer in minimizing model-level energy loss by extending modal truncation for a single system. LAST scores are evaluated using $\mathcal{H}_{\infty}$ norms of subsystems for each state and layer-wise energy normalization. The scores serve as global pruning criteria, enabling cross-layer comparison of states and layer-adaptive pruning. Across various sequence benchmarks, LAST optimizes previous SSMs, revealing the redundancy and compressibility of their state spaces. Notably, we demonstrate that, on average, pruning 33% of states still maintains performance with 0.52% accuracy loss in multi-input multi-output SSMs without retraining. Code is available at $\href{https://github.com/msgwak/LAST}{\text{this https URL}}$.

[Arxiv](https://arxiv.org/abs/2411.02824)