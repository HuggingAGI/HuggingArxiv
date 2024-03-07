# [WanJuan-CC 是一个公开发布的高品质英文网络文本数据集，注重安全性和高质量标准。](https://arxiv.org/abs/2402.19282)

发布时间：2024年02月29日

`LLM应用`

> WanJuan-CC: A Safe and High-Quality Open-sourced English Webtext Dataset

> 本文推出了基于Common Crawl数据源打造的安全高品质开源英文网络文本数据集——万卷-CC。面对为语言模型构建大型预训练数据集所需海量优质数据的难题，我们精心设计了一整套处理流程，从约6800亿份英文原文档中萃取出2.22万亿个安全Token，并严选其中1万亿高质量Token构成了万卷-CC的核心部分，目前已对外开源3000亿Token。同时，文中详尽展示了与数据品质相关的统计数据，方便用户按需挑选适宜数据。为进一步验证万卷-CC的数据质量和实用价值，我们采用其与RefinedWeb数据集分别训练了10亿和30亿参数规模的模型。实验结果显示，在验证集及下游任务测试中，万卷-CC展现出了更为出色的性能表现。

> This paper presents WanJuan-CC, a safe and high-quality open-sourced English webtext dataset derived from Common Crawl data. The study addresses the challenges of constructing large-scale pre-training datasets for language models, which require vast amounts of high-quality data. A comprehensive process was designed to handle Common Crawl data, including extraction, heuristic rule filtering, fuzzy deduplication, content safety filtering, and data quality filtering. From approximately 68 billion original English documents, we obtained 2.22T Tokens of safe data and selected 1.0T Tokens of high-quality data as part of WanJuan-CC. We have open-sourced 300B Tokens from this dataset. The paper also provides statistical information related to data quality, enabling users to select appropriate data according to their needs. To evaluate the quality and utility of the dataset, we trained 1B-parameter and 3B-parameter models using WanJuan-CC and another dataset, RefinedWeb. Results show that WanJuan-CC performs better on validation datasets and downstream tasks.