# ISO：LLM 推理中计算与通信的交织

发布时间：2024年09月04日

`LLM理论` `人工智能` `高性能计算`

> ISO: Overlap of Computation and Communication within Seqenence For LLM Inference

# 摘要

> 在 LLM 推理中，transformer 模型的结构与多 GPU 并行策略结合，导致计算与通信的顺序执行，造成通信阶段资源利用率低下。为解决这一问题，现有技术主要通过重叠计算与通信或交错微批次来优化资源利用，但效果有限或应用受限。本文提出了一种新的序列级计算-通信重叠策略，不仅提高了重叠度，还减少了应用限制。实验表明，该策略在 30b/70b 模型上显著提升了效率，预填充阶段在 4090 GPU 上节省了约 35% 的时间，在 A800 GPU 上节省了约 15% 的时间。

> In the realm of Large Language Model (LLM) inference, the inherent structure of transformer models coupled with the multi-GPU tensor parallelism strategy leads to a sequential execution of computation and communication. This results in substantial underutilization of computing resources during the communication phase. To mitigate this inefficiency, various techniques have been developed to optimize the use of computational power throughout the communication process. These strategies primarily involve overlapping matrix computations and communications, as well as interleaving micro-batches across different requests. Nonetheless, these approaches either fall short of achieving ideal overlap or impose certain limitations on their application. To overcome these challenges, this paper introduces a novel strategy for computation-communication overlap that operates at the sequence level. This method not only enhances the degree of overlap but also minimizes the constraints on its applicability. Experimental evaluations conducted using 30b/70b models have demonstrated significant improvements in efficiency. Specifically, the proposed technique has been shown to reduce time consumption by approximately 35% on 4090 GPU and by roughly 15% on A800 GPU during the prefill stage of LLM inference.

[Arxiv](https://arxiv.org/abs/2409.11155)