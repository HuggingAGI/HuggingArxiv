# 文本至像素：深化多模态大型语言模型中的长上下文理解

发布时间：2024年05月23日

`LLM应用

这篇论文介绍了SEEKER模型，该模型旨在解决多模态大型语言模型（MLLMs）在处理复杂视觉与文本信息时的限制，特别是在处理长序列输入方面的能力。SEEKER通过创新的文本压缩技术，将文本信息压缩至视觉像素空间，从而实现了对长文本的高效紧凑编码。这种方法使得模型能够在固定的令牌长度内有效处理长文本，提高了模型在多模态任务中的性能。因此，这篇论文属于LLM应用分类，因为它专注于开发和应用特定的技术来优化大型语言模型在实际任务中的表现。` `多模态处理` `文本压缩`

> From Text to Pixel: Advancing Long-Context Understanding in MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）的飞速进步将处理复杂视觉与文本信息的能力推向新高度。然而，整合多图像与广泛文本上下文仍受限于模型高效处理长序列输入的能力。本文推出的SEEKER模型，专为攻克此难题而设计。SEEKER通过将文本压缩至视觉像素空间，实现了长文本的高效紧凑编码，使其在固定令牌长度内自如应对长文本。实证显示，在六大长上下文多模态任务中，SEEKER以更少图像令牌传递等量文本信息，优于基于OCR的方法，且在理解和生成长格式多模态内容方面表现卓越，显著领先于所有现有MLLMs。

> The rapid progress in Multimodal Large Language Models (MLLMs) has significantly advanced their ability to process and understand complex visual and textual information. However, the integration of multiple images and extensive textual contexts remains a challenge due to the inherent limitation of the models' capacity to handle long input sequences efficiently. In this paper, we introduce SEEKER, a multimodal large language model designed to tackle this issue. SEEKER aims to optimize the compact encoding of long text by compressing the text sequence into the visual pixel space via images, enabling the model to handle long text within a fixed token-length budget efficiently. Our empirical experiments on six long-context multimodal tasks demonstrate that SEEKER can leverage fewer image tokens to convey the same amount of textual information compared with the OCR-based approach, and is more efficient in understanding long-form multimodal input and generating long-form textual output, outperforming all existing proprietary and open-source MLLMs by large margins.

[Arxiv](https://arxiv.org/abs/2405.14213)