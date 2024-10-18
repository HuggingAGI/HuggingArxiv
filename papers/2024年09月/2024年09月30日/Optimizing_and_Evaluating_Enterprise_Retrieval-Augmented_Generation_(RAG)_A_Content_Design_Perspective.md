# 从内容设计角度优化与评估企业 RAG 系统

发布时间：2024年09月30日

`RAG` `企业服务` `客户支持`

> Optimizing and Evaluating Enterprise Retrieval-Augmented Generation (RAG): A Content Design Perspective

# 摘要

> RAG 技术利用 LLM 构建客户支持和问答系统，本文分享了我们团队在企业级 RAG 解决方案中的实践经验。我们发现，简单调整知识库内容的方式，能显著提升 RAG 效果。此外，面对新颖用户问题，传统的 RAG 评估方法不再适用，我们采用了灵活的“以人为先”策略。

> Retrieval-augmented generation (RAG) is a popular technique for using large language models (LLMs) to build customer-support, question-answering solutions. In this paper, we share our team's practical experience building and maintaining enterprise-scale RAG solutions that answer users' questions about our software based on product documentation. Our experience has not always matched the most common patterns in the RAG literature. This paper focuses on solution strategies that are modular and model-agnostic. For example, our experience over the past few years - using different search methods and LLMs, and many knowledge base collections - has been that simple changes to the way we create knowledge base content can have a huge impact on our RAG solutions' success. In this paper, we also discuss how we monitor and evaluate results. Common RAG benchmark evaluation techniques have not been useful for evaluating responses to novel user questions, so we have found a flexible, "human in the lead" approach is required.

[Arxiv](https://arxiv.org/abs/2410.12812)