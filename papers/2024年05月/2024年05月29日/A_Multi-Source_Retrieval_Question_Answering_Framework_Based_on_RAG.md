# 基于RAG技术的多源检索问答框架

发布时间：2024年05月29日

`RAG

这篇论文主要探讨了检索增强生成（RAG）的改进方法，特别是通过使用GPT-3.5替代传统检索器，并开发了一种新的多源检索框架（MSRAG）来提高检索信息的相关性和生成结果的可靠性。这些改进措施直接关联到RAG技术的应用和优化，因此将其归类为RAG。` `问答系统` `知识检索`

> A Multi-Source Retrieval Question Answering Framework Based on RAG

# 摘要

> 随着大型语言模型的飞速发展，检索增强生成（RAG）已成为主流。但现有RAG模式常受错误信息干扰，影响生成结果的可靠性。为此，本研究创新性地采用GPT-3.5替代传统检索器，借助其海量知识库提升检索信息的相关性。同时，我们开发了一种基于网络的精细知识检索方法，利用GPT-3.5的强大推理力进行问题语义划分。为减少GPT检索的偏差及网络检索的噪声，我们提出了名为MSRAG的多源检索框架，融合了GPT与网络检索的优势。实验证明，该框架在提升问答系统的效率与准确性上，超越了现有RAG框架。

> With the rapid development of large-scale language models, Retrieval-Augmented Generation (RAG) has been widely adopted. However, existing RAG paradigms are inevitably influenced by erroneous retrieval information, thereby reducing the reliability and correctness of generated results. Therefore, to improve the relevance of retrieval information, this study proposes a method that replaces traditional retrievers with GPT-3.5, leveraging its vast corpus knowledge to generate retrieval information. We also propose a web retrieval based method to implement fine-grained knowledge retrieval, Utilizing the powerful reasoning capability of GPT-3.5 to realize semantic partitioning of problem.In order to mitigate the illusion of GPT retrieval and reduce noise in Web retrieval,we proposes a multi-source retrieval framework, named MSRAG, which combines GPT retrieval with web retrieval. Experiments on multiple knowledge-intensive QA datasets demonstrate that the proposed framework in this study performs better than existing RAG framework in enhancing the overall efficiency and accuracy of QA systems.

[Arxiv](https://arxiv.org/abs/2405.19207)