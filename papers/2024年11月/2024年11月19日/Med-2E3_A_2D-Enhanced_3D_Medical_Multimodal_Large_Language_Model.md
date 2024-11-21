# Med-2E3：一款 2D 增强型的 3D 医学多模态大型语言模型

发布时间：2024年11月19日

`LLM应用` `医学图像`

> Med-2E3: A 2D-Enhanced 3D Medical Multimodal Large Language Model

# 摘要

> 3D 医学图像的分析对现代医疗保健意义重大，然而传统的特定任务模型因在不同临床场景中的通用性受限，已愈发难以满足需求。多模态大型语言模型（MLLMs）为这些难题带来了颇具前景的解决办法。但现有的 MLLMs 在充分挖掘 3D 医学图像中丰富的分层信息方面存在不足。受临床实践的启发，即放射科医生会同时关注 3D 空间结构和 2D 平面内容，我们提出了 Med-2E3，这是一款用于 3D 医学图像分析的新型 MLLM，它融合了 3D 和 2D 编码器。为更有效地聚合 2D 特征，我们设计了文本引导的切片间（TG-IS）评分模块，该模块依据切片内容和任务指令为每个 2D 切片的注意力打分。据我们所知，Med-2E3 是首个将 3D 和 2D 特征整合用于 3D 医学图像分析的 MLLM。在大规模、开源的 3D 医学多模态基准上开展的实验表明，Med-2E3 呈现出特定任务的注意力分布，且显著优于当下最先进的模型，报告生成方面提升了 14%，医学视觉问答（VQA）方面提高了 5%，凸显了该模型在处理复杂多模态临床任务上的潜力。代码将在被接收后发布。

> The analysis of 3D medical images is crucial for modern healthcare, yet traditional task-specific models are becoming increasingly inadequate due to limited generalizability across diverse clinical scenarios. Multimodal large language models (MLLMs) offer a promising solution to these challenges. However, existing MLLMs have limitations in fully leveraging the rich, hierarchical information embedded in 3D medical images. Inspired by clinical practice, where radiologists focus on both 3D spatial structure and 2D planar content, we propose Med-2E3, a novel MLLM for 3D medical image analysis that integrates 3D and 2D encoders. To aggregate 2D features more effectively, we design a Text-Guided Inter-Slice (TG-IS) scoring module, which scores the attention of each 2D slice based on slice contents and task instructions. To the best of our knowledge, Med-2E3 is the first MLLM to integrate both 3D and 2D features for 3D medical image analysis. Experiments on a large-scale, open-source 3D medical multimodal benchmark demonstrate that Med-2E3 exhibits task-specific attention distribution and significantly outperforms current state-of-the-art models, with a 14% improvement in report generation and a 5% gain in medical visual question answering (VQA), highlighting the model's potential in addressing complex multimodal clinical tasks. The code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2411.12783)