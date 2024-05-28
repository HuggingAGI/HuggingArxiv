# RTL-Repo：大型语言模型在大型RTL设计项目上的评估基准

发布时间：2024年05月27日

`LLM应用

理由：该论文介绍了RTL-Repo这一基准，专门用于评估大型语言模型（LLMs）在实际的硬件描述语言（如Verilog）设计任务中的性能。这涉及到具体的应用场景，即在硬件设计领域中使用LLMs来生成代码，而不是探讨LLMs的理论基础或Agent的设计与应用。因此，它属于LLM应用类别。` `硬件设计` `基准测试`

> RTL-Repo: A Benchmark for Evaluating LLMs on Large-Scale RTL Design Projects

# 摘要

> 大型语言模型（LLMs）在协助RTL设计任务上展现出潜力，但现有的基准测试仍未能准确反映真实世界RTL项目的复杂性。为此，我们推出了RTL-Repo，一个专为评估LLMs在大规模RTL设计上的性能而设计的基准。RTL-Repo收录了超过4000个来自GitHub的Verilog代码样本，每个样本都附带了完整的仓库上下文。我们在此基准上测试了包括GPT-4、GPT-3.5、Starcoder2及Verilog专用模型在内的多种先进模型，并对比了它们在复杂项目中生成Verilog代码的能力。RTL-Repo不仅为硬件设计界提供了一个评估和比较LLMs在实际RTL设计中表现的工具，还为训练LLMs进行复杂多文件RTL项目中的Verilog代码生成提供了平台。此基准已开源，并可在GitHub上免费获取。

> Large Language Models (LLMs) have demonstrated potential in assisting with Register Transfer Level (RTL) design tasks. Nevertheless, there remains to be a significant gap in benchmarks that accurately reflect the complexity of real-world RTL projects. To address this, this paper presents RTL-Repo, a benchmark specifically designed to evaluate LLMs on large-scale RTL design projects. RTL-Repo includes a comprehensive dataset of more than 4000 Verilog code samples extracted from public GitHub repositories, with each sample providing the full context of the corresponding repository. We evaluate several state-of-the-art models on the RTL-Repo benchmark, including GPT-4, GPT-3.5, Starcoder2, alongside Verilog-specific models like VeriGen and RTLCoder, and compare their performance in generating Verilog code for complex projects. The RTL-Repo benchmark provides a valuable resource for the hardware design community to assess and compare LLMs' performance in real-world RTL design scenarios and train LLMs specifically for Verilog code generation in complex, multi-file RTL projects. RTL-Repo is open-source and publicly available on Github.

[Arxiv](https://arxiv.org/abs/2405.17378)