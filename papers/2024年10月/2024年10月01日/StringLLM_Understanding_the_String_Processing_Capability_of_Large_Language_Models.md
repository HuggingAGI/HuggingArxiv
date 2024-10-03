# StringLLM：探索大型语言模型在字符串处理方面的潜力

发布时间：2024年10月01日

`LLM应用` `计算机科学`

> StringLLM: Understanding the String Processing Capability of Large Language Models

# 摘要

> 字符串处理作为现代计算的基础，主要涉及字符串的分析与操作。尽管大型语言模型 (LLM) 在自然语言处理 (NLP) 任务中取得了显著进展，但其在字符串处理方面的能力仍未得到充分探索。为此，我们深入研究了 LLM 的字符串处理能力，并提出了 StringLLM 方法，用于构建基准测试数据集。通过 StringLLM，我们创建了名为 StringBench 的数据集系列，涵盖多种字符串处理任务，系统评估了 LLM 的表现。结果显示，LLM 在字符串处理上仍不及人类。为探究原因，我们进行了深入分析，并提出了一种通过微调显著提升 LLM 字符串处理能力的方法。这项研究为未来探索 LLM 的字符串处理能力奠定了基础。代码与数据已公开，详见 https://github.com/wxl-lxw/StringLLM。

> String processing, which mainly involves the analysis and manipulation of strings, is a fundamental component of modern computing. Despite the significant advancements of large language models (LLMs) in various natural language processing (NLP) tasks, their capability in string processing remains underexplored and underdeveloped. To bridge this gap, we present a comprehensive study of LLMs' string processing capability. In particular, we first propose StringLLM, a method to construct datasets for benchmarking string processing capability of LLMs. We use StringLLM to build a series of datasets, referred to as StringBench. It encompasses a wide range of string processing tasks, allowing us to systematically evaluate LLMs' performance in this area. Our evaluations indicate that LLMs struggle with accurately processing strings compared to humans. To uncover the underlying reasons for this limitation, we conduct an in-depth analysis and subsequently propose an effective approach that significantly enhances LLMs' string processing capability via fine-tuning. This work provides a foundation for future research to understand LLMs' string processing capability. Our code and data are available at https://github.com/wxl-lxw/StringLLM.

[Arxiv](https://arxiv.org/abs/2410.01208)