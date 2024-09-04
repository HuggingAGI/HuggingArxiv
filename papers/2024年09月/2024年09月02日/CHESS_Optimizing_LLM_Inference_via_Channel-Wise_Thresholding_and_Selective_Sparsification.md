# CHESS：利用通道阈值化和选择性稀疏化技术，优化大型语言模型的推理性能。

发布时间：2024年09月02日

`LLM应用` `边缘计算` `人工智能`

> CHESS: Optimizing LLM Inference via Channel-Wise Thresholding and Selective Sparsification

# 摘要

> 在边缘设备上部署大型语言模型（LLM）面临巨大计算和内存挑战。激活稀疏化通过减少激活神经元数量来缓解这些问题。现有方法虽基于激活张量统计进行阈值稀疏化，但未明确考虑其对性能的影响，导致性能下降不理想。为此，本文引入新目标优化稀疏化决策，提出CHESS方法，通过通道级阈值和选择性稀疏化实现通用激活稀疏化。该方法首先为前馈网络层中每个激活通道设定独特阈值，然后在注意力模块特定层应用基于阈值的稀疏化。此外，详细实现稀疏内核以加速LLM推理。实验显示，CHESS在8个下游任务中性能下降更少，参数激活更少，推理速度提升高达1.27倍。

> Deploying large language models (LLMs) on edge devices presents significant challenges due to the substantial computational overhead and memory requirements. Activation sparsification can mitigate these challenges by reducing the number of activated neurons during inference. Existing methods typically employ thresholding-based sparsification based on the statistics of activation tensors. However, these methods do not explicitly model the impact of activation sparsification on performance, leading to suboptimal performance degradation. To address this issue, this paper reformulates the activation sparsification problem by introducing a new objective that optimizes the sparsification decisions. Building on this reformulation, we propose CHESS, a general activation sparsification approach via CHannel-wise thrEsholding and Selective Sparsification. First, channel-wise thresholding assigns a unique threshold to each activation channel in the feed-forward network (FFN) layers. Then, selective sparsification involves applying thresholding-based activation sparsification to specific layers within the attention modules. Finally, we detail the implementation of sparse kernels to accelerate LLM inference. Experimental results demonstrate that the proposed CHESS achieves lower performance degradation over 8 downstream tasks while activating fewer parameters compared to existing methods, thus speeding up the LLM inference by up to 1.27x.

[Arxiv](https://arxiv.org/abs/2409.01366)