# 上下文驱动的索引修剪：从数据质量视角增强RALMs的精准性

发布时间：2024年08月10日

`RAG` `问答系统` `数据质量`

> Context-Driven Index Trimming: A Data Quality Perspective to Enhancing Precision of RALMs

# 摘要

> 增强型检索大型语言模型 (RALMs) 在提升回答准确性方面取得了显著成果，但现有研究常忽视检索结果中的数据质量问题。我们通过 Context-Driven Index Trimming (CDIT) 框架，利用 Context Matching Dependencies (CMDs) 作为逻辑规则，从数据质量角度提升 RALMs 的答案精确度。基于 LLMs 的语义理解，CDIT 能有效识别并剔除与查询不符的检索结果，优化数据库索引，从而提升答案质量。实验证明，CDIT 在复杂问答任务中表现出色，并因其与多种模型和索引方法的兼容性，为提升 RALMs 的数据质量和检索精度提供了灵活且有效的方法。

> Retrieval-Augmented Large Language Models (RALMs) have made significant strides in enhancing the accuracy of generated responses.However, existing research often overlooks the data quality issues within retrieval results, often caused by inaccurate existing vector-distance-based retrieval methods.We propose to boost the precision of RALMs' answers from a data quality perspective through the Context-Driven Index Trimming (CDIT) framework, where Context Matching Dependencies (CMDs) are employed as logical data quality rules to capture and regulate the consistency between retrieved contexts.Based on the semantic comprehension capabilities of Large Language Models (LLMs), CDIT can effectively identify and discard retrieval results that are inconsistent with the query context and further modify indexes in the database, thereby improving answer quality.Experiments demonstrate on challenging question-answering tasks.Also, the flexibility of CDIT is verified through its compatibility with various language models and indexing methods, which offers a promising approach to bolster RALMs' data quality and retrieval precision jointly.

[Arxiv](https://arxiv.org/abs/2408.05524)