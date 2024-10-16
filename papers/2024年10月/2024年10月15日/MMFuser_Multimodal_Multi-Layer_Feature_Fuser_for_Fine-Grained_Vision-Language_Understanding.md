# MMFuser：一款多模态多层特征融合器，专为细粒度的视觉与语言理解而设计。

发布时间：2024年10月15日

`LLM应用` `人工智能` `计算机视觉`

> MMFuser: Multimodal Multi-Layer Feature Fuser for Fine-Grained Vision-Language Understanding

# 摘要

> 尽管多模态大型语言模型 (MLLM) 在通过跨模态交互理解复杂人类意图方面取得了显著进展，但捕捉复杂图像细节仍然是一个挑战。先前的多视觉编码器集成方法虽然增强了视觉细节，却引入了冗余和计算开销。我们发现，大多数 MLLM 仅依赖视觉编码器的最后一层特征图，忽略了浅层特征图中的丰富细粒度信息。为此，我们提出了 \modelname，一种简单高效的多层特征融合器，能够有效整合 Vision Transformers (ViTs) 的深层和浅层特征。它通过语义对齐的深层特征动态提取浅层特征中的缺失细节，既保留了语义对齐，又丰富了细粒度信息的表示。应用于 LLaVA-1.5 模型时，\modelname 在视觉表示和基准性能上均有显著提升，相较于多编码器集成方法，提供了更灵活轻量级的解决方案。代码和模型已在 https://github.com/yuecao0119/MMFuser 发布。

> Despite significant advancements in Multimodal Large Language Models (MLLMs) for understanding complex human intentions through cross-modal interactions, capturing intricate image details remains challenging. Previous methods integrating multiple vision encoders to enhance visual detail introduce redundancy and computational overhead. We observe that most MLLMs utilize only the last-layer feature map of the vision encoder for visual representation, neglecting the rich fine-grained information in shallow feature maps. To address this issue, we propose \modelname, a simple yet effective multi-layer feature fuser that efficiently integrates deep and shallow features from Vision Transformers (ViTs). Specifically, it leverages semantically aligned deep features as queries to dynamically extract missing details from shallow features, thus preserving semantic alignment while enriching the representation with fine-grained information. Applied to the LLaVA-1.5 model, \modelname~achieves significant improvements in visual representation and benchmark performance, providing a more flexible and lightweight solution compared to multi-encoder ensemble methods. The code and model have been released at https://github.com/yuecao0119/MMFuser.

[Arxiv](https://arxiv.org/abs/2410.11829)