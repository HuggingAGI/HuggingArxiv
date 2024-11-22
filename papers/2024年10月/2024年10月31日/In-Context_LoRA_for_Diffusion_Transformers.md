# In-Context LoRA 应用于扩散 Transformer

发布时间：2024年10月31日

`其他` `图像生成` `计算机视觉`

> In-Context LoRA for Diffusion Transformers

# 摘要

> 摘要：近期的研究 arXiv:2410.15027 探索了通过简单跨图像连接注意力标记来运用扩散变压器（DiTs）进行与任务无关的图像生成。然而，即便有大量计算资源，所生成图像的保真度仍欠佳。在本研究中，我们重新评估并优化了此框架，假定文本到图像的 DiTs 本就具备上下文生成能力，仅需极少的调整来激活。通过各类任务实验，我们定性地证实现有的文本到图像的 DiTs 无需任何调整就能有效进行上下文生成。基于此发现，我们提出了一个极为简便的流程来利用 DiTs 的上下文能力：（1）连接图像而非标记，（2）对多个图像进行联合标题标注，（3）使用小数据集（如 20 至 100 个样本）进行任务特定的 LoRA 调整，而非用大数据集进行全参数调整。我们将模型命名为上下文 LoRA（IC-LoRA）。此方法无需对原始 DiT 模型做修改，仅需变更训练数据。值得一提的是，我们的流程生成的高保真图像集更贴合提示。虽然在调整数据上针对特定任务，但我们的框架在架构和流程上仍与任务无关，为社区提供了有力工具，并为产品级与任务无关的生成系统的进一步研究提供了宝贵见解。我们在这个 https URL 发布了代码、数据和模型。

> 
Abstract:Recent research arXiv:2410.15027 has explored the use of diffusion transformers (DiTs) for task-agnostic image generation by simply concatenating attention tokens across images. However, despite substantial computational resources, the fidelity of the generated images remains suboptimal. In this study, we reevaluate and streamline this framework by hypothesizing that text-to-image DiTs inherently possess in-context generation capabilities, requiring only minimal tuning to activate them. Through diverse task experiments, we qualitatively demonstrate that existing text-to-image DiTs can effectively perform in-context generation without any tuning. Building on this insight, we propose a remarkably simple pipeline to leverage the in-context abilities of DiTs: (1) concatenate images instead of tokens, (2) perform joint captioning of multiple images, and (3) apply task-specific LoRA tuning using small datasets (e.g., 20~100 samples) instead of full-parameter tuning with large datasets. We name our models In-Context LoRA (IC-LoRA). This approach requires no modifications to the original DiT models, only changes to the training data. Remarkably, our pipeline generates high-fidelity image sets that better adhere to prompts. While task-specific in terms of tuning data, our framework remains task-agnostic in architecture and pipeline, offering a powerful tool for the community and providing valuable insights for further research on product-level task-agnostic generation systems. We release our code, data, and models at this https URL


[Arxiv](https://arxiv.org/pdf/2410.23775)