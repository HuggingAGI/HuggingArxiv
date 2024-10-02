# 在 RAG 过程中，通过机械分析量化对外部信息的依赖，超越了对参数化知识的依赖。

发布时间：2024年10月01日

`RAG` `人工智能`

> Quantifying reliance on external information over parametric knowledge during Retrieval Augmented Generation (RAG) using mechanistic analysis

# 摘要

> RAG 在自然语言应用中广泛使用，但语言模型如何利用检索到的上下文仍不明确。本文揭示了 LMs 的“捷径”效应，即强烈依赖检索上下文，几乎不依赖模型先验。我们通过因果中介分析和注意力贡献剔除，证明了参数记忆的低利用率，以及残差流主要从 RAG 上下文而非问题主体标记中获得丰富。这种“捷径”行为在 LLMs 和 SLMs 中普遍存在。

> Retrieval Augmented Generation (RAG) is a widely used approach for leveraging external context in several natural language applications such as question answering and information retrieval. Yet, the exact nature in which a Language Model (LM) leverages this non-parametric memory or retrieved context isn't clearly understood. This paper mechanistically examines the RAG pipeline to highlight that LMs demonstrate a "shortcut'' effect and have a strong bias towards utilizing the retrieved context to answer questions, while relying minimally on model priors. We propose (a) Causal Mediation Analysis; for proving that parametric memory is minimally utilized when answering a question and (b) Attention Contributions and Knockouts for showing the last token residual stream do not get enriched from the subject token in the question, but gets enriched from tokens of RAG-context. We find this pronounced "shortcut'' behaviour to be true across both LLMs (e.g.,LlaMa) and SLMs (e.g., Phi)

[Arxiv](https://arxiv.org/abs/2410.00857)