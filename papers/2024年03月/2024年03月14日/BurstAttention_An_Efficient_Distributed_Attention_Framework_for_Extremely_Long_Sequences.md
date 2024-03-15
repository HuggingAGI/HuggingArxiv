# [BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](https://arxiv.org/abs/2403.09347)

发布时间：2024年03月14日

`LLM理论`

``

`分布式计算`

> BurstAttention: An Efficient Distributed Attention Framework for Extremely Long Sequences

> 注意力机制对于Transformer类LLMs的成功至关重要，但其对长序列处理的时间与内存消耗呈平方级增长，带来了难题。为解决这一问题，研究者尝试使用分布式集群跨多设备并行计算注意力模块。然而，分布式策略虽有效，却会带来存储局部注意力结果的额外内存开销以及整合局部结果所需的额外通信成本。本文创新性地提出了“BurstAttention”分布式注意力框架，它着力于从全局集群到单个设备层面优化内存访问和通信效率。实验中，我们对比了BurstAttention与其他适用于长序列处理的分布式注意力方案，并发现BurstAttention在处理长序列任务时表现卓越：相比于竞争对手，它能减少高达40%的通信开销，并在8块A100显卡上训练32K长度序列时实现两倍的速度提升。

> Effective attention modules have played a crucial role in the success of Transformer-based large language models (LLMs), but the quadratic time and memory complexities of these attention modules also pose a challenge when processing long sequences. One potential solution for the long sequence problem is to utilize distributed clusters to parallelize the computation of attention modules across multiple devices (e.g., GPUs). However, adopting a distributed approach inevitably introduces extra memory overheads to store local attention results and incurs additional communication costs to aggregate local results into global ones. In this paper, we propose a distributed attention framework named ``BurstAttention'' to optimize memory access and communication operations at both the global cluster and local device levels. In our experiments, we compare BurstAttention with other competitive distributed attention solutions for long sequence processing. The experimental results under different length settings demonstrate that BurstAttention offers significant advantages for processing long sequences compared with these competitive baselines, reducing 40% communication overheads and achieving 2 X speedup during training 32K sequence length on 8 X A100.

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x1.png)

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x2.png)

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x3.png)

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x4.png)

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x5.png)

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x6.png)

![BurstAttention，这是一种专为处理超长序列而设计的高效分布式注意力机制框架。](../../../paper_images/2403.09347/x7.png)