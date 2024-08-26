# CRUXEval-X：多语言代码推理、理解和执行的综合基准

发布时间：2024年08月23日

`LLM应用` `软件开发` `编程语言`

> CRUXEval-X: A Benchmark for Multilingual Code Reasoning, Understanding and Execution

# 摘要

> HumanEval 等代码基准测试广泛用于评估 LLM 的编程能力，但现有基准存在显著的编程语言偏差，主要集中在 Python，忽略了 LLM 在 Java 和 C/C++ 等其他语言的能力。此外，现有基准多关注代码生成，而对代码推理这一核心能力测试不足。为此，我们推出了 CRUXEVAL-X，一个涵盖 19 种编程语言的多语言代码推理基准，每种语言包含至少 600 个题目，总计 19K 测试。CRUXEVAL-X 采用全自动化、测试引导的建设流程，并针对语言特性制定了转换规则，以促进跨语言翻译。我们的评估显示，TypeScript 和 JavaScript 高度相关，而 Racket 相关性较低。更有趣的是，仅在 Python 上训练的模型，在其他语言中也能达到高达 34.4% 的通过率，显示了 LLM 的跨语言泛化潜力。

> Code benchmarks such as HumanEval are widely adopted to evaluate Large Language Models' (LLMs) coding capabilities. However, there is an unignorable programming language bias in existing code benchmarks -- over 95% code generation benchmarks are dominated by Python, leaving the LLMs' capabilities in other programming languages such as Java and C/C++ unknown. Moreover, coding task bias is also crucial. Most benchmarks focus on code generation capability, while benchmarks for code reasoning (given input, reasoning output; and given output, reasoning input), an essential coding capability, are insufficient. Yet, constructing multi-lingual benchmarks can be expensive and labor-intensive, and codes in contest websites such as Leetcode suffer from data contamination during training. To fill this gap, we propose CRUXEVAL-X, a multi-lingual code reasoning benchmark that contains 19 programming languages. It comprises at least 600 subjects for each language, along with 19K content-consistent tests in total. In particular, the construction pipeline of CRUXEVAL-X works in a fully automated and test-guided manner, which iteratively generates and repairs based on execution feedback. Also, to cross language barriers (e.g., dynamic/static type systems in Python/C++), we formulated various transition rules between language pairs to facilitate translation. Our intensive evaluation of 24 representative LLMs reveals the correlation between language pairs. For example, TypeScript and JavaScript show a significant positive correlation, while Racket has less correlation with other languages. More interestingly, even a model trained solely on Python can achieve at most 34.4% Pass@1 in other languages, revealing the cross-language generalization of LLMs.

[Arxiv](https://arxiv.org/abs/2408.13001)