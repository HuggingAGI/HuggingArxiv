# WeatherQA：探究多模态语言模型在严重天气问题上的推理能力。

发布时间：2024年06月17日

`LLM应用

这篇论文介绍了WeatherQA，一个专为机器推理复杂天气组合并预测实际严重天气而设计的多模态数据集。它通过评估顶尖的视觉语言模型（如GPT4、Claude3等）在预测受影响区域的多选QA和严重对流发展潜力的分类任务上的表现，来探讨这些模型在处理复杂天气预测问题上的能力和局限性。这表明论文主要关注的是大型语言模型（LLM）在实际应用中的表现，特别是在天气预测这一特定领域，因此属于LLM应用分类。` `气象预测` `灾害管理`

> WeatherQA: Can Multimodal Language Models Reason about Severe Weather?

# 摘要

> 严重的对流天气，如冰雹、龙卷风和雷暴，虽来势汹汹，却每年造成数十亿美元的损失。提前数小时预测此类天气的重要性不言而喻，以便气象学家和居民能做好准备。现有的天气预测模型多关注文本特征下的天气参数变化，而我们推出的WeatherQA，是首个多模态数据集，专为机器推理复杂天气组合并预测实际严重天气而设计。包含8,000多对（图像与文本），每对均富含预测关键信息——图像捕捉环境不稳定、地面观测和雷达反射率，文本则包含专家的预测分析。我们通过WeatherQA评估了顶尖的视觉语言模型，如GPT4、Claude3等，并设计了两项挑战任务：预测受影响区域的多选QA和严重对流发展潜力的分类，这些任务考验模型对大气动力学等知识的深入理解和多模态数据的复杂推理能力。结果显示，即使是最强的GPT4o模型，与人类推理相比仍有显著差距。与气象学家的深入探讨揭示了模型的不足，强调了改进训练和数据整合的必要性。WeatherQA链接：https://github.com/chengqianma/WeatherQA。

> Severe convective weather events, such as hail, tornadoes, and thunderstorms, often occur quickly yet cause significant damage, costing billions of dollars every year. This highlights the importance of forecasting severe weather threats hours in advance to better prepare meteorologists and residents in at-risk areas. Can modern large foundation models perform such forecasting? Existing weather benchmarks typically focus only on predicting time-series changes in certain weather parameters (e.g., temperature, moisture) with text-only features. In this work, we introduce WeatherQA, the first multimodal dataset designed for machines to reason about complex combinations of weather parameters (a.k.a., ingredients) and predict severe weather in real-world scenarios. The dataset includes over 8,000 (multi-images, text) pairs for diverse severe weather events. Each pair contains rich information crucial for forecasting -- the images describe the ingredients capturing environmental instability, surface observations, and radar reflectivity, and the text contains forecast analyses written by human experts. With WeatherQA, we evaluate state-of-the-art vision language models , including GPT4, Claude3, Gemini-1.5, and a fine-tuned Llama3-based VLM, by designing two challenging tasks: (1) multi-choice QA for predicting affected area and (2) classification of the development potential of severe convection. These tasks require deep understanding of domain knowledge (e.g., atmospheric dynamics) and complex reasoning over multimodal data (e.g., interactions between weather parameters). We show a substantial gap between the strongest VLM, GPT4o, and human reasoning. Our comprehensive case study with meteorologists further reveals the weaknesses of the models, suggesting that better training and data integration are necessary to bridge this gap. WeatherQA link: https://github.com/chengqianma/WeatherQA.

[Arxiv](https://arxiv.org/abs/2406.11217)