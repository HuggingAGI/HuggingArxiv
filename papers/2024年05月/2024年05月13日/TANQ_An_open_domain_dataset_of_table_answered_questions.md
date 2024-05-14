# TANQ：探索开放领域，揭秘表格之谜——一个专为回答问题而生的数据集。

发布时间：2024年05月13日

`RAG

这篇论文介绍了TANQ数据集，这是一个专注于从多源信息构建表格的开放域问答数据集。它探讨了语言模型结合检索工具在处理复杂问题时的应用，特别是在多源检索信息、处理数据以提炼洞见，并以表格形式呈现发现的能力。这与RAG（Retrieval-Augmented Generation）的概念相符，RAG是一种结合了检索和生成能力的模型架构，用于增强语言模型在问答等任务中的表现。因此，这篇论文属于RAG分类。` `问答系统` `数据分析`

> TANQ: An open domain dataset of table answered questions

# 摘要

> 语言模型结合检索工具正成为解答问题的利器。在现实世界中，解答问题往往涉及从多源检索信息、处理数据以提炼洞见，并以表格、图表等形式呈现复杂发现。本文推出的TANQ数据集，是首个要求从多源信息构建表格的开放域问答数据集。我们为每个表格单元提供了完整的源信息，并对顶尖语言模型在开放、神谕和闭书模式下进行了测试。GPT4作为最佳基线，其F1分数为29.1，与人类表现相差19.7分。我们分析了模型在不同技能要求上的表现，如多跳推理、数学运算和单位转换，并探讨了模型答案中的常见错误，揭示了TANQ任务的复杂性和未来挑战。

> Language models, potentially augmented with tool usage such as retrieval are becoming the go-to means of answering questions. Understanding and answering questions in real-world settings often requires retrieving information from different sources, processing and aggregating data to extract insights, and presenting complex findings in form of structured artifacts such as novel tables, charts, or infographics. In this paper, we introduce TANQ, the first open domain question answering dataset where the answers require building tables from information across multiple sources. We release the full source attribution for every cell in the resulting table and benchmark state-of-the-art language models in open, oracle, and closed book setups. Our best-performing baseline, GPT4 reaches an overall F1 score of 29.1, lagging behind human performance by 19.7 points. We analyse baselines' performance across different dataset attributes such as different skills required for this task, including multi-hop reasoning, math operations, and unit conversions. We further discuss common failures in model-generated answers, suggesting that TANQ is a complex task with many challenges ahead.

[Arxiv](https://arxiv.org/abs/2405.07765)