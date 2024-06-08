# 探究日本大型语言模型中的社会偏见现象

发布时间：2024年06月04日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）在特定语言（日语）中的社会偏见问题，并通过创建日语偏见基准数据集JBBQ来评估和分析这些偏见。研究内容涉及模型的应用层面，即如何通过调整和提示来减轻模型中的偏见影响，而不是深入探讨LLM的理论基础或Agent的设计与应用，也不是关于检索增强生成（RAG）的研究。因此，将其归类为LLM应用是合适的。` `社会科学` `语言模型`

> Analyzing Social Biases in Japanese Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的进步，其内部的社会偏见问题日益凸显。虽然已有多种语言的社会偏见评估标准，但日本LLMs的社会偏见程度尚未被深入探究。本研究基于英语偏见基准BBQ，创建了日语偏见基准数据集JBBQ，并针对日本LLMs进行了社会偏见分析。研究发现，尽管通过指令调整提升了JBBQ的准确率，但模型的偏见分数却有所增加。有趣的是，在提示中加入关于社会偏见的警告，能有效减轻部分模型中的偏见影响。

> With the development of Large Language Models (LLMs), social biases in the LLMs have become a crucial issue. While various benchmarks for social biases have been provided across languages, the extent to which Japanese LLMs exhibit social biases has not been fully investigated. In this study, we construct the Japanese Bias Benchmark dataset for Question Answering (JBBQ) based on the English bias benchmark BBQ, and analyze social biases in Japanese LLMs. The results show that while current Japanese LLMs improve their accuracies on JBBQ by instruction-tuning, their bias scores become larger. In addition, augmenting their prompts with warning about social biases reduces the effect of biases in some models.

![探究日本大型语言模型中的社会偏见现象](../../../paper_images/2406.02050/figure2.png)

[Arxiv](https://arxiv.org/abs/2406.02050)