# RSTeller：借助公开数据和大型语言模型的丰富语义，在遥感领域中提升视觉语言建模的规模。

发布时间：2024年08月26日

`LLM应用` `地理信息系统`

> RSTeller: Scaling Up Visual Language Modeling in Remote Sensing with Rich Linguistic Semantics from Openly Available Data and Large Language Models

# 摘要

> 遥感领域中，丰富且标注良好的多模态数据对于将复杂视觉场景与人类语言对齐至关重要，推动了多样遥感任务的视觉语言模型发展。然而，大规模为遥感图像添加丰富语言语义标注既昂贵又不切实际。本研究提出一种工作流程，利用大型语言模型从普通OpenStreetMap数据中大规模生成富含语义的多模态数据集，图像源自Google Earth Engine平台。此方法促进配对遥感数据生成，并可轻松扩展。我们介绍的RSTeller数据集包含超百万遥感图像，每张附多描述性标注。实验证明，RSTeller通过持续预训练提升多个视觉语言模型在遥感场景理解性能。我们的方法大幅减少标注遥感图像所需人工努力和专业知识，使高质量标注数据获取更民主化。这一进步推动视觉语言建模发展，并鼓励更广泛遥感研究和应用参与。RSTeller数据集可于https://github.com/SlytherinGe/RSTeller获取。

> Abundant, well-annotated multimodal data in remote sensing are pivotal for aligning complex visual remote sensing (RS) scenes with human language, enabling the development of specialized vision language models across diverse RS interpretation tasks. However, annotating RS images with rich linguistic semantics at scale demands expertise in RS and substantial human labor, making it costly and often impractical. In this study, we propose a workflow that leverages large language models (LLMs) to generate multimodal datasets with semantically rich captions at scale from plain OpenStreetMap (OSM) data for images sourced from the Google Earth Engine (GEE) platform. This approach facilitates the generation of paired remote sensing data and can be readily scaled up using openly available data. Within this framework, we present RSTeller, a multimodal dataset comprising over 1 million RS images, each accompanied by multiple descriptive captions. Extensive experiments demonstrate that RSTeller enhances the performance of multiple existing vision language models for RS scene understanding through continual pre-training. Our methodology significantly reduces the manual effort and expertise needed for annotating remote sensing imagery while democratizing access to high-quality annotated data. This advancement fosters progress in visual language modeling and encourages broader participation in remote sensing research and applications. The RSTeller dataset is available at https://github.com/SlytherinGe/RSTeller.

[Arxiv](https://arxiv.org/abs/2408.14744)