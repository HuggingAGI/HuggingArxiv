# 多计划探索与反馈驱动细化相结合的代码生成配对编程框架

发布时间：2024年09月08日

`Agent` `软件开发` `人工智能`

> A Pair Programming Framework for Code Generation via Multi-Plan Exploration and Feedback-Driven Refinement

# 摘要

> 大型语言模型（LLM）在代码生成上表现出色，但面对复杂编程问题时，因解决方案僵化而受限。本文借鉴结对编程，推出 PairCoder 框架：两个 LLM 代理协作，Navigator 负责高层次规划，Driver 负责具体实现。Navigator 提出并选择最优方案，Driver 则生成、测试并优化代码。这种迭代流程模拟了结对编程的协作，显著提升了代码生成的准确性，与直接提示 LLM 相比，pass@1 提升高达 12.00%-162.43%。

> Large language models (LLMs) have achieved impressive performance on code generation. Although prior studies enhanced LLMs with prompting techniques and code refinement, they still struggle with complex programming problems due to rigid solution plans. In this paper, we draw on pair programming practices to propose PairCoder, a novel LLM-based framework for code generation. PairCoder incorporates two collaborative LLM agents, namely a Navigator agent for high-level planning and a Driver agent for specific implementation. The Navigator is responsible for proposing promising solution plans, selecting the current optimal plan, and directing the next iteration round based on execution feedback. The Driver follows the guidance of Navigator to undertake initial code generation, code testing, and refinement. This interleaved and iterative workflow involves multi-plan exploration and feedback-based refinement, which mimics the collaboration of pair programmers. We evaluate PairCoder with both open-source and closed-source LLMs on various code generation benchmarks. Extensive experimental results demonstrate the superior accuracy of PairCoder, achieving relative pass@1 improvements of 12.00%-162.43% compared to prompting LLMs directly.

[Arxiv](https://arxiv.org/abs/2409.05001)