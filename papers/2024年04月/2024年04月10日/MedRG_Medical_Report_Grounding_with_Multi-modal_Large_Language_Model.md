# MedRG：借助多模态大型语言模型实现医学报告的精准定位

发布时间：2024年04月10日

`LLM应用` `医学图像处理`

> MedRG: Medical Report Grounding with Multi-modal Large Language Model

# 摘要

> 医学报告定位对于根据特定短语查询在医学图像中找出最相关区域极为关键，这对于医学图像分析和放射学诊断来说至关重要。但目前的视觉定位技术往往需要手动从医学报告中提取关键词，这对系统效能和医生工作都构成了巨大压力。本文提出了一个创新框架——医学报告定位（MedRG），它是一个端到端的解决方案，通过在词汇中引入一个特殊的标记BOX，利用多模态大型语言模型预测关键词，该标记作为嵌入，用于激活检测功能。接着，视觉编码器和解码器共同解析隐藏的嵌入和输入的医学图像，生成对应的定位框。实验结果显示，MedRG的有效性超越了目前所有最先进的医学短语定位技术。这项研究是医学报告定位任务的首次探索，为该领域的发展迈出了重要一步。

> Medical Report Grounding is pivotal in identifying the most relevant regions in medical images based on a given phrase query, a critical aspect in medical image analysis and radiological diagnosis. However, prevailing visual grounding approaches necessitate the manual extraction of key phrases from medical reports, imposing substantial burdens on both system efficiency and physicians. In this paper, we introduce a novel framework, Medical Report Grounding (MedRG), an end-to-end solution for utilizing a multi-modal Large Language Model to predict key phrase by incorporating a unique token, BOX, into the vocabulary to serve as an embedding for unlocking detection capabilities. Subsequently, the vision encoder-decoder jointly decodes the hidden embedding and the input medical image, generating the corresponding grounding box. The experimental results validate the effectiveness of MedRG, surpassing the performance of the existing state-of-the-art medical phrase grounding methods. This study represents a pioneering exploration of the medical report grounding task, marking the first-ever endeavor in this domain.

![MedRG：借助多模态大型语言模型实现医学报告的精准定位](../../../paper_images/2404.06798/x1.png)

![MedRG：借助多模态大型语言模型实现医学报告的精准定位](../../../paper_images/2404.06798/x2.png)

![MedRG：借助多模态大型语言模型实现医学报告的精准定位](../../../paper_images/2404.06798/x3.png)

![MedRG：借助多模态大型语言模型实现医学报告的精准定位](../../../paper_images/2404.06798/x4.png)

[Arxiv](https://arxiv.org/abs/2404.06798)