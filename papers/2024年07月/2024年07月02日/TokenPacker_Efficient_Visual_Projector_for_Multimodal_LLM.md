# TokenPacker：专为多模态 LLM 设计的高效视觉投影工具

发布时间：2024年07月02日

`LLM应用` `计算机视觉` `人工智能`

> TokenPacker: Efficient Visual Projector for Multimodal LLM

# 摘要

> 在多模态大型语言模型（MLLM）中，视觉投影仪是连接视觉编码器与大型语言模型（LLM）的关键桥梁。传统方法通过简单MLP保留视觉上下文，但处理高分辨率图像时，视觉令牌冗余增加，影响效率。近期改进虽减少令牌数量，却牺牲了细节和推理能力。我们提出新视觉投影仪，采用由粗到细策略，注入丰富特征生成浓缩令牌。首先，将视觉特征插值为低分辨率点查询，奠定整体视觉基础；接着，通过区域到点注入模块，利用高分辨率、多层次区域线索，在局部上下文区域充分吸收，有效更新点查询，为LLM推理提供丰富信息。实验显示，我们的方法大幅压缩令牌（75%~89%），在多样化基准测试中性能卓越，效率显著提升。源代码见https://github.com/CircleRadon/TokenPacker。

> The visual projector serves as an essential bridge between the visual encoder and the Large Language Model (LLM) in a Multimodal LLM (MLLM). Typically, MLLMs adopt a simple MLP to preserve all visual contexts via one-to-one transformation. However, the visual tokens are redundant and can be considerably increased when dealing with high-resolution images, impairing the efficiency of MLLMs significantly. Some recent works have introduced resampler or abstractor to reduce the number of resulting visual tokens. Unfortunately, they fail to capture finer details and undermine the visual reasoning capabilities of MLLMs. In this work, we propose a novel visual projector, which adopts a coarse-to-fine scheme to inject the enriched characteristics to generate the condensed visual tokens. In specific, we first interpolate the visual features as a low-resolution point query, providing the overall visual representation as the foundation. Then, we introduce a region-to-point injection module that utilizes high-resolution, multi-level region-based cues as fine-grained reference keys and values, allowing them to be fully absorbed within the corresponding local context region. This step effectively updates the coarse point query, transforming it into an enriched one for the subsequent LLM reasoning. Extensive experiments demonstrate that our approach compresses the visual tokens by 75%~89%, while achieves comparable or even better performance across diverse benchmarks with significantly higher efficiency. The source codes can be found at https://github.com/CircleRadon/TokenPacker.

[Arxiv](https://arxiv.org/abs/2407.02392)