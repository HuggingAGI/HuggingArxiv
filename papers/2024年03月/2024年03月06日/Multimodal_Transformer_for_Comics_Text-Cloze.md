# 针对漫画文本完形填空任务，我们采用多模态 Transformer 技术，旨在整合图像与文本信息，以提升模型在理解漫画情境并准确完成文本完形填空方面的性能。

发布时间：2024年03月06日

`LLM应用`

> Multimodal Transformer for Comics Text-Cloze

# 摘要

> 本工作深入探索漫画这一视觉与文字交融的领域，聚焦于“文本完形”任务——根据周边面板选取正确文字填充漫画格。传统循环神经网络方法受限于OCR识别准确性和模型内在局限，在此任务上力不从心。为此，我们创新推出一种专为“文本完形”定制的多模态大型语言模型架构（Multimodal-LLM），不仅在易、难两种变体任务上超越现有最优模型10%，而且其核心组件是一个经过SimCLR自监督方式微调以适应漫画领域的Domain-Adapted ResNet-50视觉编码器，尽管参数量仅为同类复杂模型的五分之一，却能实现媲美甚至超越的表现。同时，我们还提供了新一批对该数据集的OCR标注信息，有效提升模型输入质量，进而带来额外1%的性能增长。最终，我们进一步将任务拓展至生成式模式，设立了全新的基准，并为漫画分析领域的研究开启了更多可能的方向。

> This work explores a closure task in comics, a medium where visual and textual elements are intricately intertwined. Specifically, Text-cloze refers to the task of selecting the correct text to use in a comic panel, given its neighboring panels. Traditional methods based on recurrent neural networks have struggled with this task due to limited OCR accuracy and inherent model limitations. We introduce a novel Multimodal Large Language Model (Multimodal-LLM) architecture, specifically designed for Text-cloze, achieving a 10% improvement over existing state-of-the-art models in both its easy and hard variants. Central to our approach is a Domain-Adapted ResNet-50 based visual encoder, fine-tuned to the comics domain in a self-supervised manner using SimCLR. This encoder delivers comparable results to more complex models with just one-fifth of the parameters. Additionally, we release new OCR annotations for this dataset, enhancing model input quality and resulting in another 1% improvement. Finally, we extend the task to a generative format, establishing new baselines and expanding the research possibilities in the field of comics analysis.

[Arxiv](https://arxiv.org/abs/2403.03719)