# AutoSafeCoder：通过静态分析与模糊测试，为 LLM 代码生成提供安全保障的多代理框架

发布时间：2024年09月16日

`Agent` `软件开发` `网络安全`

> AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation through Static Analysis and Fuzz Testing

# 摘要

> 最新的大型语言模型 (LLM) 自动代码生成技术让我们离完全自动化的安全软件开发更近一步。然而，现有方法多依赖单一代理生成代码，难以确保安全无漏洞。传统 LLM 程序合成主要关注功能正确性，常忽略运行时的动态安全问题。为此，我们推出 AutoSafeCoder，一个多代理框架，通过 LLM 驱动的代理协作进行代码生成、漏洞分析和安全增强。框架包含编码、静态分析和模糊测试三个代理，分别负责代码生成、漏洞识别和动态测试。我们的创新在于在 LLM 代码生成过程中，通过迭代集成动态和静态测试，确保多代理代码生成的安全性。实验显示，与基线 LLM 相比，代码漏洞减少 13%，功能性不受影响。

> Recent advancements in automatic code generation using large language models (LLMs) have brought us closer to fully automated secure software development. However, existing approaches often rely on a single agent for code generation, which struggles to produce secure, vulnerability-free code. Traditional program synthesis with LLMs has primarily focused on functional correctness, often neglecting critical dynamic security implications that happen during runtime. To address these challenges, we propose AutoSafeCoder, a multi-agent framework that leverages LLM-driven agents for code generation, vulnerability analysis, and security enhancement through continuous collaboration. The framework consists of three agents: a Coding Agent responsible for code generation, a Static Analyzer Agent identifying vulnerabilities, and a Fuzzing Agent performing dynamic testing using a mutation-based fuzzing approach to detect runtime errors. Our contribution focuses on ensuring the safety of multi-agent code generation by integrating dynamic and static testing in an iterative process during code generation by LLM that improves security. Experiments using the SecurityEval dataset demonstrate a 13% reduction in code vulnerabilities compared to baseline LLMs, with no compromise in functionality.

[Arxiv](https://arxiv.org/abs/2409.10737)