# 探究日本大型语言模型中的社会偏见现象

发布时间：2024年06月04日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLM）在特定语言（日语）中的应用问题，即社会偏见。它通过创建一个新的偏见基准数据集（JBBQ）来评估和分析日语LLMs中的社会偏见现象，并探讨了减轻这些偏见的方法。这与LLM的理论研究不同，因为它更侧重于实际应用中的问题解决和改进，而不是理论模型的构建或分析。因此，它属于LLM应用类别。` `社会科学` `语言模型`

> Analyzing Social Biases in Japanese Large Language Models

# 摘要

> 随着大型语言模型的发展，这些模型中存在的社会偏见问题日益凸显。虽然已有多种语言的社会偏见评估基准，但针对日语LLMs的社会偏见研究尚不充分。本研究基于英语偏见基准BBQ，创建了日语偏见基准数据集JBBQ，并深入分析了日语LLMs中的社会偏见现象。研究发现，尽管通过指令调整提升了模型在JBBQ上的准确率，但偏见分数却有所增加。有趣的是，在提示中加入关于社会偏见的警告，能够有效减轻部分模型中的偏见影响。

> With the development of Large Language Models (LLMs), social biases in the LLMs have become a crucial issue. While various benchmarks for social biases have been provided across languages, the extent to which Japanese LLMs exhibit social biases has not been fully investigated. In this study, we construct the Japanese Bias Benchmark dataset for Question Answering (JBBQ) based on the English bias benchmark BBQ, and analyze social biases in Japanese LLMs. The results show that while current Japanese LLMs improve their accuracies on JBBQ by instruction-tuning, their bias scores become larger. In addition, augmenting their prompts with warning about social biases reduces the effect of biases in some models.

![探究日本大型语言模型中的社会偏见现象](../../../paper_images/2406.02050/figure2.png)

[Arxiv](https://arxiv.org/abs/2406.02050)