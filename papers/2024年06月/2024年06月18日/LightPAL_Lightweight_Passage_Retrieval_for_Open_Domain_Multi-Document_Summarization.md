# LightPAL：开放域多文档摘要的轻量级文本检索利器

发布时间：2024年06月18日

`RAG

这篇论文主要介绍了一种轻量级的段落检索方法LightPAL，用于解决开放域多文档摘要（ODMDS）的问题。该方法利用大型语言模型（LLM）在索引时构建段落关系图，并在推理时采用随机漫步而非迭代推理和检索，以提高效率和摘要质量。这种方法属于信息检索和摘要生成技术的应用，特别是在处理大型文档集合和复杂查询时的优化，因此归类为RAG。` `信息检索` `文档摘要`

> LightPAL: Lightweight Passage Retrieval for Open Domain Multi-Document Summarization

# 摘要

> 开放域多文档摘要（ODMDS）对于满足多样化的信息需求至关重要，它旨在通过综合大型文档集合中多个相关文档的内容，生成一个回答用户查询的摘要。现有的先检索相关段落再生成摘要的方法在ODMDS中表现不佳，因为开放式查询往往需要更多上下文来全面覆盖主题，这使得最初检索所有相关段落变得极具挑战。尽管迭代检索方法在多跳问题回答（MQA）中有所探索，但由于大型语言模型（LLM）推理的重复导致的高延迟，它们并不适用于ODMDS。为此，我们提出了LightPAL，一种轻量级的段落检索方法，它在索引时利用LLM构建段落关系图，并在推理时采用随机漫步而非迭代推理和检索。实验结果显示，LightPAL在提高摘要质量的同时，比迭代MQA方法效率更高。

> Open-Domain Multi-Document Summarization (ODMDS) is crucial for addressing diverse information needs, which aims to generate a summary as answer to user's query, synthesizing relevant content from multiple documents in a large collection. Existing approaches that first find relevant passages and then generate a summary using a language model are inadequate for ODMDS. This is because open-ended queries often require additional context for the retrieved passages to cover the topic comprehensively, making it challenging to retrieve all relevant passages initially. While iterative retrieval methods have been explored for multi-hop question answering (MQA), they are impractical for ODMDS due to high latency from repeated large language model (LLM) inference for reasoning. To address this issue, we propose LightPAL, a lightweight passage retrieval method for ODMDS that constructs a graph representing passage relationships using an LLM during indexing and employs random walk instead of iterative reasoning and retrieval at inference time. Experiments on ODMDS benchmarks show that LightPAL outperforms baseline retrievers in summary quality while being significantly more efficient than an iterative MQA approach.

![LightPAL：开放域多文档摘要的轻量级文本检索利器](../../../paper_images/2406.12494/overview.png)

![LightPAL：开放域多文档摘要的轻量级文本检索利器](../../../paper_images/2406.12494/graph_win_ppr_commandr_v2.png)

![LightPAL：开放域多文档摘要的轻量级文本检索利器](../../../paper_images/2406.12494/graph_win_promptrank_commandr_v2.png)

[Arxiv](https://arxiv.org/abs/2406.12494)