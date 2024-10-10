# ACPBench：探索行动、变化与规划的推理平台

发布时间：2024年10月07日

`LLM应用` `人工智能`

> ACPBench: Reasoning about Action, Change, and Planning

# 摘要

> 随着 LLM 在规划和多步骤推理领域的应用日益广泛，评估其核心规划技能变得至关重要。为此，我们推出了 ACPBench，一个专注于规划领域推理任务的基准。该基准涵盖 13 个规划领域的 7 项推理任务，所有任务均基于形式语言描述的规划领域构建，确保了问题解决方案的正确性，并能自动生成大量问题。我们对 22 个开源及前沿 LLM 的评估显示，其推理能力存在显著差距，即使是顶尖的 GPT-4o，平均准确率也可能低至 52.50%。ACPBench 现已开放，网址为 https://ibm.github.io/ACPBench。

> There is an increasing body of work using Large Language Models (LLMs) as agents for orchestrating workflows and making decisions in domains that require planning and multi-step reasoning. As a result, it is imperative to evaluate LLMs on core skills required for planning. In this work, we present ACPBench, a benchmark for evaluating the reasoning tasks in the field of planning. The benchmark consists of 7 reasoning tasks over 13 planning domains. The collection is constructed from planning domains described in a formal language. This allows us to synthesize problems with provably correct solutions across many tasks and domains. Further, it allows us the luxury of scale without additional human effort, i.e., many additional problems can be created automatically. Our extensive evaluation of 22 open-sourced and frontier LLMs highlight the significant gap in the reasoning capability of the LLMs. The average accuracy of one of the best-performing frontier LLMs -- GPT-4o on these tasks can fall as low as 52.50% ACPBench collection is available at https://ibm.github.io/ACPBench.

[Arxiv](https://arxiv.org/abs/2410.05669)