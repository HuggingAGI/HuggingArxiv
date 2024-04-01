# 通过调整策略和采用多分支推理方法，我们可以有效提升低参数大型语言模型的通用性能力。

发布时间：2024年03月28日

`Agent` `智能代理` `任务规划`

> Enhancing the General Agent Capabilities of Low-Parameter LLMs through Tuning and Multi-Branch Reasoning

# 摘要

> 开源的大型语言模型（LLMs）在理解和生成语言方面表现出色，广泛应用于多种任务并取得显著成效。但面对现实世界的复杂问题，其表现却难与ChatGPT和GPT-4等行业巨头相提并论。LLMs作为智能代理，需具备任务规划、长期记忆和运用外部资源的能力，以提升其效能。目前，众多方法被提出以增强LLMs的代理能力，包括创建特定代理数据、微调模型，以及设计能激发LLMs推理能力的提示。我们针对7B和13B模型，对这些策略进行了深入研究。本研究提出了一种全新的方法，利用GPT-4构建适合代理的数据集，并通过监督微调，显著降低了任务中的幻觉现象和格式错误。同时，通过多路径推理和任务分解等技术，有效简化了问题，提升了LLMs作为代理的性能。我们在AgentBench的五项代理任务上进行了测试，成果令人满意。

> Open-source pre-trained Large Language Models (LLMs) exhibit strong language understanding and generation capabilities, making them highly successful in a variety of tasks. However, when used as agents for dealing with complex problems in the real world, their performance is far inferior to large commercial models such as ChatGPT and GPT-4. As intelligent agents, LLMs need to have the capabilities of task planning, long-term memory, and the ability to leverage external tools to achieve satisfactory performance. Various methods have been proposed to enhance the agent capabilities of LLMs. On the one hand, methods involve constructing agent-specific data and fine-tuning the models. On the other hand, some methods focus on designing prompts that effectively activate the reasoning abilities of the LLMs. We explore both strategies on the 7B and 13B models. We propose a comprehensive method for constructing agent-specific data using GPT-4. Through supervised fine-tuning with constructed data, we find that for these models with a relatively small number of parameters, supervised fine-tuning can significantly reduce hallucination outputs and formatting errors in agent tasks. Furthermore, techniques such as multi-path reasoning and task decomposition can effectively decrease problem complexity and enhance the performance of LLMs as agents. We evaluate our method on five agent tasks of AgentBench and achieve satisfactory results.

![通过调整策略和采用多分支推理方法，我们可以有效提升低参数大型语言模型的通用性能力。](../../../paper_images/2403.19962/agent-intro.png)

![通过调整策略和采用多分支推理方法，我们可以有效提升低参数大型语言模型的通用性能力。](../../../paper_images/2403.19962/agent-data-sft-1.png)

![通过调整策略和采用多分支推理方法，我们可以有效提升低参数大型语言模型的通用性能力。](../../../paper_images/2403.19962/agent-taskde.png)

![通过调整策略和采用多分支推理方法，我们可以有效提升低参数大型语言模型的通用性能力。](../../../paper_images/2403.19962/agent-backtracking.png)

![通过调整策略和采用多分支推理方法，我们可以有效提升低参数大型语言模型的通用性能力。](../../../paper_images/2403.19962/agent-analysis.png)

[Arxiv](https://arxiv.org/abs/2403.19962)