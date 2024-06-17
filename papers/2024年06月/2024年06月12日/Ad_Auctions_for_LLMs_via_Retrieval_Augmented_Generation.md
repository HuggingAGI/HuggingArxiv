# 大型语言模型广告拍卖：检索增强生成策略

发布时间：2024年06月12日

`RAG

该论文摘要描述了一种基于检索增强生成（RAG）的拍卖机制，用于在大型语言模型（LLMs）的文本输出中进行广告分配与定价。这种方法通过设计一种分段拍卖机制，根据广告的出价和相关性在不同的话语段中概率性地选择广告，并依据竞争出价进行定价。这种机制旨在最大化对数社会福利，并确保激励兼容的定价规则。因此，该论文属于RAG分类，因为它专注于使用RAG技术来优化广告在LLMs输出中的分配和定价。` `计算广告` `拍卖机制`

> Ad Auctions for LLMs via Retrieval Augmented Generation

# 摘要

> 在计算广告领域，将广告巧妙融入大型语言模型（LLMs）的输出，既支持了服务又不损内容之真。本文创新性地引入了基于检索增强生成（RAG）的拍卖机制，用于LLMs文本输出中的广告分配与定价。我们设计了一种分段拍卖机制，根据广告的出价和相关性，在每个话语段（如段落、章节或全文）中概率性地选择广告，并依据竞争出价定价。此机制不仅最大化了对数社会福利——一种兼顾效率与公平的新福利概念，还明确了激励兼容的定价规则。此外，我们还探讨了每个分段内多广告分配的情况。通过实证评估，我们的方法在多种广告拍卖场景中展现了其可行性与效能，同时揭示了在赋予LLMs更多广告分配灵活性时，指标间的内在权衡。

> In the field of computational advertising, the integration of ads into the outputs of large language models (LLMs) presents an opportunity to support these services without compromising content integrity. This paper introduces novel auction mechanisms for ad allocation and pricing within the textual outputs of LLMs, leveraging retrieval-augmented generation (RAG). We propose a segment auction where an ad is probabilistically retrieved for each discourse segment (paragraph, section, or entire output) according to its bid and relevance, following the RAG framework, and priced according to competing bids. We show that our auction maximizes logarithmic social welfare, a new notion of welfare that balances allocation efficiency and fairness, and we characterize the associated incentive-compatible pricing rule. These results are extended to multi-ad allocation per segment. An empirical evaluation validates the feasibility and effectiveness of our approach over several ad auction scenarios, and exhibits inherent tradeoffs in metrics as we allow the LLM more flexibility to allocate ads.

![大型语言模型广告拍卖：检索增强生成策略](../../../paper_images/2406.09459/x1.png)

[Arxiv](https://arxiv.org/abs/2406.09459)