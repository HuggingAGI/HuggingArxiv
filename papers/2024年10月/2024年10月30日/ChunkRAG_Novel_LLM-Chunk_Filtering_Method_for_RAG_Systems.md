# ChunkRAG：RAG 系统的全新 LLM-Chunk 过滤之法

发布时间：2024年10月30日

`RAG` `信息检索` `语言模型`

> ChunkRAG: Novel LLM-Chunk Filtering Method for RAG Systems

# 摘要

> 在使用大型语言模型（LLMs）的检索增强生成（RAG）系统中，常因检索到不相关或关联松散的信息而生成不准确的回应。现有的在文档层面运作的方法，难以有效滤除这类内容。我们提出了由 LLM 驱动的块过滤——ChunkRAG，这是一个能在块级别评估和过滤检索信息从而增强 RAG 系统的框架。我们的方法运用语义分块将文档分成连贯的部分，并借助基于 LLM 的相关性评分来评估每个块与用户查询的契合度。在生成阶段之前滤除不太相关的块，显著减少了幻觉，提高了事实准确性。实验显示，我们的方法优于现有的 RAG 模型，在需要精准信息检索的任务中达到了更高的准确率。这一进展提升了 RAG 系统的可靠性，使其在事实核查和多跳推理等应用中尤为有益。

> Retrieval-Augmented Generation (RAG) systems using large language models (LLMs) often generate inaccurate responses due to the retrieval of irrelevant or loosely related information. Existing methods, which operate at the document level, fail to effectively filter out such content. We propose LLM-driven chunk filtering, ChunkRAG, a framework that enhances RAG systems by evaluating and filtering retrieved information at the chunk level. Our approach employs semantic chunking to divide documents into coherent sections and utilizes LLM-based relevance scoring to assess each chunk's alignment with the user's query. By filtering out less pertinent chunks before the generation phase, we significantly reduce hallucinations and improve factual accuracy. Experiments show that our method outperforms existing RAG models, achieving higher accuracy on tasks requiring precise information retrieval. This advancement enhances the reliability of RAG systems, making them particularly beneficial for applications like fact-checking and multi-hop reasoning.

[Arxiv](https://arxiv.org/abs/2410.19572)