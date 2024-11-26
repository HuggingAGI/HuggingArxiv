# CATP-LLM：助力大型语言模型实现成本感知的工具规划

发布时间：2024年11月25日

`LLM应用` `人工智能` `工具规划`

> CATP-LLM: Empowering Large Language Models for Cost-Aware Tool Planning

# 摘要

> 利用大型语言模型（LLMs）进行工具规划已成为开发通用人工智能系统的一条颇具前景的路径，LLMs 会依据任务描述自动调度外部工具（如视觉模型）来应对复杂任务。要将此模式应用于实际，LLMs 在工具规划时考虑工具执行成本（如执行时间）极为关键。遗憾的是，先前的研究忽视了工具执行成本，致使生成的计划成本过高，超出了任务性能。为弥补这一空缺，我们提出了基于 LLMs 的成本感知工具规划（CATP-LLM）框架，这是首次提供了一个连贯的设计，让 LLMs 能够进行成本感知的工具规划。具体来说，CATP-LLM 融入了一种工具规划语言，增强 LLM 生成多个分支的非顺序计划，以实现高效的并发工具执行和成本降低。此外，还进一步设计了一种成本感知的离线强化学习算法，用于微调 LLM，优化工具规划中的性能与成本权衡。鉴于缺乏公共的成本相关数据集，我们进一步推出了 OpenCATP，这是首个用于成本感知规划评估的平台。在 OpenCATP 上的实验显示，即便以 Llama2-7B 作为其核心，CATP-LLM 也优于 GPT-4，在具有挑战性的规划任务中，平均计划性能提升 28.2%-30.2%，成本降低 24.7%-45.8%。CATP-LLM 和 OpenCATP 的代码将会公开。

> Utilizing large language models (LLMs) for tool planning has emerged as a promising avenue for developing general AI systems, where LLMs automatically schedule external tools (e.g. vision models) to tackle complex tasks based on task descriptions. To push this paradigm toward practical applications, it is crucial for LLMs to consider tool execution costs (e.g. execution time) for tool planning. Unfortunately, prior studies overlook the tool execution costs, leading to the generation of expensive plans of which the costs outweigh task performance. To fill this gap, we propose the Cost-Aware Tool Planning with LLMs (CATP-LLM) framework, which for the first time provides a coherent design to empower LLMs for cost-aware tool planning. Specifically, CATP-LLM incorporates a tool planning language to enhance the LLM to generate non-sequential plans of multiple branches for efficient concurrent tool execution and cost reduction. Moreover, it further designs a cost-aware offline reinforcement learning algorithm to fine-tune the LLM to optimize the performance-cost trade-off in tool planning. In lack of public cost-related datasets, we further present OpenCATP, the first platform for cost-aware planning evaluation. Experiments on OpenCATP show that CATP-LLM outperforms GPT-4 even when using Llama2-7B as its backbone, with the average improvement of 28.2%-30.2% higher plan performance and 24.7%-45.8% lower costs even on the challenging planning tasks. The codes of CATP-LLM and OpenCATP will be publicly available.

[Arxiv](https://arxiv.org/abs/2411.16313)