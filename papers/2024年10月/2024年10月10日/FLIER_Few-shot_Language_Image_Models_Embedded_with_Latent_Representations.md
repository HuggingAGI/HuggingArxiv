# FLIER：一种嵌入了潜在表示的少样本语言图像模型

发布时间：2024年10月10日

`LLM应用` `计算机视觉` `机器学习`

> FLIER: Few-shot Language Image Models Embedded with Latent Representations

# 摘要

> 随着 CLIP 等大型视觉语言模型的兴起，类似 CLIP 的方法在低数据场景下的视觉识别表现出色。然而，这些方法大多局限于对文本和图像编码器的微调。近期，潜在扩散模型 (LDM) 在图像生成领域崭露头角。受此启发，我们提出 FLIER 模型，通过联合训练潜在编码器与 CLIP 的图像编码器，融合 CLIP 的预训练知识和稳定扩散的潜在表示，实现少样本图像识别。实验证明，FLIER 在多个数据集上的少样本分类任务中表现卓越。

> As the boosting development of large vision-language models like Contrastive Language-Image Pre-training (CLIP), many CLIP-like methods have shown impressive abilities on visual recognition, especially in low-data regimes scenes. However, we have noticed that most of these methods are limited to introducing new modifications on text and image encoder. Recently, latent diffusion models (LDMs) have shown good ability on image generation. The potent capabilities of LDMs direct our focus towards the latent representations sampled by UNet. Inspired by the conjecture in CoOp that learned prompts encode meanings beyond the existing vocabulary, we assume that, for deep models, the latent representations are concise and accurate understanding of images, in which high-frequency, imperceptible details are abstracted away. In this paper, we propose a Few-shot Language Image model Embedded with latent Representations (FLIER) for image recognition by introducing a latent encoder jointly trained with CLIP's image encoder, it incorporates pre-trained vision-language knowledge of CLIP and the latent representations from Stable Diffusion. We first generate images and corresponding latent representations via Stable Diffusion with the textual inputs from GPT-3. With latent representations as "models-understandable pixels", we introduce a flexible convolutional neural network with two convolutional layers to be the latent encoder, which is simpler than most encoders in vision-language models. The latent encoder is jointly trained with CLIP's image encoder, transferring pre-trained knowledge to downstream tasks better. Experiments and extensive ablation studies on various visual classification tasks demonstrate that FLIER performs state-of-the-art on 11 datasets for most few-shot classification.

[Arxiv](https://arxiv.org/abs/2410.07648)