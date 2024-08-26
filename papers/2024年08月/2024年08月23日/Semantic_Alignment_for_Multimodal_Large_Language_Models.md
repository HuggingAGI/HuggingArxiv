# 多模态大型语言模型的语义对齐

发布时间：2024年08月23日

`LLM应用` `计算机视觉` `人工智能`

> Semantic Alignment for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 在处理多图像跨模态指令方面取得了显著进展，尤其是在高度相似图像的场景中。然而，现有模型在独立提取每个图像的视觉标记时，可能导致语义优先级不同，进而影响后续分析中图像间链接信息的保留。针对这一问题，我们提出了语义对齐 (SAM) 方法，通过双向语义指导增强链接信息的保留，并在输入 LLM 前对齐图像语义。我们还创建了包含多样图像的 MmLINK 数据集，实验证明 SAM 在组描述和叙事任务上显著优于现有方法。项目详情见：https://mccartney01.github.io/SAM。

> Research on Multi-modal Large Language Models (MLLMs) towards the multi-image cross-modal instruction has received increasing attention and made significant progress, particularly in scenarios involving closely resembling images (e.g., change captioning). Existing MLLMs typically follow a two-step process in their pipelines: first, extracting visual tokens independently for each input image, and then aligning these visual tokens from different images with the Large Language Model (LLM) in its textual feature space. However, the independent extraction of visual tokens for each image may result in different semantics being prioritized for different images in the first step, leading to a lack of preservation of linking information among images for subsequent LLM analysis. This issue becomes more serious in scenarios where significant variations exist among the images (e.g., visual storytelling). To address this challenge, we introduce Semantic Alignment for Multi-modal large language models (SAM). By involving the bidirectional semantic guidance between different images in the visual-token extraction process, SAM aims to enhance the preservation of linking information for coherent analysis and align the semantics of different images before feeding them into LLM. As the test bed, we propose a large-scale dataset named MmLINK consisting of 69K samples. Different from most existing datasets for MLLMs fine-tuning, our MmLINK dataset comprises multi-modal instructions with significantly diverse images. Extensive experiments on the group captioning task and the storytelling task prove the effectiveness of our SAM model, surpassing the state-of-the-art methods by a large margin (+37% for group captioning and +22% for storytelling on CIDEr score). Project page: https://mccartney01.github.io/SAM.

[Arxiv](https://arxiv.org/abs/2408.12867)