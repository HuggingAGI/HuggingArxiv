# 利用时间适配器从长期社交媒体数据中提取情感聚合，应用于大型语言模型

发布时间：2024年09月26日

`LLM应用` `社交媒体` `情感分析`

> Extracting Affect Aggregates from Longitudinal Social Media Data with Temporal Adapters for Large Language Models

# 摘要

> 本文提出使用时间对齐的 LLM 进行社交媒体数据的纵向分析。我们微调了 Llama 3 8B 的时间适配器，并提取了情感和态度的纵向数据。通过与英国调查数据对比，我们发现了几种集体情感的强正相关。这些估计在不同训练和提示设置中表现稳健，并与传统分类模型结果一致。这是首次将 LLM 情感分析扩展到纵向研究，为社交媒体数据分析开辟了新途径。

> This paper proposes temporally aligned Large Language Models (LLMs) as a tool for longitudinal analysis of social media data. We fine-tune Temporal Adapters for Llama 3 8B on full timelines from a panel of British Twitter users, and extract longitudinal aggregates of emotions and attitudes with established questionnaires. We validate our estimates against representative British survey data and find strong positive, significant correlations for several collective emotions. The obtained estimates are robust across multiple training seeds and prompt formulations, and in line with collective emotions extracted using a traditional classification model trained on labeled data. To the best of our knowledge, this is the first work to extend the analysis of affect in LLMs to a longitudinal setting through Temporal Adapters. Our work enables new approaches towards the longitudinal analysis of social media data.

[Arxiv](https://arxiv.org/abs/2409.17990)