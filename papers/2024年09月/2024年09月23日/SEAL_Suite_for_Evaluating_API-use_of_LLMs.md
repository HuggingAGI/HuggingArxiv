# SEAL：一套专为评估大型语言模型（LLM）API 使用情况而设计的工具集

发布时间：2024年09月23日

`LLM应用` `软件开发` `测试评估`

> SEAL: Suite for Evaluating API-use of LLMs

# 摘要

> 大型语言模型 (LLM) 在处理需要实时访问外部 API 的任务时存在局限性。尽管已有 ToolBench 和 APIGen 等基准来评估 LLM 的 API 使用能力，但这些基准通常存在通用性不足、多步推理覆盖有限以及实时 API 波动导致的稳定性问题。为此，我们推出了 SEAL，一个端到端的测试平台，专门用于评估 LLM 在实际 API 使用中的表现。SEAL 不仅标准化了现有基准，还集成了代理系统用于 API 检索和规划测试，并通过 GPT-4 驱动的 API 模拟器解决了实时 API 的不稳定性问题。SEAL 提供了一个全面的评估流程，涵盖 API 检索、调用和最终响应，为在各种实际场景中进行结构化性能比较提供了可靠框架。SEAL 现已公开，并持续更新以支持新的基准。

> Large language models (LLMs) have limitations in handling tasks that require real-time access to external APIs. While several benchmarks like ToolBench and APIGen have been developed to assess LLMs' API-use capabilities, they often suffer from issues such as lack of generalizability, limited multi-step reasoning coverage, and instability due to real-time API fluctuations. In this paper, we introduce SEAL, an end-to-end testbed designed to evaluate LLMs in real-world API usage. SEAL standardizes existing benchmarks, integrates an agent system for testing API retrieval and planning, and addresses the instability of real-time APIs by introducing a GPT-4-powered API simulator with caching for deterministic evaluations. Our testbed provides a comprehensive evaluation pipeline that covers API retrieval, API calls, and final responses, offering a reliable framework for structured performance comparison in diverse real-world scenarios. SEAL is publicly available, with ongoing updates for new benchmarks.

[Arxiv](https://arxiv.org/abs/2409.15523)