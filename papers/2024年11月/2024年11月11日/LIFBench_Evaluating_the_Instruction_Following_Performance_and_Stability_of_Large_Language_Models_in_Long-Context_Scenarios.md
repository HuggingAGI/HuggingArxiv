# LIFBench：评估大型语言模型在长上下文场景中的指令跟随性能和稳定性

发布时间：2024年11月11日

`LLM应用` `大型语言模型`

> LIFBench: Evaluating the Instruction Following Performance and Stability of Large Language Models in Long-Context Scenarios

# 摘要

> 随着大型语言模型（LLM）在自然语言处理（NLP）中不断发展，它们在长上下文输入中稳定遵循指令的能力对于实际应用变得至关重要。虽然现有的基准评估了各种 LLM 能力，但它们很少关注长上下文场景中的指令遵循或不同输入的稳定性。作为回应，我们引入了长上下文指令遵循基准（LIFBench），这是一个可扩展的数据集，旨在评估 LLM 在长上下文中的指令遵循能力和稳定性。LIFBench 包括三个长上下文场景和十一个不同的任务，由通过在长度、表达和变量三个维度上的自动扩展方法生成的 2766 条指令支持。为了进行评估，我们提出了 LIFEval，这是一个基于规则的评估框架，无需依赖 LLM 辅助评估或人类判断，即可为复杂的 LLM 响应提供精确、自动的评分。这种方法有助于从各个角度对模型性能和稳定性进行全面分析。我们在六个长度区间的 20 个著名 LLM 上进行了广泛的实验，分析了它们的指令遵循能力和稳定性。我们的工作贡献了 LIFBench 和 LIFEval 作为评估 LLM 在复杂长上下文环境中性能的强大工具，提供了可为未来 LLM 开发提供信息的见解。

> As Large Language Models (LLMs) continue to advance in natural language processing (NLP), their ability to stably follow instructions in long-context inputs has become crucial for real-world applications. While existing benchmarks assess various LLM capabilities, they rarely focus on instruction-following in long-context scenarios or stability on different inputs. In response, we introduce the Long-context Instruction-Following Benchmark (LIFBench), a scalable dataset designed to evaluate LLMs' instruction-following capabilities and stability across long contexts. LIFBench comprises three long-context scenarios and eleven diverse tasks, supported by 2,766 instructions generated through an automated expansion method across three dimensions: length, expression, and variables. For evaluation, we propose LIFEval, a rubric-based assessment framework that provides precise, automated scoring of complex LLM responses without relying on LLM-assisted evaluations or human judgments. This approach facilitates a comprehensive analysis of model performance and stability across various perspectives. We conduct extensive experiments on 20 notable LLMs across six length intervals, analyzing their instruction-following capabilities and stability. Our work contributes LIFBench and LIFEval as robust tools for assessing LLM performance in complex, long-context settings, providing insights that can inform future LLM development.

[Arxiv](https://arxiv.org/abs/2411.07037)