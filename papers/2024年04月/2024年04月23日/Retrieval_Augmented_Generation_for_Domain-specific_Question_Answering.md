# 为特定领域问答设计的检索增强生成技术

发布时间：2024年04月23日

`LLM应用` `客户服务` `问答系统`

> Retrieval Augmented Generation for Domain-specific Question Answering

# 摘要

> 问答系统在大型语言模型的高级应用中占据了重要地位。然而，通用的大型语言模型在理解特定领域的专业知识和术语方面存在局限，如金融、医疗、教育和产品客户服务等。为了提升对特定领域的理解，我们为Adobe产品开发了定制的问答系统。我们设计了一个创新的框架，用以构建庞大的问答数据库，并提出了一种针对检索优化的微调方法，以提升大型语言模型的性能。实践证明，对检索器进行微调能够显著提升最终的生成质量。我们的策略不仅提高了生成内容的准确性，还确保了生成过程中信息的及时更新和上下文关联。

> Question answering (QA) has become an important application in the advanced development of large language models. General pre-trained large language models for question-answering are not trained to properly understand the knowledge or terminology for a specific domain, such as finance, healthcare, education, and customer service for a product. To better cater to domain-specific understanding, we build an in-house question-answering system for Adobe products. We propose a novel framework to compile a large question-answer database and develop the approach for retrieval-aware finetuning of a Large Language model. We showcase that fine-tuning the retriever leads to major improvements in the final generation. Our overall approach reduces hallucinations during generation while keeping in context the latest retrieval information for contextual grounding.

[Arxiv](https://arxiv.org/abs/2404.14760)