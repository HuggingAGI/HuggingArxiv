# Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。

发布时间：2024年07月05日

`LLM应用` `云计算` `人工智能`

> Lazarus: Resilient and Elastic Training of Mixture-of-Experts Models with Adaptive Expert Placement

# 摘要

> 稀疏激活的混合专家（MoE）架构因其对计算成本的次线性缩放特性，正被广泛用于扩展大型语言模型（LLM）。然而，随着训练规模的扩大，频繁的失败问题依然严峻。每一次失败都可能导致所有GPU空闲等待，直至问题解决，进而可能丢失大量训练进度。现有高效容错训练方案或缺乏弹性，或依赖于流水线并行中的弹性构建，但这些方案因MoE架构的专家并行策略而无法适用。为此，我们推出了Lazarus系统，专为MoE模型的弹性训练设计。Lazarus通过自适应分配专家副本，有效应对专家工作负载的不平衡，并加速训练进程。同时，我们开发了一种最优专家放置算法，以最大化失败时的恢复概率。借助自适应专家放置和灵活的令牌调度器，Lazarus能在失败后充分利用所有可用节点，确保无GPU空闲。评估结果表明，在频繁节点失败和真实现货实例环境下，Lazarus的性能分别比现有MoE训练系统高出5.7倍和3.4倍。

> Sparsely-activated Mixture-of-Experts (MoE) architecture has increasingly been adopted to further scale large language models (LLMs) due to its sub-linear scaling for computation costs. However, frequent failures still pose significant challenges as training scales. The cost of even a single failure is significant, as all GPUs need to wait idle until the failure is resolved, potentially losing considerable training progress as training has to restart from checkpoints. Existing solutions for efficient fault-tolerant training either lack elasticity or rely on building resiliency into pipeline parallelism, which cannot be applied to MoE models due to the expert parallelism strategy adopted by the MoE architecture.
  We present Lazarus, a system for resilient and elastic training of MoE models. Lazarus adaptively allocates expert replicas to address the inherent imbalance in expert workload and speeds-up training, while a provably optimal expert placement algorithm is developed to maximize the probability of recovery upon failures. Through adaptive expert placement and a flexible token dispatcher, Lazarus can also fully utilize all available nodes after failures, leaving no GPU idle. Our evaluation shows that Lazarus outperforms existing MoE training systems by up to 5.7x under frequent node failures and 3.4x on a real spot instance trace.

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x1.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x2.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x3.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x4.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x5.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x6.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x7.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x8.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x9.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x10.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x11.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x12.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x13.png)

![Lazarus：通过自适应专家部署，实现混合专家模型的弹性与韧性训练。](../../../paper_images/2407.04656/x14.png)

[Arxiv](https://arxiv.org/abs/2407.04656)