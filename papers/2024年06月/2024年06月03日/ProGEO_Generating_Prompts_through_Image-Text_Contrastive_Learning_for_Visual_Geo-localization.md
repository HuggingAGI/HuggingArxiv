# ProGEO：利用图像与文本的对比学习，巧妙生成提示，助力视觉地理定位任务。

发布时间：2024年06月03日

`Agent

理由：这篇论文主要描述了一种针对视觉地理定位（VG）技术的改进方法，通过两阶段训练法和对比学习来提升图像识别地理位置的能力。这种方法涉及到开发和训练特定的模型（Agent）来处理视觉数据，以提高地理定位的准确性。虽然这种方法可能涉及到一些大型语言模型（LLM）的应用，但论文的重点在于开发和优化一个特定的Agent来解决视觉地理定位的问题，而不是探讨LLM的理论或应用。因此，将其归类为Agent更为合适。` `自动驾驶` `元宇宙`

> ProGEO: Generating Prompts through Image-Text Contrastive Learning for Visual Geo-localization

# 摘要

> 视觉地理定位（VG）技术，广泛应用于自动驾驶、元宇宙等领域，旨在通过图像识别地理位置。然而，细粒度图像因缺乏明确文本描述，常使模型过度关注细节，忽视图像的深层语义。为此，我们开发了一种两阶段训练法，结合对比学习，以提升视觉识别能力并挖掘复杂样本。首先，我们利用CLIP模型的多模态能力，为每张地理图像生成可调整的文本提示，形成初步描述。接着，通过动态文本提示辅助图像编码器训练，使其能更有效地学习并泛化视觉特征。这一策略有效解决了地理图像因描述不精确而难以应用的问题。我们在多个大型数据集上验证了此方法的有效性，并取得了优异成绩。相关代码和模型已公开于https://github.com/Chain-Mao/ProGEO。

> Visual Geo-localization (VG) refers to the process to identify the location described in query images, which is widely applied in robotics field and computer vision tasks, such as autonomous driving, metaverse, augmented reality, and SLAM. In fine-grained images lacking specific text descriptions, directly applying pure visual methods to represent neighborhood features often leads to the model focusing on overly fine-grained features, unable to fully mine the semantic information in the images. Therefore, we propose a two-stage training method to enhance visual performance and use contrastive learning to mine challenging samples. We first leverage the multi-modal description capability of CLIP (Contrastive Language-Image Pretraining) to create a set of learnable text prompts for each geographic image feature to form vague descriptions. Then, by utilizing dynamic text prompts to assist the training of the image encoder, we enable the image encoder to learn better and more generalizable visual features. This strategy of applying text to purely visual tasks addresses the challenge of using multi-modal models for geographic images, which often suffer from a lack of precise descriptions, making them difficult to utilize widely. We validate the effectiveness of the proposed strategy on several large-scale visual geo-localization datasets, and our method achieves competitive results on multiple visual geo-localization datasets. Our code and model are available at https://github.com/Chain-Mao/ProGEO.

![ProGEO：利用图像与文本的对比学习，巧妙生成提示，助力视觉地理定位任务。](../../../paper_images/2406.01906/visual.png)

![ProGEO：利用图像与文本的对比学习，巧妙生成提示，助力视觉地理定位任务。](../../../paper_images/2406.01906/all.png)

![ProGEO：利用图像与文本的对比学习，巧妙生成提示，助力视觉地理定位任务。](../../../paper_images/2406.01906/stage1.png)

![ProGEO：利用图像与文本的对比学习，巧妙生成提示，助力视觉地理定位任务。](../../../paper_images/2406.01906/stage2.png)

![ProGEO：利用图像与文本的对比学习，巧妙生成提示，助力视觉地理定位任务。](../../../paper_images/2406.01906/plot.png)

[Arxiv](https://arxiv.org/abs/2406.01906)