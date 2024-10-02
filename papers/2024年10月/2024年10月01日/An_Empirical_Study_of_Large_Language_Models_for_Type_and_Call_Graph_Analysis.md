# 探究大型语言模型在类型与调用图分析中的实际应用

发布时间：2024年10月01日

`LLM应用` `软件工程` `静态分析`

> An Empirical Study of Large Language Models for Type and Call Graph Analysis

# 摘要

> 大型语言模型 (LLM) 在软件工程，尤其是静态分析任务中的应用潜力正受到广泛关注。本研究探索了当前 LLM 在提升 Python 和 JavaScript 程序的调用图分析和类型推断方面的能力。我们评估了 24 个 LLM，包括 OpenAI 的 GPT 系列和开源模型如 LLaMA 和 Mistral，使用现有和新开发的基准。我们改进了 TypeEvalPy，使其自动生成功能从 860 扩展到 77,268 个类型注释。同时，引入了 SWARM-CG 和 SWARM-JS，用于跨语言调用图构建工具的综合评估。研究发现，LLM 在静态分析中的表现参差不齐。在 Python 中，传统工具 PyCG 在调用图生成上优于 LLM；而在 JavaScript 中，TAJS 因无法处理现代语言特性而表现不佳，LLM 虽有潜力，但在完整性和正确性上仍有不足。相反，LLM 在 Python 类型推断中表现出色，超越了传统和混合工具。这些发现表明，LLM 在类型推断中潜力巨大，但在调用图分析中仍需更多研究。本研究为 LLM 在静态分析中的应用提供了基础，揭示了其优势与局限。

> Large Language Models (LLMs) are increasingly being explored for their potential in software engineering, particularly in static analysis tasks. In this study, we investigate the potential of current LLMs to enhance call-graph analysis and type inference for Python and JavaScript programs. We empirically evaluated 24 LLMs, including OpenAI's GPT series and open-source models like LLaMA and Mistral, using existing and newly developed benchmarks. Specifically, we enhanced TypeEvalPy, a micro-benchmarking framework for type inference in Python, with auto-generation capabilities, expanding its scope from 860 to 77,268 type annotations for Python. Additionally, we introduced SWARM-CG and SWARM-JS, comprehensive benchmarking suites for evaluating call-graph construction tools across multiple programming languages. Our findings reveal a contrasting performance of LLMs in static analysis tasks. For call-graph generation in Python, traditional static analysis tools like PyCG significantly outperform LLMs. In JavaScript, the static tool TAJS underperforms due to its inability to handle modern language features, while LLMs, despite showing potential with models like mistral-large-it-2407-123b and GPT-4o, struggle with completeness and soundness in both languages for call-graph analysis. Conversely, LLMs demonstrate a clear advantage in type inference for Python, surpassing traditional tools like HeaderGen and hybrid approaches such as HiTyper. These results suggest that while LLMs hold promise in type inference, their limitations in call-graph analysis highlight the need for further research. Our study provides a foundation for integrating LLMs into static analysis workflows, offering insights into their strengths and current limitations.

[Arxiv](https://arxiv.org/abs/2410.00603)