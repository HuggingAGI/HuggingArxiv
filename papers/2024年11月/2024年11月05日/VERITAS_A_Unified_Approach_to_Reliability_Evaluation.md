# VERITAS：一种可靠性评估的统一方法

发布时间：2024年11月05日

`LLM应用` `语言模型` `事实核查`

> VERITAS: A Unified Approach to Reliability Evaluation

# 摘要

> 大型语言模型（LLMs）常常无法从其上下文中综合信息以生成准确的响应。这使得它们在输出可靠性至关重要的知识密集型环境中不可靠。可靠的大型语言模型的一个关键组成部分是集成一个强大的事实核查系统，该系统能够检测各种格式的幻觉。虽然有几个开放获取的事实核查模型可用，但它们的功能通常仅限于特定任务，例如有根据的问答或蕴含验证，并且在对话环境中效果较差。另一方面，像 GPT-4 和 Claude 这样的封闭访问模型在包括有根据的对话验证在内的不同上下文中提供了更大的灵活性，但受到高成本和延迟的阻碍。在这项工作中，我们引入了 VERITAS，这是一系列幻觉检测模型，旨在在不同的上下文中灵活运行，同时最大限度地减少延迟和成本。VERITAS 在所有主要幻觉检测基准的平均性能方面取得了最先进的结果，与类似规模的模型相比，平均性能提高了 10％，并且在 LLM 作为评判者的设置下接近 GPT4 turbo 的性能。

> Large language models (LLMs) often fail to synthesize information from their context to generate an accurate response. This renders them unreliable in knowledge intensive settings where reliability of the output is key. A critical component for reliable LLMs is the integration of a robust fact-checking system that can detect hallucinations across various formats. While several open-access fact-checking models are available, their functionality is often limited to specific tasks, such as grounded question-answering or entailment verification, and they perform less effectively in conversational settings. On the other hand, closed-access models like GPT-4 and Claude offer greater flexibility across different contexts, including grounded dialogue verification, but are hindered by high costs and latency. In this work, we introduce VERITAS, a family of hallucination detection models designed to operate flexibly across diverse contexts while minimizing latency and costs. VERITAS achieves state-of-the-art results considering average performance on all major hallucination detection benchmarks, with $10\%$ increase in average performance when compared to similar-sized models and get close to the performance of GPT4 turbo with LLM-as-a-judge setting.

[Arxiv](https://arxiv.org/abs/2411.03300)