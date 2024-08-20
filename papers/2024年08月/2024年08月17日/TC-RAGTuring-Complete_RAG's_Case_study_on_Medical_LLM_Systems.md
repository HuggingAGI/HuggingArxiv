# TC-RAG：探索图灵完备 RAG 在医疗大型语言模型系统中的应用案例

发布时间：2024年08月17日

`RAG` `人工智能`

> TC-RAG:Turing-Complete RAG's Case study on Medical LLM Systems

# 摘要

> 在提升领域特定大型语言模型 (LLM) 的探索中，检索增强生成 (RAG) 崭露头角，旨在解决幻觉、知识陈旧及专业查询中的知识局限等问题。然而，现有 RAG 方法因忽视关键的系统状态变量而受限，这些变量对自适应控制、检索终止及系统收敛至关重要。本文中，我们提出 TC-RAG 框架，通过集成图灵完备系统有效管理状态变量，显著提升知识检索的效率与准确性。借助具备自适应检索、推理与规划功能的内存堆栈系统，TC-RAG 不仅实现了检索过程的精准控制，还通过推入与弹出操作有效减少了错误知识的累积。在医学领域的实证研究中，基于真实医疗数据集的实验显示，TC-RAG 在准确性上超越现有方法达 7.20% 以上。相关数据集与代码已公开于 https://github.com/Artessay/SAMA.git。

> 
Abstract:In the pursuit of enhancing domain-specific Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) emerges as a promising solution to mitigate issues such as hallucinations, outdated knowledge, and limited expertise in highly specialized queries. However, existing approaches to RAG fall short by neglecting system state variables, which are crucial for ensuring adaptive control, retrieval halting, and system convergence. In this paper, we introduce the TC-RAG through rigorous proof, a novel framework that addresses these challenges by incorporating a Turing Complete System to manage state variables, thereby enabling more efficient and accurate knowledge retrieval. By leveraging a memory stack system with adaptive retrieval, reasoning, and planning capabilities, TC-RAG not only ensures the controlled halting of retrieval processes but also mitigates the accumulation of erroneous knowledge via Push and Pop actions. In the case study of the medical domain, our extensive experiments on real-world healthcare datasets demonstrate the superiority of TC-RAG over existing methods in accuracy by over 7.20\%. Our dataset and code have been available at https://https://github.com/Artessay/SAMA.git.
    

[Arxiv](https://arxiv.org/pdf/2408.09199)