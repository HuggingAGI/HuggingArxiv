# 为特定领域的问题解答，引入了检索增强生成技术。

发布时间：2024年04月23日

`LLM应用` `问答系统` `领域定制`

> Retrieval Augmented Generation for Domain-specific Question Answering

# 摘要

> 问答系统在大型语言模型的高级应用中扮演着关键角色。然而，通用的预训练模型往往缺乏对特定领域知识的理解，比如金融、医疗、教育或产品客服等。为了提升对特定领域的理解，我们为Adobe产品量身打造了一个内部问答系统。我们引入了一个创新框架，用以构建庞大的问答数据库，并提出了一种针对大型语言模型的检索感知微调方法。实践证明，对检索器进行微调能显著提升最终的生成质量。我们的方法在确保生成内容的准确性的同时，有效减少了生成过程中的臆造信息。

> Question answering (QA) has become an important application in the advanced development of large language models. General pre-trained large language models for question-answering are not trained to properly understand the knowledge or terminology for a specific domain, such as finance, healthcare, education, and customer service for a product. To better cater to domain-specific understanding, we build an in-house question-answering system for Adobe products. We propose a novel framework to compile a large question-answer database and develop the approach for retrieval-aware finetuning of a Large Language model. We showcase that fine-tuning the retriever leads to major improvements in the final generation. Our overall approach reduces hallucinations during generation while keeping in context the latest retrieval information for contextual grounding.

[Arxiv](https://arxiv.org/abs/2404.14760)