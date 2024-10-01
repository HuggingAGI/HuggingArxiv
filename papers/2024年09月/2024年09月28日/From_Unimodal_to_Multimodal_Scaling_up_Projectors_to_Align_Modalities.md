# 从单一模态迈向多模态：扩展投影技术以实现模态对齐

发布时间：2024年09月28日

`LLM应用` `计算机视觉`

> From Unimodal to Multimodal: Scaling up Projectors to Align Modalities

# 摘要

> 近期，CLIP 等对比多模态视觉-语言模型因其对齐的潜在空间，在开放世界语义理解方面表现出色，成为视觉-语言应用的标准图像骨干。然而，这种做法却使得视觉和语言的单模态编码器在多模态应用中未被充分利用，引发了一个关键问题：是否有一种合理的方法来连接单模态骨干网络以进行零样本视觉-语言任务？为此，我们提出了一种新颖的方法，仅使用预训练的、冻结的单模态编码器上的投影层来对齐视觉和语言模态。我们的方法利用了经过良好训练的视觉和语言模型嵌入空间之间的高度语义相似性，涉及在潜在空间中选择语义相似的编码器，策划一个概念丰富的图像-标题对数据集，并训练简单的 MLP 投影器。我们在 12 个零样本分类数据集和 2 个图像-文本检索数据集上评估了我们的方法。我们最好的模型，利用 DINOv2 和 All-Roberta-Large 文本编码器，在 ImageNet 上达到了 76% 的准确率，数据减少了 20 倍，计算需求减少了 65 倍。所提出的框架不仅增强了模型开发的可达性，还实现了在不同场景中的灵活适应，通过利用现有的单模态架构，提供了一种高效构建多模态模型的方法。代码和数据集即将发布。

> Recent contrastive multimodal vision-language models like CLIP have demonstrated robust open-world semantic understanding, becoming the standard image backbones for vision-language applications due to their aligned latent space. However, this practice has left powerful unimodal encoders for both vision and language underutilized in multimodal applications which raises a key question: Is there a plausible way to connect unimodal backbones for zero-shot vision-language tasks? To this end, we propose a novel approach that aligns vision and language modalities using only projection layers on pretrained, frozen unimodal encoders. Our method exploits the high semantic similarity between embedding spaces of well-trained vision and language models. It involves selecting semantically similar encoders in the latent space, curating a concept-rich dataset of image-caption pairs, and training simple MLP projectors. We evaluated our approach on 12 zero-shot classification datasets and 2 image-text retrieval datasets. Our best model, utilizing DINOv2 and All-Roberta-Large text encoder, achieves 76\(\%\) accuracy on ImageNet with a 20-fold reduction in data and 65 fold reduction in compute requirements. The proposed framework enhances the accessibility of model development while enabling flexible adaptation across diverse scenarios, offering an efficient approach to building multimodal models by utilizing existing unimodal architectures. Code and datasets will be released soon.

[Arxiv](https://arxiv.org/abs/2409.19425)