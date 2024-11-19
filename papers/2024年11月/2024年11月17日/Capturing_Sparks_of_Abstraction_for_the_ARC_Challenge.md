# 为 ARC 挑战捕捉抽象的灵光一闪

发布时间：2024年11月17日

`LLM应用` `软件开发` `人工智能`

> Capturing Sparks of Abstraction for the ARC Challenge

# 摘要

> 最近在解决 ARC 挑战问题方面取得了出色的进展。然而，要想将准确率推高到 60%以上，似乎需要新的技术。就连商业大型语言模型（LLMs）在面对许多问题（给出输入和输出网格时）也难以“理解”，这使得通过 LLM 主导的程序搜索来发现解决方案显得有些徒劳。
  在这项工作中，从一个更有力的起点尝试 LLM 的“理解”：为 LLM 提供任务的完整代码解决方案，然后要求其在不同抽象级别解释任务的解决方式。具体而言，为 LLM 提供在 arc-dsl-llm 中实现的代码解决方案（Hodel 的 arc-dsl 的 LLM 可读版本），以获取：（a）带注释的代码；（b）重构为可重用功能块的代码；（c）问题解决步骤；（d）高级问题解决策略。
  我们证明可以从 LLM 输出中提取“抽象的火花”——以一种可用于下游任务的形式，本地 LLMs 有资格角逐 ARC 奖。
  arc-dsl-llm DSL 框架（含重新设计的解决方案）和 Gemini LLM 生成的数据（连同生成代码）均已开源。

> Excellent progress has been made recently in solving ARC Challenge problems. However, it seems that new techniques may be required to push beyond 60% accuracy. Even commercial Large Language Models (LLMs) struggle to 'understand' many of the problems (when given the input and output grids), which makes discovering solutions by LLM-lead program search somewhat futile.
  In this work, LLM 'understanding' is attempted from a stronger starting position : An LLM is given complete solutions to tasks in code, and then asked to explain how the task is being solved at various levels of abstraction. Specifically, the LLM was given code solutions implemented in arc-dsl-llm (an LLM-legible version of Hodel's arc-dsl to obtain: (a) commented code; (b) code refactored into reusable functional chunks; (c) problem solution steps; and (d) high-level problem-solving tactics.
  We demonstrate that 'Sparks of Abstraction' can be extracted from the LLM output - in a form that could be used in downstream tasks with Local LLMs eligible to enter the ARC Prize.
  Both the arc-dsl-llm DSL framework (with the re-engineered solutions) and the Gemini LLM-generated data (along with the generation code) are made Open Source.

[Arxiv](https://arxiv.org/abs/2411.11206)