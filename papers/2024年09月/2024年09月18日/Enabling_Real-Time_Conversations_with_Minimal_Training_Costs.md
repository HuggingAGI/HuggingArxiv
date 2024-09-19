# 以最低训练成本实现实时对话

发布时间：2024年09月18日

`LLM应用` `人工智能` `通信技术`

> Enabling Real-Time Conversations with Minimal Training Costs

# 摘要

> 大型语言模型（LLM）通过对话交互显著提升了人类效率。然而，传统基于回合制的对话系统在生成响应时无法实现实时互动。为此，研究人员引入了双工模型，能动态适应用户输入，提供实时反馈。但这些方法通常需要大量计算资源。本文提出了一种新型双工解码方法，仅需少量额外训练即可赋予 LLM 双工能力。该方法通过并行解码对话中的查询与响应，实现了高效的通道分割多路复用策略。实验显示，这种方法在极低训练成本下，大幅提升了用户与 AI 交互的自然度和人性化。

> Large language models (LLMs) have demonstrated the ability to improve human efficiency through conversational interactions. Conventional LLM-powered dialogue systems, operating on a turn-based paradigm, preclude real-time interaction during response generation. To address this limitation, researchers have proposed duplex models. These models can dynamically adapt to user input, facilitating real-time interactive feedback. However, these methods typically require substantial computational resources to acquire the ability. To reduce overhead, this paper presents a new duplex decoding approach that enhances LLMs with duplex ability, requiring minimal additional training. Specifically, our method employs parallel decoding of queries and responses in conversations, effectively implementing a channel-division-multiplexing decoding strategy. Experimental results indicate that our proposed method significantly enhances the naturalness and human-likeness of user-AI interactions with minimal training costs.

[Arxiv](https://arxiv.org/abs/2409.11727)