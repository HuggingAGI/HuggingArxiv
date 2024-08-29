# 分割、征服与结合：一种无需训练的框架，专为多模态大型语言模型中的高分辨率图像感知设计。

发布时间：2024年08月28日

`LLM应用` `图像处理` `多模态技术`

> Divide, Conquer and Combine: A Training-Free Framework for High-Resolution Image Perception in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）虽有进步，但在高分辨率图像细节识别上仍显不足。现有基准仅支持至2K分辨率，未能全面测试SOTA模型的真实能力。为此，我们推出HR-Bench，首个专为4K和8K图像设计的评估基准。实验表明，尽管下采样导致视觉信息丢失，但结合文本等互补模态可有效弥补。基于此，我们提出无需训练的DC$^2$框架，通过分割、描述、整合三步，显著提升MLLM对HR图像的感知能力。实验结果显示，DC$^2$在HR-Bench及通用多模态基准上分别提升6%和8%，远超SOTA模型的63%准确率，接近人类的87%。我们期待这一成果能推动多模态领域的研发进步。

> Multimodal large language models (MLLMs) have experienced significant advancements recently, but still struggle to recognize and interpret intricate details in high-resolution (HR) images effectively. While state-of-the-art (SOTA) MLLMs claim to process images at 4K resolution, existing MLLM benchmarks only support up to 2K, leaving the capabilities of SOTA models on true HR images largely untested. Furthermore, existing methods for enhancing HR image perception in MLLMs rely on computationally expensive visual instruction tuning. To address these limitations, we introduce HR-Bench, the first deliberately designed benchmark to rigorously evaluate MLLM performance on 4K&8K images. Through extensive experiments, we demonstrate that while downsampling HR images leads to vision information loss, leveraging complementary modalities, e.g., text, can effectively compensate for this loss. Building upon this insight, we propose Divide, Conquer and Combine (DC$^2$), a novel training-free framework for enhancing MLLM perception of HR images. DC$^2$ follows a three-staged approach: 1) Divide: recursively partitioning the HR image into patches and merging similar patches to minimize computational overhead, 2) Conquer: leveraging the MLLM to generate accurate textual descriptions for each image patch, and 3) Combine: utilizing the generated text descriptions to enhance the MLLM's understanding of the overall HR image. Extensive experiments show that: 1) the SOTA MLLM achieves 63% accuracy, which is markedly lower than the 87% accuracy achieved by humans on HR-Bench; 2) our DC$^2$ brings consistent and significant improvements (a relative increase of +6% on HR-Bench and +8% on general multimodal benchmarks). The benchmark and code will be released to facilitate the multimodal R&D community.

[Arxiv](https://arxiv.org/abs/2408.15556)