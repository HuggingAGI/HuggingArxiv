# MoNDE：融合近数据专家的大规模稀疏模型解决方案

发布时间：2024年05月29日

`LLM应用

这篇论文主要关注的是大型语言模型（LLM）中的混合专家（MoE）架构的内存优化问题。通过提出一种名为混合近数据专家（MoNDE）的新方法，该研究解决了MoE模型在推理过程中因内存需求超出GPU容量而导致的参数迁移成本问题。这种方法通过仅将活跃的专家参数转移到GPU，并在主机内存中处理其余部分，有效减少了参数传输量，从而提高了MoE模型的推理效率。因此，这篇论文属于LLM应用类别，因为它专注于优化和改进LLM的实际应用性能。` `人工智能` `高性能计算`

> MoNDE: Mixture of Near-Data Experts for Large-Scale Sparse Models

# 摘要

> 混合专家（MoE）大型语言模型（LLM）的内存需求常超出GPU容量，导致昂贵的参数迁移以进行专家计算。本研究提出了一种名为混合近数据专家（MoNDE）的解决方案，它通过仅将活跃的专家参数转移到GPU，并在主机内存中处理其余部分，有效减少了参数传输量。这一创新使得MoE推理更为高效，大幅提升了编码器和解码器操作的速度，超越了现有的参数卸载框架。

> Mixture-of-Experts (MoE) large language models (LLM) have memory requirements that often exceed the GPU memory capacity, requiring costly parameter movement from secondary memories to the GPU for expert computation. In this work, we present Mixture of Near-Data Experts (MoNDE), a near-data computing solution that efficiently enables MoE LLM inference. MoNDE reduces the volume of MoE parameter movement by transferring only the $\textit{hot}$ experts to the GPU, while computing the remaining $\textit{cold}$ experts inside the host memory device. By replacing the transfers of massive expert parameters with the ones of small activations, MoNDE enables far more communication-efficient MoE inference, thereby resulting in substantial speedups over the existing parameter offloading frameworks for both encoder and decoder operations.

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x1.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x2.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x3.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x4.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x5.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x6.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x7.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x8.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x9.png)

![MoNDE：融合近数据专家的大规模稀疏模型解决方案](../../../paper_images/2405.18832/x10.png)

[Arxiv](https://arxiv.org/abs/2405.18832)