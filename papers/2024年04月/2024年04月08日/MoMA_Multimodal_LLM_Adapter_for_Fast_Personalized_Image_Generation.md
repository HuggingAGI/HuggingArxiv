# MoMA 是一款多模态适配器，专为大型语言模型打造，旨在实现快速且个性化的图像创作。

发布时间：2024年04月08日

`LLM应用` `图像生成` `个性化推荐`

> MoMA: Multimodal LLM Adapter for Fast Personalized Image Generation

# 摘要

> 本文介绍了MoMA模型：一个开放词汇量的个性化图像生成器，具备灵活的零-shot功能，无需额外训练。随着文本到图像模型的快速演进，对高质量图像转换的需求日益增加。MoMA专注于根据主题生成个性化图像，它利用开源的多模态大型语言模型（MLLM），身兼特征提取和图像生成双重角色。这一策略巧妙融合了参考图像与文本提示，创造出丰富的图像特征，助力图像扩散过程。为了更高效地利用这些特征，我们还创新性地提出了一种自注意力快捷方法，它能够将图像特征快速传递给扩散模型，从而提升生成图像中目标物体的相似度。MoMA模型作为一个即插即用的模块，只需一张参考图像，便能在图像细节、身份保持和忠实度方面超越现有技术。我们的研究成果已开源，让更多人能够便捷地享受到这些技术进步。

> In this paper, we present MoMA: an open-vocabulary, training-free personalized image model that boasts flexible zero-shot capabilities. As foundational text-to-image models rapidly evolve, the demand for robust image-to-image translation grows. Addressing this need, MoMA specializes in subject-driven personalized image generation. Utilizing an open-source, Multimodal Large Language Model (MLLM), we train MoMA to serve a dual role as both a feature extractor and a generator. This approach effectively synergizes reference image and text prompt information to produce valuable image features, facilitating an image diffusion model. To better leverage the generated features, we further introduce a novel self-attention shortcut method that efficiently transfers image features to an image diffusion model, improving the resemblance of the target object in generated images. Remarkably, as a tuning-free plug-and-play module, our model requires only a single reference image and outperforms existing methods in generating images with high detail fidelity, enhanced identity-preservation and prompt faithfulness. Our work is open-source, thereby providing universal access to these advancements.

[Arxiv](https://arxiv.org/abs/2404.05674)