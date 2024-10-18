# 借助内循环查询机制，提升 LLM 在长上下文中的表现

发布时间：2024年10月11日

`RAG` `人工智能`

> Enhancing Long Context Performance in LLMs Through Inner Loop Query Mechanism

# 摘要

> Transformer 的计算复杂度与输入大小呈二次方关系，限制了 LLM 的输入上下文窗口大小。而基于 RAG 的模型通过检索系统过滤不必要信息，能更好地处理长上下文。然而，大多数 RAG 方法仅基于初始查询进行检索，难以应对复杂问题。我们提出了一种新方法——内循环记忆增强树检索 (ILM-TR)，不仅基于查询问题，还基于中间发现进行内循环查询。在推理时，模型从 RAG 系统中检索信息，整合长文档数据。LLM 根据检索信息生成文本，存储在短期记忆 (STM) 中，用于制定下一个查询。此过程重复，直到 STM 中的文本收敛。实验表明，使用 STM 进行检索显著提升了传统 RAG 模型的性能，特别是在 M-NIAH 和 BABILong 等长上下文测试中。

> Transformers have a quadratic scaling of computational complexity with input size, which limits the input context window size of large language models (LLMs) in both training and inference. Meanwhile, retrieval-augmented generation (RAG) besed models can better handle longer contexts by using a retrieval system to filter out unnecessary information. However, most RAG methods only perform retrieval based on the initial query, which may not work well with complex questions that require deeper reasoning. We introduce a novel approach, Inner Loop Memory Augmented Tree Retrieval (ILM-TR), involving inner-loop queries, based not only on the query question itself but also on intermediate findings. At inference time, our model retrieves information from the RAG system, integrating data from lengthy documents at various levels of abstraction. Based on the information retrieved, the LLM generates texts stored in an area named Short-Term Memory (STM) which is then used to formulate the next query. This retrieval process is repeated until the text in STM converged. Our experiments demonstrate that retrieval with STM offers improvements over traditional retrieval-augmented LLMs, particularly in long context tests such as Multi-Needle In A Haystack (M-NIAH) and BABILong.

[Arxiv](https://arxiv.org/abs/2410.12859)