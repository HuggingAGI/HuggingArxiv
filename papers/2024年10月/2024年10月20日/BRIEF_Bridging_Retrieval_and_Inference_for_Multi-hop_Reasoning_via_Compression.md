# BRIEF：通过压缩技术，巧妙连接检索与推理，助力多跳推理。

发布时间：2024年10月20日

`RAG` `问答系统` `人工智能`

> BRIEF: Bridging Retrieval and Inference for Multi-hop Reasoning via Compression

# 摘要

> 检索增强生成 (RAG) 通过整合外部知识，为大型语言模型 (LLM) 提供了有力补充。然而，随着检索文档数量的增加，输入长度线性增长，导致延迟剧增和长上下文理解能力下降，尤其在多跳问题中更为严重。为此，我们提出了 BRIEF（通过证据融合桥接检索和推理），一种轻量级方法，通过将检索文档压缩成高度密集的文本摘要，实现查询感知的多跳推理，并整合到上下文学习中。我们通过提取源文档中的原始命题表达式，构建合成数据，以实现多跳推理的学习压缩。基于开源模型构建的合成数据，BRIEF 生成的摘要更简洁，使 LLM 在开放域问答 (QA) 中表现卓越。例如，在 HotpotQA 上，BRIEF 将压缩率提高 2 倍，EM 和 F1 分别提升 3.00% 和 4.16%，且生成的摘要比 GPT-3.5 更简洁，QA 性能几乎相同。

> Retrieval-augmented generation (RAG) can supplement large language models (LLMs) by integrating external knowledge. However, as the number of retrieved documents increases, the input length to LLMs grows linearly, causing a dramatic increase in latency and a degradation in long-context understanding. This is particularly serious for multi-hop questions that require a chain of reasoning across documents. To accelerate inference, reduce costs, and minimize distractions, this paper presents BRIEF (Bridging Retrieval and Inference through Evidence Fusion), a lightweight approach that performs query-aware multi-hop reasoning by compressing retrieved documents into highly dense textual summaries to integrate into in-context learning. To enable learning compression for multi-hop reasoning, we curate synthetic data by extracting atomic proposition expressions that encapsulate distinct factoids from the source documents to compose synthetic summaries. Based on our synthetic data built entirely by open-source models, BRIEF generates more concise summaries and enables a range of LLMs to achieve exceptional open-domain question answering (QA) performance. For example, on HotpotQA, BRIEF improves the compression rate by 2 times compared to the state-of-the-art baseline, while outperforming it by 3.00% EM and 4.16% F1 with Flan-UL2 as the reader LM. It also generates more concise summaries than proprietary GPT-3.5, while demonstrating nearly identical QA performance.

[Arxiv](https://arxiv.org/abs/2410.15277)