# Python 符号执行结合 LLM 驱动的代码生成

发布时间：2024年09月13日

`Agent` `软件测试` `人工智能`

> Python Symbolic Execution with LLM-powered Code Generation

# 摘要

> 符号执行作为软件测试的核心技术，通过收集符号路径约束并利用 SMT 求解器解决这些约束来生成测试用例。尽管符号执行在生成高覆盖率测试用例方面表现出色，但其局限性，如解决路径约束的困难，限制了其在软件测试中的广泛应用。此外，符号执行在处理 Python 这类动态类型语言时面临诸多挑战，因为将灵活的 Python 语法转换为严格的求解器极具挑战性。为应对在 Python 中应用符号执行的挑战，我们推出了 LLM-Sym，一个由 LLM 驱动的智能代理，它自动调用 SMT 求解器 Z3 来解决执行路径约束。基于基础的符号执行引擎，LLM-Sym 能够扩展支持包含复杂数据类型 `list' 的程序。其核心在于将复杂的 Python 路径约束转换为 Z3 代码。为确保路径到 Z3 的准确转换，我们设计了一个多步骤的代码生成流程，包括类型推断、检索和自我改进。实验结果显示，LLM-Sym 能够解决 Leetcode 问题中包含复杂控制流和列表数据结构的路径约束，这是基础符号执行引擎无法实现的。这一创新不仅融合了 LLM 的生成能力与符号求解器的推理能力，更为 LLM 增强的测试用例生成打开了新的大门。

> Symbolic execution is a key technology in software testing, which generates test cases by collecting symbolic path constraints and then solving constraints with SMT solvers. Symbolic execution has been proven helpful in generating high-coverage test cases, but its limitations, e.g., the difficulties in solving path constraints, prevent it from broader usage in software testing. Moreover, symbolic execution has encountered many difficulties when applied to dynamically typed languages like Python, because it is extremely challenging to translate the flexible Python grammar into rigid solvers.
  To overcome the main challenges of applying symbolic execution in Python, we proposed an LLM-empowered agent, LLM-Sym, that automatically calls an SMT solver, Z3, to solve execution path constraints. Based on an introductory-level symbolic execution engine, our LLM agent can extend it to supporting programs with complex data type `list'. The core contribution of LLM-Sym is translating complex Python path constraints into Z3 code. To enable accurate path-to-Z3 translation, we design a multiple-step code generation pipeline including type inference, retrieval and self-refine. Our experiments demonstrate that LLM-Sym is capable of solving path constraints on Leetcode problems with complicated control flows and list data structures, which is impossible for the backbone symbolic execution engine. Our approach paves the way for the combination of the generation ability of LLMs with the reasoning ability of symbolic solvers, and opens up new opportunities in LLM-augmented test case generation.

[Arxiv](https://arxiv.org/abs/2409.09271)