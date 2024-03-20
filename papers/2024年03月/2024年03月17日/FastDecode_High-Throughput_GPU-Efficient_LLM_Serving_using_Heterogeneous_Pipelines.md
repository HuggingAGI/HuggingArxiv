# FastDecode是一种利用异构流水线技术，大幅提升GPU效率以实现大规模语言模型（LLM）高速服务的方法。

发布时间：2024年03月17日

`Agent` `高性能计算`

> FastDecode: High-Throughput GPU-Efficient LLM Serving using Heterogeneous Pipelines

> 尽管服务LLM的成本高昂，且GPU在串行生成令牌时效率低下，除非批量增大，但受制于KV-Cache这类重复使用的中间结果占用大量内存，导致无法充分利用GPU并行处理更多序列。尽管可以考虑将KV-Cache移至主机内存，却又受限于CPU与GPU之间的带宽瓶颈。为此，我们创新性地将Transformer模型拆分为两个特性迥异的部分，并着重利用多节点CPU整合的内存资源、带宽及计算力来处理涉及KV-Cache访问的内存密集型部分。这样不仅能减少数据传输负担，还能够通过释放GPU资源专注于处理模型的其余部分，从而显著提升整体性能。同时，我们运用调度技术和性能建模手段有效应对了时间和设备层级上的异构性问题。实验证明，在同等GPU条件下，我们的系统在服务于现代LLM时，其吞吐量可达vLLM系统的1.88至5.04倍之高。

> Cost of serving large language models (LLM) is high, but the expensive and scarce GPUs are poorly efficient when generating tokens sequentially, unless the batch of sequences is enlarged. However, the batch size is limited by some constantly reused intermediate results, namely KV-Cache. They occupy too much memory to fit more sequences into a GPU simultaneously. While they could be offloaded to host memory, the CPU-GPU bandwidth is an inevitable bottleneck.
  We find a way to decompose the transformer models into two parts of different characteristics, one of which includes the memory-bound KV-Cache accessing. Our key insight is that the aggregated memory capacity, bandwidth, and computing power of CPUs across multiple nodes is an efficient option to process this part. Performance improvement comes from reduced data transmission overhead and boosted GPU throughput to process the other model part. Moreover, we address efficiency challenges brought by heterogeneity at both temporal and inter-device scopes using scheduling and performance modeling techniques. Evaluation results show that our system achieves 1.88x - 5.04x the throughput of vLLM when serving modern LLMs with the same GPU.

[Arxiv](https://arxiv.org/abs/2403.11421)