# HLSPilot：基于大型语言模型的高级综合工具

发布时间：2024年08月13日

`LLM应用` `硬件设计` `半导体`

> HLSPilot: LLM-based High-Level Synthesis

# 摘要

> 大型语言模型 (LLM) 推动了自动代码生成的蓬勃发展，特别是在寄存器传输级 (RTL) 代码生成领域备受瞩目。然而，由于自然语言与硬件设计意图之间的语义鸿沟，使用自然语言进行 RTL 代码生成仍存在错误风险且局限于小模块。为此，我们提出了一种新方法，通过 C/C++ 结合高级综合 (HLS) 工具来缩小这一鸿沟。我们设计了一系列针对不同代码模式的 C-to-HLS 优化策略，并通过上下文学习将这些策略应用于 C/C++ 代码，为 LLM 提供转换示例。这一方法有效提升了 HLS 设计的生成效率。针对 LLM 在精确调整优化参数上的挑战，我们引入了设计空间探索 (DSE) 工具进行辅助。同时，利用分析工具定位程序瓶颈，并将其转换为 HLS 代码以加速硬件实现。综合这些技术，我们开发了 HLSPilot，这是首个由 LLM 驱动的高级综合框架，可在混合 CPU-FPGA 架构上实现全自动的高级应用加速。实验表明，HLSPilot 不仅性能卓越，甚至能超越手工优化，展现了 LLM 在硬件设计领域的巨大潜力。

> Large language models (LLMs) have catalyzed an upsurge in automatic code generation, garnering significant attention for register transfer level (RTL) code generation. Despite the potential of RTL code generation with natural language, it remains error-prone and limited to relatively small modules because of the substantial semantic gap between natural language expressions and hardware design intent. In response to the limitations, we propose a methodology that reduces the semantic gaps by utilizing C/C++ for generating hardware designs via High-Level Synthesis (HLS) tools. Basically, we build a set of C-to-HLS optimization strategies catering to various code patterns, such as nested loops and local arrays. Then, we apply these strategies to sequential C/C++ code through in-context learning, which provides the LLMs with exemplary C/C++ to HLS prompts. With this approach, HLS designs can be generated effectively. Since LLMs still face problems in determining the optimized pragma parameters precisely, we have a design space exploration (DSE) tool integrated for pragma parameter tuning. Furthermore, we also employ profiling tools to pinpoint the performance bottlenecks within a program and selectively convert bottleneck components to HLS code for hardware acceleration. By combining the LLM-based profiling, C/C++ to HLS translation, and DSE, we have established HLSPilot, the first LLM-enabled high-level synthesis framework, which can fully automate the high-level application acceleration on hybrid CPU-FPGA architectures. According to our experiments on real-world application benchmarks, HLSPilot achieve comparable performance in general and can even outperform manually crafted counterparts, thereby underscoring the substantial promise of LLM-assisted hardware designs.

[Arxiv](https://arxiv.org/abs/2408.06810)