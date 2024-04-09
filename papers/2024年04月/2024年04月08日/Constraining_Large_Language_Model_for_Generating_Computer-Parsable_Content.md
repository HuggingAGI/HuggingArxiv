# 通过对大型语言模型施加限制，我们能够生成计算机能够理解和解析的内容。

发布时间：2024年04月08日

`LLM应用` `计算机程序` `结构化内容生成`

> Constraining Large Language Model for Generating Computer-Parsable Content

# 摘要

> 我们设计了一种新技术，能够让大型语言模型（LLMs）在不经过微调的情况下，生成遵循特定规则的结构化内容。通过应用基于协程的生成约束和预设的上下文无关语法（CFG），在解码阶段引导LLMs输出符合规范的正式语言。这种方法提高了生成目标数据结构、类型或指令的稳定性与一致性，简化了应用程序的开发流程。实验表明，对于超过36和282个令牌的DSLs，GPT-2和Gemma的错误率均超过95%。我们推出了YieldLang，一个基于协程的DSL生成框架，通过LLMs在生成JSON和Mermaid流程图等任务上进行了测试。与行业标准相比，我们的方案将准确度提升了1.09至11.6倍，且LLMs仅需约16.5%的样本量即可有效生成JSON，极大地增强了LLM生成内容在计算机程序中的应用潜力。

> We propose a method to guide Large Language Models (LLMs) in generating structured content adhering to specific conventions without fine-tuning. By utilizing coroutine-based content generation constraints through a pre-agreed context-free grammar (CFG), LLMs are directed during decoding to produce formal language compliant outputs. This enhances stability and consistency in generating target data structures, types, or instructions, reducing application development complexities. Experimentally, error rates of GPT-2 and Gemma exceed 95% for DSLs longer than 36 and 282 tokens, respectively. We introduce YieldLang, a coroutine-based DSL generation framework, and evaluate it with LLMs on various tasks including JSON and Mermaid flowchart generation. Compared to benchmarks, our approach improves accuracy by 1.09 to 11.6 times, with LLMs requiring only about 16.5% of the samples to generate JSON effectively. This enhances usability of LLM-generated content for computer programs.

[Arxiv](https://arxiv.org/abs/2404.05499)