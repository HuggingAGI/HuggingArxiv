# SeerAttention：让 LLMs 学会内在的稀疏注意力

发布时间：2024年10月17日

`LLM理论` `人工智能`

> SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs

# 摘要

> 注意力机制是现代大型语言模型的核心，但其二次复杂性限制了模型在长上下文中的效率和扩展性。本文提出了一种新的解决方案——SeerAttention，通过学习而非预定义的方式来捕捉注意力稀疏性。SeerAttention 通过一个可学习的门控机制，自适应地选择注意力图中的重要部分，从而在保持准确性的同时大幅提升计算效率。实验结果显示，SeerAttention 在训练后阶段和长上下文微调中均表现优异，尤其是在与 YaRN 结合时，能够在 32k 上下文长度下实现 90% 的稀疏比率，并提供 5.67 倍的加速效果。

> Attention is the cornerstone of modern Large Language Models (LLMs). Yet its quadratic complexity limits the efficiency and scalability of LLMs, especially for those with a long-context window. A promising approach addressing this limitation is to leverage the sparsity in attention. However, existing sparsity-based solutions predominantly rely on predefined patterns or heuristics to approximate sparsity. This practice falls short to fully capture the dynamic nature of attention sparsity in language-based tasks. This paper argues that attention sparsity should be learned rather than predefined. To this end, we design SeerAttention, a new Attention mechanism that augments the conventional attention with a learnable gate that adaptively selects significant blocks in an attention map and deems the rest blocks sparse. Such block-level sparsity effectively balances accuracy and speedup. To enable efficient learning of the gating network, we develop a customized FlashAttention implementation that extracts the block-level ground truth of attention map with minimum overhead. SeerAttention not only applies to post-training, but also excels in long-context fine-tuning. Our results show that at post-training stages, SeerAttention significantly outperforms state-of-the-art static or heuristic-based sparse attention methods, while also being more versatile and flexible to adapt to varying context lengths and sparsity ratios. When applied to long-context fine-tuning with YaRN, SeerAttention can achieve a remarkable 90% sparsity ratio at a 32k context length with minimal perplexity loss, offering a 5.67x speedup over FlashAttention-2.

[Arxiv](https://arxiv.org/abs/2410.13276)