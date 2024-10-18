# HEALTH-PARIKSHA：评估健康聊天机器人在多语言真实环境中的RAG模型表现

发布时间：2024年10月17日

`LLM应用` `人工智能`

> HEALTH-PARIKSHA: Assessing RAG Models for Health Chatbots in Real-World Multilingual Settings

# 摘要

> 评估大型语言模型（LLM）的能力与局限性备受关注，但在实际应用中对多模型的综合评估仍不多见。多语言评估常依赖翻译基准，难以捕捉源语言的细微文化差异。本研究深入评估了24个LLM在印度患者与医疗聊天机器人互动的真实数据上的表现，涵盖印度英语及四种其他印度语言。我们采用统一的检索增强生成框架生成回复，并通过自动化与人工评估，针对四个关键指标进行评价。研究发现，模型性能差异显著，且经过指令优化的印度语言模型在处理印度语言查询时表现不尽如人意。此外，实证数据显示，印度语言查询的回复在事实准确性上普遍低于英语查询。最后，定性分析揭示，数据集中的代码混合和文化相关查询对模型构成了挑战。

> Assessing the capabilities and limitations of large language models (LLMs) has garnered significant interest, yet the evaluation of multiple models in real-world scenarios remains rare. Multilingual evaluation often relies on translated benchmarks, which typically do not capture linguistic and cultural nuances present in the source language. This study provides an extensive assessment of 24 LLMs on real world data collected from Indian patients interacting with a medical chatbot in Indian English and 4 other Indic languages. We employ a uniform Retrieval Augmented Generation framework to generate responses, which are evaluated using both automated techniques and human evaluators on four specific metrics relevant to our application. We find that models vary significantly in their performance and that instruction tuned Indic models do not always perform well on Indic language queries. Further, we empirically show that factual correctness is generally lower for responses to Indic queries compared to English queries. Finally, our qualitative work shows that code-mixed and culturally relevant queries in our dataset pose challenges to evaluated models.

[Arxiv](https://arxiv.org/abs/2410.13671)