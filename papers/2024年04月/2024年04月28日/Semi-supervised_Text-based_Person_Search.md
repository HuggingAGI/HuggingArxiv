# 半监督文本人物搜索

发布时间：2024年04月28日

`分类：Agent` `计算机视觉` `半监督学习`

> Semi-supervised Text-based Person Search

# 摘要

> 基于文本的人物搜索（TBPS）的目的是通过自然语言描述，从海量的图像库中找出特定人物的图片。目前的方法大多依赖于大规模的标注图像-文本数据集，在完全监督的环境下达到较好的效果。然而，这在实际操作中面临巨大挑战，因为从监控视频中获取人物图像较为简单，但获取相应的标注文本却相当困难。本研究首次尝试在半监督的环境下探索TBPS问题，即只有少数人物图像附有文本描述，而大多数图像并未标注。我们提出了一个分两步的解决方案：首先利用图像描述模型为未标注图像生成伪文本，以此扩充标注数据；然后在扩充后的数据基础上，执行全监督的检索学习。特别地，为了应对伪文本带来的噪声干扰，我们设计了一个抗噪声检索框架，该框架通过混合Patch-Channel掩码（PC-Mask）技术和噪声引导的渐进式训练（NP-Train）策略，提升了模型处理噪声数据的能力。PC-Mask技术在输入数据的patch层和channel层进行掩码操作，防止对噪声标签的过拟合。NP-Train则根据伪文本的噪声水平，采用渐进式训练计划，以实现鲁棒学习。在多个TBPS基准测试中的广泛实验结果表明，我们提出的框架在半监督环境下展现出了优异的性能。

> Text-based person search (TBPS) aims to retrieve images of a specific person from a large image gallery based on a natural language description. Existing methods rely on massive annotated image-text data to achieve satisfactory performance in fully-supervised learning. It poses a significant challenge in practice, as acquiring person images from surveillance videos is relatively easy, while obtaining annotated texts is challenging. The paper undertakes a pioneering initiative to explore TBPS under the semi-supervised setting, where only a limited number of person images are annotated with textual descriptions while the majority of images lack annotations. We present a two-stage basic solution based on generation-then-retrieval for semi-supervised TBPS. The generation stage enriches annotated data by applying an image captioning model to generate pseudo-texts for unannotated images. Later, the retrieval stage performs fully-supervised retrieval learning using the augmented data. Significantly, considering the noise interference of the pseudo-texts on retrieval learning, we propose a noise-robust retrieval framework that enhances the ability of the retrieval model to handle noisy data. The framework integrates two key strategies: Hybrid Patch-Channel Masking (PC-Mask) to refine the model architecture, and Noise-Guided Progressive Training (NP-Train) to enhance the training process. PC-Mask performs masking on the input data at both the patch-level and the channel-level to prevent overfitting noisy supervision. NP-Train introduces a progressive training schedule based on the noise level of pseudo-texts to facilitate noise-robust learning. Extensive experiments on multiple TBPS benchmarks show that the proposed framework achieves promising performance under the semi-supervised setting.

[Arxiv](https://arxiv.org/abs/2404.18106)