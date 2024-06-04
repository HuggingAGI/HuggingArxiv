# Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。

发布时间：2024年05月29日

`LLM应用

这篇论文探讨了如何通过在大型语言模型（LLM）的解码过程中同步执行外部工具的部分功能来提高处理效率。具体来说，论文介绍了Conveyor系统，这是一个专门设计来优化涉及外部工具请求处理的系统。通过创新的接口和请求调度器，该系统能够有效地集成和利用外部工具的功能，从而显著减少请求处理时间。这种方法直接应用于LLM的实际操作中，以提高其服务效率，因此属于LLM应用分类。` `人工智能` `云计算`

> Conveyor: Efficient Tool-aware LLM Serving with Tool Partial Execution

# 摘要

> 随着与外部工具（如ChatGPT插件）的集成，大型语言模型（LLM）的服务负载变得更加复杂。本文揭示了一种新策略：在LLM解码过程中同步进行工具的部分执行，以提升处理触发工具请求的效率。为此，我们开发了Conveyor系统，专为优化涉及外部工具的请求处理。通过创新的接口，工具开发者能向LLM服务系统展示部分执行的潜力，并借助请求调度器实现这一过程。实证结果表明，此方法能将请求处理时间缩短高达38.8%。

> The complexity of large language model (LLM) serving workloads has substantially increased due to the integration with external tool invocations, such as ChatGPT plugins. In this paper, we identify a new opportunity for efficient LLM serving for requests that trigger tools: tool partial execution alongside LLM decoding. To this end, we design Conveyor, an efficient LLM serving system optimized for handling requests involving external tools. We introduce a novel interface for tool developers to expose partial execution opportunities to the LLM serving system and a request scheduler that facilitates partial tool execution. Our results demonstrate that tool partial execution can improve request completion latency by up to 38.8%.

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/x1.png)

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/x2.png)

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/x3.png)

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/x4.png)

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/x5.png)

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/x6.png)

![Conveyor：一种高效的大型语言模型服务系统，专为工具感知设计，支持工具的部分执行，以提升服务效率。](../../../paper_images/2406.00059/theoretical2.png)

[Arxiv](https://arxiv.org/abs/2406.00059)