# 企业RAG中基于问题的检索采用原子单元进行优化

发布时间：2024年05月20日

`RAG

该论文摘要描述了一种针对企业检索增强生成（RAG）框架的改进方法，该方法通过将文档块分解为原子陈述，并生成合成问题来进行更精确的检索。这种方法旨在提高LLM在RAG框架下的性能，特别是在检索环节的准确性。因此，这篇论文的内容与RAG框架的具体应用和改进紧密相关，适合归类到RAG分类中。` `企业信息检索`

> Question-Based Retrieval using Atomic Units for Enterprise RAG

# 摘要

> 企业检索增强生成（RAG）框架巧妙地将大型语言模型（LLMs）与内部动态变化的文档结合，首先将文档切分为块，再根据用户查询检索相关块，并以此为上下文，由LLM生成响应。但检索环节可能因错误块导致LLM生成错误答案。为此，本研究提出了一种零-shot密集检索改进方法，通过将块分解为原子陈述，并基于此生成合成问题，进而进行精确检索。实验表明，这种基于原子的检索方法召回率更高，且通过合成问题检索进一步提升了性能。这一改进显著提高了企业LLM在RAG框架下的整体表现。

> Enterprise retrieval augmented generation (RAG) offers a highly flexible framework for combining powerful large language models (LLMs) with internal, possibly temporally changing, documents. In RAG, documents are first chunked. Relevant chunks are then retrieved for a specific user query, which are passed as context to a synthesizer LLM to generate the query response. However, the retrieval step can limit performance, as incorrect chunks can lead the synthesizer LLM to generate a false response. This work proposes a zero-shot adaptation of standard dense retrieval steps for more accurate chunk recall. Specifically, a chunk is first decomposed into atomic statements. A set of synthetic questions are then generated on these atoms (with the chunk as the context). Dense retrieval involves finding the closest set of synthetic questions, and associated chunks, to the user query. It is found that retrieval with the atoms leads to higher recall than retrieval with chunks. Further performance gain is observed with retrieval using the synthetic questions generated over the atoms. Higher recall at the retrieval step enables higher performance of the enterprise LLM using the RAG pipeline.

[Arxiv](https://arxiv.org/abs/2405.12363)