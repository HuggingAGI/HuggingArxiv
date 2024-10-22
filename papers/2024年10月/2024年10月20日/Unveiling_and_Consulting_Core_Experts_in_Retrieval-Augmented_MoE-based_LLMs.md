# 揭秘并咨询基于检索增强的 MoE 大型语言模型中的核心专家

发布时间：2024年10月20日

`RAG` `人工智能`

> Unveiling and Consulting Core Experts in Retrieval-Augmented MoE-based LLMs

# 摘要

> RAG 显著提升了 LLM 处理知识密集型任务的能力。尽管现有研究通过优化文档检索和设计特定 LLM 来提升 RAG 性能，但 LLM 内部机制对 RAG 有效性的贡献仍未充分探索。本文探讨了基于 MoE 的 LLM 内部机制，并展示了通过专家激活优化 RAG 的方法。实验发现，几组核心专家主导了 RAG 相关行为，其激活能反映模型对内外部知识的倾向并调整行为。例如，这些专家能评估内部知识充足性、检索文档质量及上下文利用能力。基于此，我们提出了提升 RAG 效率和效果的策略。跨数据集和 MoE 模型的实验验证了方法的有效性。

> Retrieval-Augmented Generation (RAG) significantly improved the ability of Large Language Models (LLMs) to solve knowledge-intensive tasks. While existing research seeks to enhance RAG performance by retrieving higher-quality documents or designing RAG-specific LLMs, the internal mechanisms within LLMs that contribute to the effectiveness of RAG systems remain underexplored. In this paper, we aim to investigate these internal mechanisms within the popular Mixture-of-Expert (MoE)-based LLMs and demonstrate how to improve RAG by examining expert activations in these LLMs. Our controlled experiments reveal that several core groups of experts are primarily responsible for RAG-related behaviors. The activation of these core experts can signify the model's inclination towards external/internal knowledge and adjust its behavior. For instance, we identify core experts that can (1) indicate the sufficiency of the model's internal knowledge, (2) assess the quality of retrieved documents, and (3) enhance the model's ability to utilize context. Based on these findings, we propose several strategies to enhance RAG's efficiency and effectiveness through expert activation. Experimental results across various datasets and MoE-based LLMs show the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.15438)