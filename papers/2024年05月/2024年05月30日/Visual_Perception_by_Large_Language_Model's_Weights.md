# 大型语言模型权重下的视觉感知探索

发布时间：2024年05月30日

`LLM应用

理由：这篇论文主要介绍了一种新的方法——参数空间对齐，用于改进多模态大型语言模型（MLLMs）的效率和性能。这种方法通过将视觉信息转化为模型权重，从而减少了计算成本并提高了模型的效率。论文中提到的VLoRA是一个具体的应用实例，展示了如何将这一理论应用于实际的模型开发中。因此，这篇论文更偏向于LLM的应用层面，而不是理论研究或Agent、RAG的范畴。` `计算机视觉`

> Visual Perception by Large Language Model's Weights

# 摘要

> 现有的多模态大型语言模型（MLLMs）通过将视觉特征与大型语言模型（LLMs）的输入空间对齐，并将视觉令牌与文本令牌结合，形成一个统一的输入序列，以感知视觉信息。尽管这些方法在视觉-语言任务上取得了良好效果，但高昂的计算成本限制了其发展。本文提出了一种创新的参数空间对齐方法，将视觉信息转化为模型权重，而非传统的输入空间对齐。我们利用视觉编码器提取图像特征，并将其转换为感知权重，进而与LLM的权重融合。这一创新使得LLM无需视觉令牌，有效缩短了输入序列，大幅提升了效率。基于此，我们开发了VLoRA，并为其配备了感知权重生成器，该生成器能将视觉特征高效转换为低秩的感知权重，类似于LoRA。实验证明，VLoRA在多个MLLMs基准测试中表现出色，同时显著降低了计算成本。我们计划公开发布相关代码和模型。

> Existing Multimodal Large Language Models (MLLMs) follow the paradigm that perceives visual information by aligning visual features with the input space of Large Language Models (LLMs), and concatenating visual tokens with text tokens to form a unified sequence input for LLMs. These methods demonstrate promising results on various vision-language tasks but are limited by the high computational effort due to the extended input sequence resulting from the involvement of visual tokens. In this paper, instead of input space alignment, we propose a novel parameter space alignment paradigm that represents visual information as model weights. For each input image, we use a vision encoder to extract visual features, convert features into perceptual weights, and merge the perceptual weights with LLM's weights. In this way, the input of LLM does not require visual tokens, which reduces the length of the input sequence and greatly improves efficiency. Following this paradigm, we propose VLoRA with the perceptual weights generator. The perceptual weights generator is designed to convert visual features to perceptual weights with low-rank property, exhibiting a form similar to LoRA. The experimental results show that our VLoRA achieves comparable performance on various benchmarks for MLLMs, while significantly reducing the computational costs for both training and inference. The code and models will be made open-source.

![大型语言模型权重下的视觉感知探索](../../../paper_images/2405.20339/x1.png)

![大型语言模型权重下的视觉感知探索](../../../paper_images/2405.20339/x2.png)

![大型语言模型权重下的视觉感知探索](../../../paper_images/2405.20339/x3.png)

![大型语言模型权重下的视觉感知探索](../../../paper_images/2405.20339/x4.png)

![大型语言模型权重下的视觉感知探索](../../../paper_images/2405.20339/x5.png)

[Arxiv](https://arxiv.org/abs/2405.20339)