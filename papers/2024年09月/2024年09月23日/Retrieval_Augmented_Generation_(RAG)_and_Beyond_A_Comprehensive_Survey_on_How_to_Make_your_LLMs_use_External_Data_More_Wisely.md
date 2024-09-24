# RAG 及其进阶：一份详尽的调查，探讨如何让 LLMs 更聪明地利用外部数据

发布时间：2024年09月23日

`RAG` `人工智能` `数据科学`

> Retrieval Augmented Generation (RAG) and Beyond: A Comprehensive Survey on How to Make your LLMs use External Data More Wisely

# 摘要

> 结合外部数据的大型语言模型 (LLM) 在处理现实任务时表现出色。诸如 Retrieval-Augmented Generation (RAG) 和微调等技术，正日益受到关注并广泛应用。然而，在各专业领域有效部署这些数据增强的 LLM 仍面临诸多挑战，从数据检索到意图解读，再到复杂任务的推理能力利用。我们坚信，数据增强的 LLM 应用没有万能解决方案。实践中，性能不佳常因未能精准把握任务核心，或任务本身需多重能力协同，而这些能力需解耦以优化解决。本调查提出 RAG 任务分类法，根据数据需求和任务焦点，将用户查询分为四类：显式、隐式事实查询，及可解释、隐藏理由查询。我们定义这些类别，提供相关数据集，并总结应对挑战的关键技术和有效策略。最后，探讨三种外部数据整合方式：上下文、小模型和微调，分析各自优劣及适用问题。旨在助您全面理解并破解 LLM 应用的数据需求与瓶颈，提供系统开发指南。

> Large language models (LLMs) augmented with external data have demonstrated remarkable capabilities in completing real-world tasks. Techniques for integrating external data into LLMs, such as Retrieval-Augmented Generation (RAG) and fine-tuning, are gaining increasing attention and widespread application. Nonetheless, the effective deployment of data-augmented LLMs across various specialized fields presents substantial challenges. These challenges encompass a wide range of issues, from retrieving relevant data and accurately interpreting user intent to fully harnessing the reasoning capabilities of LLMs for complex tasks. We believe that there is no one-size-fits-all solution for data-augmented LLM applications. In practice, underperformance often arises from a failure to correctly identify the core focus of a task or because the task inherently requires a blend of multiple capabilities that must be disentangled for better resolution. In this survey, we propose a RAG task categorization method, classifying user queries into four levels based on the type of external data required and primary focus of the task: explicit fact queries, implicit fact queries, interpretable rationale queries, and hidden rationale queries. We define these levels of queries, provide relevant datasets, and summarize the key challenges and most effective techniques for addressing these challenges. Finally, we discuss three main forms of integrating external data into LLMs: context, small model, and fine-tuning, highlighting their respective strengths, limitations, and the types of problems they are suited to solve. This work aims to help readers thoroughly understand and decompose the data requirements and key bottlenecks in building LLM applications, offering solutions to the different challenges and serving as a guide to systematically developing such applications.

[Arxiv](https://arxiv.org/abs/2409.14924)