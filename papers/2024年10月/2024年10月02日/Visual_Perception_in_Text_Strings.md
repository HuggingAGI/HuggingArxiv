# 文本中的视觉感知

发布时间：2024年10月02日

`LLM应用` `人工智能` `视觉识别`

> Visual Perception in Text Strings

# 摘要

> 理解连续字符中的视觉语义，对 LLM 和 MLLM 至关重要。这种工件的独特之处在于，相同信息能轻松在文本和图像中表达，成为分析现代模型模态无关视觉理解能力的重要工具。我们选择 ASCII 艺术为代表，将其视为识别任务，构建了精细分类的评估数据集，并收集训练集以测试模型的视觉感知能力。结果显示，人类准确率接近 100%，而最先进的 LLM 和 MLLM 则远远落后。仅凭文本输入，模型对某些概念的识别准确率超过 60%，但平均准确率仅为约 30%。提供图像输入时，GPT-4o 的准确率达到 82.68%，比最强开源 MLLM 高出 21.95%。尽管模型对不同模态的 ASCII 艺术有偏好，但在同时提供两种模态时，MLLM 并未受益。监督微调虽能提高准确性，特别是在图像模态下，但也凸显了改进模态间信息融合训练技术的必要性。

> Understanding visual semantics embedded in consecutive characters is a crucial capability for both large language models (LLMs) and multi-modal large language models (MLLMs). This type of artifact possesses the unique characteristic that identical information can be readily formulated in both texts and images, making them a significant proxy for analyzing modern LLMs' and MLLMs' capabilities in modality-agnostic vision understanding. In this work, we select ASCII art as a representative artifact, where the lines and brightness used to depict each concept are rendered by characters, and we frame the problem as an ASCII art recognition task. We benchmark model performance on this task by constructing an evaluation dataset with an elaborate categorization tree and also collect a training set to elicit the models' visual perception ability. Through a comprehensive analysis of dozens of models, results reveal that although humans can achieve nearly 100% accuracy, the state-of-the-art LLMs and MLLMs lag far behind. Models are capable of recognizing concepts depicted in the ASCII arts given only text inputs indicated by over 60% accuracy for some concepts, but most of them achieves merely around 30% accuracy when averaged across all categories. When provided with images as inputs, GPT-4o gets 82.68%, outperforming the strongest open-source MLLM by 21.95%. Although models favor different kinds of ASCII art depending on the modality provided, none of the MLLMs successfully benefit when both modalities are supplied simultaneously. Moreover, supervised fine-tuning helps improve models' accuracy especially when provided with the image modality, but also highlights the need for better training techniques to enhance the information fusion among modalities.

[Arxiv](https://arxiv.org/abs/2410.01733)