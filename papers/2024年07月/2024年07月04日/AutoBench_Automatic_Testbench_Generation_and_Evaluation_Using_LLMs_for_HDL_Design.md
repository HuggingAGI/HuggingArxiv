# AutoBench：借助 LLM 实现 HDL 设计的自动化测试台生成与评估

发布时间：2024年07月04日

`LLM应用` `电子工程` `硬件验证`

> AutoBench: Automatic Testbench Generation and Evaluation Using LLMs for HDL Design

# 摘要

> 在数字电路设计领域，测试平台是硬件验证的基石。传统方法在生成测试平台时仍依赖部分手动操作，这不仅效率低下，还耗费设计师大量时间。为此，我们推出了AutoBench，这是首个基于大型语言模型（LLM）的自动化测试平台生成器，仅需待测设计的描述即可自动创建全面测试平台。AutoBench通过LLM实现了混合结构和自检系统，并引入了一个自动评估框架，从多角度评估测试平台质量。实验显示，AutoBench在通过率上比传统方法提升了57%，对75个顺序电路的测试平台通过率更是基线的3.36倍。所有源代码和实验结果已在GitHub开源。

> In digital circuit design, testbenches constitute the cornerstone of simulation-based hardware verification. Traditional methodologies for testbench generation during simulation-based hardware verification still remain partially manual, resulting in inefficiencies in testing various scenarios and requiring expensive time from designers. Large Language Models (LLMs) have demonstrated their potential in automating the circuit design flow. However, directly applying LLMs to generate testbenches suffers from a low pass rate. To address this challenge, we introduce AutoBench, the first LLM-based testbench generator for digital circuit design, which requires only the description of the design under test (DUT) to automatically generate comprehensive testbenches. In AutoBench, a hybrid testbench structure and a self-checking system are realized using LLMs. To validate the generated testbenches, we also introduce an automated testbench evaluation framework to evaluate the quality of generated testbenches from multiple perspectives. Experimental results demonstrate that AutoBench achieves a 57% improvement in the testbench pass@1 ratio compared with the baseline that directly generates testbenches using LLMs. For 75 sequential circuits, AutoBench successfully has a 3.36 times testbench pass@1 ratio compared with the baseline. The source codes and experimental results are open-sourced at this link: https://github.com/AutoBench/AutoBench

[Arxiv](https://arxiv.org/abs/2407.03891)