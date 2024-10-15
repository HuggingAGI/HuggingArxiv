# EasyRAG：为网络自动化操作量身打造的高效检索增强生成框架

发布时间：2024年10月14日

`RAG` `网络自动化` `问答系统`

> EasyRAG: Efficient Retrieval-Augmented Generation Framework for Network Automated Operations

# 摘要

> 本文推出 EasyRAG，一个简单、轻量级且高效的网络自动化操作增强生成框架。我们的方案优势如下：1. 精准问答：基于特定数据处理流程、双路径稀疏检索、LLM 重排序及答案优化，我们在 GLM4 赛道预赛夺冠，半决赛摘银。2. 简易部署：无需模型微调，占用极少 VRAM，轻松部署且高度可扩展，提供灵活代码库，支持多种搜索与生成策略。3. 高效推理：设计高效推理加速方案，显著降低延迟，保持高准确性，各加速方案可即插即用，持续提升系统效率。代码与数据已发布于 https://github.com/BUAADreamer/EasyRAG。

> This paper presents EasyRAG, a simple, lightweight, and efficient retrieval-augmented generation framework for network automated operations. The advantages of our solution are: 1.Accurate Question Answering: We designed a straightforward RAG scheme based on (1) a specific data processing workflow (2) dual-route sparse retrieval for coarse ranking (3) LLM Reranker for reranking (4) LLM answer generation and optimization. This approach achieved first place in the GLM4 track in the preliminary round and second place in the GLM4 track in the semifinals. 2.Simple Deployment: Our method primarily consists of BM25 retrieval and BGE-reranker reranking, requiring no fine-tuning of any models, occupying minimal VRAM, easy to deploy, and highly scalable; we provide a flexible code library with various search and generation strategies, facilitating custom process implementation. 3.Efficient Inference: We designed an efficient inference acceleration scheme for the entire coarse ranking, reranking, and generation process that significantly reduces the inference latency of RAG while maintaining a good level of accuracy; each acceleration scheme can be plug-and-play into any component of the RAG process, consistently enhancing the efficiency of the RAG system. Our code and data are released at https://github.com/BUAADreamer/EasyRAG.

[Arxiv](https://arxiv.org/abs/2410.10315)