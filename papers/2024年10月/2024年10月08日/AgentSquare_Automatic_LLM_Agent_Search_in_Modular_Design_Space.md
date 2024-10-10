# AgentSquare：模块化设计空间中的自动 LLM 代理搜索

发布时间：2024年10月08日

`Agent` `人工智能` `软件工程`

> AgentSquare: Automatic LLM Agent Search in Modular Design Space

# 摘要

> 大型语言模型 (LLM) 的进步催生了能处理各种复杂任务的智能系统。然而，现有研究多依赖手工设计的特定任务方案，限制了其适应新任务的能力。为此，我们提出了模块化 LLM 代理搜索 (MoLAS) 的新课题。我们设计了一个包含规划、推理、工具使用和记忆四大模块的抽象空间，每个模块均具备统一的 IO 接口。基于此，我们开发了 AgentSquare 框架，通过模块进化与重组两大核心机制，高效搜索优化代理。为加速进程，我们还设计了利用上下文代理模型的性能预测器，以跳过不具前景的设计。实验表明，AgentSquare 在多个基准测试中显著超越手工设计代理，平均性能提升达 17.2%。此外，它还能生成可解释的设计见解，深化对代理架构及其任务性能影响的理解。我们相信，模块化设计与 AgentSquare 框架为挖掘成功设计潜力、整合研究力量提供了有力平台。代码已开源，详见 https://github.com/tsinghua-fib-lab/AgentSquare。

> Recent advancements in Large Language Models (LLMs) have led to a rapid growth of agentic systems capable of handling a wide range of complex tasks. However, current research largely relies on manual, task-specific design, limiting their adaptability to novel tasks. In this paper, we introduce a new research problem: Modularized LLM Agent Search (MoLAS). We propose a modular design space that abstracts existing LLM agent designs into four fundamental modules with uniform IO interface: Planning, Reasoning, Tool Use, and Memory. Building on this design space, we present a novel LLM agent search framework called AgentSquare, which introduces two core mechanisms, i.e., module evolution and recombination, to efficiently search for optimized LLM agents. To further accelerate the process, we design a performance predictor that uses in-context surrogate models to skip unpromising agent designs. Extensive experiments across six benchmarks, covering the diverse scenarios of web, embodied, tool use and game applications, show that AgentSquare substantially outperforms hand-crafted agents, achieving an average performance gain of 17.2% against best-known human designs. Moreover, AgentSquare can generate interpretable design insights, enabling a deeper understanding of agentic architecture and its impact on task performance. We believe that the modular design space and AgentSquare search framework offer a platform for fully exploiting the potential of prior successful designs and consolidating the collective efforts of research community. Code repo is available at https://github.com/tsinghua-fib-lab/AgentSquare.

[Arxiv](https://arxiv.org/abs/2410.06153)