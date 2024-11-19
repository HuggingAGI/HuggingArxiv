# 视觉语言智能体：致力于协作式的上下文对象推理

发布时间：2024年11月15日

`Agent` `计算机视觉` `多模态`

> Visual-Linguistic Agent: Towards Collaborative Contextual Object Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）在图像的描述任务上表现出众，但在精确对象定位上常遇难题，而这恰是可靠视觉解读的关键。相较而言，传统对象检测模型定位精准度高，却因对象间关系建模有限，常得出缺乏上下文连贯性的检测结果。为攻克这一根本局限，我们推出了	extbf{视觉语言智能体（VLA），一个融合了 MLLMs 关系推理长处和传统对象检测器精确定位能力的协作框架。在 VLA 模式下，MLLM 充当核心语言智能体，与负责对象检测和分类的专门视觉智能体协同合作。语言智能体依据对象间的空间及上下文关系进行推理，评估并优化检测结果，分类视觉智能体则提供纠错反馈以提升分类准确率。这种协作方式让 VLA 大幅增强空间推理和对象定位能力，化解多模态理解中的关键难题。在 COCO 数据集上的大量评估显示，多个检测模型的性能显著提升，凸显出 VLA 在精准且上下文连贯的对象检测方面有望树立新标杆的潜力。

> Multimodal Large Language Models (MLLMs) excel at descriptive tasks within images but often struggle with precise object localization, a critical element for reliable visual interpretation. In contrast, traditional object detection models provide high localization accuracy but frequently generate detections lacking contextual coherence due to limited modeling of inter-object relationships. To address this fundamental limitation, we introduce the \textbf{Visual-Linguistic Agent (VLA), a collaborative framework that combines the relational reasoning strengths of MLLMs with the precise localization capabilities of traditional object detectors. In the VLA paradigm, the MLLM serves as a central Linguistic Agent, working collaboratively with specialized Vision Agents for object detection and classification. The Linguistic Agent evaluates and refines detections by reasoning over spatial and contextual relationships among objects, while the classification Vision Agent offers corrective feedback to improve classification accuracy. This collaborative approach enables VLA to significantly enhance both spatial reasoning and object localization, addressing key challenges in multimodal understanding. Extensive evaluations on the COCO dataset demonstrate substantial performance improvements across multiple detection models, highlighting VLA's potential to set a new benchmark in accurate and contextually coherent object detection.

[Arxiv](https://arxiv.org/abs/2411.10252)