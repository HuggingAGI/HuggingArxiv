# QirK：借助知识图谱的中间表示实现问答功能

发布时间：2024年08月14日

`LLM应用` `知识图谱` `数据库`

> QirK: Question Answering via Intermediate Representation on Knowledge Graphs

# 摘要

> 我们推出了 QirK 系统，专门解答知识图谱上的复杂自然语言问题，这些问题目前仍是大型语言模型的难题。QirK 结合了数据库技术、大型语言模型和向量嵌入的语义搜索，通过中间表示将问题转化为有效的数据库查询，巧妙融合了语言模型的智能与知识图谱的准确性。  想了解更多，请观看展示 QirK 的短视频：https://youtu.be/6c81BLmOZ0U。

> We demonstrate QirK, a system for answering natural language questions on Knowledge Graphs (KG). QirK can answer structurally complex questions that are still beyond the reach of emerging Large Language Models (LLMs). It does so using a unique combination of database technology, LLMs, and semantic search over vector embeddings. The glue for these components is an intermediate representation (IR). The input question is mapped to IR using LLMs, which is then repaired into a valid relational database query with the aid of a semantic search on vector embeddings. This allows a practical synthesis of LLM capabilities and KG reliability.
  A short video demonstrating QirK is available at https://youtu.be/6c81BLmOZ0U.

[Arxiv](https://arxiv.org/abs/2408.07494)