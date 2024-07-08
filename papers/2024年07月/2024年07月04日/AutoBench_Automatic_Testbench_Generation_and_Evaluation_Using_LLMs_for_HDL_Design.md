# AutoBench：借助 LLM 实现 HDL 设计的自动化测试平台生成与评估

发布时间：2024年07月04日

`LLM应用` `电子工程` `硬件验证`

> AutoBench: Automatic Testbench Generation and Evaluation Using LLMs for HDL Design

# 摘要

> 在数字电路设计领域，测试平台是硬件验证的关键。传统方法依赖人工，效率低下且耗时。为此，我们推出了AutoBench，首个利用大型语言模型（LLM）自动生成测试平台的工具，仅需DUT描述即可。AutoBench采用混合结构和自检系统，并通过自动化评估框架确保质量。实验显示，AutoBench在通过率上比传统方法提升了57%，对75个电路的通过率更是基线的3.36倍。所有资源已开源，详见：https://github.com/AutoBench/AutoBench。

> In digital circuit design, testbenches constitute the cornerstone of simulation-based hardware verification. Traditional methodologies for testbench generation during simulation-based hardware verification still remain partially manual, resulting in inefficiencies in testing various scenarios and requiring expensive time from designers. Large Language Models (LLMs) have demonstrated their potential in automating the circuit design flow. However, directly applying LLMs to generate testbenches suffers from a low pass rate. To address this challenge, we introduce AutoBench, the first LLM-based testbench generator for digital circuit design, which requires only the description of the design under test (DUT) to automatically generate comprehensive testbenches. In AutoBench, a hybrid testbench structure and a self-checking system are realized using LLMs. To validate the generated testbenches, we also introduce an automated testbench evaluation framework to evaluate the quality of generated testbenches from multiple perspectives. Experimental results demonstrate that AutoBench achieves a 57% improvement in the testbench pass@1 ratio compared with the baseline that directly generates testbenches using LLMs. For 75 sequential circuits, AutoBench successfully has a 3.36 times testbench pass@1 ratio compared with the baseline. The source codes and experimental results are open-sourced at this link: https://github.com/AutoBench/AutoBench

[Arxiv](https://arxiv.org/abs/2407.03891)