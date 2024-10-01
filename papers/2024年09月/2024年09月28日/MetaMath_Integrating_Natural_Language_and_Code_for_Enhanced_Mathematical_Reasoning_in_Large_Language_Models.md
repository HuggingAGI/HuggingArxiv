# MetaMath：融合自然语言与代码，提升大型语言模型中的数学推理能力

发布时间：2024年09月28日

`LLM应用` `人工智能`

> MetaMath: Integrating Natural Language and Code for Enhanced Mathematical Reasoning in Large Language Models

# 摘要

> LLM 通常用于生成数学推理问题的解决方案，形式包括自然语言、代码或两者结合。本文探讨了使用 GPT-4o-mini 和 LLama-3.1-8b-Turbo 等先进 LLM 解决这些问题的基本问题。研究发现，LLM 在自然语言推理上表现更佳，尽管自然语言和代码是互补的推理形式，但在某些情况下可能相互影响。基于这些发现，我们开发了 MetaMath 提示方法，通过 LLM 动态选择最佳推理形式，显著提升了性能。

> Large Language Models (LLMs) are commonly used to generate solutions for mathematical reasoning problems in the following formats: natural language, code, or a combination of both. In this paper, we explore fundamental questions related to solving mathematical reasoning problems using natural language and code with state-of-the-art LLMs, including GPT-4o-mini and LLama-3.1-8b-Turbo. Our findings show that LLMs are better at reasoning in natural language compared to code. Additionally, although natural language and code serve as complementary forms of reasoning, they can affect each other in a negative way in certain scenarios. These insights motivate our development of a new prompting method, MetaMath, which leverages an LLM to dynamically select the most appropriate reasoning form, resulting in improved performance over comparable baselines with GPT-4o-mini.

[Arxiv](https://arxiv.org/abs/2409.19381)