# TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作

发布时间：2024年05月26日

`LLM应用

这篇论文介绍了一种创新的图像编辑框架，该框架利用多模态大型语言模型（LLMs）的链式思维（CoT）推理与定位功能来增强扩散模型的图像生成能力。论文详细描述了如何通过构建CoT流程，包括指令分解、区域定位及详细描述，以及如何对轻量级多模态LLM——LISA模型进行微调，以提高图像编辑的质量和一致性。这种方法的应用性质明显，因为它专注于改进现有的图像生成技术，并通过实际的模型微调和实验验证其效果，因此属于LLM应用分类。` `图像处理` `人工智能`

> TIE: Revolutionizing Text-based Image Editing for Complex-Prompt Following and High-Fidelity Editing

# 摘要

> 随着图像生成技术的飞速进步，传统扩散模型及结合多模态大型语言模型（LLMs）的模型在处理复杂提示和维持编辑前后图像一致性上仍显不足。为此，我们创新性地开发了一种图像编辑框架，该框架借助多模态LLMs的强大链式思维（CoT）推理与定位功能，助力扩散模型产出更为精细的图像。我们精心构建了一个CoT流程，包括指令分解、区域定位及详细描述。接着，我们采用这一CoT流程及编辑图像的掩码，对轻量级多模态LLM——LISA模型进行微调。通过赋予扩散模型关于生成提示和图像掩码的认知，我们的模型在理解指令方面更上一层楼，生成的图像质量更佳。经过大量实验验证，我们的模型在图像生成领域的表现超越了当前顶尖水平，尤其在处理复杂提示、生成高质量且前后一致的图像方面展现出显著优势。

> As the field of image generation rapidly advances, traditional diffusion models and those integrated with multimodal large language models (LLMs) still encounter limitations in interpreting complex prompts and preserving image consistency pre and post-editing. To tackle these challenges, we present an innovative image editing framework that employs the robust Chain-of-Thought (CoT) reasoning and localizing capabilities of multimodal LLMs to aid diffusion models in generating more refined images. We first meticulously design a CoT process comprising instruction decomposition, region localization, and detailed description. Subsequently, we fine-tune the LISA model, a lightweight multimodal LLM, using the CoT process of Multimodal LLMs and the mask of the edited image. By providing the diffusion models with knowledge of the generated prompt and image mask, our models generate images with a superior understanding of instructions. Through extensive experiments, our model has demonstrated superior performance in image generation, surpassing existing state-of-the-art models. Notably, our model exhibits an enhanced ability to understand complex prompts and generate corresponding images, while maintaining high fidelity and consistency in images before and after generation.

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x1.png)

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x2.png)

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x3.png)

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x4.png)

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x5.png)

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x6.png)

![TIE：引领文本驱动图像编辑革命，精准响应复杂指令，实现高保真视觉创作](../../../paper_images/2405.16803/x7.png)

[Arxiv](https://arxiv.org/abs/2405.16803)