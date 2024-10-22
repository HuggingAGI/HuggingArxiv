# RAG4ITOps：专为 IT 运维与维护设计的可监督、可微调的全面 RAG 框架

发布时间：2024年10月21日

`RAG` `IT运维` `云计算`

> RAG4ITOps: A Supervised Fine-Tunable and Comprehensive RAG Framework for IT Operations and Maintenance

# 摘要

> 随着IT运维和维护领域对问答系统的需求日益增长，我们急需一个高效且可监督的微调框架，以确保数据安全、私有部署和持续升级。尽管大型语言模型（LLMs）在开放领域问答中表现出色，但如何高效处理企业专属语料库并构建领域特定的问答系统，仍是工业应用中的研究空白。为此，我们提出了一种基于检索增强生成（RAG）的通用框架——RAG4ITOps，涵盖了从模型微调到在线问答系统构建的全流程。实验结果显示，我们的方法在云计算领域的问答任务中表现优异，为实际企业级应用提供了有力支持。

> With the ever-increasing demands on Question Answering (QA) systems for IT operations and maintenance, an efficient and supervised fine-tunable framework is necessary to ensure the data security, private deployment and continuous upgrading. Although Large Language Models (LLMs) have notably improved the open-domain QA's performance, how to efficiently handle enterprise-exclusive corpora and build domain-specific QA systems are still less-studied for industrial applications. In this paper, we propose a general and comprehensive framework based on Retrieval Augmented Generation (RAG) and facilitate the whole business process of establishing QA systems for IT operations and maintenance. In accordance with the prevailing RAG method, our proposed framework, named with RAG4ITOps, composes of two major stages: (1) Models Fine-tuning \& Data Vectorization, and (2) Online QA System Process. At the Stage 1, we leverage a contrastive learning method with two negative sampling strategies to fine-tune the embedding model, and design the instruction templates to fine-tune the LLM with a Retrieval Augmented Fine-Tuning method. At the Stage 2, an efficient process of QA system is built for serving. We collect enterprise-exclusive corpora from the domain of cloud computing, and the extensive experiments show that our method achieves superior results than counterparts on two kinds of QA tasks. Our experiment also provide a case for applying the RAG4ITOps to real-world enterprise-level applications.

[Arxiv](https://arxiv.org/abs/2410.15805)