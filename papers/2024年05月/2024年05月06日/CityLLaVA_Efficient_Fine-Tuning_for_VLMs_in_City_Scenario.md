# CityLLaVA：在城市环境中为超大型语言模型（VLM）实现高效微调的解决方案。

发布时间：2024年05月06日

`分类：LLM应用

这篇论文介绍了一个名为 CityLLaVA 的微调框架，它专为城市环境的视觉语言模型（VLMs）设计，以提高模型的理解和预测能力。这个框架通过四个关键策略来实现这一目标，包括视觉数据的最优预处理、构建简洁的问答对和设计文本提示、采用块扩展技术进行微调，以及通过独特的顺序提问法增强预测的准确性。这个框架在性能上取得了显著的成果，并在排行榜上取得了高分。由于这个框架是针对视觉语言模型的应用，所以它属于 LLM 应用类别。` `保险业` `交通分析`

> CityLLaVA: Efficient Fine-Tuning for VLMs in City Scenario

# 摘要

> 在繁华且瞬息万变的城市生活中，交通状况的描述与分析对于保险业检查和预防事故等应用至关重要。本文提出了 CityLLaVA，这是一个创新的微调框架，专为城市环境的视觉语言模型（VLMs）量身打造。CityLLaVA 通过四个关键策略提升了模型的理解和预测能力：首先，利用边界框技术进行视觉数据的最优预处理，包括视频的最佳视角选择和视觉提示的精心设计；其次，构建简洁的问答对并设计文本提示以提高指令理解的精确度；第三，采用块扩展技术高效地微调大型 VLMs；最后，通过独特的顺序提问法增强预测的准确性。CityLLaVA 在性能上达到了新高度，以 33.4308 的高分在排行榜上独占鳌头。相关代码已在 GitHub 上发布，地址为：https://github.com/alibaba/AICITY2024_Track2_AliOpenTrek_CityLLaVA。

> In the vast and dynamic landscape of urban settings, Traffic Safety Description and Analysis plays a pivotal role in applications ranging from insurance inspection to accident prevention. This paper introduces CityLLaVA, a novel fine-tuning framework for Visual Language Models (VLMs) designed for urban scenarios. CityLLaVA enhances model comprehension and prediction accuracy through (1) employing bounding boxes for optimal visual data preprocessing, including video best-view selection and visual prompt engineering during both training and testing phases; (2) constructing concise Question-Answer sequences and designing textual prompts to refine instruction comprehension; (3) implementing block expansion to fine-tune large VLMs efficiently; and (4) advancing prediction accuracy via a unique sequential questioning-based prediction augmentation. Demonstrating top-tier performance, our method achieved a benchmark score of 33.4308, securing the leading position on the leaderboard. The code can be found: https://github.com/alibaba/AICITY2024_Track2_AliOpenTrek_CityLLaVA

[Arxiv](https://arxiv.org/abs/2405.03194)