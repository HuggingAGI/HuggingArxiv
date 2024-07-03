# 实现高效稀疏注意力，关键在于自适应释放令牌。

发布时间：2024年07月02日

`LLM理论` `计算机科学` `人工智能`

> Efficient Sparse Attention needs Adaptive Token Release

# 摘要

> 近年来，大型语言模型在众多文本任务中表现卓越，但其庞大的规模带来了计算和存储上的重大挑战，尤其是在处理 transformer 的关键-值状态时，限制了其广泛应用。为此，我们提出一种自适应资源释放策略，通过轻量级控制器模块实现理想的 top-$K$ 稀疏注意力，保留高权重令牌并重建必要但被丢弃的令牌，以备未来解码所需。实验表明，我们的方法不仅在性能上与全注意力相当，还显著提升了吞吐量，高达 221.8%。复现代码已公开在 https://github.com/WHUIR/ADORE。

> In recent years, Large Language Models (LLMs) have demonstrated remarkable capabilities across a wide array of text-centric tasks. However, their `large' scale introduces significant computational and storage challenges, particularly in managing the key-value states of the transformer, which limits their wider applicability. Therefore, we propose to adaptively release resources from caches and rebuild the necessary key-value states. Particularly, we accomplish this by a lightweight controller module to approximate an ideal top-$K$ sparse attention. This module retains the tokens with the highest top-$K$ attention weights and simultaneously rebuilds the discarded but necessary tokens, which may become essential for future decoding. Comprehensive experiments in natural language generation and modeling reveal that our method is not only competitive with full attention in terms of performance but also achieves a significant throughput improvement of up to 221.8%. The code for replication is available on the https://github.com/WHUIR/ADORE.

[Arxiv](https://arxiv.org/abs/2407.02328)