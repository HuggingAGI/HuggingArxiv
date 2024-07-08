# LoCo：专为大规模模型训练设计的低比特通信适配器

发布时间：2024年07月05日

`LLM理论` `人工智能` `云计算`

> LoCo: Low-Bit Communication Adaptor for Large-scale Model Training

# 摘要

> 为了提升大规模模型的训练效率，我们引入了低比特通信适配器（LoCo），通过在压缩前补偿本地GPU节点的梯度，确保高效的梯度同步且不牺牲训练质量。LoCo利用历史补偿误差的移动平均来精确估计并补偿当前的梯度压缩误差，从而实现更高效的压缩。这一创新机制不仅兼容Adam等通用优化器，还适用于FSDP等分片策略。理论与实验双重验证显示，LoCo在不影响收敛速度的前提下，大幅提升了通信效率，例如在大型语言模型训练中，将Adam的训练速度提升了14%至40%，且性能未受影响。

> To efficiently train large-scale models, low-bit gradient communication compresses full-precision gradients on local GPU nodes into low-precision ones for higher gradient synchronization efficiency among GPU nodes. However, it often degrades training quality due to compression information loss. To address this, we propose the Low-bit Communication Adaptor (LoCo), which compensates gradients on local GPU nodes before compression, ensuring efficient synchronization without compromising training quality. Specifically, LoCo designs a moving average of historical compensation errors to stably estimate concurrent compression error and then adopts it to compensate for the concurrent gradient compression, yielding a less lossless compression. This mechanism allows it to be compatible with general optimizers like Adam and sharding strategies like FSDP. Theoretical analysis shows that integrating LoCo into full-precision optimizers like Adam and SGD does not impair their convergence speed on nonconvex problems. Experimental results show that across large-scale model training frameworks like Megatron-LM and PyTorch's FSDP, LoCo significantly improves communication efficiency, e.g., improving Adam's training speed by 14% to 40% without performance degradation on large language models like LLAMAs and MoE.

[Arxiv](https://arxiv.org/abs/2407.04480)