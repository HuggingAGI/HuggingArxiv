# TextToucher：细腻的文本触感生成

发布时间：2024年09月09日

`LLM应用` `机器人` `人工智能`

> TextToucher: Fine-Grained Text-to-Touch Generation

# 摘要

> 触觉感知在多模态大模型和具身智能中至关重要。为低成本收集触觉数据，研究者尝试通过视觉到触觉的图像翻译生成触觉图像。然而，视觉模态的触觉生成难以准确描绘人类触觉感知。本文从对象级和传感器级两个粒度详细分析触觉图像特征，通过文本描述建模这些信息，提出细粒度文本到触觉生成方法（TextToucher），生成高质量触觉样本。我们引入多模态大语言模型构建对象级触觉信息文本，并使用可学习文本提示表示传感器级触觉信息。为更好指导触觉生成，我们融合双粒度文本信息，在扩散变换器架构中探索多种双粒度文本条件方法。此外，提出对比文本触觉预训练（CTTP）度量，精确评估文本驱动生成触觉数据质量。实验证明TextToucher方法的优越性。源代码将在\url{https://github.com/TtuHamg/TextToucher}上提供。

> Tactile sensation plays a crucial role in the development of multi-modal large models and embodied intelligence. To collect tactile data with minimal cost as possible, a series of studies have attempted to generate tactile images by vision-to-touch image translation. However, compared to text modality, visual modality-driven tactile generation cannot accurately depict human tactile sensation. In this work, we analyze the characteristics of tactile images in detail from two granularities: object-level (tactile texture, tactile shape), and sensor-level (gel status). We model these granularities of information through text descriptions and propose a fine-grained Text-to-Touch generation method (TextToucher) to generate high-quality tactile samples. Specifically, we introduce a multimodal large language model to build the text sentences about object-level tactile information and employ a set of learnable text prompts to represent the sensor-level tactile information. To better guide the tactile generation process with the built text information, we fuse the dual grains of text information and explore various dual-grain text conditioning methods within the diffusion transformer architecture. Furthermore, we propose a Contrastive Text-Touch Pre-training (CTTP) metric to precisely evaluate the quality of text-driven generated tactile data. Extensive experiments demonstrate the superiority of our TextToucher method. The source codes will be available at \url{https://github.com/TtuHamg/TextToucher}.

[Arxiv](https://arxiv.org/abs/2409.05427)