# GRASP：一款基于网格的基准测试，专为评估常识空间推理能力而设计。

发布时间：2024年07月01日

`Agent` `人工智能`

> GRASP: A Grid-Based Benchmark for Evaluating Commonsense Spatial Reasoning

# 摘要

> 空间推理，这一人类认知的关键能力，不仅应用广泛，而且是常识技能的核心组成部分，它超越了纯粹的语言依赖，要求一定程度的规划以达成可行（而非最优）方案。当前的常识空间推理（CSR）评估往往聚焦于大型语言模型（LLM）对文本空间描述的解读，而非直接检验其针对空间推理挑战所制定的计划。为此，我们创建了名为$\textbf{GRASP}$的大规模基准，涵盖16,000个网格环境，每个环境设定代理解决能量收集问题。这些环境细分为100个实例，每实例基于160种独特网格配置，涉及五类能量分布、两种起始位置、两类障碍布局及三种代理限制。通过GRASP，我们对比了传统方法（如随机游走与贪心搜索）与尖端LLM（如GPT-3.5-Turbo和GPT-4o）的表现。实验揭示，即便是最先进的LLM，在持续提供满意解方面也面临挑战。

> Spatial reasoning, an important faculty of human cognition with many practical applications, is one of the core commonsense skills that is not purely language-based and, for satisfying (as opposed to optimal) solutions, requires some minimum degree of planning. Existing benchmarks of Commonsense Spatial Reasoning (CSR) tend to evaluate how Large Language Models (LLMs) interpret text-based spatial descriptions rather than directly evaluate a plan produced by the LLM in response to a spatial reasoning scenario. In this paper, we construct a large-scale benchmark called $\textbf{GRASP}$, which consists of 16,000 grid-based environments where the agent is tasked with an energy collection problem. These environments include 100 grid instances instantiated using each of the 160 different grid settings, involving five different energy distributions, two modes of agent starting position, and two distinct obstacle configurations, as well as three kinds of agent constraints. Using GRASP, we compare classic baseline approaches, such as random walk and greedy search methods, with advanced LLMs like GPT-3.5-Turbo and GPT-4o. The experimental results indicate that even these advanced LLMs struggle to consistently achieve satisfactory solutions.

[Arxiv](https://arxiv.org/abs/2407.01892)