# PixWizard：一款多功能图像转换助手，支持开放语言指令操作

发布时间：2024年09月23日

`LLM应用` `图像处理` `人工智能`

> PixWizard: Versatile Image-to-Image Visual Assistant with Open-Language Instructions

# 摘要

> 本文推出了一款全能图像助手 PixWizard，它能够根据自由语言指令生成、编辑和翻译图像。我们构建了一个统一的图像-文本-图像框架，并创建了 Omni 像素到像素指令数据集，涵盖了从文本生成图像到图像修复等多样任务。PixWizard 基于扩散变换器（DiT），具备灵活的任意分辨率处理能力，能动态适应输入图像的宽高比，更贴近人类感知。此外，模型还通过结构和语义引导，有效融合图像信息。实验显示，PixWizard 不仅在处理多分辨率图像时表现出色，还能灵活应对新任务和指令。项目代码和资源已公开在 https://github.com/AFeng-x/PixWizard。

> This paper presents a versatile image-to-image visual assistant, PixWizard, designed for image generation, manipulation, and translation based on free-from language instructions. To this end, we tackle a variety of vision tasks into a unified image-text-to-image generation framework and curate an Omni Pixel-to-Pixel Instruction-Tuning Dataset. By constructing detailed instruction templates in natural language, we comprehensively include a large set of diverse vision tasks such as text-to-image generation, image restoration, image grounding, dense image prediction, image editing, controllable generation, inpainting/outpainting, and more. Furthermore, we adopt Diffusion Transformers (DiT) as our foundation model and extend its capabilities with a flexible any resolution mechanism, enabling the model to dynamically process images based on the aspect ratio of the input, closely aligning with human perceptual processes. The model also incorporates structure-aware and semantic-aware guidance to facilitate effective fusion of information from the input image. Our experiments demonstrate that PixWizard not only shows impressive generative and understanding abilities for images with diverse resolutions but also exhibits promising generalization capabilities with unseen tasks and human instructions. The code and related resources are available at https://github.com/AFeng-x/PixWizard

[Arxiv](https://arxiv.org/abs/2409.15278)