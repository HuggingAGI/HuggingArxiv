# TRANSAGENT：一个基于 LLM 的多智能体系统，专为代码翻译而生

发布时间：2024年09月29日

`Agent` `软件开发` `人工智能`

> TRANSAGENT: An LLM-Based Multi-Agent System for Code Translation

# 摘要

> 代码翻译在软件迁移、系统重构和跨平台开发中至关重要，它能在保持功能不变的前提下，将代码从一种编程语言转换为另一种。传统方法依赖手动编写的规则，耗时且代码可读性差。为此，基于学习的方法应运而生，利用并行数据训练模型实现自动翻译。随着大型语言模型 (LLM) 的进步，这一领域得到了进一步推动。然而，LLM 翻译的代码仍存在语法和语义错误，且自我调试困难。为此，我们提出了 TRANSAGENT，一个基于 LLM 的多代理系统，通过四个代理协同工作，修复语法和语义错误，提升代码翻译质量。TRANSAGENT 的核心在于通过执行对齐定位错误代码块，缩小修复范围，降低难度。我们构建了新的基准测试，结果显示 TRANSAGENT 在效果和效率上均优于 UniTrans。此外，评估表明 TRANSAGENT 具有良好的泛化能力，消融研究揭示了各代理的贡献。

> Code translation converts code from one programming language to another while maintaining its original functionality, which is crucial for software migration, system refactoring, and cross-platform development. Traditional rule-based methods rely on manually-written rules, which can be time-consuming and often result in less readable code. To overcome this, learning-based methods have been developed, leveraging parallel data to train models for automated code translation. More recently, the advance of Large Language Models (LLMs) further boosts learning-based code translation. Although promising, LLM-translated program still suffers from diverse quality issues (e.g., syntax errors and semantic errors). In particular, it can be challenging for LLMs to self-debug these errors when simply provided with the corresponding error messages.
  In this work, we propose a novel LLM-based multi-agent system TRANSAGENT, which enhances LLM-based code translation by fixing the syntax errors and semantic errors with the synergy between four LLM-based agents, including Initial Code Translator, Syntax Error Fixer, Code Aligner, and Semantic Error Fixer. The main insight of TRANSAGENT is to first localize the error code block in the target program based on the execution alignment between the target and source program, which can narrow down the fixing space and thus lower down the fixing difficulties. To evaluate TRANSAGENT, we first construct a new benchmark from recent programming tasks to mitigate the potential data leakage issue. On our benchmark, TRANSAGENT outperforms the latest LLM-based code translation technique UniTrans in both translation effectiveness and efficiency; additionally, our evaluation on different LLMs show the generalization of TRANSAGENT and our ablation study shows the contribution of each agent.

[Arxiv](https://arxiv.org/abs/2409.19894)