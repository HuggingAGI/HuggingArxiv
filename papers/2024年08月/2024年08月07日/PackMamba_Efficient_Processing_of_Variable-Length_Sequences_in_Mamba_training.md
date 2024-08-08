# PackMamba 技术旨在在 Mamba 训练过程中，高效地处理长度不一的序列数据。

发布时间：2024年08月07日

`LLM理论` `人工智能` `高性能计算`

> PackMamba: Efficient Processing of Variable-Length Sequences in Mamba training

# 摘要

> 随着大型语言模型的演进，传统 Transformer 模型因序列长度计算的二次增长而对长序列处理需求激增。Mamba，作为生成 AI 领域的创新架构，以其降低的计算和内存复杂性在长序列处理中表现卓越。然而，Mamba 现有训练框架在处理可变长度序列时效率欠佳，单序列训练 GPU 利用率低，批处理则带来显著开销。为此，我们分析了 Mamba 瓶颈操作符性能，并提出 PackMamba，高效处理可变长度序列的高吞吐量方案。通过优化状态空间模型中的并行操作，我们避免了序列间信息传递，同时保持高性能。实验表明，在 NVIDIA A100 GPU 上，PackMamba 在 1.4B 和 2.8B 模型上的吞吐量分别提升了 3.06 倍和 2.62 倍，超越了传统单序列处理方案。

> With the evolution of large language models, traditional Transformer models become computationally demanding for lengthy sequences due to the quadratic growth in computation with respect to the sequence length. Mamba, emerging as a groundbreaking architecture in the field of generative AI, demonstrates remarkable proficiency in handling elongated sequences with reduced computational and memory complexity. Nevertheless, the existing training framework of Mamba presents inefficiency with variable-length sequence inputs. Either single-sequence training results in low GPU utilization, or batched processing of variable-length sequences to a maximum length incurs considerable memory and computational overhead. To address this problem, we analyze the performance of bottleneck operators in Mamba under diverse tensor shapes and proposed PackMamba, a high-throughput Mamba that efficiently handles variable-length sequences. Diving deep into state-space models (SSMs), we modify the parallel operators to avoid passing information between individual sequences while maintaining high performance. Experimental results on an NVIDIA A100 GPU demonstrate throughput exceeding the baseline single-sequence processing scheme: 3.06x speedup on the 1.4B model and 2.62x on the 2.8B model.

[Arxiv](https://arxiv.org/abs/2408.03865)