# 利用CLIP引导的属性感知预训练，提升图像质量评估的泛化能力

发布时间：2024年06月03日

`LLM应用

理由：这篇论文探讨了如何利用视觉语言模型（LLM）来改进无参考图像质量评估（IQA）的方法。通过创新的预训练框架，结合文本提示和大规模数据集，论文提出了一种生成伪标签的方法，以构建适用于IQA的泛化表示。这种方法在多个IQA数据集上展示了优异的性能和泛化能力，并探索了其在评估图像生成模型和训练图像增强模型等实际应用中的潜力。因此，这篇论文属于LLM应用类别，因为它展示了LLM在特定任务（图像质量评估）中的应用和效果。` `图像质量评估` `计算机视觉`

> CLIP-Guided Attribute Aware Pretraining for Generalizable Image Quality Assessment

# 摘要

> 在无参考图像质量评估领域，数据集的局限性一直是开发鲁棒且通用模型的一大障碍。传统方法依赖大规模数据集来提取图像质量的丰富特征。同时，基于视觉语言模型的方法虽有提出，但因通用模型与特定IQA任务间的领域差异，其应用受限。本研究创新性地提出了一种预训练框架，通过精心挑选与图像质量相关的文本提示，利用视觉语言模型生成伪标签，并结合大规模数据集的优势，构建了适用于IQA的泛化表示。我们的方法不仅在多个IQA数据集上取得了顶尖性能，还展现了卓越的泛化能力。基于此，我们探索了其在评估图像生成模型和训练图像增强模型等实际应用中的潜力，并计划公开相关代码，以促进更广泛的研究与应用。

> In no-reference image quality assessment (NR-IQA), the challenge of limited dataset sizes hampers the development of robust and generalizable models. Conventional methods address this issue by utilizing large datasets to extract rich representations for IQA. Also, some approaches propose vision language models (VLM) based IQA, but the domain gap between generic VLM and IQA constrains their scalability. In this work, we propose a novel pretraining framework that constructs a generalizable representation for IQA by selectively extracting quality-related knowledge from VLM and leveraging the scalability of large datasets. Specifically, we carefully select optimal text prompts for five representative image quality attributes and use VLM to generate pseudo-labels. Numerous attribute-aware pseudo-labels can be generated with large image datasets, allowing our IQA model to learn rich representations about image quality. Our approach achieves state-of-the-art performance on multiple IQA datasets and exhibits remarkable generalization capabilities. Leveraging these strengths, we propose several applications, such as evaluating image generation models and training image enhancement models, demonstrating our model's real-world applicability. We will make the code available for access.

![利用CLIP引导的属性感知预训练，提升图像质量评估的泛化能力](../../../paper_images/2406.01020/x1.png)

![利用CLIP引导的属性感知预训练，提升图像质量评估的泛化能力](../../../paper_images/2406.01020/x2.png)

![利用CLIP引导的属性感知预训练，提升图像质量评估的泛化能力](../../../paper_images/2406.01020/x3.png)

![利用CLIP引导的属性感知预训练，提升图像质量评估的泛化能力](../../../paper_images/2406.01020/x4.png)

[Arxiv](https://arxiv.org/abs/2406.01020)