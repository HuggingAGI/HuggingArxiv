# 借助大型语言模型之力，探索网络爬虫的新境界

发布时间：2024年06月12日

`RAG

这篇论文主要探讨了如何结合预训练的大型语言模型（LLMs）和RAG模型（Retrieval-Augmented Generation）来提高数据提取的准确性和效率。论文中提到的研究重点是如何利用RAG模型在信息检索和知识表示方面的优势，以及如何通过优化分割、搜索和排名算法来提升数据提取的能力。因此，这篇论文更偏向于RAG模型的应用和改进，而不是Agent、LLM应用或LLM理论。` `数据提取`

> Leveraging Large Language Models for Web Scraping

# 摘要

> 大型语言模型（LLMs）在模拟人类任务和提高生产效率方面表现出色，但直接用于数据提取时，因偏重流畅性而牺牲事实准确性，且处理特定信息的能力有限。为此，本研究结合预训练LLMs的知识表示能力和RAG模型精准信息访问的优势，开发了一种适用于语言生成RAG模型的通用准确数据抓取方案。我们采用带有潜在知识检索器的预训练语言模型，使模型能从庞大语料库中提取并聚焦文档，以更模块化和可解释的方式捕捉知识。通过深入分析RAG模型在HTML元素语义分类、文本分割及不同LLMs与排名算法比较等任务中的表现，我们发现，结合有效的分割、搜索和排名算法，预训练于标准自然语言的LLMs能成为从非结构化文本中提取复杂数据的高效工具。未来研究将聚焦于解决基于RAG的数据提取框架中来源追踪和动态知识更新的难题，有望彻底革新从海量文本信息中提取数据的方式。

> Large Language Models (LLMs) demonstrate remarkable capabilities in replicating human tasks and boosting productivity. However, their direct application for data extraction presents limitations due to a prioritisation of fluency over factual accuracy and a restricted ability to manipulate specific information. Therefore to overcome these limitations, this research leverages the knowledge representation power of pre-trained LLMs and the targeted information access enabled by RAG models, this research investigates a general-purpose accurate data scraping recipe for RAG models designed for language generation. To capture knowledge in a more modular and interpretable way, we use pre trained language models with a latent knowledge retriever, which allows the model to retrieve and attend over documents from a large corpus. We utilised RAG model architecture and did an in-depth analysis of their capabilities under three tasks: (i) Semantic Classification of HTML elements, (ii) Chunking HTML text for effective understanding, and (iii) comparing results from different LLMs and ranking algorithms. While previous work has developed dedicated architectures and training procedures for HTML understanding and extraction, we show that LLMs pre-trained on standard natural language with an addition of effective chunking, searching and ranking algorithms, can prove to be efficient data scraping tool to extract complex data from unstructured text. Future research directions include addressing the challenges of provenance tracking and dynamic knowledge updates within the proposed RAG-based data extraction framework. By overcoming these limitations, this approach holds the potential to revolutionise data extraction from vast repositories of textual information.

[Arxiv](https://arxiv.org/abs/2406.08246)