# Gödel Agent：一个自指代理框架，专为递归自我改进设计

发布时间：2024年10月06日

`Agent` `人工智能` `自动化`

> Gödel Agent: A Self-Referential Agent Framework for Recursive Self-Improvement

# 摘要

> 随着 LLM 的迅猛发展，AI 代理的能力得到了显著提升。然而，现有代理系统受限于人类设计，无法探索整个设计空间，可能错失最优方案。本文介绍的 Gödel Agent，灵感源自 Gödel 机器，是一个自进化框架，无需预设规则或固定算法，即可递归改进。它借助 LLM 动态调整自身逻辑与行为，仅凭高级目标指引。实验显示，Gödel Agent 在数学推理和复杂任务中，持续自我提升，性能、效率和通用性均超越手工代理。

> The rapid advancement of large language models (LLMs) has significantly enhanced the capabilities of AI-driven agents across various tasks. However, existing agentic systems, whether based on fixed pipeline algorithms or pre-defined meta-learning frameworks, cannot search the whole agent design space due to the restriction of human-designed components, and thus might miss the globally optimal agent design. In this paper, we introduce Gödel Agent, a self-evolving framework inspired by the Gödel machine, enabling agents to recursively improve themselves without relying on predefined routines or fixed optimization algorithms. Gödel Agent leverages LLMs to dynamically modify its own logic and behavior, guided solely by high-level objectives through prompting. Experimental results on mathematical reasoning and complex agent tasks demonstrate that implementation of Gödel Agent can achieve continuous self-improvement, surpassing manually crafted agents in performance, efficiency, and generalizability.

[Arxiv](https://arxiv.org/abs/2410.04444)