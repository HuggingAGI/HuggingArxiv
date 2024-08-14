# 高效代码生成的语言模型评估

发布时间：2024年08月12日

`LLM应用` `软件开发` `性能评估`

> Evaluating Language Models for Efficient Code Generation

# 摘要

> 我们提出了差异性能评估（DPE）框架，旨在精准评估大型语言模型（LLM）的代码生成效率。传统编码基准因依赖简单输入和缺乏有效复合指标而难以提供可靠的效率见解。DPE通过聚焦高效率编程任务和构建有洞察力的复合性能指标来解决这一问题。DPE分两阶段运作：首先，从现有基准中精选高效率任务，并设计计算密集型输入以挑战LLM解决方案的效率；其次，通过性能分析新方案并全局对比不同效率水平的参考方案，确定其效率得分。作为概念验证，我们用DPE打造了EvalPerf基准，包含121个高难度编码任务。全面评估揭示了模型规模、指令调优及提示对效率的影响，例如，规模法则未涵盖代码效率，而指令调优则同时提升正确性与效率。此外，通过验证DPE的有效性，我们证明EvalPerf不仅可靠，且跨平台使用便捷。

> We introduce Differential Performance Evaluation (DPE), a framework designed to reliably evaluate Large Language Models (LLMs) for efficient code generation. Traditional coding benchmarks often fail to provide reliable insights into code efficiency, due to their reliance on simplistic test inputs and the absence of effective compound metrics. DPE addresses these issues by focusing on efficiency-demanding programming tasks and establishing an insightful compound metric for performance evaluation. DPE operates in two phases: To curate efficiency datasets, it selects efficiency-demanding tasks from existing coding benchmarks and generates computationally expensive inputs to stress the efficiency of LLM solutions. To assess the code efficiency, DPE profiles the new solution and compares it globally against a set of reference solutions that exhibit distinct efficiency levels, where the matched level defines its efficiency score. As a proof of concept, we use DPE to create EvalPerf, a benchmark with 121 performance-challenging coding tasks. Our comprehensive evaluation draws interesting findings on the efficiency impact of model sizes, instruction tuning, and prompting. For example, while the scaling law fails to account for code efficiency, general instruction tuning benefits both code correctness and efficiency. We also evaluate the evaluation by examining the effectiveness of DPE, showing that EvalPerf is reliable and convenient to use even across platforms.

[Arxiv](https://arxiv.org/abs/2408.06450)