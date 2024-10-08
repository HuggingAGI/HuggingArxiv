# GARLIC：利用 LLM 引导的动态进度控制和分层加权图，实现长文档问答的优化。

发布时间：2024年10月07日

`RAG` `问答系统`

> GARLIC: LLM-Guided Dynamic Progress Control with Hierarchical Weighted Graph for Long Document QA

# 摘要

> 过去，RAG 方法通过将文本分块来帮助语言模型处理长文档。最新的树形 RAG 方法在保留全局上下文的同时，能够检索详细信息。然而，随着 Llama 3.1 等更强大的 LLM 的出现，我们发现即使是最新的树形 RAG 方法，其表现也不如直接将整个文档输入 Llama 3.1。尽管如此，RAG 方法在降低计算成本方面仍有优势。为此，我们提出了一种名为 GARLIC 的新检索方法，它在保留 RAG 方法计算效率的同时，超越了包括 Llama 3.1 在内的所有现有方法。GARLIC 的创新点包括：(1) 构建了一个多对多摘要的层次加权有向无环图，而非传统的树结构；(2) 利用 LLM 的注意力权重进行检索，而非传统的密集嵌入相似性；(3) 通过 LLM 动态控制检索过程，根据不同查询调整信息量和深度。实验证明，GARLIC 在多个 QA 数据集上均优于现有方法，且计算复杂度与传统 RAG 方法相当。

> In the past, Retrieval-Augmented Generation (RAG) methods split text into chunks to enable language models to handle long documents. Recent tree-based RAG methods are able to retrieve detailed information while preserving global context. However, with the advent of more powerful LLMs, such as Llama 3.1, which offer better comprehension and support for longer inputs, we found that even recent tree-based RAG methods perform worse than directly feeding the entire document into Llama 3.1, although RAG methods still hold an advantage in reducing computational costs. In this paper, we propose a new retrieval method, called LLM-Guided Dynamic Progress Control with Hierarchical Weighted Graph (GARLIC), which outperforms previous state-of-the-art baselines, including Llama 3.1, while retaining the computational efficiency of RAG methods. Our method introduces several improvements: (1) Rather than using a tree structure, we construct a Hierarchical Weighted Directed Acyclic Graph with many-to-many summarization, where the graph edges are derived from attention mechanisms, and each node focuses on a single event or very few events. (2) We introduce a novel retrieval method that leverages the attention weights of LLMs rather than dense embedding similarity. Our method allows for searching the graph along multiple paths and can terminate at any depth. (3) We use the LLM to control the retrieval process, enabling it to dynamically adjust the amount and depth of information retrieved for different queries. Experimental results show that our method outperforms previous state-of-the-art baselines, including Llama 3.1, on two single-document and two multi-document QA datasets, while maintaining similar computational complexity to traditional RAG methods.

[Arxiv](https://arxiv.org/abs/2410.04790)