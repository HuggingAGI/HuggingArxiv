# VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。

发布时间：2024年03月19日

`LLM应用` `图像处理` `质量评估`

> VisualCritic: Making LMMs Perceive Visual Quality Like Humans

# 摘要

> 当前，LMMs 在理解与生成视觉信号上展现出了卓越的通用性，但对标人眼对低层次视觉质量的感知能力尚显不足。那么，LMMs 是否有可能在这一维度上实现相同水平的通用性呢？答案是肯定的！这份论文深入探究此问题，并推出首款适用于广泛图像主观质量评估的 LMM——VisualCritic。无需如传统专项模型那样针对特定数据集做适应性调整，VisualCritic 即可开箱即用地处理各类数据。作为一款遵循指令的 LMM，VisualCritic 带来了三大创新功能：一是定量计算图像的感知质量，包括平均意见评分（MOS）、噪声度、色彩鲜艳度、锐利度等量化指标；二是定性评价视觉质量并给出具有解释性的描述；三是辨别图像源自 AI 生成还是摄影拍摄。大量的实验通过与其它开源 LMMs 及传统专项模型对比，充分验证了 VisualCritic 在处理 AI 生成及真实摄影图像时的有效性。

> At present, large multimodal models (LMMs) have exhibited impressive generalization capabilities in understanding and generating visual signals. However, they currently still lack sufficient capability to perceive low-level visual quality akin to human perception. Can LMMs achieve this and show the same degree of generalization in this regard? If so, not only could the versatility of LMMs be further enhanced, but also the challenge of poor cross-dataset performance in the field of visual quality assessment could be addressed. In this paper, we explore this question and provide the answer "Yes!". As the result of this initial exploration, we present VisualCritic, the first LMM for broad-spectrum image subjective quality assessment. VisualCritic can be used across diverse data right out of box, without any requirements of dataset-specific adaptation operations like conventional specialist models. As an instruction-following LMM, VisualCritic enables new capabilities of (1) quantitatively measuring the perceptual quality of given images in terms of their Mean Opinion Score (MOS), noisiness, colorfulness, sharpness, and other numerical indicators, (2) qualitatively evaluating visual quality and providing explainable descriptions, (3) discerning whether a given image is AI-generated or photographic. Extensive experiments demonstrate the efficacy of VisualCritic by comparing it with other open-source LMMs and conventional specialist models over both AI-generated and photographic images.

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x1.png)

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x2.png)

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x3.png)

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x4.png)

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x5.png)

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x6.png)

![VisualCritic，这一创新技术致力于使大型多模态模型（LMMs）能够像人类一样敏锐地评估和理解视觉质量。](../../../paper_images/2403.12806/x7.png)

[Arxiv](https://arxiv.org/abs/2403.12806)