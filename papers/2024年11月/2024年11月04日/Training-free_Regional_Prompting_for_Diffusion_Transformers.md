# 免训练的区域提示用于扩散变压器

发布时间：2024年11月04日

`LLM应用` `图像生成` `文本处理`

> Training-free Regional Prompting for Diffusion Transformers

# 摘要

> 扩散模型在文本到图像生成方面展现出了出色的能力。它们的语义理解（即遵循提示）能力也在大型语言模型（例如 T5、Llama）的帮助下得到了极大的提升。然而，现有的模型无法完美处理长而复杂的文本提示，特别是当文本提示包含具有众多属性和相互关联的空间关系的各种对象时。虽然已经为基于 UNet 的模型（SD1.5、SDXL）提出了许多区域提示方法，但基于最近的扩散变压器（DiT）架构（如 SD3 和 FLUX.1）仍然没有实现。在本报告中，我们基于注意力操纵为 FLUX.1 提出并实现了区域提示，这使得 DiT 能够以无训练的方式具备细粒度的组合式文本到图像生成能力。代码可在 https://github.com/antonioo-c/Regional-Prompting-FLUX 获得。

> Diffusion models have demonstrated excellent capabilities in text-to-image generation. Their semantic understanding (i.e., prompt following) ability has also been greatly improved with large language models (e.g., T5, Llama). However, existing models cannot perfectly handle long and complex text prompts, especially when the text prompts contain various objects with numerous attributes and interrelated spatial relationships. While many regional prompting methods have been proposed for UNet-based models (SD1.5, SDXL), but there are still no implementations based on the recent Diffusion Transformer (DiT) architecture, such as SD3 and FLUX.1.In this report, we propose and implement regional prompting for FLUX.1 based on attention manipulation, which enables DiT with fined-grained compositional text-to-image generation capability in a training-free manner. Code is available at https://github.com/antonioo-c/Regional-Prompting-FLUX.

[Arxiv](https://arxiv.org/abs/2411.02395)