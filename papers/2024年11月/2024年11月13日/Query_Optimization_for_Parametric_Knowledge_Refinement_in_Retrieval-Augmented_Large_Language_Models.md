# 在检索增强型大型语言模型中针对参数知识细化的查询优化

发布时间：2024年11月13日

`RAG` `问答系统` `检索系统`

> Query Optimization for Parametric Knowledge Refinement in Retrieval-Augmented Large Language Models

# 摘要

> 我们引入了“提取-精炼-检索-读取”（ERRR）框架，这是一种新颖的方法，旨在通过针对大型语言模型（LLM）的特定知识需求定制的查询优化来弥合检索增强生成（RAG）系统中的预检索信息差距。与 RAG 中使用的传统查询优化技术不同，ERRR 框架首先从 LLM 中提取参数知识，然后使用专门的查询优化器来精炼这些查询。这个过程确保只检索生成准确响应所必需的最相关信息。此外，为了提高灵活性并降低计算成本，我们为我们的管道提出了一个可训练的方案，该方案利用一个更小的、可调整的模型作为查询优化器，该优化器通过从一个更大的教师模型进行知识蒸馏而得到精炼。我们在各种问答（QA）数据集和不同的检索系统上的评估表明，ERRR 始终优于现有的基线，被证明是一个通用且具有成本效益的模块，用于提高 RAG 系统的实用性和准确性。

> We introduce the Extract-Refine-Retrieve-Read (ERRR) framework, a novel approach designed to bridge the pre-retrieval information gap in Retrieval-Augmented Generation (RAG) systems through query optimization tailored to meet the specific knowledge requirements of Large Language Models (LLMs). Unlike conventional query optimization techniques used in RAG, the ERRR framework begins by extracting parametric knowledge from LLMs, followed by using a specialized query optimizer for refining these queries. This process ensures the retrieval of only the most pertinent information essential for generating accurate responses. Moreover, to enhance flexibility and reduce computational costs, we propose a trainable scheme for our pipeline that utilizes a smaller, tunable model as the query optimizer, which is refined through knowledge distillation from a larger teacher model. Our evaluations on various question-answering (QA) datasets and with different retrieval systems show that ERRR consistently outperforms existing baselines, proving to be a versatile and cost-effective module for improving the utility and accuracy of RAG systems.

[Arxiv](https://arxiv.org/abs/2411.07820)