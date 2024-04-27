# 探讨在多 FPGA 平台上部署大型变换器的可能性

发布时间：2024年04月24日

`LLM应用` `数据中心` `机器学习`

> The Feasibility of Implementing Large-Scale Transformers on Multi-FPGA Platforms

# 摘要

> 在数据中心部署大型机器学习应用，如大型语言模型（LLMs），通常不会提及现场可编程门阵列（FPGA）。然而，有证据显示，单个FPGA在某些计算任务上的性能可与GPU媲美，尤其在低延迟计算上，且在能耗效率上往往更胜一筹。这一发现激励我们考虑利用多个FPGA来执行大型机器学习任务。面临的挑战在于，目前缺乏一套广泛接受的开发和部署多FPGA应用的流程，也就是说，缺少能够描述、映射并部署大型应用到多FPGA平台的工具。本文中，我们探讨了利用多个FPGA实现大型变换器的可能性，包括开发一个可扩展的多FPGA平台和相应的映射工具。我们通过设计高效的多FPGA版本的I-BERT变换器，并用六个FPGA实现一个编码器作为实际概念验证，来验证我们的方法。根据我们的概念验证原型以及与GPU相比的最新FPGA性能估算，我们得出结论，FPGA在大型机器学习应用领域确实有其一席之地。我们的初步成果表明，只要有合适的基础设施和工具，进一步探索FPGA在LLMs等应用中的潜在优势是值得的。

> FPGAs are rarely mentioned when discussing the implementation of large machine learning applications, such as Large Language Models (LLMs), in the data center. There has been much evidence showing that single FPGAs can be competitive with GPUs in performance for some computations, especially for low latency, and often much more efficient when power is considered. This suggests that there is merit to exploring the use of multiple FPGAs for large machine learning applications. The challenge with using multiple FPGAs is that there is no commonly-accepted flow for developing and deploying multi-FPGA applications, i.e., there are no tools to describe a large application, map it to multiple FPGAs and then deploy the application on a multi-FPGA platform. In this paper, we explore the feasibility of implementing large transformers using multiple FPGAs by developing a scalable multi-FPGA platform and some tools to map large applications to the platform. We validate our approach by designing an efficient multi-FPGA version of the I-BERT transformer and implement one encoder using six FPGAs as a working proof-of-concept to show that our platform and tools work. Based on our proof-of-concept prototype and the estimations of performance using the latest FPGAs compared to GPUs, we conclude that there can be a place for FPGAs in the world of large machine learning applications. We demonstrate a promising first step that shows that with the right infrastructure and tools it is reasonable to continue to explore the possible benefits of using FPGAs for applications such as LLMs.

[Arxiv](https://arxiv.org/abs/2404.16158)