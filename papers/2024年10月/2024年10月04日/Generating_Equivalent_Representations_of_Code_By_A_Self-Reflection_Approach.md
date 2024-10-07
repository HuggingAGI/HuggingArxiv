# 利用自反思技术，生成代码的等效表达

发布时间：2024年10月04日

`LLM应用` `软件开发` `人工智能`

> Generating Equivalent Representations of Code By A Self-Reflection Approach

# 摘要

> 代码的等效表示（ERs），如自然语言注释和伪代码，在软件开发中至关重要。然而，自动生成ERs仍是一个挑战。本文提出了一种自反思方法，使两个大型语言模型（LLMs）通过协作生成ERs。我们的方法在无约束和有约束两种设置中生成ERs，并进行了实证研究，揭示了LLMs如何理解代码结构和计算。此外，我们还探讨了未来的研究方向，如开发中间语言和优化需求描述。我们相信，本文将激发研究社区的广泛讨论和后续研究。

> Equivalent Representations (ERs) of code are textual representations that preserve the same semantics as the code itself, e.g., natural language comments and pseudocode. ERs play a critical role in software development and maintenance. However, how to automatically generate ERs of code remains an open challenge. In this paper, we propose a self-reflection approach to generating ERs of code. It enables two Large Language Models (LLMs) to work mutually and produce an ER through a reflection process. Depending on whether constraints on ERs are applied, our approach generates ERs in both open and constrained settings. We conduct a empirical study to generate ERs in two settings and obtain eight findings. (1) Generating ERs in the open setting. In the open setting, we allow LLMs to represent code without any constraints, analyzing the resulting ERs and uncovering five key findings. These findings shed light on how LLMs comprehend syntactic structures, APIs, and numerical computations in code. (2) Generating ERs in the constrained setting. In the constrained setting, we impose constraints on ERs, such as natural language comments, pseudocode, and flowcharts. This allows our approach to address a range of software engineering tasks. Based on our experiments, we have three findings demonstrating that our approach can effectively generate ERs that adhere to specific constraints, thus supporting various software engineering tasks. (3) Future directions. We also discuss potential future research directions, such as deriving intermediate languages for code generation, exploring LLM-friendly requirement descriptions, and further supporting software engineering tasks. We believe that this paper will spark discussions in research communities and inspire many follow-up studies.

[Arxiv](https://arxiv.org/abs/2410.03351)