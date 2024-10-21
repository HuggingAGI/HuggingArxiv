# Agents4PLC：借助 LLM 代理，自动化工业控制系统中的闭环 PLC 代码生成与验证

发布时间：2024年10月18日

`Agent` `工业控制` `自动化`

> Agents4PLC: Automating Closed-loop PLC Code Generation and Verification in Industrial Control Systems using LLM-based Agents

# 摘要

> 在工业控制系统中，PLC 代码的生成与验证对操作效率和安全至关重要。尽管 LLM 在自动代码生成方面有所突破，但在正确性保证和 PLC 编程支持上仍显不足。为此，我们推出了 Agents4PLC 框架，它不仅自动化 PLC 代码生成，还通过 LLM 多代理系统进行代码级验证。我们首先构建了从自然语言需求到人工验证形式规范的全面基准。接着，通过 RAG、高级提示技术和思维链策略，我们专门优化了工业控制系统的“代理”。评估显示，Agents4PLC 在严格指标上显著超越以往方法。这项研究不仅攻克了 PLC 编程难题，更展示了我们框架在实际工业应用中生成可验证代码的潜力。

> In industrial control systems, the generation and verification of Programmable Logic Controller (PLC) code are critical for ensuring operational efficiency and safety. While Large Language Models (LLMs) have made strides in automated code generation, they often fall short in providing correctness guarantees and specialized support for PLC programming. To address these challenges, this paper introduces Agents4PLC, a novel framework that not only automates PLC code generation but also includes code-level verification through an LLM-based multi-agent system. We first establish a comprehensive benchmark for verifiable PLC code generation area, transitioning from natural language requirements to human-written-verified formal specifications and reference PLC code. We further enhance our `agents' specifically for industrial control systems by incorporating Retrieval-Augmented Generation (RAG), advanced prompt engineering techniques, and Chain-of-Thought strategies. Evaluation against the benchmark demonstrates that Agents4PLC significantly outperforms previous methods, achieving superior results across a series of increasingly rigorous metrics. This research not only addresses the critical challenges in PLC programming but also highlights the potential of our framework to generate verifiable code applicable to real-world industrial applications.

[Arxiv](https://arxiv.org/abs/2410.14209)