# 填充曼巴：RNN 长上下文建模中的状态崩溃与容量

发布时间：2024年10月09日

`LLM理论` `密码学`

> Stuffed Mamba: State Collapse and State Capacity of RNN-Based Long-Context Modeling

# 摘要

> 循环神经网络 (RNNs) 在处理长序列时，因其线性计算复杂度而比基于 Transformer 的模型更快。然而，现有 RNNs 大多在短序列上训练，长上下文处理效果不佳。本文探讨了 RNNs 处理长上下文的瓶颈，并提出了解决方案。我们发现，RNNs 在长序列上的表现受限于 *状态崩溃* (SC) 和内存容量。通过实验，我们提出了三种方法来缓解 SC，使 Mamba-2 能处理超百万 token。此外，我们还发现 RNNs 在密码检索中的状态容量与状态大小呈指数关系，训练出的 Mamba-2 370M 在 256K 上下文长度上表现优异。这些发现为 RNN 在长上下文建模中的应用带来了希望。

> One essential advantage of recurrent neural networks (RNNs) over transformer-based language models is their linear computational complexity concerning the sequence length, which makes them much faster in handling long sequences during inference. However, most publicly available RNNs (e.g., Mamba and RWKV) are trained on sequences with less than 10K tokens, and their effectiveness in longer contexts remains largely unsatisfying so far. In this paper, we study the cause of the inability to process long context for RNNs and suggest critical mitigations. We examine two practical concerns when applying state-of-the-art RNNs to long contexts: (1) the inability to extrapolate to inputs longer than the training length and (2) the upper bound of memory capacity. Addressing the first concern, we first investigate *state collapse* (SC), a phenomenon that causes severe performance degradation on sequence lengths not encountered during training. With controlled experiments, we attribute this to overfitting due to the recurrent state being overparameterized for the training length. For the second concern, we train a series of Mamba-2 models on long documents to empirically estimate the recurrent state capacity in language modeling and passkey retrieval. Then, three SC mitigation methods are proposed to improve Mamba-2's length generalizability, allowing the model to process more than 1M tokens without SC. We also find that the recurrent state capacity in passkey retrieval scales exponentially to the state size, and we empirically train a Mamba-2 370M with near-perfect passkey retrieval accuracy on 256K context length. This suggests a promising future for RNN-based long-context modeling.

[Arxiv](https://arxiv.org/abs/2410.07145)