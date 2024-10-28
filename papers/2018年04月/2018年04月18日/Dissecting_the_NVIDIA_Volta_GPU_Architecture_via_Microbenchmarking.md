# 通过微基准测试剖析 NVIDIA Volta GPU 架构

发布时间：2018年04月18日

`其他` `计算机硬件` `微架构`

> Dissecting the NVIDIA Volta GPU Architecture via Microbenchmarking

# 摘要

> 摘要：每年都会推出新的 NVIDIA GPU 设计。这种快速的架构和技术进步，再加上制造商不愿披露底层细节，即使是最熟练的 GPU 软件设计师也难以在微架构层面跟上技术进步的步伐。为了解决新型 NVIDIA GPU 缺乏公开的微架构层面信息的问题，独立研究人员不得不依靠基于微基准测试的剖析和发现。这导致了大量的出版物，揭示了指令编码以及各级内存层次结构的几何形状和特征。即描述了 Kepler、Maxwell 和 Pascal 架构的性能和行为的研究。在本技术报告中，我们通过展示通过微基准测试和指令集反汇编发现的 NVIDIA Volta 架构的微架构细节，继续这一研究路线。此外，我们还定量地将我们对 Volta 的发现与其前辈 Kepler、Maxwell 和 Pascal 进行了比较。

> 
Abstract:Every year, novel NVIDIA GPU designs are introduced. This rapid architectural and technological progression, coupled with a reluctance by manufacturers to disclose low-level details, makes it difficult for even the most proficient GPU software designers to remain up-to-date with the technological advances at a microarchitectural level. To address this dearth of public, microarchitectural-level information on the novel NVIDIA GPUs, independent researchers have resorted to microbenchmarks-based dissection and discovery. This has led to a prolific line of publications that shed light on instruction encoding, and memory hierarchy's geometry and features at each level. Namely, research that describes the performance and behavior of the Kepler, Maxwell and Pascal architectures. In this technical report, we continue this line of research by presenting the microarchitectural details of the NVIDIA Volta architecture, discovered through microbenchmarks and instruction set disassembly. Additionally, we compare quantitatively our Volta findings against its predecessors, Kepler, Maxwell and Pascal.
    

[Arxiv](https://arxiv.org/pdf/1804.06826)