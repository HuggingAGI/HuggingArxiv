# 保持中立并非易事 —— 人类与基于大型语言模型的病患评论情感分析

发布时间：2024年04月29日

`LLM应用`

> It's Difficult to be Neutral -- Human and LLM-based Sentiment Annotation of Patient Comments

# 摘要

> 情感分析作为收集患者反馈、优化医疗服务的关键技术，依赖于领域内标注数据的丰富性。本文介绍了挪威公共卫生研究所（NIPH）在患者调查的开放式评论中加入情感标注的工作。鉴于人工标注既耗时又需专业知识，我们探索了使用大型语言模型（LLMs）作为自动标注工具的可能性。通过对比两种挪威语预训练LLMs在不同提示和上下文学习配置下的表现，我们对其进行了深入评估，并与人工标注的结果进行了比较。研究发现，即便在零样本的情况下，模型在二元情感分类上的表现也远超基准水平，但面对完整数据集，其性能仍未达到人工标注的水准。

> Sentiment analysis is an important tool for aggregating patient voices, in order to provide targeted improvements in healthcare services. A prerequisite for this is the availability of in-domain data annotated for sentiment. This article documents an effort to add sentiment annotations to free-text comments in patient surveys collected by the Norwegian Institute of Public Health (NIPH). However, annotation can be a time-consuming and resource-intensive process, particularly when it requires domain expertise. We therefore also evaluate a possible alternative to human annotation, using large language models (LLMs) as annotators. We perform an extensive evaluation of the approach for two openly available pretrained LLMs for Norwegian, experimenting with different configurations of prompts and in-context learning, comparing their performance to human annotators. We find that even for zero-shot runs, models perform well above the baseline for binary sentiment, but still cannot compete with human annotators on the full dataset.

[Arxiv](https://arxiv.org/abs/2404.18832)