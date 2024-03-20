# 探究大型语言模型在优化 GitHub 工作流程上的效能步骤 1 翻译：关于大型语言模型对 GitHub 工作流程有效性的研究步骤 2 优化：本研究探讨大型语言模型如何有效地赋能 GitHub 工作流程，以提升其性能和效率。

发布时间：2024年03月19日

`LLM应用` `软件开发` `持续集成`

> On the effectiveness of Large Language Models for GitHub Workflows

> GitHub Workflows 是一款广受欢迎的CI工具，让开发者通过编写YAML格式的工作流文件自动完成各类软件开发任务。尽管如此，创建有效且无误的工作流实属不易，且易导致供应链安全隐患。最近，大型语言模型（LLMs）在众多软件开发任务中崭露头角。不过，GitHub Workflows 结构和语义特性区别于普通程序。为此，我们首开先河，针对五个涉及不同层级提示的与工作流相关的任务，深入探究LLMs的有效性。我们精心筛选了近40万个样本工作流，并设计了一系列详略不一的提示内容。此外，我们还专门针对GitHub工作流任务对LLMs进行了优化训练。通过评估三个尖端LLM及其优化变体，我们揭示了当前LLMs在实际应用中的显著效果及潜在局限性。

> GitHub workflows or GitHub CI is a popular continuous integration platform that enables developers to automate various software engineering tasks by specifying them as workflows, i.e., YAML files with a list of jobs. However, engineering valid workflows is tedious. They are also prone to severe security issues, which can result in supply chain vulnerabilities. Recent advancements in Large Language Models (LLMs) have demonstrated their effectiveness in various software development tasks. However, GitHub workflows differ from regular programs in both structure and semantics. We perform the first comprehensive study to understand the effectiveness of LLMs on five workflow-related tasks with different levels of prompts. We curated a set of $\sim$400K workflows and generated prompts with varying detail. We also fine-tuned LLMs on GitHub workflow tasks. Our evaluation of three state-of-the-art LLMs and their fine-tuned variants revealed various interesting findings on the current effectiveness and drawbacks of LLMs.

[Arxiv](https://arxiv.org/abs/2403.12446)