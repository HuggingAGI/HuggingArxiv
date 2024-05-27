# 认证报告辅助的混合上下文增强生成流程：结合LLM优化的知识图谱与向量数据库，提升检索效率。

发布时间：2024年05月24日

`RAG

理由：这篇论文介绍了一个混合的上下文检索增强生成系统，用于辅助商学院完成认证所需的文档对齐和报告工作。该系统结合了向量数据库与知识图谱，并利用了RAGAs框架来评估系统性能。这里的重点是使用检索增强生成（RAG）技术来优化文档生成过程，这与RAG分类相符。虽然系统可能涉及LLM的应用，但论文的主要贡献在于RAG技术的应用和评估，而不是LLM的理论或应用。此外，论文没有特别强调Agent的概念或LLM的理论研究。` `高等教育` `商学院认证`

> Hybrid Context Retrieval Augmented Generation Pipeline: LLM-Augmented Knowledge Graphs and Vector Database for Accreditation Reporting Assistance

# 摘要

> 在高等教育领域，认证是确保教育质量的关键环节，它要求机构证明其致力于为学生提供优质的教育项目与服务。对于商学院来说，国际商学院促进协会（AACSB）的认证堪称黄金标准。商学院若想获得并保持这一认证，必须通过一系列严格且耗时的报告和同行评审，以确保其符合AACSB的标准。为此，我们开发了一套混合的上下文检索增强生成系统，旨在辅助商学院完成认证所需的文档对齐和报告工作。该系统结合了向量数据库与知识图谱，存储了机构数据及AACSB标准数据，其输出可帮助机构利益相关者构建认证报告，确保报告内容与知识库中的上下文紧密对齐。我们通过手动构建与LLM增强的方法创建了知识图谱，并利用RAGAs框架评估了系统性能，结果显示在答案的相关性与正确性上达到了最佳水平。

> In higher education, accreditation is a quality assurance process, where an institution demonstrates a commitment to delivering high quality programs and services to their students. For business schools nationally and internationally the Association to Advance Collegiate Schools of Business (AACSB) accreditation is the gold standard. For a business school to receive and subsequently maintain accreditation, the school must undertake a rigorous, time consuming reporting and peer review process, to demonstrate alignment with the AACSB Standards. For this project we create a hybrid context retrieval augmented generation pipeline that can assist in the documentation alignment and reporting process necessary for accreditation. We implement both a vector database and knowledge graph, as knowledge stores containing both institutional data and AACSB Standard data. The output of the pipeline can be used by institution stakeholders to build their accreditation report, dually grounded by the context from the knowledge stores. To develop our knowledge graphs we utilized both a manual construction process as well as an LLM Augmented Knowledge Graph approach. We evaluated the pipeline using the RAGAs framework and observed optimal performance on answer relevancy and answer correctness metrics.

[Arxiv](https://arxiv.org/abs/2405.15436)