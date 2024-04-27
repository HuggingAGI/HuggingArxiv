# 利用大型语言模型提升企业知识库的问答能力

发布时间：2024年04月20日

`LLM应用` `企业知识管理`

> Enhancing Question Answering for Enterprise Knowledge Bases using Large Language Models

# 摘要

> 高效管理知识对于提升企业与组织的运作效能和创新实力至关重要。通过知识向量化索引，催生了众多知识检索技术，极大提升了知识管理系统的效率。随着生成式自然语言处理技术的突飞猛进，现在能够从相关文档中提取出精确且连贯的答案。但在企业知识库中，由于数据隐私和安全政策的限制，从头构建大量的训练数据集以支持知识检索和生成，既是一项艰巨任务，又成本高昂。为应对这一挑战，本文提出了EKRG，一种创新的基于大型语言模型（LLMs）的检索-生成框架，旨在以较低的注释成本为企业知识库提供问答服务。具体而言，在检索阶段，我们首先采用一种指令调优方法，利用LLM生成充足的文档-问题对，以训练知识检索器。这种方法通过精心设计的指令，能够为企业知识库高效生成多样化的问题，涵盖事实型和解决方案型知识。我们还开发了一种感知相关性的师生学习策略，进一步提升了训练效率。在生成阶段，我们提出了一种基于思维链（CoT）的微调方法，使LLM能够灵活运用检索到的文档，精准回应用户询问。最终，我们在真实世界数据集上的广泛实验验证了我们框架的有效性。

> Efficient knowledge management plays a pivotal role in augmenting both the operational efficiency and the innovative capacity of businesses and organizations. By indexing knowledge through vectorization, a variety of knowledge retrieval methods have emerged, significantly enhancing the efficacy of knowledge management systems. Recently, the rapid advancements in generative natural language processing technologies paved the way for generating precise and coherent answers after retrieving relevant documents tailored to user queries. However, for enterprise knowledge bases, assembling extensive training data from scratch for knowledge retrieval and generation is a formidable challenge due to the privacy and security policies of private data, frequently entailing substantial costs. To address the challenge above, in this paper, we propose EKRG, a novel Retrieval-Generation framework based on large language models (LLMs), expertly designed to enable question-answering for Enterprise Knowledge bases with limited annotation costs. Specifically, for the retrieval process, we first introduce an instruction-tuning method using an LLM to generate sufficient document-question pairs for training a knowledge retriever. This method, through carefully designed instructions, efficiently generates diverse questions for enterprise knowledge bases, encompassing both fact-oriented and solution-oriented knowledge. Additionally, we develop a relevance-aware teacher-student learning strategy to further enhance the efficiency of the training process. For the generation process, we propose a novel chain of thought (CoT) based fine-tuning method to empower the LLM-based generator to adeptly respond to user questions using retrieved documents. Finally, extensive experiments on real-world datasets have demonstrated the effectiveness of our proposed framework.

![利用大型语言模型提升企业知识库的问答能力](../../../paper_images/2404.08695/x1.png)

![利用大型语言模型提升企业知识库的问答能力](../../../paper_images/2404.08695/ablation.png)

[Arxiv](https://arxiv.org/abs/2404.08695)