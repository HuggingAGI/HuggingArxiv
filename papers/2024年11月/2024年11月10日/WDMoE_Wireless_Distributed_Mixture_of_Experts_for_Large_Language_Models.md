# WDMoE：用于大型语言模型的无线分布式专家混合体

发布时间：2024年11月10日

`LLM应用` `无线网络`

> WDMoE: Wireless Distributed Mixture of Experts for Large Language Models

# 摘要

> 大型语言模型（LLMs）在各种自然语言处理任务中取得了显著的成功，但无线网络在支持 LLMs 方面的作用尚未得到彻底探索。在本文中，我们提出了一种无线分布式专家混合（WDMoE）架构，以实现在无线网络中基站（BS）的边缘服务器和移动设备之间对 LLMs 的协同部署。具体来说，我们通过将选通网络和前面的神经网络层放置在 BS 处，同时在设备之间分配专家网络，来分解 LLMs 中的 MoE 层。这种部署利用了移动设备上专家网络的并行推理能力，有效地利用了这些设备有限的计算和缓存资源。因此，我们为基于 WDMoE 的 LLMs 开发了一个性能指标，该指标同时考虑了模型能力和延迟。为了在保持准确性的同时最小化延迟，我们根据性能指标共同优化专家选择和带宽分配。此外，我们使用 NVIDIA Jetson 套件构建了一个硬件测试平台，以验证 WDMoE 的有效性。理论模拟和实际硬件实验都表明，所提出的方法可以在不影响 LLMs 性能的情况下显著降低延迟。

> Large Language Models (LLMs) have achieved significant success in various natural language processing tasks, but the role of wireless networks in supporting LLMs has not been thoroughly explored. In this paper, we propose a wireless distributed Mixture of Experts (WDMoE) architecture to enable collaborative deployment of LLMs across edge servers at the base station (BS) and mobile devices in wireless networks. Specifically, we decompose the MoE layer in LLMs by placing the gating network and the preceding neural network layer at BS, while distributing the expert networks among the devices. This deployment leverages the parallel inference capabilities of expert networks on mobile devices, effectively utilizing the limited computing and caching resources of these devices. Accordingly, we develop a performance metric for WDMoE-based LLMs, which accounts for both model capability and latency. To minimize the latency while maintaining accuracy, we jointly optimize expert selection and bandwidth allocation based on the performance metric. Moreover, we build a hardware testbed using NVIDIA Jetson kits to validate the effectiveness of WDMoE. Both theoretical simulations and practical hardware experiments demonstrate that the proposed method can significantly reduce the latency without compromising LLM performance.

[Arxiv](https://arxiv.org/abs/2411.06681)