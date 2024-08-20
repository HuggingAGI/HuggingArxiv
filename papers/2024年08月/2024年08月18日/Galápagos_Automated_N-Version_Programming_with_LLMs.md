# Galápagos：借助 LLMs 实现自动化多版本编程

发布时间：2024年08月18日

`LLM应用` `软件开发` `自动化`

> Galápagos: Automated N-Version Programming with LLMs

# 摘要

> N-Version Programming 面临的主要挑战是高昂的开发成本，需要多个团队开发同一系统的不同版本。为此，我们提出利用大型语言模型自动生成系统变体。我们设计并实现了 Galápagos 工具，该工具利用 LLM 生成程序变体，验证其功能等效性，并用于构建 N-Version 软件。通过实际 C 代码的 N-Version 组件测试，我们发现 Galápagos 能生成功能等效的变体，即便这些变体采用不同编程语言编写。此外，这些变体在编译后静态差异显著，运行时内部行为也各异。实验证明，Galápagos 生成的变体能有效防御 Clang 编译器的误编译错误。本研究展示了通过深度应用形式验证和生成语言模型，N-Version 软件的开发可实现高度自动化。

> One of the main challenges of N-Version Programming is development cost: it requires paying multiple teams to develop variants of the same system. To address this issue, we propose the automated generation of variants using large language models. We design, develop and evaluate Galápagos: a tool for generating program variants using LLMs, validating their correctness and equivalence, and using them to assemble N-Version binaries. We evaluate Galápagos by creating N-Version components of real-world C code. Our original results show that Galápagos can produce program variants that are proven to be functionally equivalent, even when the variants are written in a different programming language. Our systematic diversity measurement indicate that functionally equivalent variants produced by Galápagos, are statically different after compilation, and present diverging internal behavior at runtime. We demonstrate that the variants produced by Galápagos can protect C code against real miscompilation bugs which affect the Clang compiler. Overall, our paper shows that producing N-Version software can be drastically automated by advanced usage of practical formal verification and generative language models.

[Arxiv](https://arxiv.org/abs/2408.09536)