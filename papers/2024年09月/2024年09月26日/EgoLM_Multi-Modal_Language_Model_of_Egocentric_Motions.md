# EgoLM：探索以自我为中心运动的多模态语言模型

发布时间：2024年09月26日

`LLM应用` `可穿戴设备` `人工智能`

> EgoLM: Multi-Modal Language Model of Egocentric Motions

# 摘要

> 随着可穿戴设备的普及，学习以自我为中心的运动对于开发上下文AI至关重要。我们提出了EgoLM，一个从多模态输入中跟踪和理解以自我为中心运动的框架。EgoLM利用丰富的上下文来解决单一模态下的运动跟踪和理解问题。我们的核心思想是使用LLM对运动和语言的联合分布进行建模。通过将多模态输入编码并投影到语言模型的潜在空间，EgoLM能够生成运动或文本，从而实现运动跟踪和理解。大规模实验证明了EgoLM在通用以自我为中心学习中的有效性。

> As the prevalence of wearable devices, learning egocentric motions becomes essential to develop contextual AI. In this work, we present EgoLM, a versatile framework that tracks and understands egocentric motions from multi-modal inputs, e.g., egocentric videos and motion sensors. EgoLM exploits rich contexts for the disambiguation of egomotion tracking and understanding, which are ill-posed under single modality conditions. To facilitate the versatile and multi-modal framework, our key insight is to model the joint distribution of egocentric motions and natural languages using large language models (LLM). Multi-modal sensor inputs are encoded and projected to the joint latent space of language models, and used to prompt motion generation or text generation for egomotion tracking or understanding, respectively. Extensive experiments on large-scale multi-modal human motion dataset validate the effectiveness of EgoLM as a generalist model for universal egocentric learning.

[Arxiv](https://arxiv.org/abs/2409.18127)