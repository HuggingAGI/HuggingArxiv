# 集群检索增强生成（CRAG）技术

发布时间：2024年05月24日

`RAG

这篇论文主要讨论了基于向量数据库的检索增强生成（RAG）方法在大型语言模型（LLMs）应用中的改进。具体来说，它提出了一种名为CRAG的新方法，旨在减少提示令牌的数量，同时保持响应质量。这种方法特别关注于解决RAG方法在处理大量上下文时可能遇到的限制，如超出模型支持的窗口大小或令牌数量过多导致的成本和处理时间增加。因此，这篇论文的内容与RAG方法的改进和优化紧密相关，属于RAG分类。` `信息检索`

> Clustered Retrieved Augmented Generation (CRAG)

# 摘要

> 在实际应用中，为大型语言模型（LLMs）注入外部知识至关重要，这包括实时更新内容、获取专业领域知识以及防止信息失真。基于向量数据库的检索增强生成（RAG）方法因此广受欢迎。然而，尽管RAG方法取得了成功，但在某些情况下，由于检索到的上下文可能超出LLM支持的窗口大小，或者令牌数量过多导致成本和处理时间增加，其实用性受到限制。为此，我们开发了CRAG，一种创新方法，它能在不影响响应质量的前提下，显著减少提示令牌的数量，实验表明，CRAG能将令牌数量减少至少46%，在某些情况下甚至超过90%。与RAG相比，当分析的评论数量增多时，CRAG的令牌数量增长有限，而RAG在处理75条评论时的令牌数量是处理4条评论时的近9倍。

> Providing external knowledge to Large Language Models (LLMs) is a key point for using these models in real-world applications for several reasons, such as incorporating up-to-date content in a real-time manner, providing access to domain-specific knowledge, and contributing to hallucination prevention. The vector database-based Retrieval Augmented Generation (RAG) approach has been widely adopted to this end. Thus, any part of external knowledge can be retrieved and provided to some LLM as the input context. Despite RAG approach's success, it still might be unfeasible for some applications, because the context retrieved can demand a longer context window than the size supported by LLM. Even when the context retrieved fits into the context window size, the number of tokens might be expressive and, consequently, impact costs and processing time, becoming impractical for most applications. To address these, we propose CRAG, a novel approach able to effectively reduce the number of prompting tokens without degrading the quality of the response generated compared to a solution using RAG. Through our experiments, we show that CRAG can reduce the number of tokens by at least 46\%, achieving more than 90\% in some cases, compared to RAG. Moreover, the number of tokens with CRAG does not increase considerably when the number of reviews analyzed is higher, unlike RAG, where the number of tokens is almost 9x higher when there are 75 reviews compared to 4 reviews.

![集群检索增强生成（CRAG）技术](../../../paper_images/2406.00029/x1.png)

[Arxiv](https://arxiv.org/abs/2406.00029)