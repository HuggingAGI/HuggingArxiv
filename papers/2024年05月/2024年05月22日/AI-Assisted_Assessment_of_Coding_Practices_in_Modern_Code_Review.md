# AI助力现代代码审查中的编码实践评估

发布时间：2024年05月22日

`Agent

这篇论文介绍了AutoCommenter系统，它利用大型语言模型自动学习并执行编码规范，支持多种编程语言，并在工业界进行了性能与应用评估。这个系统可以被视为一个智能代理（Agent），因为它能够自动执行任务（即代码审查和执行编码规范），并且对开发者流程产生积极影响。因此，它符合Agent分类的定义。` `软件开发` `代码审查`

> AI-Assisted Assessment of Coding Practices in Modern Code Review

# 摘要

> 现代代码审查涉及同行在代码提交至版本控制系统前对增量代码贡献的审查，关键在于确保代码遵循最佳实践。尽管部分最佳实践可自动验证，但其他则依赖人工审查。本文介绍了AutoCommenter的开发与应用，这是一个利用大型语言模型自动学习并执行编码规范的系统，支持C++、Java、Python和Go四种语言，并在工业界进行了性能与应用评估。结果显示，这种端到端的编码规范执行系统切实可行，且对开发者流程有积极影响。同时，本文也探讨了将该系统推广至大规模开发者群体时遇到的挑战及所得教训。

> Modern code review is a process in which an incremental code contribution made by a code author is reviewed by one or more peers before it is committed to the version control system. An important element of modern code review is verifying that code contributions adhere to best practices. While some of these best practices can be automatically verified, verifying others is commonly left to human reviewers. This paper reports on the development, deployment, and evaluation of AutoCommenter, a system backed by a large language model that automatically learns and enforces coding best practices. We implemented AutoCommenter for four programming languages (C++, Java, Python, and Go) and evaluated its performance and adoption in a large industrial setting. Our evaluation shows that an end-to-end system for learning and enforcing coding best practices is feasible and has a positive impact on the developer workflow. Additionally, this paper reports on the challenges associated with deploying such a system to tens of thousands of developers and the corresponding lessons learned.

[Arxiv](https://arxiv.org/abs/2405.13565)