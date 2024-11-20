# Just KIDDIN：用于不良模因检测的知识注入与提炼

发布时间：2024年11月18日

`LLM应用` `在线环境` `毒性检测`

> Just KIDDIN: Knowledge Infusion and Distillation for Detection of INdecent Memes

# 摘要

> 在在线多模态环境里，毒性识别是个难题，原因在于跨模态（像文本和视觉）的上下文连接颇为复杂。本文中，我们提出了一个全新的框架，它融合了来自大型视觉语言模型（LVLMs）的知识蒸馏（KD）与知识注入，以此提升仇恨模因中毒性检测的表现。我们的办法是从ConceptNet（一个大规模的常识知识图谱（KG））里提取子知识图谱，并将其注入紧凑的VLM框架。标题里有毒的短语和模因之间的关系上下文，还有模因中的视觉概念，都增强了模型的推理能力。我们针对两个仇恨言论基准数据集所做研究的实验结果显示，在AU-ROC、F1和召回率方面，相比最先进的基线，性能分别提高了1.1％、7％和35％。鉴于毒性检测任务的上下文复杂，我们的方法凸显了通过混合神经符号方法，从显性（即KG）和隐性（即LVLMs）的上下文线索中学习的重要性。这对于现实世界的应用极为关键，在这些应用里，准确且可扩展地识别有毒内容对于营造更安全的在线环境至关重要。

> Toxicity identification in online multimodal environments remains a challenging task due to the complexity of contextual connections across modalities (e.g., textual and visual). In this paper, we propose a novel framework that integrates Knowledge Distillation (KD) from Large Visual Language Models (LVLMs) and knowledge infusion to enhance the performance of toxicity detection in hateful memes. Our approach extracts sub-knowledge graphs from ConceptNet, a large-scale commonsense Knowledge Graph (KG) to be infused within a compact VLM framework. The relational context between toxic phrases in captions and memes, as well as visual concepts in memes enhance the model's reasoning capabilities. Experimental results from our study on two hate speech benchmark datasets demonstrate superior performance over the state-of-the-art baselines across AU-ROC, F1, and Recall with improvements of 1.1%, 7%, and 35%, respectively. Given the contextual complexity of the toxicity detection task, our approach showcases the significance of learning from both explicit (i.e. KG) as well as implicit (i.e. LVLMs) contextual cues incorporated through a hybrid neurosymbolic approach. This is crucial for real-world applications where accurate and scalable recognition of toxic content is critical for creating safer online environments.

[Arxiv](https://arxiv.org/abs/2411.12174)