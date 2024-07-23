# 分布式大型语言模型的训练与推理：性能建模与工作负载探究

发布时间：2024年07月19日

`LLM理论` `半导体` `高性能计算`

> Performance Modeling and Workload Analysis of Distributed Large Language Model Training and Inference

# 摘要

> 在当今世界，确保未来系统设计与大型语言模型（LLM）日益增长的计算需求相匹配至关重要。为此，我们提出了一种全面的性能建模方法，通过分析框架深入探讨了分布式LLM训练与推理的各个方面，包括计算、内存、网络及多种并行策略。我们通过公开数据和行业案例（如NVIDIA）验证了预测的准确性。在分布式训练方面，我们详细分析了不同激活重计算方法下的内存需求，并揭示了从A100到B200性能飞跃的关键因素。此外，我们还跨技术节点（从12 nm至1 nm）进行了设计探索，以评估逻辑、内存和网络扩展对性能的影响。在推理环节，我们深入剖析了不同GPU系统中矩阵运算的计算与内存需求，并研究了DRAM技术进步对推理延迟的潜在影响。借助我们的建模框架，我们清晰地展示了技术进步下LLM训练与推理的性能瓶颈演变，为未来系统设计提供了宝贵的洞察。

> Aligning future system design with the ever-increasing compute needs of large language models (LLMs) is undoubtedly an important problem in today's world. Here, we propose a general performance modeling methodology and workload analysis of distributed LLM training and inference through an analytical framework that accurately considers compute, memory sub-system, network, and various parallelization strategies (model parallel, data parallel, pipeline parallel, and sequence parallel). We validate our performance predictions with published data from literature and relevant industry vendors (e.g., NVIDIA). For distributed training, we investigate the memory footprint of LLMs for different activation re-computation methods, dissect the key factors behind the massive performance gain from A100 to B200 ($\sim$ 35x speed-up closely following NVIDIA's scaling trend), and further run a design space exploration at different technology nodes (12 nm to 1 nm) to study the impact of logic, memory, and network scaling on the performance. For inference, we analyze the compute versus memory boundedness of different operations at a matrix-multiply level for different GPU systems and further explore the impact of DRAM memory technology scaling on inference latency. Utilizing our modeling framework, we reveal the evolution of performance bottlenecks for both LLM training and inference with technology scaling, thus, providing insights to design future systems for LLM training and inference.

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x1.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/Optimus-Megatron.jpg)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x2.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x3.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x4.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x5.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x6.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x7.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x8.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x9.png)

![分布式大型语言模型的训练与推理：性能建模与工作负载探究](../../../paper_images/2407.14645/x10.png)

[Arxiv](https://arxiv.org/abs/2407.14645)