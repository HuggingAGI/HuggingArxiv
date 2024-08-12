# HybridRAG 结合知识图谱与向量检索增强生成技术，旨在提升信息提取的效率。

发布时间：2024年08月09日

`RAG` `问答系统`

> HybridRAG: Integrating Knowledge Graphs and Vector Retrieval Augmented Generation for Efficient Information Extraction

# 摘要

> 在金融领域，从财报电话会议记录等非结构化文本中提取复杂信息对大型语言模型（LLM）构成挑战，即便采用先进的检索增强生成（RAG）技术。为此，我们创新性地提出了HybridRAG方法，融合了基于知识图谱的GraphRAG和VectorRAG技术，旨在提升金融文档问答系统的信息提取能力，生成精准且上下文贴切的答案。实验证明，HybridRAG在检索和生成阶段均超越了单一的VectorRAG和GraphRAG技术，不仅在金融领域，该技术还具有广泛的应用潜力。

> Extraction and interpretation of intricate information from unstructured text data arising in financial applications, such as earnings call transcripts, present substantial challenges to large language models (LLMs) even using the current best practices to use Retrieval Augmented Generation (RAG) (referred to as VectorRAG techniques which utilize vector databases for information retrieval) due to challenges such as domain specific terminology and complex formats of the documents. We introduce a novel approach based on a combination, called HybridRAG, of the Knowledge Graphs (KGs) based RAG techniques (called GraphRAG) and VectorRAG techniques to enhance question-answer (Q&A) systems for information extraction from financial documents that is shown to be capable of generating accurate and contextually relevant answers. Using experiments on a set of financial earning call transcripts documents which come in the form of Q&A format, and hence provide a natural set of pairs of ground-truth Q&As, we show that HybridRAG which retrieves context from both vector database and KG outperforms both traditional VectorRAG and GraphRAG individually when evaluated at both the retrieval and generation stages in terms of retrieval accuracy and answer generation. The proposed technique has applications beyond the financial domain

[Arxiv](https://arxiv.org/abs/2408.04948)