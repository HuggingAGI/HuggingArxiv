# CDChat：专为遥感变化描述设计的大型多模态模型

发布时间：2024年09月24日

`LLM应用` `地理信息系统`

> CDChat: A Large Multimodal Model for Remote Sensing Change Description

# 摘要

> 大型多模态模型 (LMMs) 在自然图像领域表现出色，但在遥感图像描述方面却力不从心。GeoChat 虽在遥感任务中表现不俗，却难以捕捉双时相图像的变化。为此，我们推出了一款新型 LMM，并引入了一个变化描述数据集，助其更好地解读遥感图像的变化。经过微调，LLaVA-1.5 模型在性能上更上一层楼。

> Large multimodal models (LMMs) have shown encouraging performance in the natural image domain using visual instruction tuning. However, these LMMs struggle to describe the content of remote sensing images for tasks such as image or region grounding, classification, etc. Recently, GeoChat make an effort to describe the contents of the RS images. Although, GeoChat achieves promising performance for various RS tasks, it struggles to describe the changes between bi-temporal RS images which is a key RS task. This necessitates the development of an LMM that can describe the changes between the bi-temporal RS images. However, there is insufficiency of datasets that can be utilized to tune LMMs. In order to achieve this, we introduce a change description instruction dataset that can be utilized to finetune an LMM and provide better change descriptions for RS images. Furthermore, we show that the LLaVA-1.5 model, with slight modifications, can be finetuned on the change description instruction dataset and achieve favorably better performance.

[Arxiv](https://arxiv.org/abs/2409.16261)