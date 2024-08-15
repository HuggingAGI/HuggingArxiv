# 双重稀疏性下的训练后稀疏注意力

发布时间：2024年08月11日

`LLM理论` `计算机科学` `人工智能`

> Post-Training Sparse Attention with Double Sparsity

# 摘要

> 大型语言模型的推理过程因过度依赖Key-Value缓存而显得缓慢且内存密集。为此，我们引入了“双重稀疏性”技术，通过减少KV缓存访问来提升效率。该技术巧妙结合了令牌稀疏性和通道稀疏性，前者专注于利用关键令牌进行自注意力计算，后者则通过重要特征通道来识别这些关键令牌。我们的研究发现，通道稀疏性的模式相对稳定，因此可以通过离线校准在运行时实现高效识别，确保了重要令牌的精准与高效处理。此外，该方法还能与卸载技术结合，大幅降低内存占用。实验显示，双重稀疏性在保持准确性的同时，在多种任务中实现了显著的性能提升，包括在GPU上注意力操作加速14.1倍，端到端推理提升1.9倍，以及在序列长度为256K时，解码速度比现有最佳方案快16.3倍。相关代码已公开，详见\url{https://github.com/andy-yang-1/DoubleSparse}。

> The inference process for large language models is slow and memory-intensive, with one of the most critical bottlenecks being excessive Key-Value (KV) cache accesses. This paper introduces "Double Sparsity," a novel post-training sparse attention technique designed to alleviate this bottleneck by reducing KV cache access. Double Sparsity combines token sparsity, which focuses on utilizing only the important tokens for computing self-attention, with channel sparsity, an approach that uses important feature channels for identifying important tokens. Our key insight is that the pattern of channel sparsity is relatively static, allowing us to use offline calibration to make it efficient at runtime, thereby enabling accurate and efficient identification of important tokens. Moreover, this method can be combined with offloading to achieve significant memory usage reduction. Experimental results demonstrate that Double Sparsity can achieve \(\frac{1}{16}\) token and channel sparsity with minimal impact on accuracy across various tasks, including wiki-2 perplexity, key-value retrieval, and long context benchmarks with models including Llama-2-7B, Llama-2-70B, and Mixtral-8x7B. It brings up to a 14.1$\times$ acceleration in attention operations and a 1.9$\times$ improvement in end-to-end inference on GPUs. With offloading, it achieves a decoding speed acceleration of 16.3$\times$ compared to state-of-the-art solutions at a sequence length of 256K. Our code is publicly available at \url{https://github.com/andy-yang-1/DoubleSparse}.

[Arxiv](https://arxiv.org/abs/2408.07092)