# LLM-Ref：利用大型语言模型增强技术写作中的参考处理

发布时间：2024年11月04日

`RAG` `数据合成`

> LLM-Ref: Enhancing Reference Handling in Technical Writing with Large Language Models

# 摘要

> 大型语言模型（LLMs）在数据合成方面表现出色，但在特定领域任务中可能不准确，检索增强生成（RAG）系统通过利用用户提供的数据来解决这个问题。然而，RAG 系统在检索和生成阶段都需要优化，这可能会影响输出质量。在本文中，我们提出了 LLM-Ref，这是一种写作辅助工具，帮助研究人员从多个源文档撰写文章，具有增强的参考合成和处理能力。与使用分块和索引的传统 RAG 系统不同，我们的工具直接从文本段落中检索和生成内容。这种方法便于从生成的输出中直接提取参考，这是我们工具独有的功能。此外，我们的工具采用迭代响应生成，有效地在语言模型的限制内管理冗长的上下文。与基于基线 RAG 的系统相比，我们的方法使 Ragas 分数提高了 3.25 倍至 6.26 倍，Ragas 分数是一个综合指标，全面反映了 RAG 系统生成准确、相关和上下文合适响应的能力。这种改进表明我们的方法提高了写作辅助工具的准确性和上下文相关性。

> Large Language Models (LLMs) excel in data synthesis but can be inaccurate in domain-specific tasks, which retrieval-augmented generation (RAG) systems address by leveraging user-provided data. However, RAGs require optimization in both retrieval and generation stages, which can affect output quality. In this paper, we present LLM-Ref, a writing assistant tool that aids researchers in writing articles from multiple source documents with enhanced reference synthesis and handling capabilities. Unlike traditional RAG systems that use chunking and indexing, our tool retrieves and generates content directly from text paragraphs. This method facilitates direct reference extraction from the generated outputs, a feature unique to our tool. Additionally, our tool employs iterative response generation, effectively managing lengthy contexts within the language model's constraints. Compared to baseline RAG-based systems, our approach achieves a $3.25\times$ to $6.26\times$ increase in Ragas score, a comprehensive metric that provides a holistic view of a RAG system's ability to produce accurate, relevant, and contextually appropriate responses. This improvement shows our method enhances the accuracy and contextual relevance of writing assistance tools.

[Arxiv](https://arxiv.org/abs/2411.00294)