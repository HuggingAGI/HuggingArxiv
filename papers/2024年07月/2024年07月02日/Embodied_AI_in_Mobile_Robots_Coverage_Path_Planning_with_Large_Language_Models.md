# 移动机器人中的具身AI：借助大型语言模型实现高效覆盖路径规划

发布时间：2024年07月02日

`Agent` `自动化` `机器人`

> Embodied AI in Mobile Robots: Coverage Path Planning with Large Language Models

# 摘要

> 近年来，大型语言模型（LLM）在数学问题解决方面表现出色，促进了多领域的发展。我们设计了一种移动代理的LLM路径规划框架，专注于高级覆盖路径规划和低级控制。该框架采用多层架构，在路径规划阶段融合提示LLM与移动代理的执行器。为评估LLM性能，我们引入了覆盖加权路径规划指标。实验表明，该框架增强了LLM的空间推理能力，通过利用其自然语言处理能力，显著提升了任务效率和准确性。实验还显示，该框架能增强LLM的二维推理能力，并有效完成全覆盖路径规划。我们测试了三种LLM内核：gpt-4o、gemini-1.5-flash和claude-3.5-sonnet，结果显示claude-3.5在不同场景下的覆盖规划任务中表现更优。

> In recent years, Large Language Models (LLMs) have demonstrated remarkable capabilities in understanding and solving mathematical problems, leading to advancements in various fields. We propose an LLM-embodied path planning framework for mobile agents, focusing on solving high-level coverage path planning issues and low-level control. Our proposed multi-layer architecture uses prompted LLMs in the path planning phase and integrates them with the mobile agents' low-level actuators. To evaluate the performance of various LLMs, we propose a coverage-weighted path planning metric to assess the performance of the embodied models. Our experiments show that the proposed framework improves LLMs' spatial inference abilities. We demonstrate that the proposed multi-layer framework significantly enhances the efficiency and accuracy of these tasks by leveraging the natural language understanding and generative capabilities of LLMs. Our experiments show that this framework can improve LLMs' 2D plane reasoning abilities and complete coverage path planning tasks. We also tested three LLM kernels: gpt-4o, gemini-1.5-flash, and claude-3.5-sonnet. The experimental results show that claude-3.5 can complete the coverage planning task in different scenarios, and its indicators are better than those of the other models.

[Arxiv](https://arxiv.org/abs/2407.02220)