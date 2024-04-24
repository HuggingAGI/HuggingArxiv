# 为特定领域的问题回答，采用检索增强的生成技术。

发布时间：2024年04月23日

`分类：LLM应用

这篇论文讨论了如何通过微调大型语言模型来提升问答系统在特定领域的性能，这属于LLM应用的范畴。论文中提到了对Adobe产品量身定制的问答系统，以及对大型语言模型进行检索感知的微调，这些都是实际应用中的具体实践。` `客户服务` `问答系统`

> Retrieval Augmented Generation for Domain-specific Question Answering

# 摘要

> 问答系统在大型语言模型的深度发展中扮演着关键角色。然而，通用的大型语言模型在理解特定领域的专业知识或术语方面存在局限，比如金融、医疗、教育和产品客户服务等领域。为了提升对特定领域的理解，我们为Adobe产品量身定制了一套内部问答系统。本系统采用了创新的框架来构建庞大的问答数据库，并采用了一种新颖的方法对大型语言模型进行检索感知的微调。我们的实验证明，对检索器进行微调能够显著提升最终生成的文本质量。这种方法不仅减少了生成文本时的臆造内容，还确保了生成内容与最新检索到的信息保持一致，为文本提供了准确的上下文基础。

> Question answering (QA) has become an important application in the advanced development of large language models. General pre-trained large language models for question-answering are not trained to properly understand the knowledge or terminology for a specific domain, such as finance, healthcare, education, and customer service for a product. To better cater to domain-specific understanding, we build an in-house question-answering system for Adobe products. We propose a novel framework to compile a large question-answer database and develop the approach for retrieval-aware finetuning of a Large Language model. We showcase that fine-tuning the retriever leads to major improvements in the final generation. Our overall approach reduces hallucinations during generation while keeping in context the latest retrieval information for contextual grounding.

[Arxiv](https://arxiv.org/abs/2404.14760)