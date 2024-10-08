# TableRAG：借助语言模型实现百万标记表格的深度理解

发布时间：2024年10月07日

`RAG` `数据分析` `人工智能`

> TableRAG: Million-Token Table Understanding with Language Models

# 摘要

> 近期，语言模型在处理表格数据方面取得了显著进展，主要得益于程序辅助机制的引入，这些机制能够操纵和分析表格数据。然而，这些方法往往需要整个表格作为输入，这带来了位置偏差和上下文长度限制导致的可扩展性问题。为此，我们推出了 TableRAG，一个专为表格理解设计的检索增强生成框架。TableRAG 通过查询扩展与模式和单元格检索相结合，能够在提供信息给语言模型之前精准定位关键数据，从而实现更高效的数据编码和精确检索，大幅缩短提示长度并减少信息丢失。我们还从 Arcade 和 BIRD-SQL 数据集中创建了两个新的百万标记基准，以全面测试 TableRAG 的性能。实验结果显示，TableRAG 的检索设计在大规模表格理解任务中表现卓越，达到了业界领先水平。

> Recent advancements in language models (LMs) have notably enhanced their ability to reason with tabular data, primarily through program-aided mechanisms that manipulate and analyze tables. However, these methods often require the entire table as input, leading to scalability challenges due to the positional bias or context length constraints. In response to these challenges, we introduce TableRAG, a Retrieval-Augmented Generation (RAG) framework specifically designed for LM-based table understanding. TableRAG leverages query expansion combined with schema and cell retrieval to pinpoint crucial information before providing it to the LMs. This enables more efficient data encoding and precise retrieval, significantly reducing prompt lengths and mitigating information loss. We have developed two new million-token benchmarks from the Arcade and BIRD-SQL datasets to thoroughly evaluate TableRAG's effectiveness at scale. Our results demonstrate that TableRAG's retrieval design achieves the highest retrieval quality, leading to the new state-of-the-art performance on large-scale table understanding.

[Arxiv](https://arxiv.org/abs/2410.04739)