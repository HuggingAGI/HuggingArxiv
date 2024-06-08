# Seq1F1B：大型语言模型训练中的高效序列级流水线并行策略

发布时间：2024年06月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在分布式训练中的技术挑战，特别是针对长序列训练时的内存消耗和流水线气泡问题。论文提出了一种新的流水线调度策略Seq1F1B，旨在优化LLMs的训练效率和扩展性。这一研究属于LLM的理论研究范畴，因为它关注的是模型训练过程中的技术细节和优化方法，而不是直接的应用或Agent行为。此外，它也不涉及RAG（Retrieval-Augmented Generation）的相关内容。因此，将其归类为LLM理论是合适的。` `人工智能` `高性能计算`

> Seq1F1B: Efficient Sequence-Level Pipeline Parallelism for Large Language Model Training

# 摘要

> 大型语言模型（LLMs）的崛起，依赖于分布式训练策略，尤其是流水线并行技术。随着LLMs的训练序列长度激增，达到32k甚至128k，现有的流水线并行方法遭遇了高内存消耗和大量流水线气泡的瓶颈，严重限制了模型的扩展性和训练效率。为此，我们提出了一种名为Seq1F1B的高效序列级1F1B流水线调度策略，专为长序列上的LLMs训练量身定制。Seq1F1B通过将调度单元细化至序列级别，有效减少了气泡和内存需求。针对序列均匀分割可能带来的额外气泡问题，我们采用了一种计算策略来优化序列分割，以减轻这一影响。与Megatron 1F1B等先进方法相比，Seq1F1B在保持较低内存占用的同时，显著提升了训练吞吐量。特别地，Seq1F1B成功在64个NVIDIA A100 GPU上训练了一个30B参数的LLM，处理长达64k的序列，无需任何重计算技巧，这是现有技术难以企及的。我们的代码基于Megatron-LM，现已开放源代码，地址为：https://github.com/MayDomine/Seq1F1B.git。

> The emergence of large language models (LLMs) relies heavily on distributed training strategies, among which pipeline parallelism plays a crucial role. As LLMs' training sequence length extends to 32k or even 128k, the current pipeline parallel methods face severe bottlenecks, including high memory footprints and substantial pipeline bubbles, greatly hindering model scalability and training throughput. To enhance memory efficiency and training throughput, in this work, we introduce an efficient sequence-level one-forward-one-backward (1F1B) pipeline scheduling method tailored for training LLMs on long sequences named Seq1F1B. Seq1F1B decomposes batch-level schedulable units into finer sequence-level units, reducing bubble size and memory footprint. Considering that Seq1F1B may produce slight extra bubbles if sequences are split evenly, we design a computation-wise strategy to partition input sequences and mitigate this side effect. Compared to competitive pipeline baseline methods such as Megatron 1F1B pipeline parallelism, our method achieves higher training throughput with less memory footprint. Notably, Seq1F1B efficiently trains a LLM with 30B parameters on sequences up to 64k using 64 NVIDIA A100 GPUs without recomputation strategies, a feat unachievable with existing methods. Our source code is based on Megatron-LM, and now is avaiable at: https://github.com/MayDomine/Seq1F1B.git.

![Seq1F1B：大型语言模型训练中的高效序列级流水线并行策略](../../../paper_images/2406.03488/x1.png)

![Seq1F1B：大型语言模型训练中的高效序列级流水线并行策略](../../../paper_images/2406.03488/x2.png)

![Seq1F1B：大型语言模型训练中的高效序列级流水线并行策略](../../../paper_images/2406.03488/x3.png)

![Seq1F1B：大型语言模型训练中的高效序列级流水线并行策略](../../../paper_images/2406.03488/x4.png)

[Arxiv](https://arxiv.org/abs/2406.03488)