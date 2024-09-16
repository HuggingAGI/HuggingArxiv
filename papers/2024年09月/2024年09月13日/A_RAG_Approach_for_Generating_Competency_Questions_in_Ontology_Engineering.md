# 本体工程中生成能力问题的一种 RAG 方法

发布时间：2024年09月13日

`RAG` `本体工程` `人工智能`

> A RAG Approach for Generating Competency Questions in Ontology Engineering

# 摘要

> 能力问题（CQ）的制定是本体开发和评估的关键环节。传统上，这一过程依赖于领域专家和知识工程师的辛勤工作，耗时且费力。随着大型语言模型（LLM）的兴起，自动化这一过程成为可能。我们提出了一种检索增强生成（RAG）方法，利用LLM根据一组科学论文自动生成CQ，这些论文被视为领域知识库。我们探讨了不同论文数量和LLM温度设置对RAG的影响，并使用GPT-4在两个本体工程任务上进行了实验，结果与专家构建的CQ进行了对比。实证评估表明，相较于零-shot提示，将领域知识融入RAG显著提升了LLM生成CQ的性能。

> Competency question (CQ) formulation is central to several ontology development and evaluation methodologies. Traditionally, the task of crafting these competency questions heavily relies on the effort of domain experts and knowledge engineers which is often time-consuming and labor-intensive. With the emergence of Large Language Models (LLMs), there arises the possibility to automate and enhance this process. Unlike other similar works which use existing ontologies or knowledge graphs as input to LLMs, we present a retrieval-augmented generation (RAG) approach that uses LLMs for the automatic generation of CQs given a set of scientific papers considered to be a domain knowledge base. We investigate its performance and specifically, we study the impact of different number of papers to the RAG and different temperature setting of the LLM. We conduct experiments using GPT-4 on two domain ontology engineering tasks and compare results against ground-truth CQs constructed by domain experts. Empirical assessments on the results, utilizing evaluation metrics (precision and consistency), reveal that compared to zero-shot prompting, adding relevant domain knowledge to the RAG improves the performance of LLMs on generating CQs for concrete ontology engineering tasks.

[Arxiv](https://arxiv.org/abs/2409.08820)