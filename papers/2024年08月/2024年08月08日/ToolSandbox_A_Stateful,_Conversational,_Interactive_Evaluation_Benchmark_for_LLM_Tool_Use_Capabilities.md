# ToolSandbox：一个集状态管理、对话交互于一体的评估平台，专为测试 LLM 工具应用能力而设计。

发布时间：2024年08月08日

`LLM应用` `人工智能` `软件开发`

> ToolSandbox: A Stateful, Conversational, Interactive Evaluation Benchmark for LLM Tool Use Capabilities

# 摘要

> 随着大型语言模型（LLM）的最新进展，研究者们越来越关注如何利用工具辅助 LLM 应对现实挑战，这要求对工具使用能力进行全面评估。ToolSandbox 框架不仅涵盖了有状态工具执行和工具间的隐式状态依赖，还通过内置用户模拟器支持在策略对话评估，并采用动态评估策略针对任意轨迹的中间及最终成果进行评估。研究表明，开源与专有模型在性能上存在显著差异，而 ToolSandbox 中定义的复杂任务，如状态依赖、规范化及信息不足，对最先进的 LLM 也构成挑战，为工具使用 LLM 能力研究开辟了新视角。ToolSandbox 评估框架已公开发布于 https://github.com/apple/ToolSandbox。

> Recent large language models (LLMs) advancements sparked a growing research interest in tool assisted LLMs solving real-world challenges, which calls for comprehensive evaluation of tool-use capabilities. While previous works focused on either evaluating over stateless web services (RESTful API), based on a single turn user prompt, or an off-policy dialog trajectory, ToolSandbox includes stateful tool execution, implicit state dependencies between tools, a built-in user simulator supporting on-policy conversational evaluation and a dynamic evaluation strategy for intermediate and final milestones over an arbitrary trajectory. We show that open source and proprietary models have a significant performance gap, and complex tasks like State Dependency, Canonicalization and Insufficient Information defined in ToolSandbox are challenging even the most capable SOTA LLMs, providing brand-new insights into tool-use LLM capabilities. ToolSandbox evaluation framework is released at https://github.com/apple/ToolSandbox

[Arxiv](https://arxiv.org/abs/2408.04682)