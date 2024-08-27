# Fire-Flyer AI-HPC：为深度学习提供了一种经济高效的软件与硬件协同设计方案。

发布时间：2024年08月26日

`LLM理论` `高性能计算`

> Fire-Flyer AI-HPC: A Cost-Effective Software-Hardware Co-Design for Deep Learning

# 摘要

> 随着深度学习和大型语言模型的迅猛发展，对计算资源和带宽的需求激增，加之高性能计算芯片和互连的高昂成本，使得高性能计算的建设成本大幅上升。为此，我们推出了 Fire-Flyer AI-HPC 架构，这一硬件与软件协同设计的框架及其最佳实践，有效应对了上述挑战。在深度学习训练方面，我们采用的 Fire-Flyer 2 系统，搭载 10,000 个 PCIe A100 GPU，不仅性能媲美 DGX-A100，更将成本削减一半，能耗降低 40%。此外，我们精心设计的 HFReduce 加速了 allreduce 通信，并采取多项措施确保计算-存储集成网络的畅通无阻。通过 HaiScale、3FS 和 HAI-Platform 等软件栈的协同作用，我们实现了计算与通信的重叠，大幅提升了系统的可扩展性。这些从深度学习训练中积累的系统化经验，为未来 AI-HPC 的发展提供了宝贵的启示。

> The rapid progress in Deep Learning (DL) and Large Language Models (LLMs) has exponentially increased demands of computational power and bandwidth. This, combined with the high costs of faster computing chips and interconnects, has significantly inflated High Performance Computing (HPC) construction costs. To address these challenges, we introduce the Fire-Flyer AI-HPC architecture, a synergistic hardware-software co-design framework and its best practices. For DL training, we deployed the Fire-Flyer 2 with 10,000 PCIe A100 GPUs, achieved performance approximating the DGX-A100 while reducing costs by half and energy consumption by 40%. We specifically engineered HFReduce to accelerate allreduce communication and implemented numerous measures to keep our Computation-Storage Integrated Network congestion-free. Through our software stack, including HaiScale, 3FS, and HAI-Platform, we achieved substantial scalability by overlapping computation and communication. Our system-oriented experience from DL training provides valuable insights to drive future advancements in AI-HPC.

[Arxiv](https://arxiv.org/abs/2408.14158)