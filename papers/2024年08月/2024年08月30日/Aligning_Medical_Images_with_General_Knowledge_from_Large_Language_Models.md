# 将医学图像与大型语言模型的通用知识相匹配

发布时间：2024年08月30日

`LLM应用` `图像分析`

> Aligning Medical Images with General Knowledge from Large Language Models

# 摘要

> 我们提出的ViP框架，通过视觉症状引导的提示学习，为医学图像分析带来了创新。该框架包含视觉症状生成器和双提示网络两大核心组件，前者从大型预训练语言模型中提取可解释的视觉症状，后者则利用这些症状指导两个提示模块的训练，从而使框架能有效适应医学图像分析。实验证明，ViP在两个挑战性数据集上的表现超越了现有最先进方法。

> Pre-trained large vision-language models (VLMs) like CLIP have revolutionized visual representation learning using natural language as supervisions, and demonstrated promising generalization ability. In this work, we propose ViP, a novel visual symptom-guided prompt learning framework for medical image analysis, which facilitates general knowledge transfer from CLIP. ViP consists of two key components: a visual symptom generator (VSG) and a dual-prompt network. Specifically, VSG aims to extract explicable visual symptoms from pre-trained large language models, while the dual-prompt network utilizes these visual symptoms to guide the training on two learnable prompt modules, i.e., context prompt and merge prompt, which effectively adapts our framework to medical image analysis via large VLMs. Extensive experimental results demonstrate that ViP can outperform state-of-the-art methods on two challenging datasets.

[Arxiv](https://arxiv.org/abs/2409.00341)