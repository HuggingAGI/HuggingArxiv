# Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术

发布时间：2024年05月29日

`Agent

这篇论文主要讨论了如何通过在大型语言模型（LLM）的解码过程中同步执行外部工具的部分功能来提高处理效率。这种集成和优化处理请求的方法，特别是通过开发Conveyor系统来实现，更符合Agent的定义，即一个能够自主执行任务并与其他系统或工具交互的实体。因此，将其归类为Agent是合适的。` `云计算` `人工智能`

> Conveyor: Efficient Tool-aware LLM Serving with Tool Partial Execution

# 摘要

> 随着与外部工具（如ChatGPT插件）的集成，大型语言模型（LLM）的服务负载变得更加复杂。本文揭示了一个创新点：在LLM解码过程中同步进行工具的部分执行，以提升处理触发工具请求的效率。为此，我们开发了Conveyor系统，专为优化处理这类请求而设计。我们为工具开发者提供了一个新接口，以便向LLM服务系统展示部分执行的可能性，并配备了一个请求调度器来支持这一过程。实证结果表明，通过工具的部分执行，我们能将请求处理时间缩短高达38.8%。

> The complexity of large language model (LLM) serving workloads has substantially increased due to the integration with external tool invocations, such as ChatGPT plugins. In this paper, we identify a new opportunity for efficient LLM serving for requests that trigger tools: tool partial execution alongside LLM decoding. To this end, we design Conveyor, an efficient LLM serving system optimized for handling requests involving external tools. We introduce a novel interface for tool developers to expose partial execution opportunities to the LLM serving system and a request scheduler that facilitates partial tool execution. Our results demonstrate that tool partial execution can improve request completion latency by up to 38.8%.

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/x1.png)

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/x2.png)

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/x3.png)

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/x4.png)

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/x5.png)

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/x6.png)

![Conveyor：高效工具感知的大型语言模型服务，采用工具部分执行技术](../../../paper_images/2406.00059/theoretical2.png)

[Arxiv](https://arxiv.org/abs/2406.00059)