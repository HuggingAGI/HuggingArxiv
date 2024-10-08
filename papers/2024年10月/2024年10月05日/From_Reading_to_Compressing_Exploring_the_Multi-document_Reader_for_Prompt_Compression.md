# 从阅读到压缩：探索多文档阅读器在提示压缩中的应用

发布时间：2024年10月05日

`LLM应用` `人工智能`

> From Reading to Compressing: Exploring the Multi-document Reader for Prompt Compression

# 摘要

> 大型语言模型 (LLM) 通过先进提示技术在多任务中表现出色，但提示过长不仅增加计算成本，还可能掩盖关键信息。为此，我们提出了 Reading To Compressing (R2C) 方法，利用 Fusion-in-Decoder (FiD) 架构精准识别提示中的重要信息。R2C 不仅有效捕捉全局上下文，还保持了语义一致性，无需伪标签即可训练压缩器。实验显示，R2C 在保留关键上下文的同时，将 LLM 性能提升了 6%，并使提示长度减少了 80%。

> Large language models (LLMs) have achieved significant performance gains using advanced prompting techniques over various tasks. However, the increasing length of prompts leads to high computational costs and often obscures crucial information. Prompt compression has been proposed to alleviate these issues, but it faces challenges in (i) capturing the global context and (ii) training the compressor effectively. To tackle these challenges, we introduce a novel prompt compression method, namely Reading To Compressing (R2C), utilizing the Fusion-in-Decoder (FiD) architecture to identify the important information in the prompt. Specifically, the cross-attention scores of the FiD are used to discern essential chunks and sentences from the prompt. R2C effectively captures the global context without compromising semantic consistency while detouring the necessity of pseudo-labels for training the compressor. Empirical results show that R2C retains key contexts, enhancing the LLM performance by 6% in out-of-domain evaluations while reducing the prompt length by 80%.

[Arxiv](https://arxiv.org/abs/2410.04139)