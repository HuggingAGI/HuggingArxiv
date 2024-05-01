# 神经视觉转语言：利用非侵入性大脑记录实现图像重建与互动

发布时间：2024年04月30日

`LLM应用` `神经科学` `人机交互`

> Neuro-Vision to Language: Image Reconstruction and Interaction via Non-invasive Brain Recordings

# 摘要

> 破译非侵入性脑电图记录对于深化我们对人类认知的理解极为关键，尽管这一过程因个体差异和神经信号的复杂性而充满挑战。传统解码方法依赖于定制化模型和大量试验，且在视觉重建任务中可解释性不足。我们提出的框架，通过三维视觉变换器整合了三维大脑结构与视觉语义，使得特征提取器能够高效地将功能磁共振成像（fMRI）特征与多层次视觉嵌入相匹配，从而省去了对个体定制模型的依赖，并实现了单次试验数据的提取。该提取器将多层次视觉特征整合进单一网络，简化了与大型语言模型（LLMs）的整合流程。我们还通过引入与fMRI图像相关的多种文本数据，增强了fMRI数据集，以促进多模态大型模型的发展。与LLMs的结合显著提升了解码能力，使得大脑字幕、问答、详细描述、复杂推理和视觉重建等任务得以实现。本方法不仅在这些任务上展现了卓越的性能，还能精确地识别和操作脑信号中的语言概念，增强了解码过程的可解释性，并为神经过程的理解提供了更深层次的洞见。这些进展极大地扩展了非侵入性脑解码技术在神经科学和人机交互领域的应用前景，为发展高级脑-机接口和认知模型铺平了道路。

> Decoding non-invasive brain recordings is crucial for advancing our understanding of human cognition, yet faces challenges from individual differences and complex neural signal representations. Traditional methods require custom models and extensive trials, and lack interpretability in visual reconstruction tasks. Our framework integrating integrates 3D brain structures with visual semantics by Vision Transformer 3D. The unified feature extractor aligns fMRI features with multiple levels of visual embeddings efficiently, removing the need for individual-specific models and allowing extraction from single-trial data. This extractor consolidates multi-level visual features into one network, simplifying integration with Large Language Models (LLMs). Additionally, we have enhanced the fMRI dataset with various fMRI-image related textual data to support multimodal large model development. The integration with LLMs enhances decoding capabilities, enabling tasks like brain captioning, question-answering, detailed descriptions, complex reasoning, and visual reconstruction. Our approach not only shows superior performance across these tasks but also precisely identifies and manipulates language-based concepts within brain signals, enhancing interpretability and providing deeper neural process insights. These advances significantly broaden non-invasive brain decoding applicability in neuroscience and human-computer interaction, setting the stage for advanced brain-computer interfaces and cognitive models.

[Arxiv](https://arxiv.org/abs/2404.19438)