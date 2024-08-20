# TBA：通过 SSD 激活卸载技术加速大型语言模型训练

发布时间：2024年08月19日

`LLM理论` `计算机科学`

> TBA: Faster Large Language Model Training Using SSD-Based Activation Offloading

# 摘要

> 随着大型语言模型（LLM）规模的快速增长，GPU内存容量的增长却未能跟上步伐，这严重影响了模型训练的效率。特别是，前向传播中产生的激活张量在GPU内存中占据了大量空间。为此，我们创新性地提出了TBA方法，通过将这些激活高效卸载至NVMe SSD，显著降低了GPU内存的负担。TBA不仅与PyTorch、Megatron等主流深度学习框架兼容，还通过张量去重、转发及自适应卸载等技术，进一步提升了处理效率。实验结果表明，TBA能有效减少高达47%的激活内存峰值使用，同时几乎不影响计算性能。通过引入ROK曲线，我们对比了TBA与其他策略，证实了其在内存节省与性能保持方面的优越性。

> The growth rate of the GPU memory capacity has not been able to keep up with that of the size of large language models (LLMs), hindering the model training process. In particular, activations -- the intermediate tensors produced during forward propagation and reused in backward propagation -- dominate the GPU memory use. To address this challenge, we propose TBA to efficiently offload activations to high-capacity NVMe SSDs. This approach reduces GPU memory usage without impacting performance by adaptively overlapping data transfers with computation. TBA is compatible with popular deep learning frameworks like PyTorch, Megatron, and DeepSpeed, and it employs techniques such as tensor deduplication, forwarding, and adaptive offloading to further enhance efficiency. We conduct extensive experiments on GPT, BERT, and T5. Results demonstrate that TBA effectively reduces 47% of the activation peak memory usage. At the same time, TBA perfectly overlaps the I/O with the computation and incurs negligible performance overhead. We introduce the recompute-offload-keep (ROK) curve to compare the TBA offloading with other two tensor placement strategies, keeping activations in memory and layerwise full recomputation. We find that TBA achieves better memory savings than layerwise full recomputation while retaining the performance of keeping the activations in memory.

[Arxiv](https://arxiv.org/abs/2408.10013)