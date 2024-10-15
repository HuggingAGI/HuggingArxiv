# MentalGLM 系列：专为中国社交媒体心理健康分析设计的可解释大型语言模型

发布时间：2024年10月14日

`LLM应用` `心理健康` `社交媒体`

> MentalGLM Series: Explainable Large Language Models for Mental Health Analysis on Chinese Social Media

# 摘要

> 随着心理健康问题的增多，社交媒体成为人们表达情感的重要平台。深度学习虽是分析心理健康的有效工具，但其黑箱模型在任务切换时不够灵活，且结果难以解释。大型语言模型 (LLM) 的出现，为心理健康分析带来了新思路。LLM 不仅能灵活处理任务，还能解释决策过程，但在复杂心理分析上仍需提升。本文首次推出多任务中文社交媒体可解释心理健康指令 (C-IMHI) 数据集，包含 9K 样本，并提出 MentalGLM 系列模型，专为中文社交媒体设计，训练于 50K 指令。这些模型在多项任务中表现优异，甚至超越了传统深度学习和其他 LLM。专家验证显示，模型生成的决策解释具有较高可信度，且在临床数据集上表现突出，显示出在临床领域的应用潜力。所有资源均已公开，详情请访问：https://github.com/zwzzzQAQ/MentalGLM。

> As the prevalence of mental health challenges, social media has emerged as a key platform for individuals to express their emotions.Deep learning tends to be a promising solution for analyzing mental health on social media. However, black box models are often inflexible when switching between tasks, and their results typically lack explanations. With the rise of large language models (LLMs), their flexibility has introduced new approaches to the field. Also due to the generative nature, they can be prompted to explain decision-making processes. However, their performance on complex psychological analysis still lags behind deep learning. In this paper, we introduce the first multi-task Chinese Social Media Interpretable Mental Health Instructions (C-IMHI) dataset, consisting of 9K samples, which has been quality-controlled and manually validated. We also propose MentalGLM series models, the first open-source LLMs designed for explainable mental health analysis targeting Chinese social media, trained on a corpus of 50K instructions. The proposed models were evaluated on three downstream tasks and achieved better or comparable performance compared to deep learning models, generalized LLMs, and task fine-tuned LLMs. We validated a portion of the generated decision explanations with experts, showing promising results. We also evaluated the proposed models on a clinical dataset, where they outperformed other LLMs, indicating their potential applicability in the clinical field. Our models show strong performance, validated across tasks and perspectives. The decision explanations enhance usability and facilitate better understanding and practical application of the models. Both the constructed dataset and the models are publicly available via: https://github.com/zwzzzQAQ/MentalGLM.

[Arxiv](https://arxiv.org/abs/2410.10323)