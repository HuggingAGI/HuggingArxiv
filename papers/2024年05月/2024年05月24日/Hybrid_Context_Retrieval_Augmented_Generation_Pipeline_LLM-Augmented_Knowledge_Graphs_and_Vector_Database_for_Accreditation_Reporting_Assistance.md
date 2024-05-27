# 认证报告辅助的混合上下文增强生成流程：结合LLM优化的知识图谱与向量数据库

发布时间：2024年05月24日

`RAG

这篇论文介绍了一个混合的上下文检索增强生成系统，专门设计来辅助商学院完成AACSB认证所需的文档对齐和报告工作。该系统利用了向量数据库和知识图谱来存储和检索相关数据，以确保报告内容与知识库中的信息一致。这种方法特别强调了检索增强生成（RAG）技术在实际应用中的效用，尤其是在处理复杂和详细的数据对齐任务时。因此，这篇论文应归类为RAG。` `高等教育` `商学院认证`

> Hybrid Context Retrieval Augmented Generation Pipeline: LLM-Augmented Knowledge Graphs and Vector Database for Accreditation Reporting Assistance

# 摘要

> 在高等教育领域，认证是确保教育质量的关键环节，它要求机构证明其致力于提供高质量的教育项目和服务。对于商学院而言，无论是在国内还是国际上，AACSB认证都是业界公认的最高标准。商学院要想获得并保持这一认证，必须经历一个既严格又耗时的报告和同行评审过程，以确保其符合AACSB的标准。为此，我们开发了一个混合的上下文检索增强生成系统，旨在辅助商学院完成认证所需的文档对齐和报告工作。该系统结合了向量数据库和知识图谱，存储了机构数据和AACSB标准数据，其输出可帮助机构利益相关者准备认证报告，确保报告内容与知识库中的信息一致。在构建知识图谱时，我们采用了手动构建和LLM增强两种方法。通过RAGAs框架的评估，我们的系统在答案的相关性和正确性方面表现出色。

> In higher education, accreditation is a quality assurance process, where an institution demonstrates a commitment to delivering high quality programs and services to their students. For business schools nationally and internationally the Association to Advance Collegiate Schools of Business (AACSB) accreditation is the gold standard. For a business school to receive and subsequently maintain accreditation, the school must undertake a rigorous, time consuming reporting and peer review process, to demonstrate alignment with the AACSB Standards. For this project we create a hybrid context retrieval augmented generation pipeline that can assist in the documentation alignment and reporting process necessary for accreditation. We implement both a vector database and knowledge graph, as knowledge stores containing both institutional data and AACSB Standard data. The output of the pipeline can be used by institution stakeholders to build their accreditation report, dually grounded by the context from the knowledge stores. To develop our knowledge graphs we utilized both a manual construction process as well as an LLM Augmented Knowledge Graph approach. We evaluated the pipeline using the RAGAs framework and observed optimal performance on answer relevancy and answer correctness metrics.

[Arxiv](https://arxiv.org/abs/2405.15436)