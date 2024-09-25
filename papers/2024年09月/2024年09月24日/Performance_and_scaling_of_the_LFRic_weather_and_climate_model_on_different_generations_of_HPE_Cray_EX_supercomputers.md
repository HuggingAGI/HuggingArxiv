# LFRic 模型在各代 HPE Cray EX 超级计算机上的表现与扩展性

发布时间：2024年09月24日

`LLM应用` `高性能计算`

> Performance and scaling of the LFRic weather and climate model on different generations of HPE Cray EX supercomputers

# 摘要

> 本研究分析了 Met Office 的 LFRic 模型在不同超级计算机和编译器上的扩展性能。该模型成功扩展至大量节点，充分利用了并行性。模型采用领域特定语言编写，并通过 PSyclone 编译器生成并行代码。性能分析揭示了算法选择对性能的影响，如冗余计算和 OpenMP 线程的扩展。此外，还探讨了如何通过未来工作提升代码其他部分的 OpenMP 性能。最后，研究了 I/O 服务器 XIOS 的性能调优。

> This study presents scaling results and a performance analysis across different supercomputers and compilers for the Met Office weather and climate model, LFRic. The model is shown to scale to large numbers of nodes which meets the design criteria, that of exploitation of parallelism to achieve good scaling. The model is written in a Domain-Specific Language, embedded in modern Fortran and uses a Domain-Specific Compiler, PSyclone, to generate the parallel code. The performance analysis shows the effect of choice of algorithm, such as redundant computation and scaling with OpenMP threads. The analysis can be used to motivate a discussion of future work to improve the OpenMP performance of other parts of the code. Finally, an analysis of the performance tuning of the I/O server, XIOS is presented.

[Arxiv](https://arxiv.org/abs/2409.15859)