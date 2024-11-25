# mR$^2$AG：针对基于知识的 VQA 的多模态检索-反思-增强式生成

发布时间：2024年11月22日

`RAG` `知识问答` `多模态`

> mR$^2$AG: Multimodal Retrieval-Reflection-Augmented Generation for Knowledge-Based VQA

# 摘要

> 先进的多模态大型语言模型（MLLMs）在 INFOSEEK 和 Encyclopedic-VQA 等基于知识的 VQA 任务中表现欠佳，这是因为其知识范畴有限且固定，往往致使回答含混不清、不够准确。于是，多模态检索增强生成（mRAG）顺势而生，为 MLLMs 提供全面且时新的知识，切实拓展了知识范畴。但当下的 mRAG 方法存在固有弊端，比如：1）即便无需外部知识，也会进行检索。2）缺少对支持查询的证据的判别。3）因额外的信息过滤模块或规则，增加了模型的复杂度。为克服这些缺陷，我们提出了一种新颖的通用框架，叫做	extbf{多模态	extbf{检索	extbf{-}	extbf{反思	extbf{-}	extbf{增强	extbf{生成}}（mR$^2$AG），它通过两个易于施行的反思操作达成自适应检索和有用信息定位，从而给出回答，同时避免了模型的高复杂度。在 mR$^2$AG 中，检索反思用于区分不同的用户查询，避免冗余的检索调用；相关性反思的引入是为了引导 MLLM 定位检索内容中的有益证据，并据此生成答案。另外，mR$^2$AG 能够融入任何训练有素的 MLLM 中，并在提出的 mR$^2$AG 指令调整数据集（mR$^2$AG-IT）上进行高效微调。mR$^2$AG 在 INFOSEEK 和 Encyclopedic-VQA 上的表现显著优于最先进的 MLLMs（如 GPT-4v/o）和基于 RAG 的 MLLMs，同时在众多视觉相关任务中保持了基础 MLLMs 的出色能力。

> Advanced Multimodal Large Language Models (MLLMs) struggle with recent Knowledge-based VQA tasks, such as INFOSEEK and Encyclopedic-VQA, due to their limited and frozen knowledge scope, often leading to ambiguous and inaccurate responses. Thus, multimodal Retrieval-Augmented Generation (mRAG) is naturally introduced to provide MLLMs with comprehensive and up-to-date knowledge, effectively expanding the knowledge scope. However, current mRAG methods have inherent drawbacks, including: 1) Performing retrieval even when external knowledge is not needed. 2) Lacking of identification of evidence that supports the query. 3) Increasing model complexity due to additional information filtering modules or rules. To address these shortcomings, we propose a novel generalized framework called \textbf{m}ultimodal \textbf{R}etrieval-\textbf{R}eflection-\textbf{A}ugmented \textbf{G}eneration (mR$^2$AG), which achieves adaptive retrieval and useful information localization to enable answers through two easy-to-implement reflection operations, preventing high model complexity. In mR$^2$AG, Retrieval-Reflection is designed to distinguish different user queries and avoids redundant retrieval calls, and Relevance-Reflection is introduced to guide the MLLM in locating beneficial evidence of the retrieved content and generating answers accordingly. In addition, mR$^2$AG can be integrated into any well-trained MLLM with efficient fine-tuning on the proposed mR$^2$AG Instruction-Tuning dataset (mR$^2$AG-IT). mR$^2$AG significantly outperforms state-of-the-art MLLMs (e.g., GPT-4v/o) and RAG-based MLLMs on INFOSEEK and Encyclopedic-VQA, while maintaining the exceptional capabilities of base MLLMs across a wide range of Visual-dependent tasks.

[Arxiv](https://arxiv.org/abs/2411.15041)