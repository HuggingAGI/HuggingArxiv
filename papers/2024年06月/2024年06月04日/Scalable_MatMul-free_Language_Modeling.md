# 无需矩阵乘法的可扩展语言建模

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中矩阵乘法（MatMul）的计算成本问题，并提出了一种无MatMul的模型架构，这在理论层面上对LLMs的计算效率和模型扩展规律进行了深入研究。此外，论文还涉及了模型在硬件上的实现和优化，这些都是对LLM理论的贡献，而非直接的应用或Agent相关研究。因此，将其归类为LLM理论是合适的。` `人工智能` `高性能计算`

> Scalable MatMul-free Language Modeling

# 摘要

> 矩阵乘法（MatMul）在大型语言模型（LLMs）的计算成本中占据主导地位，且随着模型规模的扩大，这一成本不断攀升。然而，我们的研究表明，在数十亿参数级别上，可以完全摒弃MatMul操作，同时保持卓越性能。实验结果显示，我们的无MatMul模型在高达27亿参数的规模上，与需要更多内存的顶尖Transformer模型性能相当。我们探讨了模型扩展的规律，发现随着模型尺寸的增长，无MatMul模型与全精度Transformer之间的性能差距逐渐缩小。此外，我们提供了一个GPU高效实现，该模型在训练中内存使用量可降低61%。通过推理时的优化内核，我们的模型内存消耗可降低至未优化模型的十分之一。为了评估我们架构的效率，我们在FPGA上开发了定制硬件，利用了GPU无法实现的轻量级操作，实现了数十亿参数模型的高效处理，其吞吐量远超人类可读水平，使LLMs更接近类脑效率。这项研究不仅揭示了LLMs在保持高效性能的同时可以精简到何种程度，也为未来加速器在处理下一代轻量级LLMs时应优化的操作提供了方向。我们的代码实现已公开在\url{https://github.com/ridgerchu/matmulfreellm}。

> Matrix multiplication (MatMul) typically dominates the overall computational cost of large language models (LLMs). This cost only grows as LLMs scale to larger embedding dimensions and context lengths. In this work, we show that MatMul operations can be completely eliminated from LLMs while maintaining strong performance at billion-parameter scales. Our experiments show that our proposed MatMul-free models achieve performance on-par with state-of-the-art Transformers that require far more memory during inference at a scale up to at least 2.7B parameters. We investigate the scaling laws and find that the performance gap between our MatMul-free models and full precision Transformers narrows as the model size increases. We also provide a GPU-efficient implementation of this model which reduces memory usage by up to 61% over an unoptimized baseline during training. By utilizing an optimized kernel during inference, our model's memory consumption can be reduced by more than 10x compared to unoptimized models. To properly quantify the efficiency of our architecture, we build a custom hardware solution on an FPGA which exploits lightweight operations beyond what GPUs are capable of. We processed billion-parameter scale models at 13W beyond human readable throughput, moving LLMs closer to brain-like efficiency. This work not only shows how far LLMs can be stripped back while still performing effectively, but also points at the types of operations future accelerators should be optimized for in processing the next generation of lightweight LLMs. Our code implementation is available at \url{https://github.com/ridgerchu/matmulfreellm}.

![无需矩阵乘法的可扩展语言建模](../../../paper_images/2406.02528/x1.png)

![无需矩阵乘法的可扩展语言建模](../../../paper_images/2406.02528/x2.png)

![无需矩阵乘法的可扩展语言建模](../../../paper_images/2406.02528/x3.png)

![无需矩阵乘法的可扩展语言建模](../../../paper_images/2406.02528/x4.png)

![无需矩阵乘法的可扩展语言建模](../../../paper_images/2406.02528/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02528)