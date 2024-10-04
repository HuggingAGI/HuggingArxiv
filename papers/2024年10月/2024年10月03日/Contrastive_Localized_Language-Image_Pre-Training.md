# 语言与图像的对比本地化预训练

发布时间：2024年10月03日

`LLM应用` `计算机视觉` `人工智能`

> Contrastive Localized Language-Image Pre-Training

# 摘要

> 对比语言-图像预训练 (CLIP) 是一种训练视觉编码器生成图像/文本表示的卓越方法，广泛应用于多模态大型语言模型 (MLLM) 中。然而，CLIP 在图像级别对齐网络爬取的噪声文本注释，对于需要细粒度视觉表示的下游任务可能不足。本文提出对比局部化语言-图像预训练 (CLOC)，通过区域-文本对比损失和模块增强 CLIP 的定位能力。引入可提示嵌入概念，使图像嵌入易于转换为区域表示。设计视觉丰富且空间定位的标注框架，生成大规模区域-文本伪标签。CLOC 通过扩展至数十亿带注释图像，提供高质量区域嵌入，增强 MLLM 在指代和定位任务上的表现。

> Contrastive Language-Image Pre-training (CLIP) has been a celebrated method for training vision encoders to generate image/text representations facilitating various applications. Recently, CLIP has been widely adopted as the vision backbone of multimodal large language models (MLLMs) to connect image inputs for language interactions. The success of CLIP as a vision-language foundation model relies on aligning web-crawled noisy text annotations at image levels. Nevertheless, such criteria may become insufficient for downstream tasks in need of fine-grained vision representations, especially when region-level understanding is demanding for MLLMs. In this paper, we improve the localization capability of CLIP with several advances. We propose a pre-training method called Contrastive Localized Language-Image Pre-training (CLOC) by complementing CLIP with region-text contrastive loss and modules. We formulate a new concept, promptable embeddings, of which the encoder produces image embeddings easy to transform into region representations given spatial hints. To support large-scale pre-training, we design a visually-enriched and spatially-localized captioning framework to effectively generate region-text pseudo-labels at scale. By scaling up to billions of annotated images, CLOC enables high-quality regional embeddings for image region recognition and retrieval tasks, and can be a drop-in replacement of CLIP to enhance MLLMs, especially on referring and grounding tasks.

[Arxiv](https://arxiv.org/abs/2410.02746)