# FastRAG：针对半结构化数据的检索增强式生成

发布时间：2024年11月20日

`RAG` `数据处理`

> FastRAG: Retrieval Augmented Generation for Semi-structured Data

# 摘要

> 高效处理和解读网络数据对于愈发复杂的网络运行极为关键。大型语言模型（LLM）和检索增强生成（RAG）技术的最新进展优化了网络管理中的数据处理。但像 VectorRAG 和 GraphRAG 这类现有的 RAG 方法在应对半结构化技术数据的复杂性和隐含性时力不从心，致使时间、成本和检索效率低下。本文引入了 FastRAG，这是一种专为半结构化数据打造的新型 RAG 方法。FastRAG 运用模式学习和脚本学习来提取和构建数据，无需向 LLM 提交整个数据源。它将文本搜索与知识图谱（KG）查询相融合，以提升检索富含上下文信息的准确性。评估结果显示，FastRAG 能提供精准的问答，与 GraphRAG 相比，时间最多节省 90%，成本最多降低 85%。

> Efficiently processing and interpreting network data is critical for the operation of increasingly complex networks. Recent advances in Large Language Models (LLM) and Retrieval-Augmented Generation (RAG) techniques have improved data processing in network management. However, existing RAG methods like VectorRAG and GraphRAG struggle with the complexity and implicit nature of semi-structured technical data, leading to inefficiencies in time, cost, and retrieval. This paper introduces FastRAG, a novel RAG approach designed for semi-structured data. FastRAG employs schema learning and script learning to extract and structure data without needing to submit entire data sources to an LLM. It integrates text search with knowledge graph (KG) querying to improve accuracy in retrieving context-rich information. Evaluation results demonstrate that FastRAG provides accurate question answering, while improving up to 90% in time and 85% in cost compared to GraphRAG.

[Arxiv](https://arxiv.org/abs/2411.13773)