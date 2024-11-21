# SpecTool：一个用于刻画工具使用型大语言模型错误的基准

发布时间：2024年11月20日

`LLM应用` `人工智能` `语言模型`

> SpecTool: A Benchmark for Characterizing Errors in Tool-Use LLMs

# 摘要

> 评估大型语言模型（LLMs）的输出是构建高性能复合人工智能系统的关键要点之一。因为 LLMs 的输出会传导至下游步骤，所以识别 LLM 错误对系统性能极为重要。在人工智能系统中，LLMs 的常见任务之一是工具运用。虽然有若干用于评估此任务中 LLMs 的基准环境，但它们往往只给出成功率，却未对失败案例加以任何阐释。为化解这一难题，我们推出了 SpecTool，这是一个用于识别工具使用任务中 LLM 输出错误模式的新基准。我们的基准数据集涵盖来自不同环境的查询，能够用于检测七种新定义的错误模式是否存在。通过使用 SPECTOOL，我们发现即便是最出色的 LLMs 在其输出中也会呈现这些错误模式。研究人员能够借助 SPECTOOL 的分析和见解来引导他们的错误缓解策略。

> Evaluating the output of Large Language Models (LLMs) is one of the most critical aspects of building a performant compound AI system. Since the output from LLMs propagate to downstream steps, identifying LLM errors is crucial to system performance. A common task for LLMs in AI systems is tool use. While there are several benchmark environments for evaluating LLMs on this task, they typically only give a success rate without any explanation of the failure cases. To solve this problem, we introduce SpecTool, a new benchmark to identify error patterns in LLM output on tool-use tasks. Our benchmark data set comprises of queries from diverse environments that can be used to test for the presence of seven newly characterized error patterns. Using SPECTOOL , we show that even the most prominent LLMs exhibit these error patterns in their outputs. Researchers can use the analysis and insights from SPECTOOL to guide their error mitigation strategies.

[Arxiv](https://arxiv.org/abs/2411.13547)