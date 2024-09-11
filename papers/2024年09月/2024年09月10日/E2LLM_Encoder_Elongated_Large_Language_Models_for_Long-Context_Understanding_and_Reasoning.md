# E2LLM：专为长上下文理解和推理设计的编码器延长型大型语言模型

发布时间：2024年09月10日

`LLM应用` `人工智能`

> E2LLM: Encoder Elongated Large Language Models for Long-Context Understanding and Reasoning

# 摘要

> 在大型语言模型（LLM）领域，处理长上下文的能力对于多轮对话、代码生成和文档摘要等任务至关重要。本文提出了一种名为 E2LLM 的新方法，通过将长上下文分割成块，利用预训练编码器压缩成嵌入向量，并使用适配器与仅解码器的 LLM 对齐，有效解决了“不可能三角”的挑战。实验证明，E2LLM 在长上下文任务中表现优异，同时兼顾了效率、性能和与预训练模型的兼容性。这一创新框架为长文本建模领域带来了显著进步。

> In the realm of Large Language Models (LLMs), the ability to process long contexts is increasingly crucial for tasks such as multi-round dialogues, code generation, and document summarization. This paper addresses the challenges of enhancing the long-context performance, reducing computational complexity, and leveraging pretrained models collectively termed the "impossible triangle." We introduce E2LLM (Encoder Elongated Large Language Models), a novel approach that effectively navigates this paradox. The method involves splitting long contexts into chunks, compressing each into embedding vectors via a pretrained text encoder, and utilizing an adapter to align these representations with a decoder-only LLM. Two training objectives, focusing on reconstruction of the encoder output and long-context instruction fine-tuning, are employed to facilitate the understanding of soft prompts by the LLM. Experimental results demonstrate that E2LLM achieves superior performance in long-context scenarios while balancing efficiency, performance, and compatibility with pretrained models. Our framework thus represents a significant advancement in the field, contributing to effective long-text modeling.

[Arxiv](https://arxiv.org/abs/2409.06679)