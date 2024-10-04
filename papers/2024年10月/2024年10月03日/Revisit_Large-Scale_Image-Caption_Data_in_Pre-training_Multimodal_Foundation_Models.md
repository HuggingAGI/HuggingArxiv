# 重新探索预训练多模态基础模型中的大规模图像与标题数据

发布时间：2024年10月03日

`LLM应用` `多模态模型` `计算机视觉`

> Revisit Large-Scale Image-Caption Data in Pre-training Multimodal Foundation Models

# 摘要

> 多模态模型的进步凸显了重写标题的重要性，但关键挑战犹存。合成标题虽质量高且对齐好，但其能否完全替代AltTexts尚不明朗。不同模型对标题格式有独特偏好，但优化工作有限。我们设计了一种新颖、可控且可扩展的标题生成管道，以适应不同模型。通过研究SSC到DSC+的案例，我们发现混合使用合成标题和AltTexts能提升对齐和性能，且各模型对特定格式有偏好。这一分析为优化策略提供了宝贵见解，推动了多模态模型的预训练。

> Recent advancements in multimodal models highlight the value of rewritten captions for improving performance, yet key challenges remain. For example, while synthetic captions often provide superior quality and image-text alignment, it is not clear whether they can fully replace AltTexts: the role of synthetic captions and their interaction with original web-crawled AltTexts in pre-training is still not well understood. Moreover, different multimodal foundation models may have unique preferences for specific caption formats, but efforts to identify the optimal captions for each model remain limited. In this work, we propose a novel, controllable, and scalable captioning pipeline designed to generate diverse caption formats tailored to various multimodal models. By examining Short Synthetic Captions (SSC) towards Dense Synthetic Captions (DSC+) as case studies, we systematically explore their effects and interactions with AltTexts across models such as CLIP, multimodal LLMs, and diffusion models. Our findings reveal that a hybrid approach that keeps both synthetic captions and AltTexts can outperform the use of synthetic captions alone, improving both alignment and performance, with each model demonstrating preferences for particular caption formats. This comprehensive analysis provides valuable insights into optimizing captioning strategies, thereby advancing the pre-training of multimodal foundation models.

[Arxiv](https://arxiv.org/abs/2410.02740)