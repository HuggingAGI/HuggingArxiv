# 探索大型语言模型驱动的Verilog RTL助手：实现自我验证与自我修正功能

发布时间：2024年05月31日

`LLM应用

这篇论文介绍了如何利用大型语言模型（LLMs）自动生成高质量的寄存器传输级（RTL）代码，通过开发一个名为VeriAssist的专用工具，该工具能够接收设计描述并输出高质量的RTL代码及测试平台。这种方法减少了人工介入，提高了代码生成的效率和准确性。因此，这篇论文属于LLM应用类别，因为它展示了LLMs在特定领域（硬件描述语言的RTL设计）的应用和优化。` `集成电路设计` `软件开发`

> Towards LLM-Powered Verilog RTL Assistant: Self-Verification and Self-Correction

# 摘要

> 我们研究了如何利用大型语言模型（LLMs）自动生成高质量的寄存器传输级（RTL）代码，减少人工介入。传统上，RTL设计依赖专家手动编码，耗时且易错。现在，开发者只需向LLMs说明需求，即可获得Python、C、Java等语言的代码。然而，将LLMs应用于硬件描述语言的RTL设计颇具挑战，因为硬件设计复杂且需满足严格的时序和物理限制。为此，我们开发了VeriAssist，一个专为Verilog RTL设计流程定制的LLM编程助手。它接收设计描述，输出高质量RTL代码及测试平台。VeriAssist通过自动提示系统和RTL模拟器的集成，实现了代码的自我校正和验证。首先，它生成初始RTL代码和测试平台，然后通过测试案例分析代码行为，进行自我验证，最后根据编译和模拟结果修正代码，确保最终RTL代码无误。这一流程充分发挥了LLMs在多轮对话和逻辑推理上的优势，提升了代码质量。通过多套基准测试，我们验证了VeriAssist在语法和功能上的准确性远超现有LLM工具，极大降低了人工干预，让RTL设计对新手更为友好。

> We explore the use of Large Language Models (LLMs) to generate high-quality Register-Transfer Level (RTL) code with minimal human interference. The traditional RTL design workflow requires human experts to manually write high-quality RTL code, which is time-consuming and error-prone. With the help of emerging LLMs, developers can describe their requirements to LLMs which then generate corresponding code in Python, C, Java, and more. Adopting LLMs to generate RTL design in hardware description languages is not trivial, given the complex nature of hardware design and the generated design has to meet the timing and physical constraints.
  We propose VeriAssist, an LLM-powered programming assistant for Verilog RTL design workflow. VeriAssist takes RTL design descriptions as input and generates high-quality RTL code with corresponding test benches. VeriAssist enables the LLM to self-correct and self-verify the generated code by adopting an automatic prompting system and integrating RTL simulator in the code generation loop. To generate an RTL design, VeriAssist first generates the initial RTL code and corresponding test benches, followed by a self-verification step that walks through the code with test cases to reason the code behavior at different time steps, and finally it self-corrects the code by reading the compilation and simulation results and generating final RTL code that fixes errors in compilation and simulation. This design fully leverages the LLMs' capabilities on multi-turn interaction and chain-of-thought reasoning to improve the quality of the generated code. We evaluate VeriAssist with various benchmark suites and find it significantly improves both syntax and functionality correctness over existing LLM implementations, thus minimizing human intervention and making RTL design more accessible to novice designers.

[Arxiv](https://arxiv.org/abs/2406.00115)