# HSR 增强的稀疏注意力加速

发布时间：2024年10月14日

`LLM理论` `人工智能`

> HSR-Enhanced Sparse Attention Acceleration

# 摘要

> 大型语言模型 (LLM) 在多种应用中表现出色，但在长上下文任务中，其性能常受限于注意力机制的计算复杂性。本文提出了一种新方法，通过利用注意力机制的固有稀疏性，显著加速 LLM 中的注意力计算，尤其是在长上下文场景中。我们采用半空间报告 (HSR) 数据结构，快速识别注意力矩阵中的非零或“大规模激活”条目。理论分析表明，我们的方法在注意力生成和长输入上下文的全注意力计算中，运行时间分别为 $O(mn^{4/5})$ 和 $O(mn^{1 - 1 / \lfloor d/2\rfloor} + mn^{4/5})$，显著优于朴素方法 $O(mn)$。此外，我们的方法对 ReLU 注意力无误差，对 Softmax 注意力仅引入微小误差，并得到实证验证。这项研究为 LLM 在长上下文任务中的高效处理开辟了新路径，有望扩展其在各领域的应用。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across various applications, but their performance on long-context tasks is often limited by the computational complexity of attention mechanisms. This paper introduces a novel approach to accelerate attention computation in LLMs, particularly for long-context scenarios. We leverage the inherent sparsity within attention mechanisms, both in conventional Softmax attention and ReLU attention (with $\mathsf{ReLU}^α$ activation, $α\in \mathbb{N}_+$), to significantly reduce the running time complexity. Our method employs a Half-Space Reporting (HSR) data structure to rapidly identify non-zero or "massively activated" entries in the attention matrix. We present theoretical analyses for two key scenarios: attention generation and full attention computation with long input context. Our approach achieves a running time of $O(mn^{4/5})$ significantly faster than the naive approach $O(mn)$ for attention generation, where $n$ is the context length, $m$ is the query length, and $d$ is the hidden dimension. We can also reduce the running time of full attention computation from $O(mn)$ to $O(mn^{1 - 1 / \lfloor d/2\rfloor} + mn^{4/5})$. Importantly, our method introduces no error for ReLU attention and only provably negligible error for Softmax attention, where the latter is supported by our empirical validation. This work represents a significant step towards enabling efficient long-context processing in LLMs, potentially broadening their applicability across various domains.

[Arxiv](https://arxiv.org/abs/2410.10165)