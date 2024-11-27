# InsightEdit：致力于实现更优的图像编辑指令遵循

发布时间：2024年11月26日

`LLM应用` `图像编辑` `多模态`

> InsightEdit: Towards Better Instruction Following for Image Editing

# 摘要

> 在本文中，我们聚焦于基于指令的图像编辑任务。此前的 InstructPix2Pix、InstructDiffusion 以及 SmartEdit 等工作已对端到端编辑进行了探索。然而，仍存在两大局限：其一，现有的数据集存在分辨率低、背景一致性欠佳、指令过于简单等问题；其二，当前的方法主要依赖文本条件，丰富的图像信息未被充分挖掘，所以在遵循复杂指令及保持背景一致性方面表现较差。针对这些问题，我们先是通过新颖的数据构建流程精心打造了 AdvancedEdit 数据集，形成了一个具备高视觉质量、复杂指令和良好背景一致性的大规模数据集。接着，为进一步融入丰富的图像信息，我们引入了一种双流桥接机制，借助强大的多模态大型语言模型（MLLM）推导出的文本和视觉特征，更精准地引导图像编辑过程。众多结果显示，我们的方法 InsightEdit 达到了业界领先水平，在遵循复杂指令以及保持与原始图像的高背景一致性方面表现卓越。

> In this paper, we focus on the task of instruction-based image editing. Previous works like InstructPix2Pix, InstructDiffusion, and SmartEdit have explored end-to-end editing. However, two limitations still remain: First, existing datasets suffer from low resolution, poor background consistency, and overly simplistic instructions. Second, current approaches mainly condition on the text while the rich image information is underexplored, therefore inferior in complex instruction following and maintaining background consistency. Targeting these issues, we first curated the AdvancedEdit dataset using a novel data construction pipeline, formulating a large-scale dataset with high visual quality, complex instructions, and good background consistency. Then, to further inject the rich image information, we introduce a two-stream bridging mechanism utilizing both the textual and visual features reasoned by the powerful Multimodal Large Language Models (MLLM) to guide the image editing process more precisely. Extensive results demonstrate that our approach, InsightEdit, achieves state-of-the-art performance, excelling in complex instruction following and maintaining high background consistency with the original image.

[Arxiv](https://arxiv.org/abs/2411.17323)