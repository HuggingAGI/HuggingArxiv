# Cascade-CLIP：级联视觉-语言嵌入对齐，助力零-shot 语义分割

发布时间：2024年06月02日

`LLM应用

理由：这篇论文介绍了一种名为 Cascade-CLIP 的新颖框架，该框架用于改进预训练的视觉-语言模型（如 CLIP）在零样本语义分割任务中的性能。它通过级联方式调整多级视觉特征与文本嵌入的对齐，以提高模型对新类别的识别能力。这种方法直接应用于现有的视觉-语言模型，以增强其在特定任务上的表现，因此属于 LLM 应用类别。` `计算机视觉` `语义分割`

> Cascade-CLIP: Cascaded Vision-Language Embeddings Alignment for Zero-Shot Semantic Segmentation

# 摘要

> 预训练的视觉-语言模型如 CLIP 在零样本语义分割领域大放异彩。然而，现有方法多依赖于最后一层的视觉特征与文本嵌入的对齐，却忽视了中间层中蕴含的丰富对象细节。我们发现，直接整合多级视觉特征会削弱模型对新类别的识别能力，因为不同层的视觉特征差异显著，难以与文本嵌入精准匹配。为此，我们提出了一种名为 Cascade-CLIP 的新颖框架，通过一系列独立解码器，以级联方式精细调整多级视觉特征与文本嵌入的对齐。Cascade-CLIP 不仅灵活易用，还能轻松融入现有零样本语义分割技术。实验证明，Cascade-CLIP 在 COCO-Stuff、Pascal-VOC 和 Pascal-Context 等基准测试中表现出色。源代码已公开，详情请访问：https://github.com/HVision-NKU/Cascade-CLIP。

> Pre-trained vision-language models, e.g., CLIP, have been successfully applied to zero-shot semantic segmentation. Existing CLIP-based approaches primarily utilize visual features from the last layer to align with text embeddings, while they neglect the crucial information in intermediate layers that contain rich object details. However, we find that directly aggregating the multi-level visual features weakens the zero-shot ability for novel classes. The large differences between the visual features from different layers make these features hard to align well with the text embeddings. We resolve this problem by introducing a series of independent decoders to align the multi-level visual features with the text embeddings in a cascaded way, forming a novel but simple framework named Cascade-CLIP. Our Cascade-CLIP is flexible and can be easily applied to existing zero-shot semantic segmentation methods. Experimental results show that our simple Cascade-CLIP achieves superior zero-shot performance on segmentation benchmarks, like COCO-Stuff, Pascal-VOC, and Pascal-Context. Our code is available at: https://github.com/HVision-NKU/Cascade-CLIP

[Arxiv](https://arxiv.org/abs/2406.00670)