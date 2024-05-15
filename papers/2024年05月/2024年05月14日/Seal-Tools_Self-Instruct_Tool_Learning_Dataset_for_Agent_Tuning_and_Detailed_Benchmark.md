# 海豹工具集：专为智能体自适应调优与精准基准测试而设计的自指导工具学习数据集

发布时间：2024年05月14日

`Agent

理由：这篇论文介绍了一个名为Seal-Tools的新颖工具学习数据集，它包含了自指导API风格的工具集合，并展示了这些工具在实际中的应用案例。这个数据集旨在评估大型语言模型（LLMs）的工具调用能力，特别是在需要协同多个工具或嵌套调用以完成复杂任务的情况。这表明Seal-Tools是用于训练和评估智能代理（Agent）如何有效地使用工具来执行任务的资源。因此，它与Agent的分类相关，而不是RAG（检索增强生成）、LLM应用或LLM理论。` `工具学习`

> Seal-Tools: Self-Instruct Tool Learning Dataset for Agent Tuning and Detailed Benchmark

# 摘要

> 本文推出Seal-Tools，一个新颖的工具学习数据集，内含自指导API风格的工具集合。Seal-Tools不仅汇聚众多工具，更展示了这些工具在实际中的应用案例。我们采用自指导方法，确保在生成大量数据的同时保持可靠性，精确掌控生成过程。Seal-Tools中还包含挑战性实例，需协同多个工具，甚至嵌套调用，以完成复杂任务。为全面评估，我们采用严格格式规范，并设计了三个多维度的评估指标。Seal-Tools因此成为评估大型语言模型工具调用能力的新标杆。我们对多个主流LLMs及我们微调的模型进行了测试，揭示了现有系统的不足。所有代码、数据及实验结果均公开于https://github.com/fairyshine/Seal-Tools。

> This paper presents a new tool learning dataset Seal-Tools, which contains self-instruct API-like tools. Seal-Tools not only offers a large number of tools, but also includes instances which demonstrate the practical application of tools. Seeking to generate data on a large scale while ensuring reliability, we propose a self-instruct method to generate tools and instances, allowing precise control over the process. Moreover, our Seal-Tools contains hard instances that call multiple tools to complete the job, among which some are nested tool callings. For precise and comprehensive evaluation, we use strict format control and design three metrics from different dimensions. Therefore, Seal-Tools can serve as a new benchmark to evaluate the tool-calling ability of LLMs. Finally, we evaluate several prevalent LLMs and our finetuned model on Seal-Tools. The results show that current systems are far from perfect. The code, data and experiment results are available at https://github.com/fairyshine/Seal-Tools .

[Arxiv](https://arxiv.org/abs/2405.08355)