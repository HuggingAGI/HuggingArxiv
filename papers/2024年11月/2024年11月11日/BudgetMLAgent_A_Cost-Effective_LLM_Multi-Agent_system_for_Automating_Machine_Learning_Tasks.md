# BudgetMLAgent：一个用于实现机器学习任务自动化的高性价比 LLM 多代理系统

发布时间：2024年11月11日

`Agent` `机器学习` `代码生成`

> BudgetMLAgent: A Cost-Effective LLM Multi-Agent system for Automating Machine Learning Tasks

# 摘要

> 大型语言模型（LLMs）在诸如代码片段生成等众多应用中表现出色，然而在为复杂的机器学习（ML）任务生成代码时却常常遭遇困境。现有的基于 LLM 单智能体的系统，其表现因任务复杂程度而有所不同，但它们都单纯依赖像 GPT-4 这类大型且昂贵的模型。我们的研究发现，像 Gemini-Pro、Mixtral 和 CodeLlama 这类无成本和低成本模型，在单智能体环境中的表现远不如 GPT-4。为了开发一种解决 ML 任务的高性价比基于 LLM 的方案，我们提出了一个基于 LLM 多智能体的系统，它借助专家组合，涵盖通过分析、高效检索过往观察结果、LLM 级联以及向专家提问等方式。通过对 MLAgentBench 基准中的 ML 工程任务进行实证分析，我们证实了本系统的有效性。我们使用无成本模型，即 Gemini 作为基础 LLM，并与 GPT-4 级联，同时由专家偶尔处理向专家提问的调用以进行规划。成本降低了 94.2%（从 GPT-4 单智能体系统在所有任务上的平均每次运行成本 0.931 美元降至 0.054 美元），我们的系统能够取得更优的平均成功率 32.95%，而 GPT-4 单智能体系统在 MLAgentBench 的所有任务上的平均成功率仅为 22.72%。

> Large Language Models (LLMs) excel in diverse applications including generation of code snippets, but often struggle with generating code for complex Machine Learning (ML) tasks. Although existing LLM single-agent based systems give varying performance depending on the task complexity, they purely rely on larger and expensive models such as GPT-4. Our investigation reveals that no-cost and low-cost models such as Gemini-Pro, Mixtral and CodeLlama perform far worse than GPT-4 in a single-agent setting. With the motivation of developing a cost-efficient LLM based solution for solving ML tasks, we propose an LLM Multi-Agent based system which leverages combination of experts using profiling, efficient retrieval of past observations, LLM cascades, and ask-the-expert calls. Through empirical analysis on ML engineering tasks in the MLAgentBench benchmark, we demonstrate the effectiveness of our system, using no-cost models, namely Gemini as the base LLM, paired with GPT-4 in cascade and expert to serve occasional ask-the-expert calls for planning. With 94.2\% reduction in the cost (from \$0.931 per run cost averaged over all tasks for GPT-4 single agent system to \$0.054), our system is able to yield better average success rate of 32.95\% as compared to GPT-4 single-agent system yielding 22.72\% success rate averaged over all the tasks of MLAgentBench.

[Arxiv](https://arxiv.org/abs/2411.07464)