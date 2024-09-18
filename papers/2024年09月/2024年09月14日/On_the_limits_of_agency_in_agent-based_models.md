# 探讨基于代理模型中代理的局限性

发布时间：2024年09月14日

`Agent` `公共健康` `政策制定`

> On the limits of agency in agent-based models

# 摘要

> 基于代理的建模 (ABM) 通过模拟代理在环境中的互动来解析复杂系统。其实用性在于捕捉真实环境动态和代理的适应性行为，同时高效模拟大规模人口。近期，大型语言模型 (LLM) 的进步为增强 ABM 提供了新机遇，通过将 LLM 作为代理，进一步捕捉其适应性。然而，LLM 在处理大规模人口时的计算难题限制了其应用。为此，我们推出了 AgentTorch 框架，该框架能将 ABM 扩展至百万级代理，并利用 LLM 捕捉精细的代理行为。我们通过 COVID-19 大流行案例，展示了 AgentTorch 如何模拟纽约市的 840 万人口，分析隔离和就业行为对健康和经济的影响。此外，我们还比较了不同代理架构在预测疾病和失业率方面的表现，并展示了 AgentTorch 在政策设计中的多维度分析能力。AgentTorch 是一个开源项目，正被全球用于政策制定和科学研究。项目地址：github.com/AgentTorch/AgentTorch。

> Agent-based modeling (ABM) seeks to understand the behavior of complex systems by simulating a collection of agents that act and interact within an environment. Their practical utility requires capturing realistic environment dynamics and adaptive agent behavior while efficiently simulating million-size populations. Recent advancements in large language models (LLMs) present an opportunity to enhance ABMs by using LLMs as agents with further potential to capture adaptive behavior. However, the computational infeasibility of using LLMs for large populations has hindered their widespread adoption. In this paper, we introduce AgentTorch -- a framework that scales ABMs to millions of agents while capturing high-resolution agent behavior using LLMs. We benchmark the utility of LLMs as ABM agents, exploring the trade-off between simulation scale and individual agency. Using the COVID-19 pandemic as a case study, we demonstrate how AgentTorch can simulate 8.4 million agents representing New York City, capturing the impact of isolation and employment behavior on health and economic outcomes. We compare the performance of different agent architectures based on heuristic and LLM agents in predicting disease waves and unemployment rates. Furthermore, we showcase AgentTorch's capabilities for retrospective, counterfactual, and prospective analyses, highlighting how adaptive agent behavior can help overcome the limitations of historical data in policy design. AgentTorch is an open-source project actively being used for policy-making and scientific discovery around the world. The framework is available here: github.com/AgentTorch/AgentTorch.

[Arxiv](https://arxiv.org/abs/2409.10568)