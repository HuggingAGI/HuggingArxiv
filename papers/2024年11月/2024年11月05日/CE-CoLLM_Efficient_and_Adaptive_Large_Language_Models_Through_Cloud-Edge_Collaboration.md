# CE-CoLLM：通过云边协作实现高效和自适应的大型语言模型

发布时间：2024年11月05日

`LLM应用` `云计算` `边缘计算`

> CE-CoLLM: Efficient and Adaptive Large Language Models Through Cloud-Edge Collaboration

# 摘要

> 大型语言模型（LLMs）在为终端用户提供类人智能服务方面取得了显著成功。然而，LLMs 需要大量的计算资源，这使得将它们部署以满足各种性能目标具有挑战性，例如满足靠近终端用户的边缘设备的资源限制，或者在有充足资源的情况下实现高精度。在本文中，我们介绍了 CE-CoLLM，这是一种新颖的云边协作框架，它为边缘的终端用户支持高效和自适应的 LLM 推理，有两种模式：（1）低延迟的边缘独立推理；（2）高精度的云边协同推理。首先，我们表明，在边缘和云之间传输 LLM 上下文信息的固有高通信成本主导了总体延迟，使得使用云边协作部署 LLMs 效率低下且成本高昂。其次，我们提出了几个关键技术来应对这一挑战，包括早期退出机制、云上下文管理器和云边协作中的量化，不仅能够实现低延迟的独立边缘推理，还能为 LLMs 实现高效和自适应的云边协同推理。第三，我们进行了全面的实验分析，结果表明，与流行的基于云的 LLM 部署相比，CE-CoLLM 显著减少了高达 13.81%的推理时间和高达 84.55%的云计算成本，同时保持了相当的模型精度。所提出的方法有效地将计算负载转移到边缘，减少了通信开销，能有效地与多个边缘客户端扩展，并通过云边协作提供可靠的 LLM 部署。

> Large Language Models (LLMs) have achieved remarkable success in serving end-users with human-like intelligence. However, LLMs demand high computational resources, making it challenging to deploy them to satisfy various performance objectives, such as meeting the resource constraints on edge devices close to end-users or achieving high accuracy with ample resources. In this paper, we introduce CE-CoLLM, a novel cloud-edge collaboration framework that supports efficient and adaptive LLM inference for end-users at the edge with two modes, (1) low-latency edge standalone inference and (2) highly accurate cloud-edge collaborative inference. First, we show that the inherent high communication costs for transmitting LLM contextual information between the edge and cloud dominate the overall latency, making it inefficient and costly to deploy LLMs using cloud-edge collaboration. Second, we propose several critical techniques to address this challenge, including early-exit mechanism, cloud context manager, and quantization in cloud-edge collaboration to enable not only low-latency standalone edge inference but also efficient and adaptive cloud-edge collaborative inference for LLMs. Third, we perform comprehensive experimental analysis, which demonstrates that CE-CoLLM significantly reduces inference time by up to 13.81% and cloud computation costs by up to 84.55% compared to the popular cloud-based LLM deployment, while maintaining comparable model accuracy. The proposed approach effectively shifts the computational load to the edge, reduces the communication overhead, scales efficiently with multiple edge clients, and provides reliable LLM deployment using cloud-edge collaboration.

[Arxiv](https://arxiv.org/abs/2411.02829)