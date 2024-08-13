# 借助 RAG 技术与自我微调，我们开创了一种生成指令数据集的新方法。

发布时间：2024年08月11日

`RAG`

> A New Pipeline For Generating Instruction Dataset via RAG and Self Fine-Tuning

# 摘要

> 随着大型语言模型的迅猛发展，针对企业和组织独特需求的领域特定代理的需求日益增长。本研究提出了一种流程，利用LLM和检索增强生成框架，通过自定义文档集合在特定领域构建高质量指令数据集进行微调。该流程通过摄入领域特定文档，生成相关且上下文适当的指令，有效创建全面数据集，克服了传统方法的局限。我们的流程提供动态解决方案，快速适应文档更新，无需完全重新训练，并解决数据稀缺问题，适用于数据集稀缺的专业领域。作为案例研究，我们将其应用于精神病学领域，展示了所提出方法的可行性，并强调了其在各个行业和领域中广泛采用的潜力。

> With the rapid development of large language models in recent years, there has been an increasing demand for domain-specific Agents that can cater to the unique needs of enterprises and organizations. Unlike general models, which strive for broad coverage, these specialized Agents rely on focused datasets tailored to their intended applications. This research proposes a pipeline that leverages the power of LLMs and the Retrieval-Augmented Generation related framework to construct high-quality instruction datasets for fine-tuning on specific domains using custom document collections. By ingesting domain-specific documents, the pipeline generates relevant and contextually appropriate instructions, thus effectively creating a comprehensive dataset for fine-tuning LLMs on the target domain. This approach overcomes the limitations of traditional dataset creation methods, which often rely on manual curation or web-scraping techniques that may introduce noise and irrelevant data. Notably, our pipeline offers a dynamic solution that can quickly adapt to updates or modifications in the domain-specific document collection, eliminating the need for complete retraining. Additionally, it addresses the challenge of data scarcity by enabling the generation of instruction datasets from a limited set of initial documents, rendering it suitable for unpopular or specialized domains where comprehensive datasets are scarce. As a case study, we apply this approach to the domain of psychiatry, a field requiring specialized knowledge and sensitive handling of patient information. The resulting fine-tuned LLM demonstrates showcases the viability of the proposed approach and underscores its potential for widespread adoption across various industries and domains where tailored, accurate, and contextually relevant language models are indispensable.

[Arxiv](https://arxiv.org/abs/2408.05911)