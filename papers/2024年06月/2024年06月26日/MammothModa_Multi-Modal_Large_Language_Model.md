# 巨象时尚：多模态大型语言模型

发布时间：2024年06月26日

`LLM应用

理由：这篇论文介绍了一款名为MammothModa的多模态大型语言模型，并详细阐述了其设计特点和性能提升策略。论文中提到的模型通过整合视觉注意力专家、扩展上下文窗口以及使用高质量的双语多模态数据集等方法，在视觉语言任务中取得了优异的表现。这些内容主要关注于大型语言模型的应用层面，即如何通过技术改进和数据优化来提升模型的实际应用性能，因此归类为LLM应用。` `人工智能` `多模态学习`

> MammothModa: Multi-Modal Large Language Model

# 摘要

> 本报告介绍了 MammothModa，一款旨在从基础水平跃升至顶尖性能的多模态大型语言模型。我们的设计重点有三：首先，通过整合视觉注意力专家，我们在保持语言理解深度的同时，强化了模型的视觉处理能力；其次，通过视觉合并模块和帧位置标识，我们扩展了上下文窗口，以适应高分辨率和长时视觉特征，避免了位置插值的问题；最后，我们精心筛选了一个高质量的双语多模态数据集，以减少视觉幻觉。凭借这些策略，MammothModa 在无任何额外修饰的情况下，已在多个真实世界的视觉语言基准测试中超越了如 LLaVA 系列等顶尖模型。

> In this report, we introduce MammothModa, yet another multi-modal large language model (MLLM) designed to achieve state-of-the-art performance starting from an elementary baseline. We focus on three key design insights: (i) Integrating Visual Capabilities while Maintaining Complex Language Understanding: In addition to the vision encoder, we incorporated the Visual Attention Experts into the LLM to enhance its visual capabilities. (ii) Extending Context Window for High-Resolution and Long-Duration Visual Feature: We explore the Visual Merger Module to effectively reduce the token number of high-resolution images and incorporated frame position ids to avoid position interpolation. (iii) High-Quality Bilingual Datasets: We meticulously curated and filtered a high-quality bilingual multimodal dataset to reduce visual hallucinations. With above recipe we build MammothModa that consistently outperforms the state-of-the-art models, e.g., LLaVA-series, across main real-world visual language benchmarks without bells and whistles.

[Arxiv](https://arxiv.org/abs/2406.18193)