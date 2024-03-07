# [RegionGPT——迈向理解视觉区域的新型语言模型，旨在提升视觉与语言融合模型在区域理解层面的表现。](https://arxiv.org/abs/2403.02330)

> RegionGPT: Towards Region Understanding Vision Language Model

发布时间：2024年03月04日

> 尽管 VLMs 结合 LLMs 在处理图像-文本对方面取得迅猛发展，但在细致的局部视觉理解上仍受限于视觉编码器的空间感知局限性和粗略训练数据缺乏详尽的区域特定描述。因此，我们创新提出 RegionGPT（简称 RGPT）框架，专门针对复杂区域级别的描述与理解优化设计。RGPT 对现有 VLMs 中的视觉编码器进行了简洁高效改良，以提升区域特征的空间认知力。为了在要求特定输出范围的任务上取得更优表现，我们在训练和推理阶段均融入了任务导向的指令提示，同时确保模型依然能广泛适用于各类常规任务。另外，我们构建了一条自动化区域描述数据生成流程，为训练集增添了丰富的区域级别详细标注。实验证明，一款通用型 RGPT 模型能够在多种区域级任务上得到有效应用，并能显著提升包括复杂区域描述、推理分析、物体分类及指示表达理解在内的多项任务的表现。

> Vision language models (VLMs) have experienced rapid advancements through the integration of large language models (LLMs) with image-text pairs, yet they struggle with detailed regional visual understanding due to limited spatial awareness of the vision encoder, and the use of coarse-grained training data that lacks detailed, region-specific captions. To address this, we introduce RegionGPT (short as RGPT), a novel framework designed for complex region-level captioning and understanding. RGPT enhances the spatial awareness of regional representation with simple yet effective modifications to existing visual encoders in VLMs. We further improve performance on tasks requiring a specific output scope by integrating task-guided instruction prompts during both training and inference phases, while maintaining the model's versatility for general-purpose tasks. Additionally, we develop an automated region caption data generation pipeline, enriching the training set with detailed region-level captions. We demonstrate that a universal RGPT model can be effectively applied and significantly enhancing performance across a range of region-level tasks, including but not limited to complex region descriptions, reasoning, object classification, and referring expressions comprehension.

`Agent`