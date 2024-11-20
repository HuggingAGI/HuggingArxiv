# 借助负特征值实现线性 RNN 中的状态跟踪解锁

发布时间：2024年11月19日

`LLM理论` `语言建模` `状态跟踪`

> Unlocking State-Tracking in Linear RNNs Through Negative Eigenvalues

# 摘要

> 线性循环神经网络（LRNNs），像 Mamba、RWKV、GLA、mLSTM 和 DeltaNet 等，已成为大型语言建模中 Transformer 的高效替代品，具备序列长度线性缩放和训练效率提升的优势。但 LRNNs 在状态跟踪上存在短板，可能影响诸如代码评估或象棋游戏跟踪等任务的表现。哪怕是最简单的状态跟踪任务——偶校验，像 LSTM 这类非线性 RNN 能有效应对，当前的 LRNNs 却无法搞定。近期，Sarrof 等人（2024 年）指出，像 Mamba 这类 LRNNs 解决不了偶校验，是因为把对角状态转移矩阵的值域限定在[0, 1]，引入负值就能解决此问题。我们把这一成果拓展到非对角 LRNNs，其在 DeltaNet 等模型中近来展现出潜力。我们证明，状态转移矩阵仅有正特征值的有限精度 LRNNs 无法解决偶校验，而需要复数特征值才能以 3 为模计数。值得注意的是，我们还证实，当 LRNNs 的状态转移矩阵是单位矩阵减去向量外积矩阵的乘积，且每个特征值在[-1, 1]区间时，它们能够学习任何正则语言。我们的实证结果表明，将 Mamba 和 DeltaNet 等模型的特征值范围扩展到包含负值，不但能让它们解决偶校验，还持续提升了在状态跟踪任务上的性能。此外，用扩展特征值范围对 LRNNs 进行语言建模的预训练，在代码和数学数据方面展现出良好前景的同时，实现了相当的性能和稳定性。我们的工作增强了现代 LRNNs 的表达力，在不改变训练或推理成本的情况下拓展了其适用性。

> Linear Recurrent Neural Networks (LRNNs) such as Mamba, RWKV, GLA, mLSTM, and DeltaNet have emerged as efficient alternatives to Transformers in large language modeling, offering linear scaling with sequence length and improved training efficiency. However, LRNNs struggle to perform state-tracking which may impair performance in tasks such as code evaluation or tracking a chess game. Even parity, the simplest state-tracking task, which non-linear RNNs like LSTM handle effectively, cannot be solved by current LRNNs. Recently, Sarrof et al. (2024) demonstrated that the failure of LRNNs like Mamba to solve parity stems from restricting the value range of their diagonal state-transition matrices to $[0, 1]$ and that incorporating negative values can resolve this issue. We extend this result to non-diagonal LRNNs, which have recently shown promise in models such as DeltaNet. We prove that finite precision LRNNs with state-transition matrices having only positive eigenvalues cannot solve parity, while complex eigenvalues are needed to count modulo $3$. Notably, we also prove that LRNNs can learn any regular language when their state-transition matrices are products of identity minus vector outer product matrices, each with eigenvalues in the range $[-1, 1]$. Our empirical results confirm that extending the eigenvalue range of models like Mamba and DeltaNet to include negative values not only enables them to solve parity but consistently improves their performance on state-tracking tasks. Furthermore, pre-training LRNNs with an extended eigenvalue range for language modeling achieves comparable performance and stability while showing promise on code and math data. Our work enhances the expressivity of modern LRNNs, broadening their applicability without changing the cost of training or inference.

[Arxiv](https://arxiv.org/abs/2411.12537)