# MdEval：大规模多语言代码调试

发布时间：2024年11月04日

`LLM应用` `代码调试`

> MdEval: Massively Multilingual Code Debugging

# 摘要

> 代码大型语言模型（LLMs）在代码调试方面取得了重大进展，能够根据有错误的代码片段直接生成正确的代码。编程基准测试，通常由有错误的代码片段及其相关测试用例组成，被用于评估 LLMs 的调试能力。然而，许多现有的基准测试主要集中在 Python 上，并且在语言多样性方面常常受到限制（例如，DebugBench 和 DebugEval）。为了推进 LLMs 在多语言调试领域的发展，我们提出了第一个大规模多语言调试基准，其中包括 18 种编程语言的 3600 个测试样本，并涵盖了自动程序修复（APR）任务、代码审查（CR）任务和错误识别（BI）任务。此外，我们通过将错误注入到正确的多语言查询和解决方案（xDebugGen）中引入了调试指令语料库 MDEVAL-INSTRUCT。此外，在 MDEVAL-INSTRUCT 上训练的多语言调试器 xDebugCoder 作为一个强大的基线，专门用于处理各种编程语言的错误（例如 Rust 语言中的“缺失 Mut”和 C 语言中的“错误使用宏定义”）。我们在 MDEVAL 上的大量实验揭示了开源模型和闭源 LLMs（例如 GPT 和 Claude 系列）之间存在显著的性能差距，突出了在多语言代码调试场景中巨大的改进空间。

> Code large language models (LLMs) have made significant progress in code debugging by directly generating the correct code based on the buggy code snippet. Programming benchmarks, typically consisting of buggy code snippet and their associated test cases, are used to assess the debugging capabilities of LLMs. However, many existing benchmarks primarily focus on Python and are often limited in terms of language diversity (e.g., DebugBench and DebugEval). To advance the field of multilingual debugging with LLMs, we propose the first massively multilingual debugging benchmark, which includes 3.6K test samples of 18 programming languages and covers the automated program repair (APR) task, the code review (CR) task, and the bug identification (BI) task. Further, we introduce the debugging instruction corpora MDEVAL-INSTRUCT by injecting bugs into the correct multilingual queries and solutions (xDebugGen). Further, a multilingual debugger xDebugCoder trained on MDEVAL-INSTRUCT as a strong baseline specifically to handle the bugs of a wide range of programming languages (e.g. "Missing Mut" in language Rust and "Misused Macro Definition" in language C). Our extensive experiments on MDEVAL reveal a notable performance gap between open-source models and closed-source LLMs (e.g., GPT and Claude series), highlighting huge room for improvement in multilingual code debugging scenarios.

[Arxiv](https://arxiv.org/abs/2411.02310)