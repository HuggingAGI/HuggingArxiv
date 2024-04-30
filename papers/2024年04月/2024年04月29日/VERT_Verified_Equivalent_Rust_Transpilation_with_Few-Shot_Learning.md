# VERT：运用少量学习验证 Rust 语言的等价转译

发布时间：2024年04月29日

`LLM应用` `编程语言` `代码转译`

> VERT: Verified Equivalent Rust Transpilation with Few-Shot Learning

# 摘要

> Rust，作为一种融合了内存安全与底层控制的编程语言，以其类 C 语言的性能和默认避免未定义行为的特性而广受欢迎。随着 Rust 的流行，如何安全且准确地将现有代码转译为 Rust 成为研究热点。目前的研究主要分为基于规则的方法和基于大型语言模型（LLM）的方法两大类。基于规则的方法虽能理论上保证转译的正确性，但往往产出难以阅读的 Rust 代码；而基于 LLM 的方法虽能生成更易读和安全的代码，却无法确保其正确性。本研究提出了 VERT 工具，它能够生成既易读又具有形式正确性保证的 Rust 代码转译。VERT 的使用前提仅是源语言需有 Web Assembly 编译器，这在大多数主流语言中已得到满足。VERT 利用 Web Assembly 编译器生成一个基准 Rust 程序，并同时使用 LLM 生成可读的候选 Rust 程序，通过与基准程序的对比验证，不断迭代直至验证通过。我们通过转译 1,394 个来自编程竞赛风格的基准测试程序来评估 VERT 的性能。结合 Anthropic 的 Claude-2，VERT 显著提升了 Rust 转译的测试通过率，从基于属性的测试的 31% 提升至 54%，从有界模型检查的 1% 提升至 42%。此外，VERT 在生成实际 C 项目中大量使用指针的程序的安全 Rust 代码方面的能力也得到了验证。研究结果揭示了 LLM 在编写安全 Rust 代码方面的局限性。

> Rust is a programming language that combines memory safety and low-level control, providing C-like performance while guaranteeing the absence of undefined behaviors by default. Rust's growing popularity has prompted research on safe and correct transpiling of existing code-bases to Rust. Existing work falls into two categories: rule-based and large language model (LLM)-based. While rule-based approaches can theoretically produce correct transpilations that maintain input-output equivalence to the original, they often yield unreadable Rust code that uses unsafe subsets of the Rust language. On the other hand, while LLM-based approaches typically produce more readable, maintainable, and safe code, they do not provide any guarantees about correctness. In this work, we present VERT, a tool that can produce readable Rust transpilations with formal guarantees of correctness. VERT's only requirement is that there is Web Assembly compiler for the source language, which is true for most major languages. VERT first uses the Web Assembly compiler to obtain an oracle Rust program. In parallel, VERT uses an LLM to generate a readable candidate Rust program. This candidate is verified against the oracle, and if verification fails, we regenerate a new candidate transpilation until verification succeeds. We evaluate VERT by transpiling a suite of 1,394 programs taken from competitive programming style benchmarks. Combining Anthropic's Claude-2 and VERT increases Rust transpilations passing property-based testing from 31% to 54% and bounded model-checking from 1% to 42% compared to using Claude alone. In addition, we evaluate VERT's ability to generate non-trivial safe Rust on programs taken from real-world C projects that make significant use of pointers. Our results provide insights into the limitations of LLMs to write safe Rust.

[Arxiv](https://arxiv.org/abs/2404.18852)