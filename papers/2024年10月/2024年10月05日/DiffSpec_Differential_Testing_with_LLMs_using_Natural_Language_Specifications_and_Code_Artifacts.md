# DiffSpec：借助自然语言规范与代码工件，对 LLM 进行差异测试

发布时间：2024年10月05日

`LLM应用` `软件工程` `网络安全`

> DiffSpec: Differential Testing with LLMs using Natural Language Specifications and Code Artifacts

# 摘要

> 差异测试是发现多实现软件系统中错误的高效手段，如编译器和网络协议解析器。这些系统的规范常以自然语言文档形式标准化。大型语言模型（LLM）在生成测试和处理大量文本方面表现出色，使其成为利用规范文档、错误报告和代码实现的理想工具。我们利用自然语言和代码工件，指导LLM生成针对性测试，揭示实现间的行为差异，包括潜在错误。我们推出了DiffSpec框架，通过提示链生成差异测试。在eBPF运行时和Wasm验证器上，DiffSpec生成了359个测试，揭示了eBPF中的四个已确认错误，包括内核内存泄漏。同时，在Wasm验证器中发现了279个测试，指向两个已修复的错误。

> Differential testing can be an effective way to find bugs in software systems with multiple implementations that conform to the same specification, like compilers, network protocol parsers, and language runtimes. Specifications for such systems are often standardized in natural language documents, like Instruction Set Architecture (ISA) specifications, Wasm specifications or IETF RFC's. Large Language Models (LLMs) have demonstrated potential in both generating tests and handling large volumes of natural language text, making them well-suited for utilizing artifacts like specification documents, bug reports, and code implementations. In this work, we leverage natural language and code artifacts to guide LLMs to generate targeted, meaningful tests that highlight meaningful behavioral differences between implementations, including those corresponding to bugs. We introduce DiffSpec, a framework for generating differential tests with LLMs using prompt chaining. We demonstrate the efficacy of DiffSpec on two different systems, namely, eBPF runtimes and Wasm validators. Using DiffSpec, we generated 359 differentiating tests, uncovering at least four distinct and confirmed bugs in eBPF, including a kernel memory leak, inconsistent behavior in jump instructions, and undefined behavior when using the stack pointer. We also found 279 differentiating tests in Wasm validators, that point to at least 2 confirmed and fixed bugs.

[Arxiv](https://arxiv.org/abs/2410.04249)