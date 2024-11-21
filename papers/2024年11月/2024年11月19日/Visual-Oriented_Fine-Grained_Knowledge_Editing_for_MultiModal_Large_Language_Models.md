# 针对多模态大型语言模型的面向视觉的细粒度知识编辑

发布时间：2024年11月19日

`LLM应用` `多模态` `知识编辑`

> Visual-Oriented Fine-Grained Knowledge Editing for MultiModal Large Language Models

# 摘要

> 知识编辑旨在高效且划算地纠正错误、更新过时信息。近来，将知识编辑从大型语言模型（LLMs）拓展至多模态大型语言模型（MLLMs）的兴趣愈发浓厚，MLLMs 融合了文本和视觉信息，增添了编辑的复杂性。现有的多模态知识编辑工作多聚焦于面向文本的粗粒度场景，未能应对多模态语境带来的独特挑战。本文提出了一个面向视觉的细粒度多模态知识编辑任务，旨在对有多个交互实体的图像进行精准编辑。我们引入了细粒度视觉知识编辑（FGVEdit）基准来评估该任务。此外，我们还提出了基于多模态范围分类器的知识编辑器（MSCKE）框架。MSCKE 借助融合了视觉和文本信息的多模态范围分类器，能精准识别并更新图像中特定实体的相关知识。此方法在保留无关信息的同时实现精确编辑，克服了传统纯文本编辑方法的局限。在 FGVEdit 基准上的大量实验表明，MSCKE 优于现有方法，展现出其在解决多模态知识编辑复杂难题上的有效性。

> Knowledge editing aims to efficiently and cost-effectively correct inaccuracies and update outdated information. Recently, there has been growing interest in extending knowledge editing from Large Language Models (LLMs) to Multimodal Large Language Models (MLLMs), which integrate both textual and visual information, introducing additional editing complexities. Existing multimodal knowledge editing works primarily focus on text-oriented, coarse-grained scenarios, failing to address the unique challenges posed by multimodal contexts. In this paper, we propose a visual-oriented, fine-grained multimodal knowledge editing task that targets precise editing in images with multiple interacting entities. We introduce the Fine-Grained Visual Knowledge Editing (FGVEdit) benchmark to evaluate this task. Moreover, we propose a Multimodal Scope Classifier-based Knowledge Editor (MSCKE) framework. MSCKE leverages a multimodal scope classifier that integrates both visual and textual information to accurately identify and update knowledge related to specific entities within images. This approach ensures precise editing while preserving irrelevant information, overcoming the limitations of traditional text-only editing methods. Extensive experiments on the FGVEdit benchmark demonstrate that MSCKE outperforms existing methods, showcasing its effectiveness in solving the complex challenges of multimodal knowledge editing.

[Arxiv](https://arxiv.org/abs/2411.12790)