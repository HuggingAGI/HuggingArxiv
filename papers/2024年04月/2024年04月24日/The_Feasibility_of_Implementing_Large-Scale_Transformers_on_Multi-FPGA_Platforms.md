# 探讨在多 FPGA 平台部署大型变换器的可能性

发布时间：2024年04月24日

`分类：LLM应用` `数据中心` `机器学习`

> The Feasibility of Implementing Large-Scale Transformers on Multi-FPGA Platforms

# 摘要

> 在数据中心部署大型机器学习应用，如大型语言模型（LLMs），人们很少谈及现场可编程门阵列（FPGA）的应用。众多研究已证明，单个FPGA在特定计算任务上，尤其是在低延迟方面，性能可与GPU媲美，且在能耗效率上往往更胜一筹。这一发现激励我们考虑在大型机器学习应用中采用多FPGA的可能性。然而，多FPGA应用的开发和部署缺乏统一的流程和工具，这成为了一个挑战。本文旨在探讨利用多FPGA实现大型变换器的可行性，我们开发了一个可扩展的多FPGA平台及相关工具，以便将大型应用映射到该平台。通过设计高效的多FPGA版I-BERT变换器，并用六个FPGA实现一个编码器作为实际概念验证，我们证实了我们的方法和工具的有效性。结合我们的概念验证原型以及最新的FPGA与GPU性能对比估计，我们得出结论，FPGA在大型机器学习应用领域确实有其用武之地。我们的初步成果充满希望，表明在适当的基础设施和工具支持下，深入研究FPGA在LLMs等应用中的潜在优势是值得的。

> FPGAs are rarely mentioned when discussing the implementation of large machine learning applications, such as Large Language Models (LLMs), in the data center. There has been much evidence showing that single FPGAs can be competitive with GPUs in performance for some computations, especially for low latency, and often much more efficient when power is considered. This suggests that there is merit to exploring the use of multiple FPGAs for large machine learning applications. The challenge with using multiple FPGAs is that there is no commonly-accepted flow for developing and deploying multi-FPGA applications, i.e., there are no tools to describe a large application, map it to multiple FPGAs and then deploy the application on a multi-FPGA platform. In this paper, we explore the feasibility of implementing large transformers using multiple FPGAs by developing a scalable multi-FPGA platform and some tools to map large applications to the platform. We validate our approach by designing an efficient multi-FPGA version of the I-BERT transformer and implement one encoder using six FPGAs as a working proof-of-concept to show that our platform and tools work. Based on our proof-of-concept prototype and the estimations of performance using the latest FPGAs compared to GPUs, we conclude that there can be a place for FPGAs in the world of large machine learning applications. We demonstrate a promising first step that shows that with the right infrastructure and tools it is reasonable to continue to explore the possible benefits of using FPGAs for applications such as LLMs.

[Arxiv](https://arxiv.org/abs/2404.16158)