# 大型语言模型的长上下文 RAG 性能

发布时间：2024年11月05日

`RAG` `语言模型` `检索增强生成`

> Long Context RAG Performance of Large Language Models

# 摘要

> 检索增强生成（RAG）已成为通过结合外部信息提高大型语言模型（LLM）准确性的关键技术。随着支持越来越长上下文长度的 LLM 的出现，人们对了解这些模型在 RAG 场景中的表现越来越感兴趣。这些新的长上下文模型能否提高 RAG 性能？本文对 20 个流行的开源和商业 LLM 中增加的上下文长度对 RAG 性能的影响进行了全面研究。我们在三个特定领域的数据集中运行 RAG 工作流，同时将总上下文长度从 2000 个令牌到 128000 个令牌（可能的话为 200 万个令牌）进行变化，并报告了关于 RAG 应用中长上下文的优点和局限性的关键见解。我们的发现表明，虽然检索更多文档可以提高性能，但只有少数最新的最先进的 LLM 在超过 64k 令牌的长上下文中能够保持一致的准确性。我们还确定了长上下文场景中的不同故障模式，为未来的研究指明了方向。

> Retrieval Augmented Generation (RAG) has emerged as a crucial technique for enhancing the accuracy of Large Language Models (LLMs) by incorporating external information. With the advent of LLMs that support increasingly longer context lengths, there is a growing interest in understanding how these models perform in RAG scenarios. Can these new long context models improve RAG performance? This paper presents a comprehensive study of the impact of increased context length on RAG performance across 20 popular open source and commercial LLMs. We ran RAG workflows while varying the total context length from 2,000 to 128,000 tokens (and 2 million tokens when possible) on three domain-specific datasets, and report key insights on the benefits and limitations of long context in RAG applications. Our findings reveal that while retrieving more documents can improve performance, only a handful of the most recent state of the art LLMs can maintain consistent accuracy at long context above 64k tokens. We also identify distinct failure modes in long context scenarios, suggesting areas for future research.

[Arxiv](https://arxiv.org/abs/2411.03538)