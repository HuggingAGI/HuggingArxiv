# 为特定领域问答设计的检索增强生成技术

发布时间：2024年04月23日

`LLM应用` `客户服务` `问答系统`

> Retrieval Augmented Generation for Domain-specific Question Answering

# 摘要

> 问答系统在大型语言模型的高级应用中占据了重要地位。然而，通用的预训练模型往往缺乏对特定领域，如金融、医疗、教育或产品客户服务的专业理解。为了提升对特定领域的精准把握，我们为 Adobe 产品专门打造了一套内部问答系统。本系统采用了创新框架，旨在构建庞大的问答数据库，并针对大型语言模型进行了检索感知的微调训练。实践证明，对检索器进行微调能显著提升最终输出的质量。我们的策略在确保生成内容的准确性的同时，有效减少了生成过程中可能出现的误导性信息。

> Question answering (QA) has become an important application in the advanced development of large language models. General pre-trained large language models for question-answering are not trained to properly understand the knowledge or terminology for a specific domain, such as finance, healthcare, education, and customer service for a product. To better cater to domain-specific understanding, we build an in-house question-answering system for Adobe products. We propose a novel framework to compile a large question-answer database and develop the approach for retrieval-aware finetuning of a Large Language model. We showcase that fine-tuning the retriever leads to major improvements in the final generation. Our overall approach reduces hallucinations during generation while keeping in context the latest retrieval information for contextual grounding.

[Arxiv](https://arxiv.org/abs/2404.14760)