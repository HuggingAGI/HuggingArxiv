# 语言模型能否取代程序员？REPOCOD 给出的答案是“尚未能”

发布时间：2024年10月28日

`LLM应用` `软件开发` `代码生成`

> Can Language Models Replace Programmers? REPOCOD Says 'Not Yet'

# 摘要

> 大型语言模型（LLMs）在代码生成领域展现出了惊人的能力，于 HumanEval 和 MBPP 中解决 Python 编码问题的准确率超 90% 的 pass@1。如此之高的准确率引出一个疑问：LLMs 能否替代人类程序员？现有的手工打造、简单或单行的代码生成基准，因与真实的软件开发存在差距，无法解答此问题。为回答该问题，我们推出了 REPOCOD，这一代码生成基准从 11 个热门的真实项目中收集了 980 个问题，其中超 58%的问题需要文件级或库级的上下文信息。另外，相较于现有的基准，REPOCOD 的平均标准解决方案长度最长（331.6 个标记），平均圈复杂度最高（9.00）。在对十个 LLMs 的评估里，没有一个模型在 REPOCOD 上能达到 30%以上的 pass@1，这表明有必要构建更强大的 LLMs 来助力开发者进行真实世界的软件开发。

> Large language models (LLMs) have shown remarkable ability in code generation with more than 90 pass@1 in solving Python coding problems in HumanEval and MBPP. Such high accuracy leads to the question: can LLMs replace human programmers? Existing manual crafted, simple, or single-line code generation benchmarks cannot answer this question due to their gap with real-world software development. To answer this question, we propose REPOCOD, a code generation benchmark with 980 problems collected from 11 popular real-world projects, with more than 58% of them requiring file-level or repository-level context information. In addition, REPOCOD has the longest average canonical solution length (331.6 tokens) and the highest average cyclomatic complexity (9.00) compared to existing benchmarks. In our evaluations on ten LLMs, none of the models can achieve more than 30 pass@1 on REPOCOD, disclosing the necessity of building stronger LLMs that can help developers in real-world software development.

[Arxiv](https://arxiv.org/abs/2410.21647)