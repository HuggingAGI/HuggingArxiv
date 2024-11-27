# 图书馆学习并非如此：一次性“图书馆”的奇特情形

发布时间：2024年10月26日

`LLM应用`

> Library Learning Doesn't: The Curious Case of the Single-Use "Library"

# 摘要

> 大型语言模型（LLMs）的发展掀起了数学推理的 LLM 库学习系统的热潮。这些系统致力于学习可复用的工具库，比如为一系列任务定制的正式 Isabelle 引理或 Python 程序。众多此类系统受人类将知识构建为可复用、可扩展概念的启发，然而当下的方法真能学到可复用的工具库吗？
  我们对 LEGO-Prover 和 TroVE 这两个数学库学习系统展开研究，二者均称准确率有所提升。我们发现，在 miniF2F 和 MATH 中，函数复用的情况极为少见。后续的消融实验表明，所观察到的性能提升，主要驱动因素并非复用，而是自我修正和自我一致性。我们的代码和数据可于 https://github.com/ikb-a/curious-case 获取。

> Advances in Large Language Models (LLMs) have spurred a wave of LLM library learning systems for mathematical reasoning. These systems aim to learn a reusable library of tools, such as formal Isabelle lemmas or Python programs that are tailored to a family of tasks. Many of these systems are inspired by the human structuring of knowledge into reusable and extendable concepts, but do current methods actually learn reusable libraries of tools?
  We study two library learning systems for mathematics which both reported increased accuracy: LEGO-Prover and TroVE. We find that function reuse is extremely infrequent on miniF2F and MATH. Our followup ablation experiments suggest that, rather than reuse, self-correction and self-consistency are the primary drivers of the observed performance gains. Our code and data are available at https://github.com/ikb-a/curious-case

[Arxiv](https://arxiv.org/abs/2410.20274)