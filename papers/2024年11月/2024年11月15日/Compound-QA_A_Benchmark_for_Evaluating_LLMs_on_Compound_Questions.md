# Compound-QA：评估大型语言模型处理复合问题的基准

发布时间：2024年11月15日

`LLM应用` `问答系统`

> Compound-QA: A Benchmark for Evaluating LLMs on Compound Questions

# 摘要

> 大型语言模型（LLMs）在各类任务中表现抢眼，这促使研究人员开发出多样的评估基准。然而，现有的基准往往只衡量LLMs回答单个问题的能力，而忽视了现实应用中的复杂交互。在本文中，我们引入复合问题合成（CQ-Syn）来创建复合问答基准，聚焦于包含多个子问题的复合问题。该基准源于现有的问答数据集，由专有LLMs进行标注，并经人工验证其准确性。它涵盖了五个类别：事实陈述、因果关系、假设分析、比较选择和评估建议。从理解、推理和知识这三个维度对LLM的能力进行评估。我们通过复合问答对八个开源LLMs的评估发现，它们对复合问题的回答呈现出明显的模式，且明显逊于对非复合问题的回答。此外，我们探究了多种提升LLMs在复合问题上表现的方法。结果显示，这些方法显著增强了模型对复合问题的理解和推理能力。

> Large language models (LLMs) demonstrate remarkable performance across various tasks, prompting researchers to develop diverse evaluation benchmarks. However, existing benchmarks typically measure the ability of LLMs to respond to individual questions, neglecting the complex interactions in real-world applications. In this paper, we introduce Compound Question Synthesis (CQ-Syn) to create the Compound-QA benchmark, focusing on compound questions with multiple sub-questions. This benchmark is derived from existing QA datasets, annotated with proprietary LLMs and verified by humans for accuracy. It encompasses five categories: Factual-Statement, Cause-and-Effect, Hypothetical-Analysis, Comparison-and-Selection, and Evaluation-and-Suggestion. It evaluates the LLM capability in terms of three dimensions including understanding, reasoning, and knowledge. Our assessment of eight open-source LLMs using Compound-QA reveals distinct patterns in their responses to compound questions, which are significantly poorer than those to non-compound questions. Additionally, we investigate various methods to enhance LLMs performance on compound questions. The results indicate that these approaches significantly improve the models' comprehension and reasoning abilities on compound questions.

[Arxiv](https://arxiv.org/abs/2411.10163)