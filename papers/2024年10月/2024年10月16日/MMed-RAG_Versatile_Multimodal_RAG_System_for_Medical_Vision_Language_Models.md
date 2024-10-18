# MMed-RAG：专为医学视觉语言模型设计的多功能多模态系统

发布时间：2024年10月16日

`RAG` `人工智能`

> MMed-RAG: Versatile Multimodal RAG System for Medical Vision Language Models

# 摘要

> AI 在医疗领域的应用潜力巨大，尤其是在疾病诊断和治疗规划方面。医学视觉语言模型（Med-LVLMs）的进步为交互式诊断工具带来了新机遇，但这些模型常因事实幻觉导致误诊。微调和检索增强生成（RAG）是解决这些问题的有效手段，但高质量数据和数据分布偏移问题限制了微调的应用。尽管 RAG 轻便高效，现有方法在适应不同医学领域时仍存在对齐问题。为此，我们提出了多模态 RAG 系统 MMed-RAG，通过领域感知检索、自适应上下文选择和可证明的偏好微调策略，显著提升 Med-LVLMs 的事实准确性。实验结果显示，MMed-RAG 在多个医学数据集上的事实准确性平均提高了 43.8%。相关数据和代码已公开，详见 https://github.com/richard-peng-xia/MMed-RAG。

> Artificial Intelligence (AI) has demonstrated significant potential in healthcare, particularly in disease diagnosis and treatment planning. Recent progress in Medical Large Vision-Language Models (Med-LVLMs) has opened up new possibilities for interactive diagnostic tools. However, these models often suffer from factual hallucination, which can lead to incorrect diagnoses. Fine-tuning and retrieval-augmented generation (RAG) have emerged as methods to address these issues. However, the amount of high-quality data and distribution shifts between training data and deployment data limit the application of fine-tuning methods. Although RAG is lightweight and effective, existing RAG-based approaches are not sufficiently general to different medical domains and can potentially cause misalignment issues, both between modalities and between the model and the ground truth. In this paper, we propose a versatile multimodal RAG system, MMed-RAG, designed to enhance the factuality of Med-LVLMs. Our approach introduces a domain-aware retrieval mechanism, an adaptive retrieved contexts selection method, and a provable RAG-based preference fine-tuning strategy. These innovations make the RAG process sufficiently general and reliable, significantly improving alignment when introducing retrieved contexts. Experimental results across five medical datasets (involving radiology, ophthalmology, pathology) on medical VQA and report generation demonstrate that MMed-RAG can achieve an average improvement of 43.8% in the factual accuracy of Med-LVLMs. Our data and code are available in https://github.com/richard-peng-xia/MMed-RAG.

[Arxiv](https://arxiv.org/abs/2410.13085)