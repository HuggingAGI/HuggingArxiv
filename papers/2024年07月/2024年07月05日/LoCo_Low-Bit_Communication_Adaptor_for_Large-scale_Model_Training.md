# LoCo：专为大规模模型训练设计的低比特通信适配器

发布时间：2024年07月05日

`LLM理论` `计算机科学` `人工智能`

> LoCo: Low-Bit Communication Adaptor for Large-scale Model Training

# 摘要

> 为了提升大规模模型的训练效率，我们引入了低比特通信适配器（LoCo），通过在压缩前补偿本地GPU节点的梯度，确保高效的梯度同步且不牺牲训练质量。LoCo利用历史补偿误差的移动平均值来稳定估计并补偿当前梯度压缩，实现了更优的压缩效果。这一创新机制不仅与通用优化器和分片策略兼容，还通过理论分析证实了其对优化器收敛速度的正面影响。实验证明，LoCo在大规模模型训练中显著提升了通信效率，例如，在不影响性能的前提下，将Adam的训练速度提升了14%至40%。

> To efficiently train large-scale models, low-bit gradient communication compresses full-precision gradients on local GPU nodes into low-precision ones for higher gradient synchronization efficiency among GPU nodes. However, it often degrades training quality due to compression information loss. To address this, we propose the Low-bit Communication Adaptor (LoCo), which compensates gradients on local GPU nodes before compression, ensuring efficient synchronization without compromising training quality. Specifically, LoCo designs a moving average of historical compensation errors to stably estimate concurrent compression error and then adopts it to compensate for the concurrent gradient compression, yielding a less lossless compression. This mechanism allows it to be compatible with general optimizers like Adam and sharding strategies like FSDP. Theoretical analysis shows that integrating LoCo into full-precision optimizers like Adam and SGD does not impair their convergence speed on nonconvex problems. Experimental results show that across large-scale model training frameworks like Megatron-LM and PyTorch's FSDP, LoCo significantly improves communication efficiency, e.g., improving Adam's training speed by 14% to 40% without performance degradation on large language models like LLAMAs and MoE.

[Arxiv](https://arxiv.org/abs/2407.04480)