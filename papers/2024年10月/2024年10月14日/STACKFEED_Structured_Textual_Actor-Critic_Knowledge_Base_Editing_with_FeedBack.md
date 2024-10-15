# STACKFEED：结合反馈机制的结构化文本 Actor-Critic 知识库编辑系统

发布时间：2024年10月14日

`RAG` `知识库管理` `人工智能`

> STACKFEED: Structured Textual Actor-Critic Knowledge Base Editing with FeedBack

# 摘要

> 大型语言模型 (LLM) 在处理低资源或私人数据时，常生成错误或过时信息。为解决此问题，RAG 使用外部知识库 (KB)，但 KB 也可能不准确。我们提出 STACKFEED，一种基于专家反馈和多 Actor、集中式 Critic 强化学习框架的结构化文本 Actor-Critic 知识库编辑方法，通过迭代改进 KB。每个文档由 ReACT 代理处理，根据集中式 Critic 的指令进行结构化编辑。实验表明，STACKFEED 显著提升 KB 质量和 RAG 系统性能，准确性比基线高出 8%。

> Large Language Models (LLMs) often generate incorrect or outdated information, especially in low-resource settings or when dealing with private data. To address this, Retrieval-Augmented Generation (RAG) uses external knowledge bases (KBs), but these can also suffer from inaccuracies. We introduce STACKFEED, a novel Structured Textual Actor-Critic Knowledge base editing with FEEDback approach that iteratively refines the KB based on expert feedback using a multi-actor, centralized critic reinforcement learning framework. Each document is assigned to an actor, modeled as a ReACT agent, which performs structured edits based on document-specific targeted instructions from a centralized critic. Experimental results show that STACKFEED significantly improves KB quality and RAG system performance, enhancing accuracy by up to 8% over baselines.

[Arxiv](https://arxiv.org/abs/2410.10584)