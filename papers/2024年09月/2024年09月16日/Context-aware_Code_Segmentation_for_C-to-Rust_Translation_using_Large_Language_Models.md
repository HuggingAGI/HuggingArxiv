# 利用大型语言模型实现 C 到 Rust 翻译的上下文感知代码分割

发布时间：2024年09月16日

`LLM应用` `软件开发` `编程语言`

> Context-aware Code Segmentation for C-to-Rust Translation using Large Language Models

# 摘要

> 由于 C 程序中持续的内存安全问题和 Rust 作为替代语言的崛起，将 C 代码转换为 Rust 代码的需求日益迫切。尽管大型语言模型 (LLM) 在生成更自然、更安全的代码方面显示出潜力，但先前研究表明，LLM 生成的 Rust 代码往往因语言差异和上下文限制而无法编译。为此，我们提出了一种基于 LLM 的翻译方案，通过以下三项技术提高翻译成功率：(1) 预处理 C 代码以适应 Rust 的结构和表达；(2) 将代码分割为适中的翻译单元，避免超出 LLM 的上下文限制；(3) 通过上下文补充提示，迭代编译和修复错误，确保翻译单元间的一致性。编译成功是实现功能等价的首要步骤，因为只有可编译的代码才能进行进一步测试。实验结果显示，我们成功地将 20 个包含超过 4 千行代码的基准 C 程序全部翻译为可编译的 Rust 代码，且未丢失原始代码的任何部分。

> There is strong motivation to translate C code into Rust code due to the continuing threat of memory safety vulnerabilities in existing C programs and the significant attention paid to Rust as an alternative to the C language. While large language models (LLMs) show promise for automating this translation by generating more natural and safer code than rule-based methods, previous studies have shown that LLM-generated Rust code often fails to compile, even for relatively small C programs, due to significant differences between the two languages and context window limitations. We propose an LLM-based translation scheme that improves the success rate of translating large-scale C code into compilable Rust code. Our approach involves three key techniques: (1) pre-processing the C code to better align its structure and expressions with Rust, (2) segmenting the code into optimally sized translation units to avoid exceeding the LLM's context window limits, and (3) iteratively compiling and repairing errors while maintaining consistency between translation units using context-supplementing prompts. Compilation success is an essential first step in achieving functional equivalence, as only compilable code can be further tested. In experiments with 20 benchmark C programs, including those exceeding 4 kilo lines of code, we successfully translated all programs into compilable Rust code without losing corresponding parts of the original code.

[Arxiv](https://arxiv.org/abs/2409.10506)