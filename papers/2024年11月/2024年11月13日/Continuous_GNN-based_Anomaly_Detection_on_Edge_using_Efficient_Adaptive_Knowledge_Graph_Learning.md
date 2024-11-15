# 利用高效自适应知识图谱学习实现基于连续 GNN 的边缘异常检测

发布时间：2024年11月13日

`LLM应用` `异常检测`

> Continuous GNN-based Anomaly Detection on Edge using Efficient Adaptive Knowledge Graph Learning

# 摘要

> 各行各业对强大安全解决方案的需求与日俱增，这让视频异常检测（VAD）在智能监控、证据调查、暴力检测等应用中成为关键任务。传统的 VAD 方法往往依赖对大型预训练模型的微调，这计算成本高昂，在实时或资源受限的环境中难以实现。为此，MissionGNN 引入了一种更高效的方法，即利用从 GPT-4 等大型语言模型（LLM）衍生出的固定知识图谱（KG）来训练图神经网络（GNN）。该方法虽在计算能力和内存方面效率显著，但在动态环境中存在局限，因为行为趋势和数据模式不断变化，KG 需频繁更新，而这通常需要基于云的计算，给边缘计算应用带来挑战。在本文中，我们提出了一个新颖的框架，能直接在边缘设备上实现连续的 KG 适配，克服了对云的依赖。我们的方法通过修剪、交替和创建节点这三个阶段来动态修改 KG，从而实时适应变化的数据趋势。这种持续学习的方式增强了异常检测模型的稳健性，使其更适合在动态且资源受限的环境中部署。

> The increasing demand for robust security solutions across various industries has made Video Anomaly Detection (VAD) a critical task in applications such as intelligent surveillance, evidence investigation, and violence detection. Traditional approaches to VAD often rely on finetuning large pre-trained models, which can be computationally expensive and impractical for real-time or resource-constrained environments. To address this, MissionGNN introduced a more efficient method by training a graph neural network (GNN) using a fixed knowledge graph (KG) derived from large language models (LLMs) like GPT-4. While this approach demonstrated significant efficiency in computational power and memory, it faces limitations in dynamic environments where frequent updates to the KG are necessary due to evolving behavior trends and shifting data patterns. These updates typically require cloud-based computation, posing challenges for edge computing applications. In this paper, we propose a novel framework that facilitates continuous KG adaptation directly on edge devices, overcoming the limitations of cloud dependency. Our method dynamically modifies the KG through a three-phase process: pruning, alternating, and creating nodes, enabling real-time adaptation to changing data trends. This continuous learning approach enhances the robustness of anomaly detection models, making them more suitable for deployment in dynamic and resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2411.09072)