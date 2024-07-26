# RadioRAG：通过动态检索增强生成技术，提升放射学诊断准确性的事实性大型语言模型。
发布时间：2024年07月22日

`RAG`
> RadioRAG: Factual Large Language Models for Enhanced Diagnostics in Radiology Using Dynamic Retrieval Augmented Generation
>
> 大型语言模型（LLM）在医学AI领域取得了显著进展，但常因静态训练数据集而产生过时或不准确信息。检索增强生成（RAG）通过整合外部数据源缓解了这一问题。我们开发的放射学RAG（RadioRAG）是一个端到端框架，实时从权威放射学在线资源检索数据。通过专门的放射学问答数据集（RadioQA）评估，RadioRAG在回答放射学特定问题时，显著提升了LLM的诊断准确性，相对改进高达54%。特别是在乳腺成像和急诊放射学领域，RadioRAG的表现甚至超过了未使用RAG的模型。然而，不同LLM的改进程度不一，GPT-3.5-turbo和Mixtral-8x7B-instruct-v0.1显著提升，而Mistral-7B-instruct-v0.2则无改进。这表明，当LLM能够访问特定领域数据时，其性能将得到显著提升。对于放射学领域，RadioRAG提供了一个强大的框架，大幅提升了问答的诊断准确性和事实性。
>
> https://arxiv.org/abs/2407.15621


<hr />

- 论文原文: [https://arxiv.org/abs/2407.15621](https://arxiv.org/abs/2407.15621)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1