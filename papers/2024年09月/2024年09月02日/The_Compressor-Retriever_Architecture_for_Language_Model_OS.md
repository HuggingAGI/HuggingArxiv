# 语言模型操作系统采用的压缩器-检索器架构

发布时间：2024年09月02日

`Agent` `信息技术` `操作系统`

> The Compressor-Retriever Architecture for Language Model OS

# 摘要

> 大型语言模型 (LLM) 的最新进展显著提升了其跨模态信息处理能力，使其能够执行多模态数据查询、工具使用、网络交互和长文档处理等多样化任务。这些进步为 LLM 从简单聊天机器人向现实世界交互的通用代理转变奠定了基础。本文探讨了将语言模型作为操作系统 (OS) 核心组件的概念，将其比作处理存储在上下文窗口（类似 RAM）中数据的 CPU。实现这一概念的关键挑战在于终身上下文管理和会话间状态保持，这受限于当前基于会话的交互范式和上下文窗口大小。为此，我们提出了压缩器-检索器这一模型无关架构，专门用于终身上下文管理。与依赖检索增强生成的其他长上下文解决方案不同，我们的方法仅通过基础模型的前向函数实现上下文的压缩与检索，确保了端到端的可微性。初步实验显示了该架构在上下文学习任务中的有效性，为开发完全状态的 LLM OS 迈出了重要一步。项目仓库地址：https://github.com/gblackout/LM-OS

> Recent advancements in large language models (LLMs) have significantly enhanced their capacity to aggregate and process information across multiple modalities, enabling them to perform a wide range of tasks such as multimodal data querying, tool usage, web interactions, and handling long documents. These capabilities pave the way for transforming LLMs from mere chatbots into general-purpose agents capable of interacting with the real world. This paper explores the concept of using a language model as the core component of an operating system (OS), effectively acting as a CPU that processes data stored in a context window, which functions as RAM. A key challenge in realizing such an LM OS is managing the life-long context and ensuring statefulness across sessions, a feature limited by the current session-based interaction paradigm due to context window size limit. To address this, we introduce compressor-retriever, a model-agnostic architecture designed for life-long context management. Unlike other long-context solutions such as retrieval-augmented generation, our approach exclusively uses the base model's forward function to compress and retrieve context, ensuring end-to-end differentiability. Preliminary experiments demonstrate the effectiveness of this architecture in in-context learning tasks, marking a step towards the development of a fully stateful LLM OS. Project repo available at: https://github.com/gblackout/LM-OS

[Arxiv](https://arxiv.org/abs/2409.01495)