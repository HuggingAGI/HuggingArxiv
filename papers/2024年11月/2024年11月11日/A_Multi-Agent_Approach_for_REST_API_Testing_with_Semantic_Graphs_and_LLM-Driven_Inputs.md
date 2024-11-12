# 一种使用语义图和 LLM 驱动输入的用于 REST API 测试的多智能体方法

发布时间：2024年11月11日

`Agent` `网络服务` `软件测试`

> A Multi-Agent Approach for REST API Testing with Semantic Graphs and LLM-Driven Inputs

# 摘要

> 随着现代网络服务越来越依赖 REST API，对它们进行全面测试变得至关重要。此外，诸如 OpenAPI 规范之类的 REST API 规范的出现导致了许多黑盒 REST API 测试工具的出现。然而，这些工具通常孤立地关注单个测试元素（例如，API、参数、值），导致覆盖率较低，在检测故障（即 500 响应代码）方面效果较差。为了解决这些限制，我们提出了 AutoRestTest，这是第一个采用依赖嵌入多代理方法进行 REST API 测试的黑盒框架，将多代理强化学习（MARL）与语义属性依赖图（SPDG）和大型语言模型（LLM）相结合。我们的方法将 REST API 测试视为一个可分离的问题，其中四个代理——API、依赖项、参数和值——协作以优化 API 探索。LLM 处理特定领域的值限制，SPDG 模型使用 API 操作之间的相似性得分简化依赖项的搜索空间，MARL 动态优化代理的行为。在 12 个真实世界的 REST 服务上进行评估，AutoRestTest 在代码覆盖率、操作覆盖率和故障检测方面优于四个领先的黑盒 REST API 测试工具，包括那些由 RESTGPT 辅助的工具（使用 LLM 增强实际测试输入）。值得注意的是，AutoRestTest 是唯一能够识别 Spotify 内部服务器错误的工具。我们的消融研究强调了代理学习、SPDG 和 LLM 组件的重要贡献。

> As modern web services increasingly rely on REST APIs, their thorough testing has become crucial. Furthermore, the advent of REST API specifications such as the OpenAPI Specification has led to the emergence of many black-box REST API testing tools. However, these tools often focus on individual test elements in isolation (e.g., APIs, parameters, values), resulting in lower coverage and less effectiveness in detecting faults (i.e., 500 response codes). To address these limitations, we present AutoRestTest, the first black-box framework to adopt a dependency-embedded multi-agent approach for REST API testing, integrating Multi-Agent Reinforcement Learning (MARL) with a Semantic Property Dependency Graph (SPDG) and Large Language Models (LLMs). Our approach treats REST API testing as a separable problem, where four agents -- API, dependency, parameter, and value -- collaborate to optimize API exploration. LLMs handle domain-specific value restrictions, the SPDG model simplifies the search space for dependencies using a similarity score between API operations, and MARL dynamically optimizes the agents' behavior. Evaluated on 12 real-world REST services, AutoRestTest outperforms the four leading black-box REST API testing tools, including those assisted by RESTGPT (which augments realistic test inputs using LLMs), in terms of code coverage, operation coverage, and fault detection. Notably, AutoRestTest is the only tool able to identify an internal server error in Spotify. Our ablation study underscores the significant contributions of the agent learning, SPDG, and LLM components.

[Arxiv](https://arxiv.org/abs/2411.07098)