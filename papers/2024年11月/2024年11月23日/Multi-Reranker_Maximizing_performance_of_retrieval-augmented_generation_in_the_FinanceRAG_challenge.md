# Multi-Reranker：于 FinanceRAG 挑战里将检索增强生成的性能最大化

发布时间：2024年11月23日

`RAG` `语言模型`

> Multi-Reranker: Maximizing performance of retrieval-augmented generation in the FinanceRAG challenge

# 摘要

> 随着大型语言模型（LLMs）在解决特定领域问题方面的能力不断增强，其在金融领域的应用迅速拓展。诸如分析财务报表、披露信息及相关文件这类高价值且耗时的任务，如今借助LLMs得以有效处理。本文详述了为ACM-ICAIF '24 FinanceRAG竞赛所开发的高性能、金融专用的检索增强生成（RAG）系统。我们通过在预检索阶段针对查询扩展和语料库优化的消融研究来提升性能。为提高检索精准度，我们运用了多个重排序模型。特别值得一提的是，我们在生成阶段引入了一种高效管理长上下文规模的方法，在不影响性能的前提下显著提升了响应质量。最终，我们在FinanceRAG挑战赛中荣获第二名。我们的主要贡献有：（1）预检索的消融分析，（2）强化的检索算法，（3）长上下文管理的创新手段。此项工作彰显了LLMs在有效处理和分析复杂金融数据以生成准确且有价值见解方面的潜能。源代码及更多详情可在https://github.com/cv-lee/FinanceRAG获取。

> As Large Language Models (LLMs) increasingly address domain-specific problems, their application in the financial sector has expanded rapidly. Tasks that are both highly valuable and time-consuming, such as analyzing financial statements, disclosures, and related documents, are now being effectively tackled using LLMs. This paper details the development of a high-performance, finance-specific Retrieval-Augmented Generation (RAG) system for the ACM-ICAIF '24 FinanceRAG competition. We optimized performance through ablation studies on query expansion and corpus refinement during the pre-retrieval phase. To enhance retrieval accuracy, we employed multiple reranker models. Notably, we introduced an efficient method for managing long context sizes during the generation phase, significantly improving response quality without sacrificing performance. We ultimately achieve 2nd place in the FinanceRAG Challenge. Our key contributions include: (1) pre-retrieval ablation analysis, (2) an enhanced retrieval algorithm, and (3) a novel approach for long-context management. This work demonstrates the potential of LLMs in effectively processing and analyzing complex financial data to generate accurate and valuable insights. The source code and further details are available at https://github.com/cv-lee/FinanceRAG.

[Arxiv](https://arxiv.org/abs/2411.16732)