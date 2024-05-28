# 利用大型语言模型进行语义校正的语义重要性感知通信

发布时间：2024年05月24日

`Agent

理由：这篇论文主要探讨了语义通信的新方法，特别是在代理与人类及代理间的交互中如何理解和传达语义内容。通过使用图像标题神经网络（ICNN）和预训练的大型语言模型（LLM），论文提出了一种新的通信框架，即语义重要性感知通信（SIAC），这涉及到代理（Agent）如何处理和优化语义信息的传输和理解。因此，这篇论文更符合Agent分类，因为它关注的是代理如何与人类或其他代理进行有效的语义交互。` `人工智能`

> Semantic Importance-Aware Communications with Semantic Correction Using Large Language Models

# 摘要

> 语义通信，作为一种新兴的代理与人类及代理间交互方式，虽在特征层面运作，却未能真正触及语义理解的核心。本文深入探讨了理解层面的语义通信（ULSC），旨在将视觉信息转化为人类可理解的语义内容。通过图像标题神经网络（ICNN），我们从视觉数据中提炼出语义表达，并以自然语言描述呈现。这些描述经过预训练的大型语言模型（LLM）的精炼，实现了重要性量化与语义错误的修正。在此基础上，语义重要性感知通信（SIAC）应运而生，它力求在遵守传输延迟的前提下，最大限度地减少语义损失，其策略包括自适应调制与编码。接收端则采用LLM进行语义错误的校正。若需重现视觉数据，预训练的生成AI模型将依据修正后的描述进行数据再生。我们通过比较传输与恢复内容间的语义相似度，证明了ULSC在传达语义理解上的卓越性能，相较于特征级别的语义通信（FLSC）。ULSC将视觉数据转化为自然语言，不仅促进了认知任务的多样性，还利用了人类知识库。同时，此方法在保护隐私方面亦有显著提升，因为原始数据及其特征均未直接传输。

> Semantic communications, a promising approach for agent-human and agent-agent interactions, typically operate at a feature level, lacking true semantic understanding. This paper explores understanding-level semantic communications (ULSC), transforming visual data into human-intelligible semantic content. We employ an image caption neural network (ICNN) to derive semantic representations from visual data, expressed as natural language descriptions. These are further refined using a pre-trained large language model (LLM) for importance quantification and semantic error correction. The subsequent semantic importance-aware communications (SIAC) aim to minimize semantic loss while respecting transmission delay constraints, exemplified through adaptive modulation and coding strategies. At the receiving end, LLM-based semantic error correction is utilized. If visual data recreation is desired, a pre-trained generative artificial intelligence (AI) model can regenerate it using the corrected descriptions. We assess semantic similarities between transmitted and recovered content, demonstrating ULSC's superior ability to convey semantic understanding compared to feature-level semantic communications (FLSC). ULSC's conversion of visual data to natural language facilitates various cognitive tasks, leveraging human knowledge bases. Additionally, this method enhances privacy, as neither original data nor features are directly transmitted.

[Arxiv](https://arxiv.org/abs/2405.16011)