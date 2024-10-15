# 显著性引导的扩散潜在优化

发布时间：2024年10月14日

`其他` `图像生成` `视觉注意力`

> Saliency Guided Optimization of Diffusion Latents

# 摘要

> 随着扩散模型的进步，从文本生成高质量图像已不再难事。然而，如何优化这些生成结果以更好地符合人类意图，仍是一个挑战。现有方法通常对整个图像进行全局优化，忽略了人类视觉系统更关注显著区域的特点。为此，我们提出了显著性引导的扩散潜在优化（SGOOL），通过模拟人类视觉注意力，优先优化显著区域，避免了对非显著区域的过度处理。SGOOL不仅高效，还具备即插即用的特性，无需额外训练。实验证明，SGOOL在图像质量和意图对齐方面表现出色。

> With the rapid advances in diffusion models, generating decent images from text prompts is no longer challenging. The key to text-to-image generation is how to optimize the results of a text-to-image generation model so that they can be better aligned with human intentions or prompts. Existing optimization methods commonly treat the entire image uniformly and conduct global optimization. These methods overlook the fact that when viewing an image, the human visual system naturally prioritizes attention toward salient areas, often neglecting less or non-salient regions. That is, humans are likely to neglect optimizations in non-salient areas. Consequently, although model retaining is conducted under the guidance of additional large and multimodality models, existing methods, which perform uniform optimizations, yield sub-optimal results. To address this alignment challenge effectively and efficiently, we propose Saliency Guided Optimization Of Diffusion Latents (SGOOL). We first employ a saliency detector to mimic the human visual attention system and mark out the salient regions. To avoid retraining an additional model, our method directly optimizes the diffusion latents. Besides, SGOOL utilizes an invertible diffusion process and endows it with the merits of constant memory implementation. Hence, our method becomes a parameter-efficient and plug-and-play fine-tuning method. Extensive experiments have been done with several metrics and human evaluation. Experimental results demonstrate the superiority of SGOOL in image quality and prompt alignment.

[Arxiv](https://arxiv.org/abs/2410.10257)