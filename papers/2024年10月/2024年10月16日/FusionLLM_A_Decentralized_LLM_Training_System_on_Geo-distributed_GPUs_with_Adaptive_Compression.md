# FusionLLM：一款基于地理分布 GPU 的自适应压缩分散式 LLM 训练系统

发布时间：2024年10月16日

`LLM理论` `人工智能` `云计算`

> FusionLLM: A Decentralized LLM Training System on Geo-distributed GPUs with Adaptive Compression

# 摘要

> 为了解决训练大型深度神经网络（尤其是大型语言模型）时硬件资源不足的问题，我们推出了 FusionLLM，一个利用地理分布的 GPU 在不同计算集群或个人设备上进行分布式训练的系统。分布式训练面临诸多挑战，如远程自动微分需求、模型定义的灵活性、异构硬件导致的资源利用率低以及网络通信缓慢。为此，我们将模型表示为运算符的有向无环图，用户可自定义 DNN 而无需关注底层实现，并通过细粒度子任务调度提供更多优化空间。此外，我们设计了工作负载估计器和 OP-Fence 调度器，以提高系统效率。实验证明，我们的系统在确保收敛的同时，比基线方法提速 1.45 至 9.39 倍。

> To alleviate hardware scarcity in training large deep neural networks (DNNs), particularly large language models (LLMs), we present FusionLLM, a decentralized training system designed and implemented for training DNNs using geo-distributed GPUs across different computing clusters or individual devices. Decentralized training faces significant challenges regarding system design and efficiency, including: 1) the need for remote automatic differentiation (RAD), 2) support for flexible model definitions and heterogeneous software, 3) heterogeneous hardware leading to low resource utilization or the straggler problem, and 4) slow network communication. To address these challenges, in the system design, we represent the model as a directed acyclic graph of operators (OP-DAG). Each node in the DAG represents the operator in the DNNs, while the edge represents the data dependency between operators. Based on this design, 1) users are allowed to customize any DNN without caring low-level operator implementation; 2) we enable the task scheduling with the more fine-grained sub-tasks, offering more optimization space; 3) a DAG runtime executor can implement RAD withour requiring the consistent low-level ML framework versions.
  To enhance system efficiency, we implement a workload estimator and design an OP-Fence scheduler to cluster devices with similar bandwidths together and partition the DAG to increase throughput. Additionally, we propose an AdaTopK compressor to adaptively compress intermediate activations and gradients at the slowest communication links. To evaluate the convergence and efficiency of our system and algorithms, we train ResNet-101 and GPT-2 on three real-world testbeds using 48 GPUs connected with 8 Mbps~10 Gbps networks. Experimental results demonstrate that our system and method can achieve 1.45 - 9.39x speedup compared to baseline methods while ensuring convergence.

[Arxiv](https://arxiv.org/abs/2410.12707)