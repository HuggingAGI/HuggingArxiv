# ARMADA：一种基于属性的多模态数据增强技术

发布时间：2024年08月19日

`LLM应用` `人工智能` `计算机视觉`

> ARMADA: Attribute-Based Multimodal Data Augmentation

# 摘要

> 在多模态语言模型中，手动标注高质量的图像-文本对数据成本极高。现有数据增强框架虽有改进，但常导致语义不一致或生成不真实图像。为此，我们提出基于属性的多模态数据增强方法 ARMADA，通过知识引导操作实体视觉属性，从原始文本中提取实体及属性，在知识库和大型语言模型指导下寻找替代值，并利用图像编辑模型进行图像编辑。ARMADA 框架能生成语义一致且独特的图像-文本对，利用知识库层次结构生成不同类别的视觉相似图像，并运用 LLM 的常识知识调节背景等辅助属性，以更稳健地表示实体。实证结果显示，ARMADA 能有效提升数据质量和模型性能，强调了利用外部知识增强解释性和现实世界基础的重要性。

> In Multimodal Language Models (MLMs), the cost of manually annotating high-quality image-text pair data for fine-tuning and alignment is extremely high. While existing multimodal data augmentation frameworks propose ways to augment image-text pairs, they either suffer from semantic inconsistency between texts and images, or generate unrealistic images, causing knowledge gap with real world examples. To address these issues, we propose Attribute-based Multimodal Data Augmentation (ARMADA), a novel multimodal data augmentation method via knowledge-guided manipulation of visual attributes of the mentioned entities. Specifically, we extract entities and their visual attributes from the original text data, then search for alternative values for the visual attributes under the guidance of knowledge bases (KBs) and large language models (LLMs). We then utilize an image-editing model to edit the images with the extracted attributes. ARMADA is a novel multimodal data generation framework that: (i) extracts knowledge-grounded attributes from symbolic KBs for semantically consistent yet distinctive image-text pair generation, (ii) generates visually similar images of disparate categories using neighboring entities in the KB hierarchy, and (iii) uses the commonsense knowledge of LLMs to modulate auxiliary visual attributes such as backgrounds for more robust representation of original entities. Our empirical results over four downstream tasks demonstrate the efficacy of our framework to produce high-quality data and enhance the model performance. This also highlights the need to leverage external knowledge proxies for enhanced interpretability and real-world grounding.

[Arxiv](https://arxiv.org/abs/2408.10086)