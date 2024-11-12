# PDC 和 DM-SFT：一条用于增强大型语言模型 SQL 错误修复的道路

发布时间：2024年11月11日

`LLM应用` `软件开发` `代码修复`

> PDC & DM-SFT: A Road for LLM SQL Bug-Fix Enhancing

# 摘要

> 代码大型语言模型（Code LLMs），如 Code llama 和 DeepSeek-Coder，在代码生成任务中表现出色。然而，大多数现有的模型专注于生成正确代码的能力，但在错误修复方面常常遇到困难。我们引入了一套方法来增强 LLM 的 SQL 错误修复能力。这些方法主要由两部分组成：从头开始的渐进式数据集构建（PDC）和动态掩码监督微调（DM-SFT）。PDC 分别从广度优先和深度优先的角度提出了两种数据扩展方法。DM-SFT 引入了一种高效的错误修复监督学习方法，有效地减少了总训练步骤，并减轻了 SQL 代码错误修复训练中的“迷失方向”。在我们的评估中，用这两种方法训练的代码 LLM 模型超过了所有当前性能最佳但规模大得多的模型。

> Code Large Language Models (Code LLMs), such as Code llama and DeepSeek-Coder, have demonstrated exceptional performance in the code generation tasks. However, most existing models focus on the abilities of generating correct code, but often struggle with bug repair. We introduce a suit of methods to enhance LLM's SQL bug-fixing abilities. The methods are mainly consisted of two parts: A Progressive Dataset Construction (PDC) from scratch and Dynamic Mask Supervised Fine-tuning (DM-SFT). PDC proposes two data expansion methods from the perspectives of breadth first and depth first respectively. DM-SFT introduces an efficient bug-fixing supervised learning approach, which effectively reduce the total training steps and mitigate the "disorientation" in SQL code bug-fixing training. In our evaluation, the code LLM models trained with two methods have exceeds all current best performing model which size is much larger.

[Arxiv](https://arxiv.org/abs/2411.06767)