# BordIRlines：一款专为跨语言检索增强生成评估而设计的数据集

发布时间：2024年10月01日

`RAG` `地缘政治` `人工智能`

> BordIRlines: A Dataset for Evaluating Cross-lingual Retrieval-Augmented Generation

# 摘要

> 大型语言模型擅长创意生成，但在幻觉和偏见问题上仍显不足。检索增强生成 (RAG) 虽能确保 LLM 响应基于最新信息，但仍未解决偏见问题：如何选择信息来源？如何权衡其重要性？本文探讨了跨语言 RAG 的挑战，并创建了一个数据集，用于测试现有系统在处理地缘政治争端查询时的鲁棒性。该数据集源自维基百科，涵盖了语言、文化和政治边界的交汇点。我们分析了额外上下文及其语言和来源构成对 LLM 响应的影响。结果表明，现有 RAG 系统在跨语言应用中仍显不足，且在处理多语言信息时缺乏一致性。通过案例研究，我们揭示了这些问题，并提出了未来研究的方向。数据集和代码已公开，详见 https://github.com/manestay/bordIRlines。

> Large language models excel at creative generation but continue to struggle with the issues of hallucination and bias. While retrieval-augmented generation (RAG) provides a framework for grounding LLMs' responses in accurate and up-to-date information, it still raises the question of bias: which sources should be selected for inclusion in the context? And how should their importance be weighted? In this paper, we study the challenge of cross-lingual RAG and present a dataset to investigate the robustness of existing systems at answering queries about geopolitical disputes, which exist at the intersection of linguistic, cultural, and political boundaries. Our dataset is sourced from Wikipedia pages containing information relevant to the given queries and we investigate the impact of including additional context, as well as the composition of this context in terms of language and source, on an LLM's response. Our results show that existing RAG systems continue to be challenged by cross-lingual use cases and suffer from a lack of consistency when they are provided with competing information in multiple languages. We present case studies to illustrate these issues and outline steps for future research to address these challenges. We make our dataset and code publicly available at https://github.com/manestay/bordIRlines.

[Arxiv](https://arxiv.org/abs/2410.01171)