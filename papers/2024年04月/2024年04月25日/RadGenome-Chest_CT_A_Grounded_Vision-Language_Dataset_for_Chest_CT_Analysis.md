# RadGenome-Chest CT：一个为胸部 CT 影像分析量身定制的视觉与语言结合的数据集

发布时间：2024年04月25日

`LLM应用` `医学图像处理` `人工智能`

> RadGenome-Chest CT: A Grounded Vision-Language Dataset for Chest CT Analysis

# 摘要

> 近期，医学人工智能（AI4Medicine）领域的研究者们对开发通用基础模型表现出极大兴趣。这些模型的开发关键在于依赖数据集的规模化，特别是需要创建包含不同成像技术下多样化监督信号的开源医学图像数据库。本文提出了RadGenome-Chest CT，这是一个基于CT-RATE的全面、大规模、区域导向的3D胸部CT解读数据集。我们采用了最新的先进通用分割技术和大型语言模型，对原始数据集（超过25,692个非增强3D胸部CT图像和20,000名患者的报告）进行了以下几方面的扩展：（i）涵盖197个类别的器官级分割掩模，为解读提供推理的视觉线索；（ii）66.5万个多粒度的地面化报告，每个报告句子都与CT图像中的相应解剖区域通过分割掩模关联；（iii）130万个地面化的VQA对，问题和答案均与参考分割掩模相连，使模型能够将视觉证据与文本解释相联系。验证集中的所有地面化报告和VQA对都经过了人工验证，以确保数据集的质量。我们认为，RadGenome-Chest CT能够显著推动多模态医学基础模型的发展，通过训练模型基于特定分割区域生成文本，这是之前相关数据集所无法实现的。我们将发布所有分割掩模、地面化报告和VQA对，以促进该领域的进一步研究和开发。

> Developing generalist foundation model has recently attracted tremendous attention among researchers in the field of AI for Medicine (AI4Medicine). A pivotal insight in developing these models is their reliance on dataset scaling, which emphasizes the requirements on developing open-source medical image datasets that incorporate diverse supervision signals across various imaging modalities. In this paper, we introduce RadGenome-Chest CT, a comprehensive, large-scale, region-guided 3D chest CT interpretation dataset based on CT-RATE. Specifically, we leverage the latest powerful universal segmentation and large language models, to extend the original datasets (over 25,692 non-contrast 3D chest CT volume and reports from 20,000 patients) from the following aspects: (i) organ-level segmentation masks covering 197 categories, which provide intermediate reasoning visual clues for interpretation; (ii) 665 K multi-granularity grounded reports, where each sentence of the report is linked to the corresponding anatomical region of CT volume in the form of a segmentation mask; (iii) 1.3 M grounded VQA pairs, where questions and answers are all linked with reference segmentation masks, enabling models to associate visual evidence with textual explanations. All grounded reports and VQA pairs in the validation set have gone through manual verification to ensure dataset quality. We believe that RadGenome-Chest CT can significantly advance the development of multimodal medical foundation models, by training to generate texts based on given segmentation regions, which is unattainable with previous relevant datasets. We will release all segmentation masks, grounded reports, and VQA pairs to facilitate further research and development in this field.

[Arxiv](https://arxiv.org/abs/2404.16754)