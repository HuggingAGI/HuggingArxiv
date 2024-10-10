# EMMA：赋能多模态 Mamba，实现结构与层次的精准对齐

发布时间：2024年10月08日

`LLM应用` `人工智能` `计算机视觉`

> EMMA: Empowering Multi-modal Mamba with Structural and Hierarchical Alignment

# 摘要

> Mamba 架构因其卓越性能和高效部署速度，成为深度学习的新星。然而，现有 Mamba 多模态模型在视觉特征提取上力有不逮，导致视觉与文本信息对齐失衡，拖累多模态任务表现。为此，我们推出 EMMA，通过像素级对齐模块和多尺度特征融合，实现图像与特征的精细对齐。实验表明，EMMA 不仅推理速度飞快，更在多模态任务中展现出卓越性能，细节捕捉与幻觉控制均更胜一筹。代码即将公开，敬请期待。

> Mamba-based architectures have shown to be a promising new direction for deep learning models owing to their competitive performance and sub-quadratic deployment speed. However, current Mamba multi-modal large language models (MLLM) are insufficient in extracting visual features, leading to imbalanced cross-modal alignment between visual and textural latents, negatively impacting performance on multi-modal tasks. In this work, we propose Empowering Multi-modal Mamba with Structural and Hierarchical Alignment (EMMA), which enables the MLLM to extract fine-grained visual information. Specifically, we propose a pixel-wise alignment module to autoregressively optimize the learning and processing of spatial image-level features along with textual tokens, enabling structural alignment at the image level. In addition, to prevent the degradation of visual information during the cross-model alignment process, we propose a multi-scale feature fusion (MFF) module to combine multi-scale visual features from intermediate layers, enabling hierarchical alignment at the feature level. Extensive experiments are conducted across a variety of multi-modal benchmarks. Our model shows lower latency than other Mamba-based MLLMs and is nearly four times faster than transformer-based MLLMs of similar scale during inference. Due to better cross-modal alignment, our model exhibits lower degrees of hallucination and enhanced sensitivity to visual details, which manifests in superior performance across diverse multi-modal benchmarks. Code will be provided.

[Arxiv](https://arxiv.org/abs/2410.05938)