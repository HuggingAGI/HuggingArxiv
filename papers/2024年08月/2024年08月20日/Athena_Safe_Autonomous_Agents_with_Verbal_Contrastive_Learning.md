# 雅典娜：通过言语对比学习实现自主安全代理

发布时间：2024年08月20日

`Agent` `人工智能`

> Athena: Safe Autonomous Agents with Verbal Contrastive Learning

# 摘要

> 随着大型语言模型（LLM）能力的不断涌现，它们被赋予了更多自主执行任务和决策的能力。这些自主代理不仅能理解高级指令，还能与环境互动，利用工具执行复杂任务。然而，随着这些能力的增强，确保其安全性和可信度变得尤为重要。为此，我们提出了 Athena 框架，该框架通过口头对比学习，利用历史安全和不安全行为作为上下文示例，引导代理在执行任务时确保安全。同时，框架中的批评机制在每一步都防止代理采取危险行动。为了评估这些代理的安全推理能力，我们创建了一个包含 80 个工具包和 180 个场景的安全评估基准。实验结果显示，口头对比学习和交互级批评机制显著提升了安全率。

> Due to emergent capabilities, large language models (LLMs) have been utilized as language-based agents to perform a variety of tasks and make decisions with an increasing degree of autonomy. These autonomous agents can understand high-level instructions, interact with their environments, and execute complex tasks using a selection of tools available to them. As the capabilities of the agents expand, ensuring their safety and trustworthiness becomes more imperative. In this study, we introduce the Athena framework which leverages the concept of verbal contrastive learning where past safe and unsafe trajectories are used as in-context (contrastive) examples to guide the agent towards safety while fulfilling a given task. The framework also incorporates a critiquing mechanism to guide the agent to prevent risky actions at every step. Furthermore, due to the lack of existing benchmarks on the safety reasoning ability of LLM-based agents, we curate a set of 80 toolkits across 8 categories with 180 scenarios to provide a safety evaluation benchmark. Our experimental evaluation, with both closed- and open-source LLMs, indicates verbal contrastive learning and interaction-level critiquing improve the safety rate significantly.

[Arxiv](https://arxiv.org/abs/2408.11021)