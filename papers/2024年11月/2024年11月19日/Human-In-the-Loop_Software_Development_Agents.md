# 人类参与其中的软件开发代理

发布时间：2024年11月19日

`Agent` `软件开发` `软件工程`

> Human-In-the-Loop Software Development Agents

# 摘要

> 近来，基于大型语言模型（LLMs）的软件工程多智能体范式得以推出，用于自动处理软件开发任务（比如从给定问题生成源代码）。然而，现有的相关工作是依据历史基准数据集进行评估的，在自动化软件开发流程的各个阶段均未考虑人类反馈，也尚未在实际中投入使用。在本文中，我们为软件开发引入了一个基于人类在环的 LLM 智能体框架（HULA），它能让软件工程师在为给定任务生成编码计划和源代码时对 LLM 进行优化和引导。我们设计、实现了 HULA 框架，并将其部署到 Atlassian JIRA 中供内部使用。经过对 HULA 框架的多阶段评估，Atlassian 软件工程师发现 HULA 能够最大程度减少总体开发时间和工作量，尤其在启动编码计划和为简单任务编写代码方面。另一方面，某些情况下出现了有关代码质量的挑战有待解决。我们总结经验、探讨未来工作的机遇，这将为基于 LLM 的智能体在软件开发中的发展铺平道路。

> Recently, Large Language Models (LLMs)-based multi-agent paradigms for software engineering are introduced to automatically resolve software development tasks (e.g., from a given issue to source code). However, existing work is evaluated based on historical benchmark datasets, does not consider human feedback at each stage of the automated software development process, and has not been deployed in practice. In this paper, we introduce a Human-in-the-loop LLM-based Agents framework (HULA) for software development that allows software engineers to refine and guide LLMs when generating coding plans and source code for a given task. We design, implement, and deploy the HULA framework into Atlassian JIRA for internal uses. Through a multi-stage evaluation of the HULA framework, Atlassian software engineers perceive that HULA can minimize the overall development time and effort, especially in initiating a coding plan and writing code for straightforward tasks. On the other hand, challenges around code quality are raised to be solved in some cases. We draw lessons learned and discuss opportunities for future work, which will pave the way for the advancement of LLM-based agents in software development.

[Arxiv](https://arxiv.org/abs/2411.12924)