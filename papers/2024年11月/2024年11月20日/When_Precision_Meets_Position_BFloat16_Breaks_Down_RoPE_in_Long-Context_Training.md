# 当精度与位置相遇：BFloat16 在长上下文训练中突破 RoPE

发布时间：2024年11月20日

`LLM应用` `计算机技术`

> When Precision Meets Position: BFloat16 Breaks Down RoPE in Long-Context Training

# 摘要

> 扩展上下文窗口的大小，能让大型语言模型（LLMs）处理更长的序列，应对更复杂的任务。旋转位置嵌入（RoPE）因其相对位置编码特性有益于长上下文训练，已成为实际标准。然而，我们发现，采用 BFloat16 格式的 RoPE 会引发数值问题，导致其偏离预期的相对位置编码，在长上下文场景中尤为明显。此问题源于 BFloat16 精度有限，且会随上下文长度增加而累积，其中第一个标记的影响极大。为解决此问题，我们开发了 AnchorAttention，这是一种即插即用的注意力方法，能缓解 BFloat16 导致的数值问题，增强长上下文能力，加快训练速度。AnchorAttention 减少了不必要的注意力计算，保持了语义连贯性，并将第一个标记视作具有一致位置 ID 的共享锚点，使其对训练上下文中的所有文档可见，从而提升了计算效率。在三类 LLMs 上开展的实验表明，与标准的全注意力机制相比，AnchorAttention 显著提升了长上下文性能，训练时间减少 50%以上，同时保留了原始 LLM 在一般任务上的能力。我们的代码可在 https://github.com/haonan3/AnchorContext 获取。

> Extending context window sizes allows large language models (LLMs) to process longer sequences and handle more complex tasks. Rotary Positional Embedding (RoPE) has become the de facto standard due to its relative positional encoding properties that benefit long-context training. However, we observe that using RoPE with BFloat16 format results in numerical issues, causing it to deviate from its intended relative positional encoding, especially in long-context scenarios. This issue arises from BFloat16's limited precision and accumulates as context length increases, with the first token contributing significantly to this problem. To address this, we develop AnchorAttention, a plug-and-play attention method that alleviates numerical issues caused by BFloat16, improves long-context capabilities, and speeds up training. AnchorAttention reduces unnecessary attention computations, maintains semantic coherence, and boosts computational efficiency by treating the first token as a shared anchor with a consistent position ID, making it visible to all documents within the training context. Experiments on three types of LLMs demonstrate that AnchorAttention significantly improves long-context performance and reduces training time by over 50\% compared to standard full attention mechanisms, while preserving the original LLM's capabilities on general tasks. Our code is available at https://github.com/haonan3/AnchorContext.

[Arxiv](https://arxiv.org/abs/2411.13476)