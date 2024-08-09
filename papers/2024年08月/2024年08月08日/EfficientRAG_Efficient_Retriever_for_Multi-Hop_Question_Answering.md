# EfficientRAG：专为多跳问答设计的高效检索工具

发布时间：2024年08月08日

`RAG` `问答系统` `信息检索`

> EfficientRAG: Efficient Retriever for Multi-Hop Question Answering

# 摘要

> 面对多跳查询这类复杂问题，RAG方法显得力不从心。尽管迭代检索能通过收集更多信息提升性能，但现有方法往往需多次调用大型语言模型（LLM）。本文推出的EfficientRAG，作为多跳问答的高效检索器，能在迭代中自主生成新查询，无需LLM介入，并有效剔除无关信息。实验显示，EfficientRAG在三大开放域多跳问答数据集上，性能超越了现有RAG方法。

> Retrieval-augmented generation (RAG) methods encounter difficulties when addressing complex questions like multi-hop queries. While iterative retrieval methods improve performance by gathering additional information, current approaches often rely on multiple calls of large language models (LLMs). In this paper, we introduce EfficientRAG, an efficient retriever for multi-hop question answering. EfficientRAG iteratively generates new queries without the need for LLM calls at each iteration and filters out irrelevant information. Experimental results demonstrate that EfficientRAG surpasses existing RAG methods on three open-domain multi-hop question-answering datasets.

[Arxiv](https://arxiv.org/abs/2408.04259)