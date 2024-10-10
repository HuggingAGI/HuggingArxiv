# 问题树：借助组合性提升结构化问题解决能力

发布时间：2024年10月09日

`LLM应用` `人工智能`

> Tree of Problems: Improving structured problem solving with compositionality

# 摘要

> LLM 通过 in-context learning 在多任务中表现出色。对于需要逐步推理的复杂任务，CoT prompting 结合 self-consistency 效果显著。然而，某些任务对 LLM 仍具挑战。为此，我们提出了 Tree of Problems (ToP)，一个简化版的 ToT，旨在更好地处理可分解为相同子任务的复杂问题。实证结果显示，ToP 不仅超越了 ToT 和 GoT，还在复杂推理任务中优于 CoT。所有代码已公开，详见：https://github.com/ArmelRandy/tree-of-problems。

> Large Language Models (LLMs) have demonstrated remarkable performance across multiple tasks through in-context learning. For complex reasoning tasks that require step-by-step thinking, Chain-of-Thought (CoT) prompting has given impressive results, especially when combined with self-consistency. Nonetheless, some tasks remain particularly difficult for LLMs to solve. Tree of Thoughts (ToT) and Graph of Thoughts (GoT) emerged as alternatives, dividing the complex problem into paths of subproblems. In this paper, we propose Tree of Problems (ToP), a simpler version of ToT, which we hypothesise can work better for complex tasks that can be divided into identical subtasks. Our empirical results show that our approach outperforms ToT and GoT, and in addition performs better than CoT on complex reasoning tasks. All code for this paper is publicly available here: https://github.com/ArmelRandy/tree-of-problems.

[Arxiv](https://arxiv.org/abs/2410.06634)