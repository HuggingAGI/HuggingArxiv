# 利用大型语言模型的交互式且富有表现力的代码增强规划

发布时间：2024年11月20日

`LLM应用`

> Interactive and Expressive Code-Augmented Planning with Large Language Models

# 摘要

> 大型语言模型（LLMs）在常识推理和交互式决策方面能力出众，但在复杂、长期的规划任务中常遇困境。近来的技术尝试运用控制流及其他与代码相关的技术来构建LLM的输出，以提升规划性能。这些技术涵盖使用变量（追踪重要信息）和函数（将复杂任务分解为较小的可复用子任务）。然而，纯代码的方式容易出错，且难以应对模糊或非结构化数据。为解决这些难题，我们提出了REPL-Plan，这是一种LLM规划方法，它不仅具备完整的代码表达能力（能利用代码的所有优势），还具有动态性（能灵活地从错误中适应并在模糊情形下运用LLM）。在REPL-Plan中，LLM通过与读-求值-打印循环（REPL）交互来完成任务，该循环会迭代执行和评估代码，类似于语言外壳或交互式代码笔记本，使模型能够灵活纠错并动态处理任务。我们表明，与以往方法相比，REPL-Plan在各类规划领域均成果斐然。

> Large Language Models (LLMs) demonstrate strong abilities in common-sense reasoning and interactive decision-making, but often struggle with complex, long-horizon planning tasks. Recent techniques have sought to structure LLM outputs using control flow and other code-adjacent techniques to improve planning performance. These techniques include using variables (to track important information) and functions (to divide complex tasks into smaller re-usable sub-tasks). However, purely code-based approaches can be error-prone and insufficient for handling ambiguous or unstructured data. To address these challenges, we propose REPL-Plan, an LLM planning approach that is fully code-expressive (it can utilize all the benefits of code) while also being dynamic (it can flexibly adapt from errors and use the LLM for fuzzy situations). In REPL-Plan, an LLM solves tasks by interacting with a Read-Eval-Print Loop (REPL), which iteratively executes and evaluates code, similar to language shells or interactive code notebooks, allowing the model to flexibly correct errors and handle tasks dynamically. We demonstrate that REPL-Plan achieves strong results across various planning domains compared to previous methods.

[Arxiv](https://arxiv.org/abs/2411.13826)