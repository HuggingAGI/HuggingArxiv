# OMPar：借助 AI 驱动的源到源编译技术，实现自动并行化

发布时间：2024年09月23日

`LLM应用` `软件开发` `高性能计算`

> OMPar: Automatic Parallelization with AI-Driven Source-to-Source Compilation

# 摘要

> 手动并行化代码因现代软件的复杂性和多核架构的普及而变得极具挑战。本文推出的OMPar，是一款AI驱动的工具，专为自动并行化C/C++代码而设计，利用OpenMP pragmas实现。OMPar通过两大核心组件与大型语言模型（LLMs）结合：OMPify评估循环并行潜力，MonoCoder-OMP则生成精准的OpenMP pragmas。OMPar的评估流程与传统工具如AutoPar和ICPC编译器一样严谨：确保代码串行运行无误，逐步增加线程与物理核心以测性能，并验证代码输出正确性。HeCBench和ParEval的基准测试显示，OMPar在识别并行循环和生成高效pragmas方面，显著超越传统方法。此外，OMPar能处理不完整代码库，并持续从新代码模式中学习，不断提升并行化能力。这些成果预示着LLMs在革新自动并行化技术上的巨大潜力，推动更高效、可扩展的并行计算系统的发展。

> Manual parallelization of code remains a significant challenge due to the complexities of modern software systems and the widespread adoption of multi-core architectures. This paper introduces OMPar, an AI-driven tool designed to automate the parallelization of C/C++ code using OpenMP pragmas. OMPar integrates Large Language Models (LLMs) through two key components: OMPify, which assesses loop parallelization potential, and MonoCoder-OMP, a new fine-tuned model which generates precise OpenMP pragmas. The evaluation of OMPar follows the same rigorous process applied to traditional tools like source-to-source AutoPar and ICPC compilers: (1) ensuring the generated code compiles and runs correctly in serial form, (2) assessing performance with the gradual addition of threads and corresponding physical cores, and (3) verifying and validating the correctness of the code's output. Benchmarks from HeCBench and ParEval are used to evaluate accuracy and performance. Experimental results demonstrate that OMPar significantly outperforms traditional methods, achieving higher accuracy in identifying parallelizable loops and generating efficient pragmas. Beyond accuracy, OMPar offers advantages such as the ability to work on partial or incomplete codebases and the capacity to continuously learn from new code patterns, enhancing its parallelization capabilities over time. These results underscore the potential of LLMs in revolutionizing automatic parallelization techniques, paving the way for more efficient and scalable parallel computing systems.

[Arxiv](https://arxiv.org/abs/2409.14771)