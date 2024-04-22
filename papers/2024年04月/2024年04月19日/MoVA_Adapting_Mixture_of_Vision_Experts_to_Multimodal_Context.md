# MoVA：将视觉专家的混合模型适配至多模态环境

发布时间：2024年04月19日

`分类：LLM应用` `计算机视觉` `人工智能`

> MoVA: Adapting Mixture of Vision Experts to Multimodal Context

# 摘要

> 在多模态大型语言模型（MLLMs）中，视觉编码器扮演着核心角色，对模型理解多样图像内容的能力起着决定性作用。尽管大规模预训练视觉编码器，如CLIP和DINOv2中的编码器，已经展现了可观的性能，但仍未有一种编码器能在理解各类图像内容上全面占优。例如，CLIP的视觉编码器在常规图像理解上表现优异，却在文档或图表类内容上不尽人意。为了解决CLIP视觉编码器的局限性，我们首先深入分析了不同预训练视觉编码器的内在特性，并提出了MoVA——一种创新的MLLM，它能够通过由粗到细的机制，灵活地路由并整合特定任务的视觉专家。在粗粒度层面，我们设计了一种基于上下文的专家路由策略，能够根据用户指令、输入图像以及视觉专家的专长，动态选择最合适的专家。这一策略得益于配备了专家路由低秩适应（LoRA）技术的大型语言模型（LLM）的强大功能理解能力。在细粒度层面，我们精心打造了混合视觉专家适配器（MoV-Adapter），用于从众多专家中提取并融合特定任务的关键知识。这种由粗到细的处理模式，充分利用了多模态上下文和模型专长，有效提升了模型的泛化性能。我们通过大量实验验证了该方法的有效性，MoVA在无需任何复杂设置的情况下，便能在众多具有挑战性的多模态基准测试中取得显著的性能提升。相关代码和模型将在 https://github.com/TempleX98/MoVA 上公开。

> As the key component in multimodal large language models (MLLMs), the ability of the visual encoder greatly affects MLLM's understanding on diverse image content. Although some large-scale pretrained vision encoders such as vision encoders in CLIP and DINOv2 have brought promising performance, we found that there is still no single vision encoder that can dominate various image content understanding, e.g., the CLIP vision encoder leads to outstanding results on general image understanding but poor performance on document or chart content. To alleviate the bias of CLIP vision encoder, we first delve into the inherent behavior of different pre-trained vision encoders and then propose the MoVA, a powerful and novel MLLM, adaptively routing and fusing task-specific vision experts with a coarse-to-fine mechanism. In the coarse-grained stage, we design a context-aware expert routing strategy to dynamically select the most suitable vision experts according to the user instruction, input image, and expertise of vision experts. This benefits from the powerful model function understanding ability of the large language model (LLM) equipped with expert-routing low-rank adaptation (LoRA). In the fine-grained stage, we elaborately conduct the mixture-of-vision-expert adapter (MoV-Adapter) to extract and fuse task-specific knowledge from various experts. This coarse-to-fine paradigm effectively leverages representations from experts based on multimodal context and model expertise, further enhancing the generalization ability. We conduct extensive experiments to evaluate the effectiveness of the proposed approach. Without any bells and whistles, MoVA can achieve significant performance gains over current state-of-the-art methods in a wide range of challenging multimodal benchmarks. Codes and models will be available at https://github.com/TempleX98/MoVA.

![MoVA：将视觉专家的混合模型适配至多模态环境](../../../paper_images/2404.13046/x1.png)

![MoVA：将视觉专家的混合模型适配至多模态环境](../../../paper_images/2404.13046/x2.png)

![MoVA：将视觉专家的混合模型适配至多模态环境](../../../paper_images/2404.13046/x3.png)

![MoVA：将视觉专家的混合模型适配至多模态环境](../../../paper_images/2404.13046/x4.png)

[Arxiv](https://arxiv.org/abs/2404.13046)