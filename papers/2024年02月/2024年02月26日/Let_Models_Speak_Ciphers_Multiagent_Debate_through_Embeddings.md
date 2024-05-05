# 让模型解码密语：借助嵌入技术开展多主体辩论。

发布时间：2024年02月26日

`LLM应用` `人工智能` `通信协议`

> Let Models Speak Ciphers: Multiagent Debate through Embeddings

# 摘要

> 大型语言模型（LLMs）的讨论与辩论因其可能提升模型的推理能力而备受关注。自然语言因其语言理解特性成为交流的首选，但生成自然语言时的令牌采样环节可能导致信息丢失，这一环节仅用单一令牌来表达模型对整个词汇库的判断。本文提出了一种名为CIPHER（通过嵌入表示的通信互模型协议）的新型通信机制，旨在解决这一问题。具体而言，我们取消了LLMs的令牌采样环节，允许模型通过原始变换器输出嵌入的期望值来交流其对词汇库的判断。CIPHER通过不依赖自然语言，能够编码更丰富的信息，且无需调整模型权重，便在五项推理任务和多种不同规模的开源LLMs上，比使用自然语言的最先进辩论方法的性能高出0.5-5.0%。这一发现证明了嵌入作为LLMs间通信的替代“语言”的优势和稳定性。我们预期CIPHER将激发对LLM代理系统内部交互设计的新探索，为该领域的未来发展指引新方向。

> Discussion and debate among Large Language Models (LLMs) have gained considerable attention due to their potential to enhance the reasoning ability of LLMs. Although natural language is an obvious choice for communication due to LLM's language understanding capability, the token sampling step needed when generating natural language poses a potential risk of information loss, as it uses only one token to represent the model's belief across the entire vocabulary. In this paper, we introduce a communication regime named CIPHER (Communicative Inter-Model Protocol Through Embedding Representation) to address this issue. Specifically, we remove the token sampling step from LLMs and let them communicate their beliefs across the vocabulary through the expectation of the raw transformer output embeddings. Remarkably, by deviating from natural language, CIPHER offers an advantage of encoding a broader spectrum of information without any modification to the model weights, outperforming the state-of-the-art LLM debate methods using natural language by 0.5-5.0% across five reasoning tasks and multiple open-source LLMs of varying sizes. This showcases the superiority and robustness of embeddings as an alternative "language" for communication among LLMs. We anticipate that CIPHER will inspire further exploration for the design of interactions within LLM agent systems, offering a new direction that could significantly influence future developments in the field.

[Arxiv](https://arxiv.org/abs/2310.06272)