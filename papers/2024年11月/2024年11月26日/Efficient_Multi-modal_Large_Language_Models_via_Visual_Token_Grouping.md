# 借助视觉标记分组打造高效的多模态大型语言模型

发布时间：2024年11月26日

`LLM应用` `计算机视觉` `多模态语言模型`

> Efficient Multi-modal Large Language Models via Visual Token Grouping

# 摘要

> 多模态大型语言模型（MLLMs）的发展赋予了大型语言模型（LLMs）感知非文本数据格式的能力，极大地推动了诸如视觉问答、图像字幕生成等一系列下游应用的发展。但处理高分辨率图像和视频所产生的巨大计算成本，成为了其广泛应用的阻碍。为解决这一难题，压缩 MLLMs 中的视觉标记成为降低推理成本的可行之法。现有的方法在特征对齐阶段进行标记删减。在本文中，我们推出了 VisToG，这一创新的分组机制借助预训练视觉编码器的能力对相似图像段进行分组，无需分割掩码。具体而言，在输入视觉编码器前的线性投影层之后，我们连接语义标记来表征图像语义段。此外，凭借我们采用的独立注意力，VisToG 能够利用预训练视觉编码器中的先验知识识别并去除冗余视觉标记，有效降低了计算需求。大量实验表明 VisToG 成效显著，在保持原始性能 98.1%的同时，推理时间减少超过 27％。

> The development of Multi-modal Large Language Models (MLLMs) enhances Large Language Models (LLMs) with the ability to perceive data formats beyond text, significantly advancing a range of downstream applications, such as visual question answering and image captioning. However, the substantial computational costs associated with processing high-resolution images and videos pose a barrier to their broader adoption. To address this challenge, compressing vision tokens in MLLMs has emerged as a promising approach to reduce inference costs. While existing methods conduct token reduction in the feature alignment phase. In this paper, we introduce VisToG, a novel grouping mechanism that leverages the capabilities of pre-trained vision encoders to group similar image segments without the need for segmentation masks. Specifically, we concatenate semantic tokens to represent image semantic segments after the linear projection layer before feeding into the vision encoder. Besides, with the isolated attention we adopt, VisToG can identify and eliminate redundant visual tokens utilizing the prior knowledge in the pre-trained vision encoder, which effectively reduces computational demands. Extensive experiments demonstrate the effectiveness of VisToG, maintaining 98.1% of the original performance while achieving a reduction of over 27\% inference time.

[Arxiv](https://arxiv.org/abs/2411.17773)