# 探究大型语言模型在优化GitHub工作流程方面的成效

发布时间：2024年03月19日

`LLM应用` `软件开发` `持续集成`

> On the effectiveness of Large Language Models for GitHub Workflows

# 摘要

> GitHub Workflows作为一款广受欢迎的CI平台，允许开发者借助YAML格式的工作流程文件自动执行各类软件开发任务。然而，设计出既有效又安全的工作流程实属不易，一不小心就可能引入供应链漏洞。近期，大型语言模型（LLMs）在多项软件开发任务中的表现令人瞩目。尽管如此，GitHub工作流程因其独特的结构和语义特性，给LLMs带来了新的挑战。本研究首次系统探究LLMs在处理五项不同难度层级的工作流程相关任务时的有效性。我们精心挑选了约40万个示例工作流程，制作了一系列详略不等的提示，并针对性地对LLMs进行微调训练。通过对三个顶尖LLMs及其微调版本的深入评估，我们发现了关于当前LLMs在该领域所展现的优势与局限的一些有趣结论。

> GitHub workflows or GitHub CI is a popular continuous integration platform that enables developers to automate various software engineering tasks by specifying them as workflows, i.e., YAML files with a list of jobs. However, engineering valid workflows is tedious. They are also prone to severe security issues, which can result in supply chain vulnerabilities. Recent advancements in Large Language Models (LLMs) have demonstrated their effectiveness in various software development tasks. However, GitHub workflows differ from regular programs in both structure and semantics. We perform the first comprehensive study to understand the effectiveness of LLMs on five workflow-related tasks with different levels of prompts. We curated a set of $\sim$400K workflows and generated prompts with varying detail. We also fine-tuned LLMs on GitHub workflow tasks. Our evaluation of three state-of-the-art LLMs and their fine-tuned variants revealed various interesting findings on the current effectiveness and drawbacks of LLMs.

[Arxiv](https://arxiv.org/abs/2403.12446)