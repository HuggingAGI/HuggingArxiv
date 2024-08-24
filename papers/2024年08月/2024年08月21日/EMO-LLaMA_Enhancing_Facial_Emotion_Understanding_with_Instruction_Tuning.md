# EMO-LLaMA：借助指令调优技术，提升面部情绪识别能力

发布时间：2024年08月21日

`LLM应用` `人机交互` `情感分析`

> EMO-LLaMA: Enhancing Facial Emotion Understanding with Instruction Tuning

# 摘要

> 面部表情识别（FER）在情感人工智能领域占据重要地位。尽管近年来研究成果斐然，但现有FER方法在泛化性、语义信息缺失及图像视频处理一体化方面仍显不足，限制了其在多模态情感分析和人机交互中的应用。多模态大型语言模型（MLLMs）的兴起为解决这些难题提供了新思路，有望突破传统FER的局限。然而，将预训练MLLMs直接应用于FER仍需克服诸多挑战。我们的零-shot评估发现，现有开源MLLMs在FER性能上与GPT-4V及当前顶尖监督方法存在明显差距。为此，本文致力于提升MLLMs的面部表情理解能力。我们首先利用Gemini为五个FER数据集生成指令数据，进而提出新型MLLM——EMO-LLaMA，它融合预训练面部分析网络的先验信息，强化面部特征提取。我们设计了面部信息挖掘模块，兼顾全局与局部特征，并引入手工提示，考虑年龄、性别、种族等情感差异因素。实验证明，EMO-LLaMA在静态与动态FER数据集上均表现出色，达到或接近顶尖水平。相关资源已公开于https://github.com/xxtars/EMO-LLaMA。

> Facial expression recognition (FER) is an important research topic in emotional artificial intelligence. In recent decades, researchers have made remarkable progress. However, current FER paradigms face challenges in generalization, lack semantic information aligned with natural language, and struggle to process both images and videos within a unified framework, making their application in multimodal emotion understanding and human-computer interaction difficult. Multimodal Large Language Models (MLLMs) have recently achieved success, offering advantages in addressing these issues and potentially overcoming the limitations of current FER paradigms. However, directly applying pre-trained MLLMs to FER still faces several challenges. Our zero-shot evaluations of existing open-source MLLMs on FER indicate a significant performance gap compared to GPT-4V and current supervised state-of-the-art (SOTA) methods. In this paper, we aim to enhance MLLMs' capabilities in understanding facial expressions. We first generate instruction data for five FER datasets with Gemini. We then propose a novel MLLM, named EMO-LLaMA, which incorporates facial priors from a pretrained facial analysis network to enhance human facial information. Specifically, we design a Face Info Mining module to extract both global and local facial information. Additionally, we utilize a handcrafted prompt to introduce age-gender-race attributes, considering the emotional differences across different human groups. Extensive experiments show that EMO-LLaMA achieves SOTA-comparable or competitive results across both static and dynamic FER datasets. The instruction dataset and code are available at https://github.com/xxtars/EMO-LLaMA.

[Arxiv](https://arxiv.org/abs/2408.11424)