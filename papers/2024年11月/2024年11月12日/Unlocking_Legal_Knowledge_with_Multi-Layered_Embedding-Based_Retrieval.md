# 通过基于多层嵌入的检索来解锁法律知识

发布时间：2024年11月12日

`LLM应用` `信息检索`

> Unlocking Legal Knowledge with Multi-Layered Embedding-Based Retrieval

# 摘要

> 这项工作通过为法律和立法文本提出一种基于多层嵌入的检索方法，解决了捕捉法律知识复杂性的挑战。不仅为单个条款创建嵌入，还为其组件（段落、条款）和结构分组（书籍、标题、章节等）创建嵌入，我们试图通过使用密集的嵌入向量来捕捉法律信息的微妙之处，在不同的粒度级别上表示它。我们的方法通过允许检索增强生成系统提供准确的响应，无论是针对特定片段还是整个部分，根据用户的查询进行定制，满足了各种信息需求。我们探索了法律文本中的相关性、语义分块和内在层次结构的概念，认为这种方法增强了法律信息检索。尽管重点是遵循大陆法传统的巴西立法方法和巴西宪法，但我们的研究结果原则上应该适用于不同的法律体系，包括遵循普通法传统的法律体系。此外，所提出方法的原则超出了法律领域，为在任何以分层文本编码信息为特征的领域中组织和检索信息提供了有价值的见解。

> This work addresses the challenge of capturing the complexities of legal knowledge by proposing a multi-layered embedding-based retrieval method for legal and legislative texts. Creating embeddings not only for individual articles but also for their components (paragraphs, clauses) and structural groupings (books, titles, chapters, etc), we seek to capture the subtleties of legal information through the use of dense vectors of embeddings, representing it at varying levels of granularity. Our method meets various information needs by allowing the Retrieval Augmented Generation system to provide accurate responses, whether for specific segments or entire sections, tailored to the user's query. We explore the concepts of aboutness, semantic chunking, and inherent hierarchy within legal texts, arguing that this method enhances the legal information retrieval. Despite the focus being on Brazil's legislative methods and the Brazilian Constitution, which follow a civil law tradition, our findings should in principle be applicable across different legal systems, including those adhering to common law traditions. Furthermore, the principles of the proposed method extend beyond the legal domain, offering valuable insights for organizing and retrieving information in any field characterized by information encoded in hierarchical text.

[Arxiv](https://arxiv.org/abs/2411.07739)