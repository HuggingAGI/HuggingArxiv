# 视觉回响：音视频生成领域的简洁统一Transformer

发布时间：2024年05月23日

`RAG

理由：这篇论文介绍了一种新型的生成式Transformer模型，该模型专注于多模态生成任务，特别是在图像到音频生成领域。这种模型利用了离散的音频与视觉向量量化GAN空间，并通过掩码去噪训练方法进行训练。此外，该模型还展示了模态对称性，适用于音频到图像生成及协同生成。这些特性与RAG（Retrieval-Augmented Generation）模型的概念相符，即通过增强的生成方法来处理多模态数据。因此，这篇论文更适合归类于RAG。` `多媒体` `人工智能`

> Visual Echoes: A Simple Unified Transformer for Audio-Visual Generation

# 摘要

> 近年来，基于扩散的生成模型凭借其逼真的生成效果和广泛的个人化应用，在视觉与音频生成领域备受瞩目。尽管文本到图像或文本到音频的生成技术取得了显著进步，音频到视觉或视觉到音频的生成研究却进展缓慢。当前的音视频生成技术多依赖于庞大的语言模型或可组合的扩散模型。本文提出了一种简单而轻量级的生成式Transformer，该模型在多模态生成领域尚未充分探索，却能在图像到音频生成任务中大放异彩。该Transformer在离散的音频与视觉向量量化GAN空间中运作，采用掩码去噪训练方法。训练完成后，通过即插即用的无分类器指导，无需额外调整即可提升性能。由于Transformer模型具有模态对称性，它同样适用于音频到图像生成及协同生成。实验结果显示，我们的方法在图像到音频生成领域超越了现有技术。欲听生成的音频样本，请访问https://docs.google.com/presentation/d/1ZtC0SeblKkut4XJcRaDsSTuCRIXB3ypxmSi7HTY3IyQ。

> In recent years, with the realistic generation results and a wide range of personalized applications, diffusion-based generative models gain huge attention in both visual and audio generation areas. Compared to the considerable advancements of text2image or text2audio generation, research in audio2visual or visual2audio generation has been relatively slow. The recent audio-visual generation methods usually resort to huge large language model or composable diffusion models. Instead of designing another giant model for audio-visual generation, in this paper we take a step back showing a simple and lightweight generative transformer, which is not fully investigated in multi-modal generation, can achieve excellent results on image2audio generation. The transformer operates in the discrete audio and visual Vector-Quantized GAN space, and is trained in the mask denoising manner. After training, the classifier-free guidance could be deployed off-the-shelf achieving better performance, without any extra training or modification. Since the transformer model is modality symmetrical, it could also be directly deployed for audio2image generation and co-generation. In the experiments, we show that our simple method surpasses recent image2audio generation methods. Generated audio samples can be found at https://docs.google.com/presentation/d/1ZtC0SeblKkut4XJcRaDsSTuCRIXB3ypxmSi7HTY3IyQ

[Arxiv](https://arxiv.org/abs/2405.14598)