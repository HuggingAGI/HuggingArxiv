# 主动学习在识别灾难相关推文方面，与关键词过滤和通用微调进行了比较。

发布时间：2024年08月19日

`LLM应用` `应急响应` `社交媒体分析`

> Active Learning for Identifying Disaster-Related Tweets: A Comparison with Keyword Filtering and Generic Fine-Tuning

# 摘要

> 社交媒体信息在自然灾害应急响应中提供实时关键信息，但从中筛选出灾害相关帖子颇具挑战。传统方法如关键词过滤、主题建模或分类技术已被采用。主动学习（AL）作为机器学习的一个新兴分支，在社交媒体文本分类领域应用尚少。本研究探索了AL在识别灾害相关推文中的潜力，对比了关键词过滤、通用数据微调的RoBERTa模型、AL训练的基础模型及AL微调模型。测试数据包括CrisisLex及德国洪水、智利森林火灾的手动标记数据。结果表明，结合通用微调与10轮AL的方法性能最佳，仅需少量标记工作即可训练出适用于广泛场景的灾害相关推文识别模型，为社交媒体分析研究提供了有力工具。

> Information from social media can provide essential information for emergency response during natural disasters in near real-time. However, it is difficult to identify the disaster-related posts among the large amounts of unstructured data available. Previous methods often use keyword filtering, topic modelling or classification-based techniques to identify such posts. Active Learning (AL) presents a promising sub-field of Machine Learning (ML) that has not been used much in the field of text classification of social media content. This study therefore investigates the potential of AL for identifying disaster-related Tweets. We compare a keyword filtering approach, a RoBERTa model fine-tuned with generic data from CrisisLex, a base RoBERTa model trained with AL and a fine-tuned RoBERTa model trained with AL regarding classification performance. For testing, data from CrisisLex and manually labelled data from the 2021 flood in Germany and the 2023 Chile forest fires were considered. The results show that generic fine-tuning combined with 10 rounds of AL outperformed all other approaches. Consequently, a broadly applicable model for the identification of disaster-related Tweets could be trained with very little labelling effort. The model can be applied to use cases beyond this study and provides a useful tool for further research in social media analysis.

[Arxiv](https://arxiv.org/abs/2408.09914)