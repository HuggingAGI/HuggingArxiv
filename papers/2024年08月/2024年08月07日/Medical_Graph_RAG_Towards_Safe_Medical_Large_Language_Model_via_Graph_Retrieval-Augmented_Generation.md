# 医疗图谱增强生成（Medical Graph RAG）：借助图谱检索增强技术，构建安全可靠的医疗大型语言模型。

发布时间：2024年08月07日

`RAG` `人工智能`

> Medical Graph RAG: Towards Safe Medical Large Language Model via Graph Retrieval-Augmented Generation

# 摘要

> 我们推出了一款专为医疗领域定制的基于图的 RAG 框架——**MedGraphRAG**，旨在提升大型语言模型的性能，并确保生成结果的证据基础，从而在处理敏感医疗数据时增强安全性和可靠性。我们的流程从一种创新的混合静态-语义文档分块技术开始，大幅提升了上下文捕捉能力。通过提取的实体构建了一个三层级的层次图，这些实体与医学文献和词典中的基础知识相连接。随后，这些实体相互关联形成元图，并基于语义相似性合并成一个全面的全球图，支持精准的信息检索和响应生成。检索过程中采用的 U-retrieve 方法有效平衡了全局意识和索引效率。通过全面的消融研究，我们的方法在多个医学问答基准上持续超越现有模型，并确保生成的响应包含原始文档，极大增强了医疗 LLM 的实际应用可靠性。代码即将发布于：https://github.com/MedicineToken/Medical-Graph-RAG/tree/main

> We introduce a novel graph-based Retrieval-Augmented Generation (RAG) framework specifically designed for the medical domain, called \textbf{MedGraphRAG}, aimed at enhancing Large Language Model (LLM) capabilities and generating evidence-based results, thereby improving safety and reliability when handling private medical data. Our comprehensive pipeline begins with a hybrid static-semantic approach to document chunking, significantly improving context capture over traditional methods. Extracted entities are used to create a three-tier hierarchical graph structure, linking entities to foundational medical knowledge sourced from medical papers and dictionaries. These entities are then interconnected to form meta-graphs, which are merged based on semantic similarities to develop a comprehensive global graph. This structure supports precise information retrieval and response generation. The retrieval process employs a U-retrieve method to balance global awareness and indexing efficiency of the LLM. Our approach is validated through a comprehensive ablation study comparing various methods for document chunking, graph construction, and information retrieval. The results not only demonstrate that our hierarchical graph construction method consistently outperforms state-of-the-art models on multiple medical Q\&A benchmarks, but also confirms that the responses generated include source documentation, significantly enhancing the reliability of medical LLMs in practical applications. Code will be at: https://github.com/MedicineToken/Medical-Graph-RAG/tree/main

[Arxiv](https://arxiv.org/abs/2408.04187)