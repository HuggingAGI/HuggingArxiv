# ReDeEP：利用机制可解释性，精准检测检索增强生成中的幻觉现象。

发布时间：2024年10月15日

`RAG` `人工智能`

> ReDeEP: Detecting Hallucination in Retrieval-Augmented Generation via Mechanistic Interpretability

# 摘要

> RAG 模型通过整合外部知识来减少幻觉，但即便检索内容准确，仍可能生成与事实冲突的输出。检测这些幻觉需深入理解 LLM 如何利用内外部知识。现有方法往往未能解开这些交织效应，导致检测困难。我们研究发现，当 LLM 过度依赖内部知识，而忽视外部检索内容时，幻觉便会出现。为此，我们提出 ReDeEP 方法，通过解开 LLM 对内外部知识的利用来精准检测幻觉。实验证明，ReDeEP 显著提升检测准确性。此外，我们还设计了 AARF，通过平衡内外部知识贡献来减少幻觉。

> Retrieval-Augmented Generation (RAG) models are designed to incorporate external knowledge, reducing hallucinations caused by insufficient parametric (internal) knowledge. However, even with accurate and relevant retrieved content, RAG models can still produce hallucinations by generating outputs that conflict with the retrieved information. Detecting such hallucinations requires disentangling how Large Language Models (LLMs) utilize external and parametric knowledge. Current detection methods often focus on one of these mechanisms or without decoupling their intertwined effects, making accurate detection difficult. In this paper, we investigate the internal mechanisms behind hallucinations in RAG scenarios. We discover hallucinations occur when the Knowledge FFNs in LLMs overemphasize parametric knowledge in the residual stream, while Copying Heads fail to effectively retain or integrate external knowledge from retrieved content. Based on these findings, we propose ReDeEP, a novel method that detects hallucinations by decoupling LLM's utilization of external context and parametric knowledge. Our experiments show that ReDeEP significantly improves RAG hallucination detection accuracy. Additionally, we introduce AARF, which mitigates hallucinations by modulating the contributions of Knowledge FFNs and Copying Heads.

[Arxiv](https://arxiv.org/abs/2410.11414)