# 从代码到完美：借助分层调试，完成代码生成的最后一步

发布时间：2024年10月01日

`LLM应用` `软件开发` `人工智能`

> From Code to Correctness: Closing the Last Mile of Code Generation with Hierarchical Debugging

# 摘要

> 大型语言模型在代码生成方面虽有显著进展，但细微错误常导致代码通过率受限，尤其在复杂问题中需人工干预。现有LLM调试系统将程序视为整体，无法多层次解决错误。本文提出多粒度调试器（MGDebugger），通过分层处理不同粒度错误，将问题代码分解为子函数树结构，逐层调试。为精准定位错误，我们设计了LLM模拟的Python执行器，跟踪代码执行与变量状态。实验显示，MGDebugger在HumanEval中准确性提升18.9%，修复成功率达97.6%，且能有效应对各类错误，展现其强大与高效。

> While large language models have made significant strides in code generation, the pass rate of the generated code is bottlenecked on subtle errors, often requiring human intervention to pass tests, especially for complex problems. Existing LLM-based debugging systems treat generated programs as monolithic units, failing to address bugs at multiple levels of granularity, from low-level syntax errors to high-level algorithmic flaws. In this paper, we introduce Multi-Granularity Debugger (MGDebugger), a hierarchical code debugger by isolating, identifying, and resolving bugs at various levels of granularity. MGDebugger decomposes problematic code into a hierarchical tree structure of subfunctions, with each level representing a particular granularity of error. During debugging, it analyzes each subfunction and iteratively resolves bugs in a bottom-up manner. To effectively test each subfunction, we propose an LLM-simulated Python executor, which traces code execution and tracks important variable states to pinpoint errors accurately. Extensive experiments demonstrate that MGDebugger outperforms existing debugging systems, achieving an 18.9% improvement in accuracy over seed generations in HumanEval and a 97.6% repair success rate in HumanEvalFix. Furthermore, MGDebugger effectively fixes bugs across different categories and difficulty levels, demonstrating its robustness and effectiveness.

[Arxiv](https://arxiv.org/abs/2410.01215)