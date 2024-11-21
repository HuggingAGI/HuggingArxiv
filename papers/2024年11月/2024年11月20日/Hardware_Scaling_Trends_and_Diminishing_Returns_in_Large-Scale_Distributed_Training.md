# 大规模分布式训练中的硬件缩放趋势与收益递减

发布时间：2024年11月20日

`LLM应用` `神经网络` `模型训练`

> Hardware Scaling Trends and Diminishing Returns in Large-Scale Distributed Training

# 摘要

> 近年来，神经网络模型能力的显著增强是由模型规模、训练数据以及相应计算资源的扩充所推动的。要开发像大型语言模型（LLMs）这样现代应用所需的超大型网络，模型训练需分布在数万个硬件加速器（如 GPU）上，这就要求在大型计算集群中协调计算与通信。在本项工作中，我们表明，精心考量硬件配置和并行化策略对于有效（即计算和成本高效）扩展模型规模、训练数据以及总计算量至关重要。我们针对跨模型规模、硬件配置和分布式并行化策略的大规模 LLM 训练工作负载的性能展开了广泛的实证研究。我们证实：（1）超过一定规模后，某些分布式通信策略所产生的开销致使之前被视为次优的并行化策略实际上变得更可取；（2）即便硬件和并行化策略得到恰当优化，为大型模型训练扩充加速器的总数很快就会出现收益递减，意味着每新增一单位功率或 GPU 小时的边际性能欠佳。

> Dramatic increases in the capabilities of neural network models in recent years are driven by scaling model size, training data, and corresponding computational resources. To develop the exceedingly large networks required in modern applications, such as large language models (LLMs), model training is distributed across tens of thousands of hardware accelerators (e.g. GPUs), requiring orchestration of computation and communication across large computing clusters. In this work, we demonstrate that careful consideration of hardware configuration and parallelization strategy is critical for effective (i.e. compute- and cost-efficient) scaling of model size, training data, and total computation. We conduct an extensive empirical study of the performance of large-scale LLM training workloads across model size, hardware configurations, and distributed parallelization strategies. We demonstrate that: (1) beyond certain scales, overhead incurred from certain distributed communication strategies leads parallelization strategies previously thought to be sub-optimal in fact become preferable; and (2) scaling the total number of accelerators for large model training quickly yields diminishing returns even when hardware and parallelization strategies are properly optimized, implying poor marginal performance per additional unit of power or GPU-hour.

[Arxiv](https://arxiv.org/abs/2411.13055)