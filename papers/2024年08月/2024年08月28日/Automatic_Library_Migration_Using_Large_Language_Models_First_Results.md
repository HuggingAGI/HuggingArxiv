# 大型语言模型助力自动库迁移：初探成果

发布时间：2024年08月28日

`LLM应用` `软件工程` `人工智能`

> Automatic Library Migration Using Large Language Models: First Results

# 摘要

> 尽管 LLMs 问世不久，但已广泛用于代码生成。然而，其在其他软件工程自动化领域的应用尚待探索。本文首次报告了利用 ChatGPT 辅助 API 迁移任务的研究成果，这一任务传统上需要大量人工。我们具体探讨了将客户端应用迁移至新版 SQLAlchemy 的过程，并评估了三种提示策略：零-shot、单-shot 和思维链。结果显示，单-shot 提示效果最佳，其次是思维链。通过单-shot 提示，我们不仅成功迁移了所有列，还升级了代码以利用 SQLAlchemy 新版本的功能，如 Python 的 \texttt{asyncio} 和 \texttt{typing} 模块，且保持了原有代码行为。

> Despite being introduced only a few years ago, Large Language Models (LLMs) are already widely used by developers for code generation. However, their application in automating other Software Engineering activities remains largely unexplored. Thus, in this paper, we report the first results of a study in which we are exploring the use of ChatGPT to support API migration tasks, an important problem that demands manual effort and attention from developers. Specifically, in the paper, we share our initial results involving the use of ChatGPT to migrate a client application to use a newer version of SQLAlchemy, an ORM (Object Relational Mapping) library widely used in Python. We evaluate the use of three types of prompts (Zero-Shot, One-Shot, and Chain Of Thoughts) and show that the best results are achieved by the One-Shot prompt, followed by the Chain Of Thoughts. Particularly, with the One-Shot prompt we were able to successfully migrate all columns of our target application and upgrade its code to use new functionalities enabled by SQLAlchemy's latest version, such as Python's \texttt{asyncio} and \texttt{typing} modules, while preserving the original code behavior.

[Arxiv](https://arxiv.org/abs/2408.16151)