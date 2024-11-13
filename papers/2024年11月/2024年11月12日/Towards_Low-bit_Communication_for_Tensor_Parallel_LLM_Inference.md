# 对于张量并行 LLM 推理的低比特通信的研究

发布时间：2024年11月12日

`LLM应用` `服务器` `语言模型`

> Towards Low-bit Communication for Tensor Parallel LLM Inference

# 摘要

> 张量并行提供了一种有效的方法来提高服务器大型语言模型（LLM）的推理效率，尽管会增加额外的通信成本。然而，随着服务器 LLM 的规模不断扩大，它们将需要分布在更多的设备上，从而放大了通信成本。解决这个问题的一种方法是量化，但当前针对 LLM 的方法往往避免对张量并行需要通信的特征进行量化。利用通信特征中的一致异常值，我们引入了一种量化方法，将平均通信值从 16 位减少到 4.2 位，同时几乎保留了所有原始性能。例如，在我们评估的所有任务中，我们的方法分别保持了 Gemma 2 27B 和 Llama 2 13B 约 98.0％和 99.5％的原始性能。

> Tensor parallelism provides an effective way to increase server large language model (LLM) inference efficiency despite adding an additional communication cost. However, as server LLMs continue to scale in size, they will need to be distributed across more devices, magnifying the communication cost. One way to approach this problem is with quantization, but current methods for LLMs tend to avoid quantizing the features that tensor parallelism needs to communicate. Taking advantage of consistent outliers in communicated features, we introduce a quantization method that reduces communicated values on average from 16 bits to 4.2 bits while preserving nearly all of the original performance. For instance, our method maintains around 98.0% and 99.5% of Gemma 2 27B's and Llama 2 13B's original performance, respectively, averaged across all tasks we evaluated on.

[Arxiv](https://arxiv.org/abs/2411.07942)