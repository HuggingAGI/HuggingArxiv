# FoRAG：优化事实性的检索增强生成技术，专为网络增强的长篇问答设计

发布时间：2024年06月19日

`RAG

理由：这篇论文主要关注的是 Retrieval Augmented Generation (RAG) 在长篇问答（LFQA）任务中的应用，特别是在提高答案的事实性和逻辑清晰度方面的研究。论文提出了一种新的生成器和优化方法，并通过实验证明了其在英语和中文基准测试中的优越性。这些内容与 RAG 技术的应用和发展紧密相关，因此归类为RAG。` `问答系统`

> FoRAG: Factuality-optimized Retrieval Augmented Generation for Web-enhanced Long-form Question Answering

# 摘要

> Retrieval Augmented Generation (RAG) 因其利用搜索引擎提升长篇问答（LFQA）质量的能力而在 QA 任务中广受欢迎。尽管有多种开源方法和网络增强的商业系统如 Bing Chat 出现，但生成长篇答案的事实性和逻辑清晰度两大难题仍未解决。本文通过系统研究网络增强的 LFQA 中的答案生成来应对这些挑战。我们首先提出了一种提纲增强的生成器，确保多方面答案生成逻辑清晰，并为此建立了两个数据集。接着，我们开发了一种基于双重细粒度 RLHF 框架的事实性优化方法，该框架在不同粒度级别上进行自动评估和奖励建模。我们的方法不仅包含了传统的细粒度 RLHF 方法，还通过广泛实验证明了其优越性，尤其是在英语和中文基准测试中。特别地，应用我们的方法于 Llama2-7B-chat 后，得到的 FoRAG-L-7B 模型在连贯性、有用性和事实性三个指标上超越了 WebGPT-175B，且参数数量仅为后者的 1/24。我们的数据集和模型已公开，以促进研究的可复现性：https://huggingface.co/forag。

> Retrieval Augmented Generation (RAG) has become prevalent in question-answering (QA) tasks due to its ability of utilizing search engine to enhance the quality of long-form question-answering (LFQA). Despite the emergence of various open source methods and web-enhanced commercial systems such as Bing Chat, two critical problems remain unsolved, i.e., the lack of factuality and clear logic in the generated long-form answers. In this paper, we remedy these issues via a systematic study on answer generation in web-enhanced LFQA. Specifically, we first propose a novel outline-enhanced generator to achieve clear logic in the generation of multifaceted answers and construct two datasets accordingly. Then we propose a factuality optimization method based on a carefully designed doubly fine-grained RLHF framework, which contains automatic evaluation and reward modeling in different levels of granularity. Our generic framework comprises conventional fine-grained RLHF methods as special cases. Extensive experiments verify the superiority of our proposed \textit{Factuality-optimized RAG (FoRAG)} method on both English and Chinese benchmarks. In particular, when applying our method to Llama2-7B-chat, the derived model FoRAG-L-7B outperforms WebGPT-175B in terms of three commonly used metrics (i.e., coherence, helpfulness, and factuality), while the number of parameters is much smaller (only 1/24 of that of WebGPT-175B). Our datasets and models are made publicly available for better reproducibility: https://huggingface.co/forag.

![FoRAG：优化事实性的检索增强生成技术，专为网络增强的长篇问答设计](../../../paper_images/2406.13779/x1.png)

![FoRAG：优化事实性的检索增强生成技术，专为网络增强的长篇问答设计](../../../paper_images/2406.13779/x2.png)

[Arxiv](https://arxiv.org/abs/2406.13779)