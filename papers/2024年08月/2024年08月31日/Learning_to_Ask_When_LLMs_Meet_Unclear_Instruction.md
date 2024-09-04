# 学习提问：LLM 面对模糊指令的挑战

发布时间：2024年08月31日

`LLM应用` `人工智能` `软件开发`

> Learning to Ask: When LLMs Meet Unclear Instruction

# 摘要

> 现代大型语言模型 (LLM) 能通过调用外部工具解决仅凭语言技能难以完成的任务。然而，这些工具的有效使用不仅依赖于 LLM 的高级能力，还严重依赖于精确的用户指令，这在现实世界中往往难以保证。为此，我们深入分析了用户提供的真实指令，识别了错误模式，并创建了一个名为 Noisy ToolBench 的工具使用基准。我们发现，由于训练目标为下一个标记预测，LLM 可能会随意填补缺失参数，带来幻觉和风险。为解决这一问题，我们提出了 Ask-when-Needed (AwN) 框架，鼓励 LLM 在指令不清晰时主动向用户寻求澄清。同时，为了简化用户与 LLM 的交互并全面评估工具使用性能，我们开发了 ToolEvaluator 自动化评估工具。实验结果显示，AwN 在 NoisyToolBench 中显著超越了现有框架。我们计划公开所有相关代码和数据集，以促进未来研究。

> Equipped with the capability to call functions, modern large language models (LLMs) can leverage external tools for addressing a range of tasks unattainable through language skills alone. However, the effective execution of these tools relies heavily not just on the advanced capabilities of LLMs but also on precise user instructions, which often cannot be ensured in the real world. To evaluate the performance of LLMs tool-use under imperfect instructions, we meticulously examine the real-world instructions queried from users, analyze the error patterns, and build a challenging tool-use benchmark called Noisy ToolBench (NoisyToolBench). We find that due to the next-token prediction training objective, LLMs tend to arbitrarily generate the missed argument, which may lead to hallucinations and risks. To address this issue, we propose a novel framework, Ask-when-Needed (AwN), which prompts LLMs to ask questions to users whenever they encounter obstacles due to unclear instructions. Moreover, to reduce the manual labor involved in user-LLM interaction and assess LLMs performance in tool utilization from both accuracy and efficiency perspectives, we design an automated evaluation tool named ToolEvaluator. Our experiments demonstrate that the AwN significantly outperforms existing frameworks for tool learning in the NoisyToolBench. We will release all related code and datasets to support future research.

[Arxiv](https://arxiv.org/abs/2409.00557)