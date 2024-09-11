# Alt-MoE：通过交替优化多方向 MoE 与单模态模型，实现多模态对齐

发布时间：2024年09月09日

`LLM理论` `人工智能` `多媒体`

> Alt-MoE: Multimodal Alignment via Alternating Optimization of Multi-directional MoE with Unimodal Models

# 摘要

> 最近的大型多模态模型 (LMMs) 通过轻量级连接模块，在多模态对齐方面取得了显著进展。然而，这些方法仍依赖于特定模态和方向的连接器，导致知识隔离和计算效率降低。为此，我们提出了 Alt-MoE 框架，利用专家混合 (MoE) 作为跨模态的统一连接器，并通过多步交替单向对齐策略实现双向对齐。实证研究表明，Alt-MoE 不仅整合了单模态模型的多样化知识，形成连贯的多模态表示，还能在不改变架构或策略的情况下扩展到新任务和新模态。此外，Alt-MoE 在潜在空间中运行，支持大规模数据处理。我们的方法已在多个优秀单模态模型上验证，并在广泛下游任务中表现出色。

> Recent Large Multi-Modal Models (LMMs) have made significant advancements in multi-modal alignment by employing lightweight connection modules to facilitate the representation and fusion of knowledge from existing pre-trained uni-modal models. However, these methods still rely on modality-specific and direction-specific connectors, leading to compartmentalized knowledge representations and reduced computational efficiency, which limits the model's ability to form unified multi-modal representations. To address these issues, we introduce a novel training framework, Alt-MoE, which employs the Mixture of Experts (MoE) as a unified multi-directional connector across modalities, and employs a multi-step sequential alternating unidirectional alignment strategy, which converges to bidirectional alignment over iterations. The extensive empirical studies revealed the following key points: 1) Alt-MoE achieves competitive results by integrating diverse knowledge representations from uni-modal models. This approach seamlessly fuses the specialized expertise of existing high-performance uni-modal models, effectively synthesizing their domain-specific knowledge into a cohesive multi-modal representation. 2) Alt-MoE efficiently scales to new tasks and modalities without altering its model architecture or training strategy. Furthermore, Alt-MoE operates in latent space, supporting vector pre-storage and real-time retrieval via lightweight multi-directional MoE, thereby facilitating massive data processing. Our methodology has been validated on several well-performing uni-modal models (LLAMA3, Qwen2, and DINOv2), achieving competitive results on a wide range of downstream tasks and datasets.

[Arxiv](https://arxiv.org/abs/2409.05929)