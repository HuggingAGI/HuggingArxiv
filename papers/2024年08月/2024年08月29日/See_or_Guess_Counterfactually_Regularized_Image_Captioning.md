# 观图猜语：反事实正则化图像描述技术

发布时间：2024年08月29日

`LLM应用` `计算机视觉`

> See or Guess: Counterfactually Regularized Image Captioning

# 摘要

> 图像描述生成是视觉-语言研究的核心任务，旨在用自然语言精准描述图像内容。传统模型虽能处理常规图像，但在面对部分遮挡或编辑的图像时，其描述准确性远不及人类。这些模型常因幻觉和解释性不足而在复杂场景中表现不佳。本文提出一种基于因果推断的通用框架，增强模型在干预任务中的能力，并实现反事实可解释性。我们采用总效应和自然直接效应两种方法，通过整合训练，使模型能应对反事实场景，提升泛化性。实验证明，该方法有效减少幻觉，增强模型对图像的忠实度，且适用于各类规模的图像到文本模型。相关代码已公开于https://github.com/Aman-4-Real/See-or-Guess。

> Image captioning, which generates natural language descriptions of the visual information in an image, is a crucial task in vision-language research. Previous models have typically addressed this task by aligning the generative capabilities of machines with human intelligence through statistical fitting of existing datasets. While effective for normal images, they may struggle to accurately describe those where certain parts of the image are obscured or edited, unlike humans who excel in such cases. These weaknesses they exhibit, including hallucinations and limited interpretability, often hinder performance in scenarios with shifted association patterns. In this paper, we present a generic image captioning framework that employs causal inference to make existing models more capable of interventional tasks, and counterfactually explainable. Our approach includes two variants leveraging either total effect or natural direct effect. Integrating them into the training process enables models to handle counterfactual scenarios, increasing their generalizability. Extensive experiments on various datasets show that our method effectively reduces hallucinations and improves the model's faithfulness to images, demonstrating high portability across both small-scale and large-scale image-to-text models. The code is available at https://github.com/Aman-4-Real/See-or-Guess.

[Arxiv](https://arxiv.org/abs/2408.16809)