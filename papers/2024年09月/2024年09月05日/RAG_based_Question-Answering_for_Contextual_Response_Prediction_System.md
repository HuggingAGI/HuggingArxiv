# 基于 RAG 的问答系统助力上下文响应预测

发布时间：2024年09月05日

`RAG` `问答系统`

> RAG based Question-Answering for Contextual Response Prediction System

# 摘要

> 大型语言模型 (LLM) 在多种 NLP 任务中表现出色，尤其在问答系统方面潜力巨大。然而，在行业应用中，为了提供精准且相关的信息，LLM 需要依赖全面的知识库，以避免信息失真。检索增强生成 (RAG) 技术应运而生，成为解决这一难题的希望。但利用 RAG 构建实际应用中的问答框架，仍面临三大挑战：数据获取难、生成内容质量评估难、人工评估成本高。本文提出一个端到端框架，结合 RAG 技术与 LLM，专为行业需求设计。该系统能根据客户查询，自动检索相关文档并结合历史对话，生成客服代理的响应建议。经全面评估，该方案在准确性与相关性上超越了基于 BERT 的算法。研究显示，RAG 赋能的 LLM 能有效减轻客服负担，成为他们的得力助手。

> Large Language Models (LLMs) have shown versatility in various Natural Language Processing (NLP) tasks, including their potential as effective question-answering systems. However, to provide precise and relevant information in response to specific customer queries in industry settings, LLMs require access to a comprehensive knowledge base to avoid hallucinations. Retrieval Augmented Generation (RAG) emerges as a promising technique to address this challenge. Yet, developing an accurate question-answering framework for real-world applications using RAG entails several challenges: 1) data availability issues, 2) evaluating the quality of generated content, and 3) the costly nature of human evaluation. In this paper, we introduce an end-to-end framework that employs LLMs with RAG capabilities for industry use cases. Given a customer query, the proposed system retrieves relevant knowledge documents and leverages them, along with previous chat history, to generate response suggestions for customer service agents in the contact centers of a major retail company. Through comprehensive automated and human evaluations, we show that this solution outperforms the current BERT-based algorithms in accuracy and relevance. Our findings suggest that RAG-based LLMs can be an excellent support to human customer service representatives by lightening their workload.

[Arxiv](https://arxiv.org/abs/2409.03708)