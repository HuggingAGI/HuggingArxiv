# V-LoRA：一个高效且灵活的系统借助 LoRA LMM 推动视觉应用的发展

发布时间：2024年11月01日

`LLM应用` `模型服务`

> V-LoRA: An Efficient and Flexible System Boosts Vision Applications with LoRA LMM

# 摘要

> 大型多模态模型（LMMs）在各类复杂视觉任务中成果斐然，其得益于从大型语言模型（LMMs）承袭而来的强大语言与推理能力。低秩自适应（LoRA）为将外部知识融入 LMMs 提供了极具前景的途径，弥补了其在特定领域任务方面的短板。然而，现有的 LoRA 模型服务计算开销过大，致使延迟极高。本文中，我们给出了一种端到端的解决方案，借由 LoRA LMMs 助力多样的视觉任务并丰富视觉应用。我们的系统 VaLoRA 能够实现精准高效的视觉任务，具体通过：1）精度感知的 LoRA 适配器生成方式，生成富含特定领域知识的 LoRA 适配器，以满足应用的特定精度需求；2）自适应分块的 LoRA 适配器批处理操作符，能高效计算并发的异构 LoRA 适配器；3）灵活的 LoRA 适配器编排机制，对应用请求和 LoRA 适配器进行管理，以达成最低的平均响应延迟。我们在三个 LMMs 上的五个热门视觉任务中对 VaLoRA 进行了原型开发。实验结果显示，相较于原始 LMMs，VaLoRA 的精度提升了 24 - 62%，与前沿的 LoRA 模型服务系统相比，延迟降低了 20 - 89%。

> Large Multimodal Models (LMMs) have shown significant progress in various complex vision tasks with the solid linguistic and reasoning capacity inherited from large language models (LMMs). Low-rank adaptation (LoRA) offers a promising method to integrate external knowledge into LMMs, compensating for their limitations on domain-specific tasks. However, the existing LoRA model serving is excessively computationally expensive and causes extremely high latency. In this paper, we present an end-to-end solution that empowers diverse vision tasks and enriches vision applications with LoRA LMMs. Our system, VaLoRA, enables accurate and efficient vision tasks by 1) an accuracy-aware LoRA adapter generation approach that generates LoRA adapters rich in domain-specific knowledge to meet application-specific accuracy requirements, 2) an adaptive-tiling LoRA adapters batching operator that efficiently computes concurrent heterogeneous LoRA adapters, and 3) a flexible LoRA adapter orchestration mechanism that manages application requests and LoRA adapters to achieve the lowest average response latency. We prototype VaLoRA on five popular vision tasks on three LMMs. Experiment results reveal that VaLoRA improves 24-62% of the accuracy compared to the original LMMs and reduces 20-89% of the latency compared to the state-of-the-art LoRA model serving systems.

[Arxiv](https://arxiv.org/abs/2411.00915)