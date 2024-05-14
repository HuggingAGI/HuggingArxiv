# SambaNova SN40L：以数据流与专家组合之力，突破AI内存壁垒

发布时间：2024年05月13日

`LLM理论

这篇论文探讨了大型语言模型（LLM）在硬件限制下的挑战，特别是“内存墙”问题，并提出了一种名为Samba-CoE的系统作为解决方案。该系统通过模块化设计、流数据流和三层内存系统来优化AI的训练和服务成本。论文详细介绍了Samba-CoE的设计和实现，并通过实验结果展示了其在性能上的显著提升。这表明论文主要关注的是LLM的理论和架构优化，而不是具体的应用场景或Agent的设计，因此归类为LLM理论。` `人工智能` `高性能计算`

> SambaNova SN40L: Scaling the AI Memory Wall with Dataflow and Composition of Experts

# 摘要

> GPT-4等单体LLM引领了生成式AI的新纪元，但其高昂的维护成本和复杂性却是一道难以逾越的障碍。随着AI加速器计算与内存比例的失衡，我们面临着一个名为“内存墙”的新挑战。专家组合（CoE）作为一种模块化解决方案，旨在降低AI的训练和服务成本。然而，传统硬件上的CoE面临两大难题：小模型的操作强度低，难以实现高利用率；同时，大量模型的动态切换既昂贵又缓慢。本论文介绍了Samba-CoE系统，它通过结合CoE、流数据流和三层内存系统，有效突破了“内存墙”。Samba-CoE拥有150位专家和一万亿参数，部署在SambaNova的SN40L RDU上，这是一种专为企业级AI应用设计的数据流加速器。该系统通过引入三层内存架构和专用网络，实现了高效的扩展。实验结果显示，与未融合基线相比，Samba-CoE在八个RDU套接字上的性能提升了2至13倍。对于CoE推理部署，8套接字RDU节点不仅大幅减少了机器占地面积，还将模型切换时间缩短了15至31倍，总体性能分别比DGX H100和DGX A100提升了3.7倍和6.6倍。

> Monolithic large language models (LLMs) like GPT-4 have paved the way for modern generative AI applications. Training, serving, and maintaining monolithic LLMs at scale, however, remains prohibitively expensive and challenging. The disproportionate increase in compute-to-memory ratio of modern AI accelerators have created a memory wall, necessitating new methods to deploy AI. Composition of Experts (CoE) is an alternative modular approach that lowers the cost and complexity of training and serving. However, this approach presents two key challenges when using conventional hardware: (1) without fused operations, smaller models have lower operational intensity, which makes high utilization more challenging to achieve; and (2) hosting a large number of models can be either prohibitively expensive or slow when dynamically switching between them.
  In this paper, we describe how combining CoE, streaming dataflow, and a three-tier memory system scales the AI memory wall. We describe Samba-CoE, a CoE system with 150 experts and a trillion total parameters. We deploy Samba-CoE on the SambaNova SN40L Reconfigurable Dataflow Unit (RDU) - a commercial dataflow accelerator architecture that has been co-designed for enterprise inference and training applications. The chip introduces a new three-tier memory system with on-chip distributed SRAM, on-package HBM, and off-package DDR DRAM. A dedicated inter-RDU network enables scaling up and out over multiple sockets. We demonstrate speedups ranging from 2x to 13x on various benchmarks running on eight RDU sockets compared with an unfused baseline. We show that for CoE inference deployments, the 8-socket RDU Node reduces machine footprint by up to 19x, speeds up model switching time by 15x to 31x, and achieves an overall speedup of 3.7x over a DGX H100 and 6.6x over a DGX A100.

[Arxiv](https://arxiv.org/abs/2405.07518)