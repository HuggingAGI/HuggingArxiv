# 实时代理的异步工具使用

发布时间：2024年10月28日

`Agent` `人工智能` `操作系统`

> Asynchronous Tool Usage for Real-Time Agents

# 摘要

> 尽管前沿的大型语言模型（LLMs）是颇具能力的工具使用代理，然而当下的人工智能系统仍以严格的回合制模式运作，对时间的流逝毫无感知。这种同步式设计致使用户查询和工具使用只能依次进行，阻碍了系统的多任务处理，降低了交互性。为突破这一局限，我们引入了能够并行处理和实时使用工具的异步人工智能代理。我们的核心贡献在于一个用于代理执行和提示的事件驱动有限状态机架构，它与自动语音识别和文本转语音相融合。从最初为实时操作系统所开发的理念中获取灵感，此项工作既呈现了一个概念框架，也提供了实用工具，以用于创建能够流畅进行多任务交互的人工智能代理。

> While frontier large language models (LLMs) are capable tool-using agents, current AI systems still operate in a strict turn-based fashion, oblivious to passage of time. This synchronous design forces user queries and tool-use to occur sequentially, preventing the systems from multitasking and reducing interactivity. To address this limitation, we introduce asynchronous AI agents capable of parallel processing and real-time tool-use. Our key contribution is an event-driven finite-state machine architecture for agent execution and prompting, integrated with automatic speech recognition and text-to-speech. Drawing inspiration from the concepts originally developed for real-time operating systems, this work presents both a conceptual framework and practical tools for creating AI agents capable of fluid, multitasking interactions.

[Arxiv](https://arxiv.org/abs/2410.21620)