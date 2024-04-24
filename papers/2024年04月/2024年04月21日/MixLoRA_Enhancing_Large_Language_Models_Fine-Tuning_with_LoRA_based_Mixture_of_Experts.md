# MixLoRA：借助 LoRA 技术，通过专家混合策略提升大型语言模型的微调效果。

发布时间：2024年04月21日

`LLM应用` `机器学习`

> MixLoRA: Enhancing Large Language Models Fine-Tuning with LoRA based Mixture of Experts

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理（NLP）任务上展现了非凡的成效。为了针对特定应用调整预训练模型，微调技术被广泛采用。LoRA等方法虽然有效缓解了微调时的GPU内存限制，但在多任务处理上往往受限于性能瓶颈。与此同时，像Mixtral 8x7B这样的专家混合（MoE）模型，在减少参数数量的同时，在多项NLP任务上取得了显著成绩。尽管如此，MoE模型对资源的需求对于消费级GPU而言仍是一大挑战，这些GPU的视频内存（VRAM）通常十分有限。为应对这一挑战，我们提出了MixLoRA，这是一种创新的方法，旨在构建一个基于LoRA的高效率稀疏MoE模型。MixLoRA通过微调，在冻结的预训练密集模型的前馈网络中嵌入多个LoRA专家，并采用普遍的top-k路由器。与其它基于LoRA的MoE方法相比，MixLoRA通过使用独立配置的注意力层LoRA适配器来提升模型性能，支持LoRA及其变体用于构建专家，并引入辅助负载平衡损失以解决路由器的不平衡问题。实验结果表明，MixLoRA在单任务和多任务学习场景的各项评估指标上均表现优异。在m-LoRA框架下，MixLoRA能够在单个24GB消费级GPU上实现多个专家混合模型的并行微调，无需量化，有效减少了41%的GPU内存使用率和17%的训练延迟。

> Large Language Models (LLMs) have showcased exceptional performance across a wide array of Natural Language Processing (NLP) tasks. Fine-tuning techniques are commonly utilized to tailor pre-trained models to specific applications. While methods like LoRA have effectively tackled GPU memory constraints during fine-tuning, their applicability is often restricted to limited performance, especially on multi-task. On the other hand, Mix-of-Expert (MoE) models, such as Mixtral 8x7B, demonstrate remarkable performance across multiple NLP tasks while maintaining a reduced parameter count. However, the resource requirements of these MoEs still challenging, particularly for consumer-grade GPUs only have limited VRAM. To address these challenge, we propose MixLoRA, an innovative approach aimed at constructing a resource-efficient sparse MoE model based on LoRA. MixLoRA inserts multiple LoRA-based experts within the feed-forward network block of a frozen pre-trained dense model through fine-tuning, employing a commonly used top-k router. Unlike other LoRA based MoE methods, MixLoRA enhances model performance by utilizing independently configurable attention-layer LoRA adapters, supporting the use of LoRA and its variants for the construction of experts, and applying auxiliary load balance loss to address the imbalance problem of the router. In experiments, MixLoRA achieves commendable performance across all evaluation metrics in both single-task and multi-task learning scenarios. Implemented within the m-LoRA framework, MixLoRA enables parallel fine-tuning of multiple mixture-of-experts models on a single 24GB consumer-grade GPU without quantization, thereby reducing GPU memory consumption by 41\% and latency during the training process by 17\%.

[Arxiv](https://arxiv.org/abs/2404.15159)