# AdaptVision 技术通过在 MLLMs 中实现动态输入缩放，助力于多场景理解的灵活性。

发布时间：2024年08月29日

`LLM应用` `计算机视觉` `文档处理`

> AdaptVision: Dynamic Input Scaling in MLLMs for Versatile Scene Understanding

# 摘要

> 近年来，多模态大型语言模型 (MLLMs) 的发展备受瞩目，激发了众多创新以提升其理解力。本文介绍的 AdaptVision 模型，专为动态处理不同分辨率的图像而设计。我们提出，模型所需的视觉令牌数量与图像的分辨率和内容紧密相关。例如，信息量较少的自然图像在低分辨率下即可用较少令牌解析；而富含文本的文档则需更多令牌以确保文本识别的准确性。为此，我们开发了动态图像分区模块，根据图像尺寸和比例智能调整令牌数量，有效避免了因统一分辨率调整带来的失真问题，并优化了令牌输入。该模型最高可处理 $1008\times 1008$ 分辨率的图像，并在多种数据集上展现了卓越的视觉语言任务处理能力。相关代码和数据集已公开于 \url{https://github.com/harrytea/AdaptVision}。

> Over the past few years, the advancement of Multimodal Large Language Models (MLLMs) has captured the wide interest of researchers, leading to numerous innovations to enhance MLLMs' comprehension. In this paper, we present AdaptVision, a multimodal large language model specifically designed to dynamically process input images at varying resolutions. We hypothesize that the requisite number of visual tokens for the model is contingent upon both the resolution and content of the input image. Generally, natural images with a lower information density can be effectively interpreted by the model using fewer visual tokens at reduced resolutions. In contrast, images containing textual content, such as documents with rich text, necessitate a higher number of visual tokens for accurate text interpretation due to their higher information density. Building on this insight, we devise a dynamic image partitioning module that adjusts the number of visual tokens according to the size and aspect ratio of images. This method mitigates distortion effects that arise from resizing images to a uniform resolution and dynamically optimizing the visual tokens input to the LLMs. Our model is capable of processing images with resolutions up to $1008\times 1008$. Extensive experiments across various datasets demonstrate that our method achieves impressive performance in handling vision-language tasks in both natural and text-related scenes. The source code and dataset are now publicly available at \url{https://github.com/harrytea/AdaptVision}.

[Arxiv](https://arxiv.org/abs/2408.16986)