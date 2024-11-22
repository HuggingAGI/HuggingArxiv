# 一种设计 LLM 代理的评估驱动式方法：流程与架构

发布时间：2024年11月20日

`Agent` `语言模型` `软件开发`

> An Evaluation-Driven Approach to Designing LLM Agents: Process and Architecture

# 摘要

> 大型语言模型（LLMs）的问世，让能够自主达成未明确目标并在部署后持续进化（有时无需代码或模型更新）的 LLM 代理得以开发。传统手段，像预先设定的测试用例以及代码/模型再开发流程，难以应对 LLM 代理开发的独特难题，尤其是在质量和风险控制方面。本文引入了一种受测试驱动开发启发的评估驱动设计方法来攻克这些挑战。借由多声部文献综述（MLR），我们整合了现有的 LLM 评估方法，并提出了专门针对 LLM 代理的全新流程模型和参考架构。所提方法融合了在线和离线评估，以支持自适应运行时调整和系统的离线再开发，通过持续纳入评估结果（包含来自人类和 AI 评估者的细粒度反馈）来优化运行时流程、工件、系统架构和 LLMs。

> The advent of Large Language Models (LLMs) has enabled the development of LLM agents capable of autonomously achieving under-specified goals and continuously evolving through post-deployment improvement, sometimes without requiring code or model updates. Conventional approaches, such as pre-defined test cases and code/model redevelopment pipelines, are inadequate for addressing the unique challenges of LLM agent development, particularly in terms of quality and risk control. This paper introduces an evaluation-driven design approach, inspired by test-driven development, to address these challenges. Through a multivocal literature review (MLR), we synthesize existing LLM evaluation methods and propose a novel process model and reference architecture specifically designed for LLM agents. The proposed approach integrates online and offline evaluations to support adaptive runtime adjustments and systematic offline redevelopment, improving runtime pipelines, artifacts, system architecture, and LLMs by continuously incorporating evaluation results, including fine-grained feedback from human and AI evaluators.

[Arxiv](https://arxiv.org/abs/2411.13768)