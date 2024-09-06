# LLM 硬件加速：全面调查与比较

发布时间：2024年09月05日

`LLM理论` `半导体` `人工智能`

> Hardware Acceleration of LLMs: A comprehensive survey and comparison

# 摘要

> 大型语言模型 (LLM) 凭借其理解和生成人类语言的能力，已成为自然语言处理领域的革命性工具。本文全面调查了利用硬件加速器加速 transformer 网络的研究进展。我们不仅展示了各种框架，还从技术、平台、加速、能效等多个维度进行了定量和定性比较。由于各方案基于不同工艺技术实现，公平比较颇具挑战。为此，我们创新地将性能和能效数据外推至同一工艺技术，以确保比较的公正性。通过在多个 FPGA 芯片上实现部分 LLM，我们进一步将结果外推至相同工艺技术，从而实现了更为精准的性能对比。

> Large Language Models (LLMs) have emerged as powerful tools for natural language processing tasks, revolutionizing the field with their ability to understand and generate human-like text. In this paper, we present a comprehensive survey of the several research efforts that have been presented for the acceleration of transformer networks for Large Language Models using hardware accelerators.
  The survey presents the frameworks that have been proposed and then performs a qualitative and quantitative comparison regarding the technology, the processing platform (FPGA, ASIC, In-Memory, GPU), the speedup, the energy efficiency, the performance (GOPs), and the energy efficiency (GOPs/W) of each framework. The main challenge in comparison is that every proposed scheme is implemented on a different process technology making hard a fair comparison. The main contribution of this paper is that we extrapolate the results of the performance and the energy efficiency on the same technology to make a fair comparison; one theoretical and one more practical. We implement part of the LLMs on several FPGA chips to extrapolate the results to the same process technology and then we make a fair comparison of the performance.

[Arxiv](https://arxiv.org/abs/2409.03384)