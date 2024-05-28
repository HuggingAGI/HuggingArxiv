# 利用大型语言模型进行语义校正的语义重要性感知通信

发布时间：2024年05月24日

`Agent

这篇论文主要探讨了语义通信在代理与人类及代理间交互中的应用，特别是在理解层面的语义通信（ULSC）。它通过使用图像标题神经网络（ICNN）和预训练的大型语言模型（LLM）来处理视觉数据，提取语义表示，并进行语义错误修正。此外，论文还介绍了语义重要性感知通信（SIAC），这是一种旨在最小化语义损失并满足传输延迟要求的通信策略。这些内容主要集中在代理（Agent）如何通过高级语义通信与人类或其他代理进行交互，因此归类为Agent。` `人工智能`

> Semantic Importance-Aware Communications with Semantic Correction Using Large Language Models

# 摘要

> 语义通信，作为一种前景广阔的代理与人类及代理间交互方式，通常仅在特征层面运作，缺乏深层的语义理解。本文深入探讨了理解层面的语义通信（ULSC），旨在将视觉数据转化为人类可理解的语义内容。通过图像标题神经网络（ICNN），我们从视觉数据中提取语义表示，并以自然语言描述呈现。这些描述经过预训练的大型语言模型（LLM）的精细调整，进行重要性量化和语义错误修正。在此基础上，语义重要性感知通信（SIAC）应运而生，它旨在最小化语义损失，同时满足传输延迟的要求，采用自适应调制和编码策略作为例证。接收端则利用LLM进行语义错误修正。若需重现视觉数据，预训练的生成AI模型可根据修正后的描述进行数据再生。我们通过比较传输与恢复内容间的语义相似性，证明了ULSC在传达深层语义理解方面的优越性，相较于特征层面的语义通信（FLSC）。ULSC将视觉数据转化为自然语言，不仅促进了认知任务，还利用了人类知识库。此外，此方法在保护隐私方面亦有显著提升，因为原始数据及其特征并未直接传输。

> Semantic communications, a promising approach for agent-human and agent-agent interactions, typically operate at a feature level, lacking true semantic understanding. This paper explores understanding-level semantic communications (ULSC), transforming visual data into human-intelligible semantic content. We employ an image caption neural network (ICNN) to derive semantic representations from visual data, expressed as natural language descriptions. These are further refined using a pre-trained large language model (LLM) for importance quantification and semantic error correction. The subsequent semantic importance-aware communications (SIAC) aim to minimize semantic loss while respecting transmission delay constraints, exemplified through adaptive modulation and coding strategies. At the receiving end, LLM-based semantic error correction is utilized. If visual data recreation is desired, a pre-trained generative artificial intelligence (AI) model can regenerate it using the corrected descriptions. We assess semantic similarities between transmitted and recovered content, demonstrating ULSC's superior ability to convey semantic understanding compared to feature-level semantic communications (FLSC). ULSC's conversion of visual data to natural language facilitates various cognitive tasks, leveraging human knowledge bases. Additionally, this method enhances privacy, as neither original data nor features are directly transmitted.

[Arxiv](https://arxiv.org/abs/2405.16011)