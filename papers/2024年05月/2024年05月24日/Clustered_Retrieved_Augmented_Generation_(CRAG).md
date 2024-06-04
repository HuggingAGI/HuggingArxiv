# 集群检索增强生成（CRAG）技术

发布时间：2024年05月24日

`RAG

这篇论文主要讨论了基于向量数据库的检索增强生成（RAG）方法在处理大型语言模型（LLMs）时的局限性，并提出了一种改进方法CRAG，旨在减少处理大量上下文时的令牌数量，从而提高效率和实用性。因此，这篇论文应归类于RAG，因为它专注于改进和优化RAG方法在LLM应用中的性能。` `机器学习`

> Clustered Retrieved Augmented Generation (CRAG)

# 摘要

> 在实际应用中，为大型语言模型（LLMs）注入外部知识至关重要，这包括实时更新内容、获取专业领域知识及防止信息失真。基于向量数据库的检索增强生成（RAG）方法因此广受青睐。然而，尽管RAG方法成效显著，但在某些场景下仍显不足，因为其检索的上下文可能超出了LLM所能处理的窗口范围。即便上下文适配，庞大的令牌数量也会导致成本和处理时间的增加，使得该方法在多数应用中显得不切实际。为此，我们创新性地提出了CRAG方法，它能在保证响应质量的同时，显著减少提示令牌的数量，实验表明，CRAG能将令牌数量减少至少46%，某些情况下甚至超过90%。与RAG不同，随着分析评论数量的增加，CRAG的令牌数量增长缓慢，而RAG在处理75条评论时，令牌数量是处理4条评论时的近9倍。

> Providing external knowledge to Large Language Models (LLMs) is a key point for using these models in real-world applications for several reasons, such as incorporating up-to-date content in a real-time manner, providing access to domain-specific knowledge, and contributing to hallucination prevention. The vector database-based Retrieval Augmented Generation (RAG) approach has been widely adopted to this end. Thus, any part of external knowledge can be retrieved and provided to some LLM as the input context. Despite RAG approach's success, it still might be unfeasible for some applications, because the context retrieved can demand a longer context window than the size supported by LLM. Even when the context retrieved fits into the context window size, the number of tokens might be expressive and, consequently, impact costs and processing time, becoming impractical for most applications. To address these, we propose CRAG, a novel approach able to effectively reduce the number of prompting tokens without degrading the quality of the response generated compared to a solution using RAG. Through our experiments, we show that CRAG can reduce the number of tokens by at least 46\%, achieving more than 90\% in some cases, compared to RAG. Moreover, the number of tokens with CRAG does not increase considerably when the number of reviews analyzed is higher, unlike RAG, where the number of tokens is almost 9x higher when there are 75 reviews compared to 4 reviews.

![集群检索增强生成（CRAG）技术](../../../paper_images/2406.00029/x1.png)

[Arxiv](https://arxiv.org/abs/2406.00029)