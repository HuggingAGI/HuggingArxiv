# GPT 语义缓存：借由语义嵌入缓存来降低 LLM 的成本与延迟

发布时间：2024年11月07日

`LLM应用` `客户服务`

> GPT Semantic Cache: Reducing LLM Costs and Latency via Semantic Embedding Caching

# 摘要

> 大型语言模型（LLMs），比如 GPT（Radford 等，2019），凭借实现了复杂的自然语言理解与生成，显著推动了人工智能的进步。但频繁调用这些模型的 API 所产生的高额计算和财务成本形成了重大瓶颈，对于像处理重复查询的客户服务聊天机器人这类应用尤其如此。在本文中，我们引入了 GPT 语义缓存，这是一种借助内存存储（Redis）中查询嵌入的语义缓存的方法。通过存储用户查询的嵌入，我们的方法能高效识别语义相似的问题，从而能够检索预生成的响应，无需向 LLM 进行多余的 API 调用。该技术降低了运营成本，缩短了响应时间，提升了 LLM 驱动的应用的效率。

> Large Language Models (LLMs), such as GPT (Radford et al., 2019), have significantly advanced artificial intelligence by enabling sophisticated natural language understanding and generation. However, the high computational and financial costs associated with frequent API calls to these models present a substantial bottleneck, especially for applications like customer service chatbots that handle repetitive queries. In this paper, we introduce GPT Semantic Cache, a method that leverages semantic caching of query embeddings in in-memory storage (Redis). By storing embeddings of user queries, our approach efficiently identifies semantically similar questions, allowing for the retrieval of pre-generated responses without redundant API calls to the LLM. This technique reduces operational costs and improves response times, enhancing the efficiency of LLM-powered applications.

[Arxiv](https://arxiv.org/abs/2411.05276)