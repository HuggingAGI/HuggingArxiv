# 借助大型语言模型的推理增强，分析患者转录，助力阿尔茨海默病的精准检测。

发布时间：2024年09月19日

`LLM应用` `人工智能`

> Profiling Patient Transcript Using Large Language Model Reasoning Augmentation for Alzheimer's Disease Detection

# 摘要

> 阿尔茨海默病 (AD) 是痴呆症的主要成因，表现为言语和语言能力的逐渐衰退。近期深度学习的进步使得通过自发言语进行 AD 自动检测成为可能。然而，现有的基于转录的检测方法仅关注单个话语的文本模式，缺乏对患者整体语言特征的把握，导致辨别力和解释性不足。尽管大型语言模型 (LLM) 的推理能力有所提升，但在 AD 检测和模型解释方面仍未充分发挥其潜力。为此，我们设计了一个基于 LLM 推理增强的病人级转录分析框架，旨在系统地揭示语言缺陷属性。这些属性的嵌入被整合到 Albert 模型中，用于 AD 检测。实验结果显示，与无推理增强的基线相比，该框架在 ADReSS 数据集上 ACC 和 F1 分别提升了 8.51% 和 8.34%。进一步分析表明，我们识别的语言缺陷属性具有显著效果，且 LLM 在 AD 检测解释方面展现出巨大潜力。

> Alzheimer's disease (AD) stands as the predominant cause of dementia, characterized by a gradual decline in speech and language capabilities. Recent deep-learning advancements have facilitated automated AD detection through spontaneous speech. However, common transcript-based detection methods directly model text patterns in each utterance without a global view of the patient's linguistic characteristics, resulting in limited discriminability and interpretability. Despite the enhanced reasoning abilities of large language models (LLMs), there remains a gap in fully harnessing the reasoning ability to facilitate AD detection and model interpretation. Therefore, we propose a patient-level transcript profiling framework leveraging LLM-based reasoning augmentation to systematically elicit linguistic deficit attributes. The summarized embeddings of the attributes are integrated into an Albert model for AD detection. The framework achieves 8.51\% ACC and 8.34\% F1 improvements on the ADReSS dataset compared to the baseline without reasoning augmentation. Our further analysis shows the effectiveness of our identified linguistic deficit attributes and the potential to use LLM for AD detection interpretation.

[Arxiv](https://arxiv.org/abs/2409.12541)